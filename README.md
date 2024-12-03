# Tim's kanata layout

- kanata project: https://github.com/jtroo/kanata
- kanata config guide: https://github.com/jtroo/kanata/blob/main/docs/config.adoc

## How to run

- Run [Karabiner-VirtualHIDDevice-Manager](https://github.com/pqrs-org/Karabiner-DriverKit-VirtualHIDDevice):
```
/Applications/.Karabiner-VirtualHIDDevice-Manager.app/Contents/MacOS/Karabiner-VirtualHIDDevice-Manager activate
```
- Run [Karabiner-VirtualHIDDevice-Daemon](https://github.com/pqrs-org/Karabiner-DriverKit-VirtualHIDDevice) (until this [issue](https://github.com/jtroo/kanata/issues/1317) is fixed):
```
sudo '/Library/Application Support/org.pqrs/Karabiner-DriverKit-VirtualHIDDevice/Applications/Karabiner-VirtualHIDDevice-Daemon.app/Contents/MacOS/Karabiner-VirtualHIDDevice-Daemon'
```
- Start kanata: `sudo ./kanata -c kanata.kbd`
- (Start kanata in debug mode: `sudo ./kanata -c kanata.kbd -d`)

> [!IMPORTANT]
> Important: quit Karabiner Elements before using
