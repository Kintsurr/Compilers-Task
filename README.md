## Build image
```bash
docker build -t cmp2240 .
```

## Run container
```bash
docker run -it --rm -v $(pwd):/root/cs143 cmp2240
```


## Run the compiler
```bash
coolc <filename.cl>
```

## Run the compiled code
```bash
spim <filename.s
```

## Example
```bash
coolc examples/hello_world.cl
spim hello_world.s
```
