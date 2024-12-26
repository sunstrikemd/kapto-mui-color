### `<ColorPicker/>`

A popover component to display a color tool box. It uses `ColorBox` and `material-ui-popup-state`.

```javascript
import { ColorPicker } from "mui-color";

export const Container = () => (
  <div>
    <ColorPicker defaultValue="transparent" />
  </div>
);
```

At first it display a button + an input

[ColorPicker documentation](https://mikbry.github.io/mui-color/?path=/story/components-colorpicker--basic)

### `<ColorBox />`

A component to display a color tool box

```javascript
import { ColorBox } from "mui-color";

export const Container = () => (
  <div>
    <ColorBox defaultValue="transparent" />
  </div>
);
```

[ColorBox documentation](https://mikbry.github.io/mui-color/?path=/story/components-colorbox--basic)

### `<ColorInput />`

An input component to display/edit color values in different format (plain, hex, rgb, hsl, hsv).

```javascript
import { ColorInput } from "mui-color";

export const Container = () => (
  <div>
    <ColorInput defaultValue="red" />
  </div>
);
```

[ColorInput documentation](https://mikbry.github.io/mui-color/?path=/story/components-colorinput--basic)

### `<ColorPalette />`

A component to display a grid of color buckets.

```javascript
import { ColorPalette } from "mui-color";

const palette = {
  red: "#ff0000",
  blue: "#0000ff",
  green: "#00ff00",
  yellow: "yellow",
  cyan: "cyan",
  lime: "lime",
  gray: "gray",
  orange: "orange",
  purple: "purple",
  black: "black",
  white: "white",
  pink: "pink",
  darkblue: "darkblue",
};

export const Container = () => (
  <div>
    <ColorPalette palette={palette} />
  </div>
);
```

[ColorPalette documentation](https://mikbry.github.io/mui-color/?path=/story/components-colorpalette--basic)

### `<ColorButton />`

Displays a button filled with a color

```javascript
import { ColorButton } from "mui-color";

export const Container = () => (
  <div>
    <ColorButton color="red" />
  </div>
);
```

[ColorButton documentation](https://mikbry.github.io/mui-color/?path=/story/components-colorbutton--basic)

## Roadmap

### v1.1.3 - [Current version](https://github.com/sunstrike/kapto-mui-color/releases/tag/v1.0.0)

- remove `styled-components` to have less dependencies and reduce size
- display wrong color using a red checked box
- bugs fixes

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

Released under MIT License
