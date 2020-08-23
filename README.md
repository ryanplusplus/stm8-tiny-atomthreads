# stm8-tiny-atomthreads
Fiddling around with STM8, [tiny](https://github.com/ryanplusplus/tiny), and [Atomthreads](https://atomthreads.com/).

## Setup
### Linux
- Copy `tools/Linux/udev/70-st-link.rules` to `/etc/udev/rules.d/` and run `udevadm control --reload-rules`.

## Use
### Run Tests
```
make -f test.mk
```

### Compile
```shell
make -f target.mk
```

### Clean
```shell
make -f target.mk clean
```

### Erase via SWIM
```shell
make -f target.mk erase
```

### Flash via SWIM
```shell
make -f target.mk upload
```

### Open documentation
```shell
make -f <target>.mk datasheet
```

```shell
make -f <target>.mk hardware_manual
```
