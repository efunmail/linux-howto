## See BATTERY info

- NOTE: assumes *only one* battery - re: `BAT`

```sh
upower -i $(upower -e | grep BAT) | less
```
