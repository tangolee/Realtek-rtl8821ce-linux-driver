# Realtek-rtl8821ce-linux-driver

## *linux kernel5.0+ rtl8821wireless wifi driver*
-----
## build and install
- ```make```

- ```sudo make install```

- ```sudo modprobe -a 8821ce```

if use `make` install failed, try dkms.

```shell
sudo apt install bc module-assistant build-essential dkms
sudo m-a prepare
```

### `sudo ./dkms-install.sh`

