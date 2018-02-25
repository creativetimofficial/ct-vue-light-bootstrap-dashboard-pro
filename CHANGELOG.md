# Change Log

## [1.0.0] 2017-12-28
### Stable Original Release

## [1.1.0] 2018-02-26

- Package updates
- Updated Bootstrap to final release (4.0)
- Fixed disabled button state [#1](https://github.com/creativetimofficial/vue-light-bootstrap-dashboard-pro/issues/1)
- Scope the css for dropdown (moved the css in the dropdown component) [#2](https://github.com/creativetimofficial/vue-light-bootstrap-dashboard-pro/issues/2)
- Remove buggy z-index from element-table [#6](https://github.com/creativetimofficial/vue-light-bootstrap-dashboard-pro/issues/6)
- Refinements for date-pickers to be more inline with lbd design.
- Fixed Progress component key warning for multiple values
- Internet Explorer (10-11) compatibility
- Remove element-variables.scss as it was importing the whole element-ui css. 
If you need to overwrite the variables, please refer to [custom theme docs](http://element.eleme.io/#/en-US/component/custom-theme#cli-theme-tool)
from element ui to generate your own local theme and customize the variables.
We provided custom styles only for the following components: date-picker, select, modal, input, collapse, slider and tags.
