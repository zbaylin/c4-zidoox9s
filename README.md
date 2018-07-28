# c4-zidoox9s
A Control4 Remote driver for the Zidoo X9S and other Zidoo boxes that use the [HTTP API](https://www.zidoo.tv/Support/developer.html).

## Info
🚧 This is strictly a control driver (at this point). If you wish to also have a driver that will provide an interface into the ZDMC/Theater apps on the box, take a look at the [driver provided by Zidoo](https://www.zidoo.tv/Support/control4.html). 🚧

This is a Control4 Remote driver for the Zidoo X9S, and any other Zidoo box that uses the HTTP API [documented here](https://www.zidoo.tv/Support/developer.html). Zidoo's OEM driver is good for playing movies directly from the remote, but isn't as good for directly controlling the box itself. This driver aims to fix that.

## Installation
1. Open Control4 composer and Click "Add or Update Driver" in the driver menu
2. Use the Driver pane on the right to search for the driver.
3. Drag the driver to the correct room in the project
4. Enter the IP of the Zidoo box you wish to control in the `DRIVER_IP` property.

## Contributing
If you would like to add a feature to this driver, you will most likely need Control4's Driver Editor software (I can't post it here, Google it). Before submitting a PR, make sure the driver still functions as expected in Control4 Composer Pro (again, Google it 😉).

## Maintainers
Zach Baylin - [me@zachbayl.in](mailto:me@zachbayl.in)