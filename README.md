# [Start Bootstrap - SB Admin 2](https://startbootstrap.com/theme/sb-admin-2/)

[SB Admin 2](https://startbootstrap.com/theme/sb-admin-2/) is an open source admin dashboard theme for [Bootstrap](https://getbootstrap.com/) created by [Start Bootstrap](https://startbootstrap.com/).

For the legacy Bootstrap 3 version of this theme, you can view the [last stable release](https://github.com/StartBootstrap/startbootstrap-sb-admin-2/releases/tag/v3.3.7%2B1) of SB Admin 2 for Bootstrap 3.

## Preview

[![SB Admin 2 Preview](https://assets.startbootstrap.com/img/screenshots/themes/sb-admin-2.png)](https://startbootstrap.github.io/startbootstrap-sb-admin-2/)

**[Launch Live Preview](https://startbootstrap.github.io/startbootstrap-sb-admin-2/)**

## Status

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/StartBootstrap/startbootstrap-sb-admin-2/master/LICENSE)
[![npm version](https://img.shields.io/npm/v/startbootstrap-sb-admin-2.svg)](https://www.npmjs.com/package/startbootstrap-sb-admin-2)
![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/shahryarahmad/startbootstrap-sb-admin-2-dark-light-mode)
![GitHub last commit](https://img.shields.io/github/last-commit/shahryarahmad/startbootstrap-sb-admin-2-dark-light-mode)
## Download and Installation

To begin using this template, choose one of the following options to get started:

- [Download the latest release on Start Bootstrap](https://startbootstrap.com/theme/sb-admin-2/)
- Install via npm: `npm i startbootstrap-sb-admin-2`
- Clone the repo: `git clone https://github.com/StartBootstrap/startbootstrap-sb-admin-2.git`
- [Fork, Clone, or Download on GitHub](https://github.com/StartBootstrap/startbootstrap-sb-admin-2)

## Usage

After installation, run `npm install` and then run `npm start` which will open up a preview of the template in your default browser, watch for changes to core template files, and live reload the browser when changes are saved. You can view the `gulpfile.js` to see which tasks are included with the dev environment.

### Gulp Tasks

- `gulp` the default task that builds everything
- `gulp watch` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp css` compiles SCSS files into CSS and minifies the compiled CSS
- `gulp js` minifies the themes JS file
- `gulp vendor` copies dependencies from node_modules to the vendor directory

You must have npm installed globally in order to use this build environment. This theme was built using node v11.6.0 and the Gulp CLI v2.0.1. If Gulp is not running properly after running `npm install`, you may need to update node and/or the Gulp CLI locally.

## Bugs and Issues

Have a bug or an issue with this template? [Open a new issue](https://github.com/shahryarahmad/startbootstrap-sb-admin-2-dark-light-mode/pulls) here on GitHub or leave a comment on the [template overview page at Start Bootstrap](https://shahryarahmad.github.io/startbootstrap-sb-admin-2-dark-light-mode/).

## About

Start Bootstrap is an open source library of free Bootstrap templates and themes. All of the free templates and themes on Start Bootstrap are released under the MIT license, which means you can use them for any purpose, even for commercial projects.

- <https://startbootstrap.com>
- <https://twitter.com/SBootstrap>

Start Bootstrap was created by and is maintained by **[David Miller](https://davidmiller.io/)**.

- <https://davidmiller.io>
- <https://twitter.com/davidmillerhere>
- <https://github.com/davidtmiller>

Start Bootstrap is based on the [Bootstrap](https://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

Copyright 2013-2021 Start Bootstrap LLC. Code released under the [MIT](https://github.com/StartBootstrap/startbootstrap-resume/blob/master/LICENSE) license.

Changes made for dark-mode
--------------------------

- used color `#111827` for menu and footer background
- `class` used for dark menu `bg-dark-menu`
  removed background `bg-gradient-primary`
- used `#1F2937` for page background
### Changes for dark-mode in index page
- id  `accordionSidebar` removed `bg-gradient-primary` added `bg-menu-dark`
- id  `collapseTwo` class removed  `bg-white` added `bg-dark-mode`
- id `collapseUtilities` removed `bg-white` added `bg-dark-dropdown`
- id `collapsePages` removed `bg-white` added `bg-dark-dropdown`
- class `navbar` removed `bg-white` added `bg-dark-menu` and `shadow-light`
- id `searchButton` removed `btn-primary` added `bg-dark` `text-white`
- id `DropdownSearchBox` added `bg-dark-menu`
- id `mobileSearch` removed `bg-white` added `bg-dark-mode`
- id `navAlertDropDown` added `bg-dark-mode`
- id `messageCenterDropDown` added `bg-dark-mode`
- id `userNameSpan` removed `text-gray-600` added `text-white`
- id `pageHeading` removed `text-gray-800` added `text-white`
- id `cardMonthlyHead` added `bg-transparent`
- id `cardMonthly` removed `text-gray-800` added `text-white`
- id `cardAnnualHead` added `bg-transparent`
- id `cardAnnual` removed `text-gray-800` added `text-white`
- id `cardTasksHead` added `bg-transparent`
- id `cardTasks` removed `text-gray-800`, `text-white`
- id `cardPendingRequestHead` added `bg-transparent`
- id `cardPendingRequest` removed `text-gray-80` added `text-white`
- id `cardAreaChart` added `bg-transparent` 
- id `cardAreaChartHeader` added `bg-transparent`
- id `cardAreaChartHeaderdropdown`, `bg-dark-mode`
- id `cardPieChart` added `bg-transparent`
- id `cardPieChartHeader` added `bg-transparent`
- id `cardPieChartHeaderDropDown` added `bg-dark-mode`
- id `cardProject` added `bg-transparent`
- id `cardProjectHeader` added `bg-transparent`, `text-white`
- id `cardIllustrations` added `bg-transparent`, `text-white`
- id `cardIllustrationsHeader` added `bg-transparent`
- id `cardApproach` added `bg-transparent`, `text-white`
- id `cardApproachHeader` added `bg-transparent`
- class sticky-footer added `bg-dark-menu`, `shadow-light` and `text-white`