```
usage: Usage:
$ ./proxy --local IP PORT --target IP PORT [--recv-first] [--log-file LOG]

Crude proxy on raw sockets. (NOTE: Rewrite the request_handler, resp.
response_handler functions if you want to modify the packets coming from the
client or target respectively.)

optional arguments:
  -h, --help            show this help message and exit

options:
  --local IP PORT [IP PORT ...]
                        local address and listening port (default: None)
  --target IP PORT [IP PORT ...]
                        target address and port (default: None)
  --timeout SECS        timeout (secs) in communication with target (default:
                        2.0)
  --recv-first, --rf    receive before sending to target host (default: False)
  --log-file LOG        relative path to log file (default: None)

```
