## undefined
Tooltip or a hint when hovering over a UI item. 
    The tooltip will render when hovering on top of the 
    Tip child node or string.

[![](https://cdn-images-1.medium.com/fit/c/120/120/1*TD1P0HtIH9zF0UEH28zYtw.png)](https://storybook.grommet.io/?selectedKind=Tip&full=0&addons=0&stories=1&panelRight=0) [![](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/github/grommet/grommet-sandbox?initialpath=/tip&module=%2Fsrc%2FTip.js)
## Usage

```javascript
import { Tip } from 'grommet';
<Tip />
```

## Properties

**content**

The tooltip content inside the drop.

```
node
```

**dropProps**

Any valid Drop prop to style the Tip drop container.

```
object
```
  
## Intrinsic element

```
span
```
## Theme
  
**tip**

Any valid Drop property for the Tip. Expects `object`.

Defaults to

```
undefined
```

**tip.container**

Any valid Box property for the Tip container. Expects `object`.

Defaults to

```
{ round: 'small', elevation: 'small' }
```

**global.edgeSize**

The possible sizes for margin. Expects `object`.

Defaults to

```
{
    edgeSize: {
      none: '0px',
      hair: '1px',
      xxsmall: '3px',
      xsmall: '6px',
      small: '12px',
      medium: '24px',
      large: '48px',
      xlarge: '96px',
      responsiveBreakpoint: 'small',
    },
  }
```