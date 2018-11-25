# Role: time

Configuration of timezone and ntp settings

**Compatibility tested with:**
 * Debian 8
 * Debian 9
 * Fedora 25 Server

## Configuration
| Name | Default value | Description |
|------|---------------|-------------|
|`timezone_area` | `Europe` | Timezone area |
|`timezone` | `Zurich` | Exact timezone (area needs to match) |
|`ntp_servers` | `["time.ethz.ch", "swisstime.ethz.ch"]` | Timeservers. Note that these are only guaranteed to be accessible from inside ETH's network, so you might need to specify different ones. |

## License
GPLv3
