# Bootstrap No Components
Just bootstrap css but with no components. Created because I needed all of non components css from bootstrap.

What all it includes? **Bootstrap Grid + Other Utilites not in Grid**

I compiled the following to create it:
```scss
@import "functions";
@import "variables";

@import "mixins/background-variant";
@import "mixins/hover";
@import "mixins/deprecate";
@import "mixins/clearfix";
@import "mixins/screen-reader";
@import "mixins/text-emphasis";
@import "mixins/text-hide";
@import "mixins/text-truncate";
@import "mixins/breakpoints";
@import "mixins/grid-framework";
@import "mixins/grid";

@import "grid";
@import "utilities";

```
