<p float="center">
  <img src="/resources/light-transparent.svg" width="100%" alt="Zee-Kit"/>
</p>

This is a clever word play on the word See and Kit but with Z -- for coolness, lol

If you have a better name please contact me


## How to set-up and use

```bash
py -m pip install z-kit zkit-pygame --upgrade
``` 

### Basic code example

```python
from zkit.renderer import ZKitRenderer
from zkitpg import PygameBackend, register_extension
import pygame
import zkit

# You can either use
register_extension()

renderer = zkit.Renderer(pygame)

# Or call it directly
renderer = ZKitRenderer(PygameBackend)

```
