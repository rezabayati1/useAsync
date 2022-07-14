# useAsync

    const {data, status, error, run} = useAsync({...initialState})

    React.useEffect(() => {
      return run(asyncFunction())
    }, [run])
