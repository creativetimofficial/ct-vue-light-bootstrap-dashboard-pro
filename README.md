# [Vue Light Bootstrap Dashboard PRO](https://www.creative-tim.com/product/vue-light-bootstrap-dashboard-pro) [![version][version-badge]][CHANGELOG]

![alt text](https://s3.amazonaws.com/creativetim_bucket/products/69/original/opt_lbdp_vue_thumbnail.jpg?1514476712

**[Vue Light Bootstrap Dashboard PRO](https://www.creative-tim.com/product/vue-light-bootstrap-dashboard-pro)** is a beautiful resource built over Bootstrap and Vue. 
It will help you get started developing dashboards in no time.

Vue Light Bootstrap Dashboard Pro is the Vue.js ported version of the [Original Light Bootstrap Dashboard Pro](https://www.creative-tim.com/product/light-bootstrap-dashboard-pro).
Using the Dashboard is pretty simple but requires basic knowledge of Javascript, [Vue](https://vuejs.org/v2/guide/) and [Vue-Router](https://router.vuejs.org/en/).
Vue Paper Dashboard was coded by [Cristi Jora](https://github.com/cristijora) and the design was made by [Creative Tim](https://www.creative-tim.com/). 
The product represents a big suite of front-end developer tools that can help you jump start your project. We have created it thinking about things you actually need in a dashboard. Vue Light Bootstrap Dashboard PRO contains handpicked and optimised Vuejs plugins. Everything is designed to fit with one another. As you will be able to see, the dashboard you can access on Creative Tim is a customisation of this product.

We like consistency and design that blends into its purpose. 
Vue Light Bootstrap Dashboard PRO is a perfect example of our most thoughtful work. It combines Vue.js components and plugins, while looking like everything fits together.
For an easy start or inspiration for you project, we have also create a set of example pages, like the user settings or usage graphics.

It comes with 6 filter colors for the sidebar (“black”, “azure”,”green”,”orange”,”red”,”purple”) and an option to have a background image.

Let us know what you think and what we can improve below. And good luck with development!

## Links:

+ [Live Preview](http://vuejs.creative-tim.com/vue-light-bootstrap-dashboard-pro)

## Quick Start:

Quick start options:

+ [Download from Creative Tim](https://www.creative-tim.com/product/vue-light-bootstrap-dashboard-pro).
+ Make sure you have [Node js](https://nodejs.org/en/) installed
+ Go to the downloaded folder and open a terminal
+ Type `npm install` or `yarn install` if you use [yarn](https://yarnpkg.com/en/)
+ Type `npm run dev` to start a development server

The repo uses [vue-cli](https://github.com/vuejs/vue-cli) scaffolding which takes care of the development setup with webpack and all the necessary modern tools to make web development faster and easier.

Other Products:

+ [Download FREE Vue Version](https://www.creative-tim.com/product/vue-light-bootstrap-dashboard).

### What's included

Within the download you'll find the following directories and files:
```
|-- src
    |-- App.vue
    |-- globalComponents.js
    |-- globalDirectives.js
    |-- light-bootstrap-main.js
    |-- main.js
    |-- assets
    |   |-- css
    |   |   |-- demo.css
    |   |-- sass
    |       |-- element_variables.scss
    |       |-- light-bootstrap-dashboard.scss
    |       |-- lbd
    |           |-- _alerts.scss
    |           |-- _bootstrap-switch.scss
    |           |-- _buttons.scss
    |           |-- _cards.scss
    |           |-- _chartist.scss
    |           |-- _checkbox-radio-switch.scss
    |           |-- _dropdown.scss
    |           |-- _fixed-plugin.scss
    |           |-- _footers.scss
    |           |-- _inputs.scss
    |           |-- _misc.scss
    |           |-- _mixins.scss
    |           |-- _modal.scss
    |           |-- _navbars.scss
    |           |-- _pages.scss
    |           |-- _progress_bars.scss
    |           |-- _responsive.scss
    |           |-- _sidebar-and-main-panel.scss
    |           |-- _social-buttons.scss
    |           |-- _tables.scss
    |           |-- _tabs-navs-pagination.scss
    |           |-- _tooltip.scss
    |           |-- _typography.scss
    |           |-- _variables.scss
    |           |-- element
    |           |   |-- _collapse.scss
    |           |   |-- _date_picker.scss
    |           |   |-- _input.scss
    |           |   |-- _select.scss
    |           |   |-- _slider.scss
    |           |   |-- _tables.scss
    |           |   |-- _tags.scss
    |           |-- mixins
    |           |   |-- _bootstrap_switch.scss
    |           |   |-- _buttons.scss
    |           |   |-- _cards.scss
    |           |   |-- _chartist.scss
    |           |   |-- _icons.scss
    |           |   |-- _inputs.scss
    |           |   |-- _labels.scss
    |           |   |-- _morphing-buttons.scss
    |           |   |-- _navbars.scss
    |           |   |-- _pagination.scss
    |           |   |-- _social-buttons.scss
    |           |   |-- _table-row.scss
    |           |   |-- _tabs.scss
    |           |   |-- _transparency.scss
    |           |   |-- _vendor-prefixes.scss
    |           |-- plugins
    |               |-- _animate.scss
    |               |-- _chartist.scss
    |               |-- _fullcalendar.scss
    |               |-- _jquery.jvectormap.scss
    |               |-- _perfect-scrollbar.scss
    |               |-- _sweetalert2.scss
    |               |-- _vue-tabs.scss
    |-- components
    |   |-- Dashboard
    |   |   |-- Layout
    |   |   |   |-- Content.vue
    |   |   |   |-- ContentFooter.vue
    |   |   |   |-- DashboardLayout.vue
    |   |   |   |-- LoadingMainPanel.vue
    |   |   |   |-- MobileMenu.vue
    |   |   |   |-- TopNavbar.vue
    |   |   |   |-- UserMenu.vue
    |   |   |-- Views
    |   |       |-- Charts.vue
    |   |       |-- Calendar
    |   |       |   |-- Calendar.vue
    |   |       |   |-- CalendarRoute.vue
    |   |       |-- Components
    |   |       |   |-- Buttons.vue
    |   |       |   |-- GridSystem.vue
    |   |       |   |-- Icons.vue
    |   |       |   |-- Notifications.vue
    |   |       |   |-- Panels.vue
    |   |       |   |-- SweetAlert.vue
    |   |       |   |-- Typography.vue
    |   |       |-- Dashboard
    |   |       |   |-- Overview.vue
    |   |       |   |-- Stats.vue
    |   |       |   |-- Stats
    |   |       |       |-- Task.vue
    |   |       |       |-- TaskList.vue
    |   |       |       |-- TimeLine.vue
    |   |       |       |-- TimeLineItem.vue
    |   |       |-- Forms
    |   |       |   |-- ExtendedForms.vue
    |   |       |   |-- RegularForms.vue
    |   |       |   |-- ValidationForms.vue
    |   |       |   |-- Wizard.vue
    |   |       |   |-- ValidationForms
    |   |       |   |   |-- LoginForm.vue
    |   |       |   |   |-- RegisterForm.vue
    |   |       |   |   |-- TypeValidationForm.vue
    |   |       |   |-- Wizard
    |   |       |       |-- FirstStep.vue
    |   |       |       |-- SecondStep.vue
    |   |       |-- Maps
    |   |       |   |-- API_KEY.js
    |   |       |   |-- FullScreenMap.vue
    |   |       |   |-- GoogleMaps.vue
    |   |       |   |-- VectorMaps.vue
    |   |       |   |-- VectorMapsPage.vue
    |   |       |   |-- WorldMap.vue
    |   |       |   |-- world_map.js
    |   |       |-- Pages
    |   |       |   |-- AuthLayout.vue
    |   |       |   |-- Lock.vue
    |   |       |   |-- Login.vue
    |   |       |   |-- Register.vue
    |   |       |   |-- TimeLinePage.vue
    |   |       |   |-- UserProfile.vue
    |   |       |   |-- background-2.jpg
    |   |       |   |-- UserProfile
    |   |       |       |-- EditProfileForm.vue
    |   |       |       |-- UserCard.vue
    |   |       |-- Tables
    |   |           |-- ExtendedTables.vue
    |   |           |-- PaginatedTables.vue
    |   |           |-- RegularTables.vue
    |   |           |-- users.js
    |   |-- GeneralViews
    |   |   |-- NotFoundPage.vue
    |   |-- UIComponents
    |       |-- Dropdown.vue
    |       |-- Pagination.vue
    |       |-- Progress.vue
    |       |-- Switch.vue
    |       |-- Table.vue
    |       |-- index.js
    |       |-- Breadcrumb
    |       |   |-- Breadcrumb.vue
    |       |   |-- BreadcrumbItem.vue
    |       |-- Cards
    |       |   |-- Card.vue
    |       |   |-- ChartCard.vue
    |       |   |-- CircleChartCard.vue
    |       |   |-- StatsCard.vue
    |       |-- Inputs
    |       |   |-- Checkbox.vue
    |       |   |-- Radio.vue
    |       |   |-- formGroupInput.vue
    |       |-- SidebarPlugin
    |       |   |-- SideBar.vue
    |       |   |-- SidebarItem.vue
    |       |   |-- index.js
    |       |-- Transitions
    |           |-- FadeRenderTransition.vue
    |-- routes
        |-- routes.js
```

## Useful Links

More products from Creative Tim: <https://www.creative-tim.com/bootstrap-themes>

Tutorials: <https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w>

Freebies: <https://www.creative-tim.com/products>

Affiliate Program (earn money): <https://www.creative-tim.com/affiliates/new>

Social Media:

Twitter: <https://twitter.com/CreativeTim>

Facebook: <https://www.facebook.com/CreativeTim>

Dribbble: <https://dribbble.com/creativetim>

Google+: <https://plus.google.com/+CreativetimPage>

Instagram: <https://instagram.com/creativetimofficial>

[CHANGELOG]: ./CHANGELOG.md
[version-badge]: https://img.shields.io/badge/version-1.1.0-blue.svg
