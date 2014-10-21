
## AFSK Demod

To decode the packets, use the ax25 decoder here https://github.com/phelpsw/ax25-decoder

```
mkfifo /tmp/bit_fifo

# Run ax25 decoder on fifo
./nrz /tmp/bit_fifo

# Run afskrx_file.grc which dumps demoded bits to /tmp/bit_fifo
```
