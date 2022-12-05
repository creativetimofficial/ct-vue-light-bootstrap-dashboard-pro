# Change Log

# [1.4.2] 2022-12-05
- Update dependencies and dep-dependencies
- Fix the installtion issue when running `npm i`
- Migration to `sass` from `node-sass`

# [1.4.1] 2022-02-25
- Update all dependencies with newer versions available
- `node-sass` deprecation package remove
- `sass` package add
- clean all scss files for `sass` package properly running 

# [1.4.0] 2021-08-27
- Update all dependencies
- FullCalendar syntax update

# [1.3.1] 2020-08-10
- SweetAlert library fix
- PerfectScrollbar library fix
- Delete `build` & `config`

# [1.3.0] 2020-06-24
- Update all dependencies to latest versions
- `FullCalendar`, `Vee-Validate`, `Google Maps` plugins updated to new syntax

## [1.2.0] 2019-01-05

### Breaking changes
- Update to Vue CLI 3
- Updated Full Calendar, Vector map and some other components
- Removed jquery from code base
- Added new Button component

### Updates & fixes
- Update packages
- 3, 19 Add polyfills for IE compat
- 13 Add static alert component
- 21 Fix date range picker css ui issue
- Add new button component
- 20 Fix sweetalert css, update sweet alert package

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


## [1.0.0] 2017-12-28
### Stable Original Release
