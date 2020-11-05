# pyST7920
Python library to control ST7920 128x64 monochrone LCD panel using Raspberry Pi and SPI

## Getting started

### Install required packages
> pip install pypng

> pip install spidev

## Usage

```
from st7920 import ST7920

s = ST7920()

s.clear()
s.put_text("Hello world!", 5, 10)
s.redraw()
```
