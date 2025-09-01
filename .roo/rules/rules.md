-  it's important to golf code as much as possible, and keep files small and focused so LLM can read and update them easily.

-  use as-few hooks as possible in react. defer function stability and state to a companion class instanciated with useMemo(() => new Class(props),[])
   -  and a single useEffect() to update selected props IF NEEDED.
   -  everything else will be mobx-based.
   -  extra useEffects might be ok in specific cases.

if I ask you a question about binaries like pg_restore or pg_dump, always read the man first to get the most accurate answer.
