# EdgeX GPIO Device Service Snap
[![edgex-device-gpio](https://snapcraft.io/edgex-device-gpio/badge.svg)](https://snapcraft.io/edgex-device-gpio)

This directory contains the snap packaging of the EdgeX GPIO device service.

The snap is built automatically and published on the Snap Store as [edgex-device-gpio].

For usage instructions, please refer to Device GPIO section in [Getting Started using Snaps][docs].

## Build from source
Execute the following command from the top-level directory of this repo:
```
snapcraft
```

This will create a snap package file with `.snap` extension. It can be installed locally by setting the `--dangerous` flag:
```bash
sudo snap install --dangerous <snap-file>
```

The [snapcraft overview](https://snapcraft.io/docs/snapcraft-overview) provides additional details.

### Obtain a Secret Store token
The `edgex-secretstore-token` snap slot makes it possible to automatically receive a token from a locally installed platform snap.

If the snap is built and installed locally, the interface will not auto-connect. You can check the status of the connections by running the `snap connections edgex-device-gpio` command.

To manually connect and obtain a token:
```bash
sudo snap connect edgexfoundry:edgex-secretstore-token edgex-device-gpio:edgex-secretstore-token
```

Please refer [here][secret-store-token] for further information.


[edgex-device-gpio]: https://snapcraft.io/edgex-device-gpio
[docs]: https://docs.edgexfoundry.org/2.2/getting-started/Ch-GettingStartedSnapUsers/#device-gpio
[secret-store-token]: https://docs.edgexfoundry.org/2.2/getting-started/Ch-GettingStartedSnapUsers/#secret-store-token
