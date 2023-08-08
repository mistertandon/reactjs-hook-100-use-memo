
## useMemo Hook

```
 const memoizedResult = useMemo(compute, dependencies)
```

 - During initial rendering, useMemo(compute, dependencies) invokes compute, memoizes the calculation result, and returns it to the component.

 - If during next renderings the dependencies don't change, then useMemo() doesn't invoke compute but returns the memoized value.