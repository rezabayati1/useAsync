# useAsync

    const {data: fetchData, status, error, run} = useAsync({...initialState})

    React.useEffect(() => {
      return run(asyncFunction())
    }, [run])
