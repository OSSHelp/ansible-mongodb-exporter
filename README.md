# mongodb-exporter

[![Build Status](https://drone.osshelp.ru/api/badges/ansible/mongodb-exporter/status.svg)](https://drone.osshelp.ru/ansible/mongodb-exporter)

Role for [mongodb_exporer](https://github.com/percona/mongodb_exporter) installation and configuration.

## Usage (example)

```yaml
    - role: mongodb-exporter
```

## Available parameters

### Main

Short description here.

| Param | Default | Description |
| -------- | -------- | -------- |
| `mongodb_exporter_setup` | `full` | Setup mode. See [OSSHelp KB article](https://oss.help/kb4895) |
| `mongodb_exporter_version`| `0.11.0` | Which version to install. |
| `mongodb_exporter_pass` | `passw0rd` | Password for MongoDB user, using by exporter. Must be in secrets. |

### Misc

Short description here.

| Param | Default | Description |
| -------- | -------- | -------- |
| `mongodb_exporter_uri` | `'mongodb://mongodb_exporter:passw0rd@localhost:27017/admin'` | sets MONGODB_URI in exporter config |
| `mongodb_exporter_http_auth` | `''` | sets HTTP_AUTH in exporter config |

## FAQ

None, so far.

## Useful links

- [Official documentation](https://github.com/percona/mongodb_exporter/blob/master/README.md)
- [Our article](https://oss.help/kb5264)

## TODO

None, so far.

## License

GPL3

## Author

OSSHelp Team, see <https://oss.help>
