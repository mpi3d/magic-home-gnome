# Magic Home Gnome

Program to change Magic Home led colors based on the current application color.

## Dependencies

This program require Python 3.8 or newer

It need [flux_led](https://github.com/Danielhiversen/flux_led)

```sh
pip install flux_led
```

It also need to get access to Gnome Shell introspection to get the current applications

```sh
gsettings set org.gnome.shell introspect true
```

## Usage

```
cd magic-home-gnome
chmod +x magic-home-gnome
./magic-home-gnome
```
