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
 - `PROBE_RAINBOW=0/1 | default 1` - enable rainbow texts

### Commands

 - `log <ID>` - show log file from ID
 - `rmlog <ID>` - remove specific log
 - `rmlogs` - remove all logs
 - `help` - show help output

### Logging

All stderrors are being saved under `$HOME/.cache/xaviama/tcp-probe/*log*`. If `$HOME` doesn't exists - it will save under `/tmp`.

### Copyright

**© 2023 Chimmie Firefly**

#### License

**Akini License 3.1**
