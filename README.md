# Plymouth Theme Neat

| Default                                          | Password                                           |
| ------------------------------------------------ | -------------------------------------------------- |
| ![Default Screenshot](./screenshots/default.png) | ![Password Screenshot](./screenshots/password.png) |

```sh
sudo cp -rT ./src /usr/share/plymouth/themes/neat
sudo tee /etc/plymouth/plymouthd.conf << EOF > /dev/null
[Daemon]
Theme=neat
DeviceScale=1
EOF
```
