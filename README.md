
# hi-ssh: ssh hi-cli module

## Installation guide

1. Install [hi-cli](https://github.com/hi-cli/hi-cli)

2. Install hi-ssh package
```
hi package install ssh
```

3. Features

    1. Generate ssh key
    ```
    hi ssh keygen [your.email@company.com]
    ```

    2. Copy ssh public key to remote machine(s)
    ```
    hi ssh copy id host="192.168.1.100"
    hi ssh copy id hosts="192.168.1.100 192.168.1.101 192.168.1.102"
    ```

    3. Access reomte host shortcut
    ```
    hi ssh [remote ip or hostname]
    hi ssh 192.168.1.100
    ```