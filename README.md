
# TorLog

TorLog is a Python package for generating colorful and dynamic log messages with neat effects and colors. This package is designed to make logging more visually appealing and engaging.
## Features

- Generate colorful log messages with rainbow effects.
- Customize the smoothness of fading and choose between rainbow or static colors.
- Support for static colors and a variety of predefined colors.
- Easy integration into existing Python projects.

## Installation

You can install TorLog via pip:

```bash
pip install torlog
```

## Usage

Here's a simple example of how to use TorLog to generate colorful log messages:

```python
from torlog import log

log("This is a regular log message with a timestamp!")
```

### Rainbow Effects

You can enable rainbow effects by setting the `rainbow` parameter to `True`:

```python
log("Rainbow message", rainbow=True)
```

### Customizing Fading Speed

Adjust the fading speed by specifying the `interval` parameter (default is 1):

```python
log("Custom interval", interval=2)
```

### Static Colors

You can use static colors by specifying a hex code or a predefined color:

```python
log("Static red color", static="#FF0000")
log("Static blue color", static="blue")
```

## Examples

### Basic Usage

```python
from torlog import log

log("Basic log message with timestamp")
```

### Rainbow Message

```python
log("This message has rainbow colors!", rainbow=True)
```

### Custom Rainbow Interval

```python
log("Custom interval", rainbow=True, interval=2)
```

### Static Color

```python
log("Static red color", static="red")
```
## We also offer a wide range of different colors!
```markdown
- Red Shades:
  - darker_red
  - dark_red
  - red
  - light_red
  - lighter_red

- Green Shades:
  - darker_green
  - dark_green
  - green
  - light_green
  - lighter_green

- Blue Shades:
  - darker_blue
  - dark_blue
  - blue
  - light_blue
  - lighter_blue

- Yellow Shades:
  - darker_yellow
  - dark_yellow
  - yellow
  - light_yellow
  - lighter_yellow

- Orange Shades:
  - darker_orange
  - dark_orange
  - orange
  - light_orange
  - lighter_orange

- Purple Shades:
  - darker_purple
  - dark_purple
  - purple
  - light_purple
  - lighter_purple

- Cyan Shades:
  - darker_cyan
  - dark_cyan
  - cyan
  - light_cyan
  - lighter_cyan

- Magenta Shades:
  - darker_magenta
  - dark_magenta
  - magenta
  - light_magenta
  - lighter_magenta

- Pink Shades:
  - darker_pink
  - dark_pink
  - pink
  - light_pink
  - lighter_pink

- Brown Shades:
  - darker_brown
  - dark_brown
  - brown
  - light_brown
  - lighter_brown

- Gray Shades:
  - darker_gray
  - dark_gray
  - gray
  - light_gray
  - lighter_gray

- Black & White:
  - black
  - white
```

## Example You Can Tamper With
```python
import torlog
import time

for i in range(1000):
    torlog.log(message="test", static="light_yellow")
    time.sleep(0.05)
```

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
