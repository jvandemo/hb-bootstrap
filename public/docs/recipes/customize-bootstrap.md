# How to customize Bootstrap

Bootstrap boilerplate for Harp lets you completely customize Bootstrap for each individual theme.

To reduce CSS bloat, Bootstrap boilerplate for Harp lets you select the exact Bootstrap components you wish to include for each theme.

## _bootstrap.less

Each theme contains a `_bootstrap.less` file with all Bootstrap components you wish to include for that specific theme.

To leave dropdowns and button-groups for a theme, simply comment out the following line in the `_bootstrap.less` inside the theme folder:

```less
@import "../../../bower/bootstrap/less/component-animations";
@import "../../../bower/bootstrap/less/glyphicons";
// @import "../../../bower/bootstrap/less/dropdowns";
// @import "../../../bower/bootstrap/less/button-groups";
@import "../../../bower/bootstrap/less/input-groups";
@import "../../../bower/bootstrap/less/navs";
@import "../../../bower/bootstrap/less/navbar";
```

That's all there is to it!

Very simple yet extremely powerful!