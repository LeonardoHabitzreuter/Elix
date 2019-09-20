# Tuples

## Checking size
```
tuple_size {:ok, "hello"}
```

## Get by index
```
tuple = {:ok, "hello"}
elem tuple, 1
```

## Update an index
```
put_elem(tuple, 1, "new value")
```