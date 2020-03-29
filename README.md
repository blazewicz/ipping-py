# IP ping

## UDP

Start an UDP echo server on the peer machine.

Using `socat`

```sh
socat PIPE udp-recvfrom:5554,fork
```

Using `netcat`

```sh
nc -kule /bin/cat 5554
```
