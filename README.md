# @kurkle/color

## Overview

NOTE: WIP, not released yet.

Fast and small CSS color parsing and manipulation library.

## Parsing

Supported formats:

- named

```text
blue
transparent
```

- hex

```text
#aaa
#bbba
#1A2b3c
#f1f2f388
```

- rgb(a)

```text
rgb(255, 255, 255)
rgb(255, 0, 0, 0.5)
rgb(50%, 50%, 50%, 50%)
rgb(0 0 100% / 80%)
rgba(200, 20, 233, 0.2)
```

- hsl(a)

```text
hsl(240deg, 100%, 50.5%)
hsl(0deg 100% 50%)
hsla(12, 10%, 50%, .3)
```

- hwb

```text
hwb(240, 100%, 50.5%)
hwb(244, 100%, 100%, 0.6)
```

## License

`@kurkle/color` is available under the [MIT license](LICENSE.md).
