# Anycubic Kobra Go - Klipper configuration
This is configuration with my collection of macros for Klipper on AKGO.

## A few warnings...
This is configuration that includes my calibrations. So be cautious with it and
take a look at `hardware/calibration.cfg`.

## Installation
Structure of configuration is made so that you include `main.cfg` in
`printer.cfg`. For example, you can do something like this:
```
cd <folder-with-printer.cfg>
git clone https://github.com/mora-unie-youer/anycubic-kobra-go-klipper printer


# And insert in printer.cfg this:
[include printer/main.cfg]
```

Configuration is made with idea that this will replace any included files like
Mainsail's configuration. That's why you need the only line in `printer.cfg`.
