# platform-gd32v
[![Build Status](https://travis-ci.org/sipeed/platform-gd32v.svg?branch=master)](https://travis-ci.org/sipeed/platform-gd32v)
[![Build status](https://ci.appveyor.com/api/projects/status/x71h1eyhiljmngpo?svg=true)](https://ci.appveyor.com/project/btx000/platform-gd32v)

# Usage

1. [Install PlatformIO](http://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](http://docs.platformio.org/page/projectconf.html) file:

## Stable version

```ini
[env:stable]
platform = gd32v
board = ...
...
```

## Development version

```ini
[env:development]
platform = https://github.com/sipeed/platform-gd32v.git
board = ...
...
```

## Manually install

The platform can be installed manually using `pio platform install https://github.com/richardclli/platform-gd32v.git` on [the CLI](https://docs.platformio.org/en/latest/integration/ide/vscode.html#platformio-core-cli). 

# Configuration

Please navigate to [documentation](http://docs.platformio.org/page/platforms/gd32v.html).

