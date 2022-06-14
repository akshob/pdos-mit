# Operating System Engineering

This is course `6.S081: Operating System Engineering` from MIT opencourseware.

The lecture folders contain my attempts to solve assignments. The lecture slides, videos and other materials can be found on the [schedule](https://pdos.csail.mit.edu/6.828/2021/schedule.html).

Use docker to run xv6. See [here](https://github.com/wtakuo/xv6-env) for details

Create instance:
```
docker run --name xv6 -dt -v ~/xv6-riscv:/home/xv6/xv6-riscv wtakuo/xv6-env
```

Run instance:
```
docker exec -it xv6 bash
```

Run xv6
```
$ make qemu
```
To exit from xv6, type `ctrl+a` followed by `x`