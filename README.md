# Plymouth Theme Neat

HiDPI-Friendly Plymouth Theme for Arch Linux

| Default                                          | Password                                           |
| ------------------------------------------------ | -------------------------------------------------- |
| ![Default Screenshot](./screenshots/default.png) | ![Password Screenshot](./screenshots/password.png) |

```sh
paru -S --needed plymouth-theme-neat
sudo plymouth-set-default-theme neat
echo "DeviceScale=1" | sudo tee -a /etc/plymouth/plymouthd.conf
sudo mkinitcpio -P
```
