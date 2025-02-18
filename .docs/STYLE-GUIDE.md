# Style Guide

All our React Components are created using [Material UI](https://mui.com/material-ui/getting-started/overview/) Components. It gives us custom Themed components (see [theme.ts](../theme/theme.ts)) which gives us consistent design across the whole web app. We strictly abide by this style guide to style our components.

### Styling MUI Components

1. **Style any _individual_ MUI component** by using [its `sx` prop](https://mui.com/system/getting-started/the-sx-prop/) and [its `system` props](https://mui.com/system/properties/).
   - We found styling with `sx` prop and `system` props more intuitive. Its used most of the times.
2. If you are **styling _multiple_ MUI components**, or giving complex stylings (e.g styling CSS grids), or adding complex animation, use [SASS modules](https://medium.com/clover-platform-blog/modular-scss-and-why-you-need-it-6bb2d8c40fd8) (You will see a lot of `.module.scss` files in the repo)
   - We use SCSS styling sparingly. Use only whenever necessary.

### Following the Color System and Font System

1. We follow material color system. Follow our [Color System Guide](./COLOR-SYSTEM.md).
2. We follow material Font Type system. Follow out [Type System Guide](./TYPE-SYSTEM.md)
