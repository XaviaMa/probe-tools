# Probe Tools

Uses `tcpdump` - allows analysis of what IPs are fetching/uploading data onto localhost.

### Installation

`sudo cp ./bin/* /usr/bin/`

### Environment variables

 - `PROBE_COLOR=0/1 | default 1` - set colors for a console
 - `PROBE_SRC=<string> | default 127.0.0.1` - set source destination (for `probe-out`)
 - `PROBE_DST=<string> | default 127.0.0.1` - set destination (for `probe-in`)
 - `PROBE_INTERFACE=<string> | default eth3` - set interface on which `tcpdump` should listen on
 - `PROBE_ROOT=0/1 | default 1` - check if running as root

### Copyright

**© 2023 Chimmie Firefly**

#### License

**Akini License 3.1**
