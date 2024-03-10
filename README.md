## Build image

```bash
docker build -t cmp2240 .
```

## Run container

```bash
docker run -it --rm -v $(pwd):/root/cs143 cmp2240:latest /bin/bash
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
coolc examples/hello_world.cl # Compile the file
spim examples/hello_world.s # Run the compiled code
```

## Example output

```
SPIM Version 6.5 of January 4, 2003
Copyright 1990-2003 by James R. Larus (larus@cs.wisc.edu).
All Rights Reserved.
See the file README for a full copyright notice.
Loaded: /usr/class/cs143/cool/lib/trap.handler
Hello, World.
COOL program successfully executed
Stats -- #instructions : 152
         #reads : 27  #writes 22  #branches 28  #other 75
```
