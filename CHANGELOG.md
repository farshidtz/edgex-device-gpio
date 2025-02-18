## EdgeX GPIO Device Service
[Github repository](https://github.com/edgexfoundry/device-gpio)

### Change Logs for EdgeX Dependencies
- [device-sdk-go](https://github.com/edgexfoundry/device-sdk-go/blob/main/CHANGELOG.md)
- [go-mod-core-contracts](https://github.com/edgexfoundry/go-mod-core-contracts/blob/main/CHANGELOG.md)
- [go-mod-bootstrap](https://github.com/edgexfoundry/go-mod-bootstrap/blob/main/CHANGELOG.md)  (indirect dependency)
- [go-mod-messaging](https://github.com/edgexfoundry/go-mod-messaging/blob/main/CHANGELOG.md) (indirect dependency)
- [go-mod-registry](https://github.com/edgexfoundry/go-mod-registry/blob/main/CHANGELOG.md)  (indirect dependency)
- [go-mod-secrets](https://github.com/edgexfoundry/go-mod-secrets/blob/main/CHANGELOG.md) (indirect dependency)
- [go-mod-configuration](https://github.com/edgexfoundry/go-mod-configuration/blob/main/CHANGELOG.md) (indirect dependency)

## [v2.3.0] - Levski - 2022-05-11 - (Only compatible with the 2.x releases)

### Features ✨

- Add Service Metrics configuration ([#9dfec82](https://github.com/edgexfoundry/device-gpio/commits/9dfec82))
- Add NATS configuration and build option ([#32a3024](https://github.com/edgexfoundry/device-gpio/commits/32a3024))
- Add commanding via message configuration ([#b17bad2](https://github.com/edgexfoundry/device-gpio/commits/b17bad2))
- **snap:** add config interface with unique identifier ([#62](https://github.com/edgexfoundry/device-gpio/issues/62)) ([#89403c3](https://github.com/edgexfoundry/device-gpio/commits/89403c3))

### Code Refactoring ♻

- **snap:** edgex-snap-hooks related upgrade ([#49](https://github.com/edgexfoundry/device-gpio/issues/49)) ([#e9c2a01](https://github.com/edgexfoundry/device-gpio/commits/e9c2a01))

### Build 👷

- Upgrade to Go 1.18 and optimize attributiion script ([#e50f883](https://github.com/edgexfoundry/device-gpio/commits/e50f883))

## [v2.2.0] - Kamakura - 2022-05-11 - (Only compatible with the 2.x releases)

### Documentation 📖
- **snap:** Move usage instructions to docs ([#27](https://github.com/edgexfoundry/device-gpio/issues/27)) ([#9aa390b](https://github.com/edgexfoundry/device-gpio/commits/9aa390b))

## [v2.1.0] - Jakarta - 2022-04-13 - (Only compatible with the 2.x releases)
### Features ✨
- Enable security hardening ([#99940ec](https://github.com/edgexfoundry/device-gpio/commits/99940ec))
- **api:** Upgrade to v2 API ([#427c9ef](https://github.com/edgexfoundry/device-gpio/commits/427c9ef))
- **snap:** Bump edgex-snap-hooks to v2.2.0-beta.3 ([#849856e](https://github.com/edgexfoundry/device-gpio/commits/849856e))
- **snap:** Use updated environment variable injection ([#1b28166](https://github.com/edgexfoundry/device-gpio/commits/1b28166))
- **snap:** Snap packaging ([#13](https://github.com/edgexfoundry/device-gpio/issues/13)) ([#7aa6e8d](https://github.com/edgexfoundry/device-gpio/commits/7aa6e8d))
- **snap:** Bump edgex-snap-hooks to v2.2.0-beta.5 ([#55ae9f2](https://github.com/edgexfoundry/device-gpio/commits/55ae9f2))

### Bug Fixes 🐛
- Remove set of direction of a get GPIO or read ([#24](https://github.com/edgexfoundry/device-gpio/issues/24)) ([#b9afc87](https://github.com/edgexfoundry/device-gpio/commits/b9afc87))
- Update all TOML to use quote and not single-quote ([#219ffad](https://github.com/edgexfoundry/device-gpio/commits/219ffad))
- **gpio:** Fix port and logging function ([#a363e2c](https://github.com/edgexfoundry/device-gpio/commits/a363e2c))

### Documentation 📖
- Add badges to readme ([#a2dd072](https://github.com/edgexfoundry/device-gpio/commits/a2dd072))

### Build 👷
- Change from scratch to alpine:3.14 ([#8130ef4](https://github.com/edgexfoundry/device-gpio/commits/8130ef4))
- Update alpine base to 3.14 ([#252a76c](https://github.com/edgexfoundry/device-gpio/commits/252a76c))

### Continuous Integration 🔄
- Go 1.17 related changes ([#4edcf21](https://github.com/edgexfoundry/device-gpio/commits/4edcf21))
- Remove need for CI specific Dockerfile ([#5b9f399](https://github.com/edgexfoundry/device-gpio/commits/5b9f399))
