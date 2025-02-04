---
title: Release notes
section: overview
hideTOC: true
---

# 2019.10 release notes (2019-11-25)
Packages released:
- [@patternfly/react-catalog-view-extension@1.1.38](https://www.npmjs.com/package/@patternfly/react-catalog-view-extension/v/1.1.38)
- [@patternfly/react-charts@5.2.2](https://www.npmjs.com/package/@patternfly/react-charts/v/5.2.2)
- [@patternfly/react-core@3.124.1](https://www.npmjs.com/package/@patternfly/react-core/v/3.124.1)
- [@patternfly/react-inline-edit-extension@2.13.9](https://www.npmjs.com/package/@patternfly/react-inline-edit-extension/v/2.13.9)
- [@patternfly/react-styles@3.6.11](https://www.npmjs.com/package/@patternfly/react-styles/v/3.6.11)
- [@patternfly/react-table@2.24.41](https://www.npmjs.com/package/@patternfly/react-table/v/2.24.41)
- [@patternfly/react-tokens@2.7.10](https://www.npmjs.com/package/@patternfly/react-tokens/v/2.7.10)
- [@patternfly/react-topology@2.11.27](https://www.npmjs.com/package/@patternfly/react-topology/v/2.11.27)
- [@patternfly/react-virtualized-extension@1.3.40](https://www.npmjs.com/package/@patternfly/react-virtualized-extension/v/1.3.40)
- [@patternfly/react-icons@3.14.23](https://www.npmjs.com/package/@patternfly/react-icons/v/3.14.23)

## Charts
- Put back the secondary title when showing percentage in the Donut Chart([#3299](https://github.com/patternfly/patternfly-react/pull/3299))
- Added Interactive legend example ([#3253](https://github.com/patternfly/patternfly-react/pull/3253))

## Components
- **About modal:**
   - Removed appendTo from props passed to div ([#3239](https://github.com/patternfly/patternfly-react/pull/3239))
- **Accordion:**  
  - Added a prop to allow the box shadow to be removed ([#3309](https://github.com/patternfly/patternfly-react/pull/3309))
- **Button:**  
  - Added support for setting tab index unless not button and disabled ([#3240](https://github.com/patternfly/patternfly-react/pull/3240))
- **Data toolbar:**  
  - Moved and wrapped chips in expandable content ([#3319](https://github.com/patternfly/patternfly-react/pull/3319))
- **Dropdown:**  
  - Added split button action variant ([#3307](https://github.com/patternfly/patternfly-react/pull/3307))
  - Updated keyboard interaction ([#3293](https://github.com/patternfly/patternfly-react/pull/3293))
- **Flex:**
  - In breakpointMods, set the breakpoint as optional and added enums  ([#3258](https://github.com/patternfly/patternfly-react/pull/3258))
  - Fixed typo in align and justify modifiers ([#3328](https://github.com/patternfly/patternfly-react/pull/3328))
- **Form:** 
  - Added validated variant to form inputs ([#3220](https://github.com/patternfly/patternfly-react/pull/3220))
- **Options menu:**
  - Removed the `<i>` element around selected item svg ([#3238](https://github.com/patternfly/patternfly-react/pull/3238))
- **Pagination:**
  - Fixed previous page navigation issues with 1 row per page ([#3297](https://github.com/patternfly/patternfly-react/pull/3297))
- **Select:**
  - Fixed displaying pre-selected input ([#3305](https://github.com/patternfly/patternfly-react/pull/3305))
  - Added the ability to have custom content in the select menu ([#3333](https://github.com/patternfly/patternfly-react/pull/3333))
  - Removed `<form>` from typeahead and checkbox selects ([#3298](https://github.com/patternfly/patternfly-react/pull/3298))
- **Wizard:**
  - Removed appendTo from props passed to div ([#3239](https://github.com/patternfly/patternfly-react/pull/3239))

## Catalog view extension
- **Chore:**
    - Added @patternfly/react-catalog-view-extension package to release promotion script ([#3260](https://github.com/patternfly/patternfly-react/pull/3260))
    - Removed unused packages ([#3332](https://github.com/patternfly/patternfly-react/pull/3332))
    - fixed checbox margin on filter side panel ([#3287](https://github.com/patternfly/patternfly-react/pull/3287))
    - fixed @types errors when using the extension ([#3284](https://github.com/patternfly/patternfly-react/pull/3284))
    - Removed unused dev dependencies from package.json ([#3275](https://github.com/patternfly/patternfly-react/pull/3275))
    - Added check for sass changes ([#3271](https://github.com/patternfly/patternfly-react/pull/3271))
- **Catalog tile:**  
    - Removed unneeded selector ([#3331](https://github.com/patternfly/patternfly-react/pull/3331))
    - Edited target selector ([#3291](https://github.com/patternfly/patternfly-react/pull/3291))
    - Removed margin and fixed hidden text ([#3285](https://github.com/patternfly/patternfly-react/pull/3285))
    - Updated scss and add class to image ([#3282](https://github.com/patternfly/patternfly-react/pull/3282))
- **Properties side panel:**
  - Aligned sass file with correct styles for properties panel ([#3236](https://github.com/patternfly/patternfly-react/pull/3236))

## Table
- Added types, examples, and demo for onRowClick ([#3265](https://github.com/patternfly/patternfly-react/pull/3265))
- Fixed types for table transforms ([#3203](https://github.com/patternfly/patternfly-react/pull/3203))

## Topology
- Set topology container to take full height of the view ([#3314](https://github.com/patternfly/patternfly-react/pull/3314))

## Other
- **Chore:** 
  - Updated gatsby-browser.js ([#3313](https://github.com/patternfly/patternfly-react/pull/3313))
  - Added use of node 10, more resources for doc build ([#3278](https://github.com/patternfly/patternfly-react/pull/3278))
  - Added new package to promotion script ([#3260](https://github.com/patternfly/patternfly-react/pull/3260))
  - Updated github templates ([#3261](https://github.com/patternfly/patternfly-react/pull/3261))
  - Upgraded react-bootstrap to fix React deprecated lifecycle method warnings ([#3249](https://github.com/patternfly/patternfly-react/pull/3249))
- **Demo:**  
  - Updated Pagination Table demo to add Spinner and empty state ([#3294](https://github.com/patternfly/patternfly-react/pull/3294))
- **Demo-app-ts:**  
  - Increased strict checks for react-integration ([#3222](https://github.com/patternfly/patternfly-react/pull/3222))
- **Docs:**  
  - Bumped gatsby-theme-patternfly-org  ([#3269](https://github.com/patternfly/patternfly-react/pull/3269))
  - fix(README.md) ([#3254](https://github.com/patternfly/patternfly-react/pull/3254))

## PF3
  - **Date and time picker:** 
    - Properly imported formatTime to DateTimePicker ([#3303](https://github.com/patternfly/patternfly-react/pull/3303))

# 2019.09 release notes (2019-11-01)
Packages released:
- [@patternfly/react-catalog-view-extension@1.1.5](https://www.npmjs.com/package/@patternfly/react-catalog-view-extension/v/1.1.5)
- [@patternfly/react-charts@5.1.5](https://www.npmjs.com/package/@patternfly/react-charts/v/5.1.5)
- [@patternfly/react-core@3.120.5](https://www.npmjs.com/package/@patternfly/react-core/v/3.120.5)
- [@patternfly/react-inline-edit-extension@2.12.17](https://www.npmjs.com/package/@patternfly/react-inline-edit-extension/v/2.12.17)
- [@patternfly/react-styles@3.6.5](https://www.npmjs.com/package/@patternfly/react-styles/v/3.6.5)
- [@patternfly/react-table@2.24.17](https://www.npmjs.com/package/@patternfly/react-table/v/2.24.17)
- [@patternfly/react-tokens@2.7.5](https://www.npmjs.com/package/@patternfly/react-tokens/v/2.7.5)
- [@patternfly/react-topology@2.11.5](https://www.npmjs.com/package/@patternfly/react-topology/v/2.11.5)
- [@patternfly/react-virtualized-extension@1.3.17](https://www.npmjs.com/package/@patternfly/react-virtualized-extension/v/1.3.17)
- [@patternfly/react-icons@3.14.18](https://www.npmjs.com/package/@patternfly/react-icons/v/3.14.18)

## Charts
- Added legend examples ([#3093](https://github.com/patternfly/patternfly-react/pull/3093))
- Added chart scatter examples ([#3086](https://github.com/patternfly/patternfly-react/pull/3086))
- Updated ChartThreshold to use pf-core variable ([#3085](https://github.com/patternfly/patternfly-react/pull/3085))
- Updates to use markdown links ([#3072](https://github.com/patternfly/patternfly-react/pull/3072))
- Simplified legend tooltip example ([#3069](https://github.com/patternfly/patternfly-react/pull/3069))
- Added Responsive legend ([#3067](https://github.com/patternfly/patternfly-react/pull/3067))
- Added tooltip examples ([#3061](https://github.com/patternfly/patternfly-react/pull/3061))
- Added props to ChartLabel ([#3028](https://github.com/patternfly/patternfly-react/pull/3028))
- Fixed ChartThreshold props ([#3024](https://github.com/patternfly/patternfly-react/pull/3024))
- Added custom theme example ([#3023](https://github.com/patternfly/patternfly-react/pull/3023))
- Moved ChartThreshold to its own example ([#3019](https://github.com/patternfly/patternfly-react/pull/3019))

## Components
- **About modal:**
  - Append component to an element in DOM ([#3102](https://github.com/patternfly/patternfly-react/pull/3102))
- **Application launcher:**
  - Fix unit tests ([#3107](https://github.com/patternfly/patternfly-react/pull/3107))
- **Button:**
  - Component type accepts react-router Link ([#3077](https://github.com/patternfly/patternfly-react/pull/3077))
  - Added an example of a link button with anchor component ([#3034](https://github.com/patternfly/patternfly-react/pull/3034))
- **Chip:**
  - Added OUIA compatibility to Chip component ([#2995](https://github.com/patternfly/patternfly-react/pull/2995))
- **Copy to clipboard:**
  - Wrapped pre inside the expand element ([#3169](https://github.com/patternfly/patternfly-react/pull/3169))
- **Data toolbar:** 
  - Implemented changes to match PF-Core ([#3144](https://github.com/patternfly/patternfly-react/pull/3144))
  - Add unit and integration tests ([#3201](https://github.com/patternfly/patternfly-react/pull/3201))
- **Divider:**
  - Added divider component ([#3125](https://github.com/patternfly/patternfly-react/pull/3125))
- **Dropdown:**
  - Added OUIA compatibility for Dropdown ([#3135](https://github.com/patternfly/patternfly-react/pull/3135))
  - Fix unit tests ([#3107](https://github.com/patternfly/patternfly-react/pull/3107))
- **Empty state:**
  - Removed debug message from tests ([#3161](https://github.com/patternfly/patternfly-react/pull/3161))
- **Expandable:**
  - Allowed for dynamic toggle text in uncontrolled version ([#3068](https://github.com/patternfly/patternfly-react/pull/3068))
- **Login form:**
  - Pass 'remember me' state to isChecked ([#3056](https://github.com/patternfly/patternfly-react/pull/3056))
- **Options menu:**
  - Fix unit tests and options menu([#3107](https://github.com/patternfly/patternfly-react/pull/3107)) 
- **Overflow menu:**
   - Removed unnecessary class names ([#3204](https://github.com/patternfly/patternfly-react/pull/3204))
- **Radio:**
  - Pass checked either from isChecked or checked ([#3066](https://github.com/patternfly/patternfly-react/pull/3066))
  - Fix console error ([#3138](https://github.com/patternfly/patternfly-react/pull/3138))
  - Group radio inputs in docs (axe-core) ([#2684](https://github.com/patternfly/patternfly-react/pull/2684))
- **React catalog view extension:**
  - Added catalog view extension and three components ([#3145](https://github.com/patternfly/patternfly-react/pull/3145))
- **Select:**
  - Updated prop description for selections ([#3183](https://github.com/patternfly/patternfly-react/pull/3183))
  - Set onFilter to null to run the default filter ([#3158](https://github.com/patternfly/patternfly-react/pull/3158))
  - Added plain modifier to toggle button ([#3140](https://github.com/patternfly/patternfly-react/pull/3140))
  - Use props children if custom on filter used ([#3123](https://github.com/patternfly/patternfly-react/pull/3123))
  - Modifying selection outside Select component now works ([#3096](https://github.com/patternfly/patternfly-react/pull/3096))
  - Allow custom component as select option ([#3060](https://github.com/patternfly/patternfly-react/pull/3060))
  - Added OUIA compatibility to Select component ([#2996](https://github.com/patternfly/patternfly-react/pull/2996))
- **Spinner:**
  - Fixed alert type in docs ([#3063](https://github.com/patternfly/patternfly-react/pull/3063))
- **Switch:**
  - reverted defaultChecked to checked ([#3037](https://github.com/patternfly/patternfly-react/pull/3037))
- **Tabs:**
  - Move TabButton to new file ([#3033](https://github.com/patternfly/patternfly-react/pull/3033))
- **Text area:**
  - Added a prop to allow limiting the  resize orientation of the Text are ([#3180](https://github.com/patternfly/patternfly-react/pull/3180))
- **Tooltip:**
  - Allow tooltip text to be left-aligned ([#3053](https://github.com/patternfly/patternfly-react/pull/3053))
- **Virtualized extension**
  - Added jest test ([#2761](https://github.com/patternfly/patternfly-react/pull/2761))
- **Wizard:**
  - Append component to an element in DOM ([#3102](https://github.com/patternfly/patternfly-react/pull/3102)

## Table
- Added custom row wrapper example for table  ([#3160](https://github.com/patternfly/patternfly-react/pull/3160))
- Set height auto modifier on table row ([#3133](https://github.com/patternfly/patternfly-react/pull/3133))
- Added support for custom dataLabel prop on table header ([#3040](https://github.com/patternfly/patternfly-react/pull/3040))
- Disable header controls with empty table ([#3008](https://github.com/patternfly/patternfly-react/pull/3008))
- Added OUIA compatibility to Table component ([#2964](https://github.com/patternfly/patternfly-react/pull/2964))

## Other
- **Chore:** 
  - Add issue template ([#2804](https://github.com/patternfly/patternfly-react/pull/2804))
  - Surrounded OUIA check with a try catch ([#3178](https://github.com/patternfly/patternfly-react/pull/3178))
  - Use consumer context if specified for OUIA ([#3149](https://github.com/patternfly/patternfly-react/pull/3148))
  - Updated webpack config to output source maps ([#3115](https://github.com/patternfly/patternfly-react/pull/3115))
  - Fix warnings about use of deprecated lifecycle methods ([#3098](https://github.com/patternfly/patternfly-react/pull/3098))
  - Added eslint-plugin-react-hooks ([#3083](https://github.com/patternfly/patternfly-react/pull/3083))
  - Properly use this.setState in components ([#3075](https://github.com/patternfly/patternfly-react/pull/3075))
  - Fixed sentence case for component titles ([#3054](https://github.com/patternfly/patternfly-react/pull/3054))
  - Added tslint-plugin-prettier and apply code formatting ([#2810](https://github.com/patternfly/patternfly-react/pull/2810))
- **Demo:**
  - Added bulk select demo with table and toolbar ([#3082](https://github.com/patternfly/patternfly-react/pull/3082))
  - Added table filter demo ([#3127](https://github.com/patternfly/patternfly-react/pull/3127))
- **Docs:**
   - Use gatsby-theme-patternfly-org  ([#3146](https://github.com/patternfly/patternfly-react/pull/3146))
   - Fixed regressions from gatsby-theme-patternfly-org ([#3164](https://github.com/patternfly/patternfly-react/pull/3164))

## PF3
- **Serial console:**
  - Use xterm v4 ([#3030](https://github.com/patternfly/patternfly-react/pull/3030))
- **Cards:**
  - Refactored sub-component references ([#2935](https://github.com/patternfly/patternfly-react/pull/2935))
  
# 2019.08 release notes (2019-10-01)
Packages released:
- [@patternfly/react-charts@5.0.13](https://www.npmjs.com/package/@patternfly/react-charts/v/5.0.13)
- [@patternfly/react-core@3.112.3](https://www.npmjs.com/package/@patternfly/react-core/v/3.112.3)
- [@patternfly/react-inline-edit-extension@2.11.70](https://www.npmjs.com/package/@patternfly/react-inline-edit-extension/v/2.11.70)
- [@patternfly/react-styles@3.5.27](https://www.npmjs.com/package/@patternfly/react-styles/v/3.5.27)
- [@patternfly/react-table@2.22.19](https://www.npmjs.com/package/@patternfly/react-table/v/2.22.19)
- [@patternfly/react-tokens@2.6.31](https://www.npmjs.com/package/@patternfly/react-tokens/v/2.6.31)
- [@patternfly/react-topology@2.8.65](https://www.npmjs.com/package/@patternfly/react-topology/v/2.8.65)
- [@patternfly/react-virtualized-extension@1.2.55](https://www.npmjs.com/package/@patternfly/react-virtualized-extension/v/1.2.55)
- [@patternfly/react-icons@3.14.7](https://www.npmjs.com/package/@patternfly/react-icons/v/3.14.7)

## Charts
- (BREAKING CHANGE) Updated Victory to 30.0.0
  - Replace `labels={(d) => x: ${d.x}}` with `labels={({ datum }) => x: ${datum.x}}`
  - **ChartPie:**
    - Removed `pieHeight` & `pieWidth` props -- use `padding` prop
    - Adjusted padding from 8px to 20px
  - **ChartDonut:**
    - Removed `donutHeight` & `donutWidth`  props -- use `padding` prop
    - Adjusted padding from 8px to 20px
  - **ChartDonutUtilization:**
    - Removed `donutHeight` & `donutWidth` props -- use `padding` prop
    - Adjusted padding from 8px to 20px
  - **ChartDonutThreshold:**
    - Removed `donutHeight` & `donutWidth` props -- use `padding` prop
    - Adjusted padding from 8px to 20px
  - **ChartBullet:**
    - Removed `bulletHeight` & `bulletWidth`  props -- use `bulletSize` prop
  - **ChartContainer:**
    - Renamed the `VictoryContainer` CSS selector as `pf-c-chart` for specificity
  - See the [Github tag notes](https://github.com/patternfly/patternfly-react/releases/tag/%40patternfly%2Freact-charts%405.0.0) or [#2883](https://github.com/patternfly/patternfly-react/pull/2883) for additional details
- Added missing style and responsive props to ChartVoronoiContainer ([#2977](https://github.com/patternfly/patternfly-react/pull/2977))
- Updated chart tutorial paths ([#2962](https://github.com/patternfly/patternfly-react/pull/2962))
- Eliminate the "missing key prop" warning seen in the browser console for ChartPie ([#2943](https://github.com/patternfly/patternfly-react/pull/2943))
- Slightly modified how chart containers are cloned and added examples. This ensures charts can be wrapped with the Tippy tooltip component as an alternate way of providing custom tooltips. ([#3048](https://github.com/patternfly/patternfly-react/pull/3048))
- **Area Chart:** 
  - Added stacked area chart demo and test ([#2896](https://github.com/patternfly/patternfly-react/pull/2896))
  - Added Horizontal indicator example ([#2796](https://github.com/patternfly/patternfly-react/pull/2796)) 
- **Sparkline:** Added line border to ChartArea and move sparkline ([#2887](https://github.com/patternfly/patternfly-react/pull/2887))
- **Donut chart:** Added simple fix for the donut chart tutorial link ([#2940](https://github.com/patternfly/patternfly-react/pull/2940))

## Components
- **App launcher:** Made dropdown/app launcher work better with router components ([#3011](https://github.com/patternfly/patternfly-react/pull/3011))
- **Button:** 
  - Added control variant to button ([#2983](https://github.com/patternfly/patternfly-react/pull/2983))
  - Set the disable modifier when component is not button ([#2683](https://github.com/patternfly/patternfly-react/pull/2683))
- **Dropdown:** Disabled button now only applies disabled attribute ([#2989](https://github.com/patternfly/patternfly-react/pull/2989))
- **Chip group:** 
  - Allowed chip group toolbar item to handle single chip ([#2882](https://github.com/patternfly/patternfly-react/pull/2882))
  - ChipGroupToolbarItem component was not propagating className despite having this prop in documentation and TS. This is a fix to ChipGroupToolbarItem className ([#2881](https://github.com/patternfly/patternfly-react/pull/2881))
  - Allowed variable number of chips to be displayed ([#2878](https://github.com/patternfly/patternfly-react/pull/2878))
- **Copy to clipboard:** 
  - Added prop for expanded by default ([#2923](https://github.com/patternfly/patternfly-react/pull/2923))
  - Added an example of copy clipboard with array of objects ([#2916](https://github.com/patternfly/patternfly-react/pull/2916))
- **Date and time picker component:** Added Date and time picker component ([#1420](https://github.com/patternfly/patternfly-react/pull/1420))
- **Data toolbar:** 
  - Added aria-haspopup to the toggle group ([#3012](https://github.com/patternfly/patternfly-react/pull/3012))
  - Added chip groups to toolbar ([#2888](https://github.com/patternfly/patternfly-react/issues/2888))
- **Dropdown split button:** Added 3rd state to split button ([#2842](https://github.com/patternfly/patternfly-react/pull/2842))
- **Empty state:** Made it possible to support primary and icon as div elements ([#2957](https://github.com/patternfly/patternfly-react/pull/2957))
- **Expandable:** The controlled version of Expandable was not reacting to changes made to the isExpanded prop after initial creation. This PR fixed the issue. ([#2955](https://github.com/patternfly/patternfly-react/pull/2955))
- **Flex:** Added support for flex layout, tests, etc. ([#2985](https://github.com/patternfly/patternfly-react/pull/2985))
- **LoginPage:** Add attributes to the submit button ([#2682](https://github.com/patternfly/patternfly-react/pull/2682))
- **Modal:**
  - Simplified disabling of FocusTrap ([#2862](https://github.com/patternfly/patternfly-react/pull/2862))
  - Changed the cancel button variant to link ([#2979](https://github.com/patternfly/patternfly-react/pull/2979))
- **Nav:** HorizontalNavMenuItem: Fixed onItemClick PropType  ([#2984](https://github.com/patternfly/patternfly-react/pull/2984))
- **Overflow:** Introduced overflow component ([#2819](https://github.com/patternfly/patternfly-react/issues/2819))
- **Pagination:** 
  - Added OUIA compatibility to Pagination component ([#2960](https://github.com/patternfly/patternfly-react/pull/2960))
  - Fixed styling discrepancy with HTML version ([#2904](https://github.com/patternfly/patternfly-react/pull/2904))
- **Select:** 
  - Added a maximum height property to select menu ([#2946](https://github.com/patternfly/patternfly-react/pull/2946))
  - Displayed selections data properly ([#2848](https://github.com/patternfly/patternfly-react/pull/2848))
  - Added props for hard coded strings ([#2993](https://github.com/patternfly/patternfly-react/pull/2993))
- **Switch:** Backward compatibility in case labelOff was not set, fixed the conditionals ([#2816](https://github.com/patternfly/patternfly-react/pull/2816))
- **Tab:** Added two new props: mountOnEnter and unmountOnExit ([#2902](https://github.com/patternfly/patternfly-react/pull/2902))
- **Wizard:** Added default function to onClose prop ([#2863](https://github.com/patternfly/patternfly-react/pull/2863))

## Table
- Fixed cell title warning ([#2967](https://github.com/patternfly/patternfly-react/pull/2967))
- Support height auto modifier in tr ([#2932](https://github.com/patternfly/patternfly-react/pull/2932))
- Added flag to hide select all ([#2926](https://github.com/patternfly/patternfly-react/pull/2926))
- Improved the documentation for Table component from react-table ([#3016](https://github.com/patternfly/patternfly-react/pull/3016))
- Added tables to integration test demos and wrote unit tests ([#2685](https://github.com/patternfly/patternfly-react/pull/2685))

## Other
- **Docs:** Fixed live edit caret color so it is visible ([#2899](https://github.com/patternfly/patternfly-react/pull/2899))
- **PF3**: Bumped PF3 deps including Storybook ([#2985](https://github.com/patternfly/patternfly-react/pull/2895))

# 2019.07 release notes (2019-09-10)
Packages released:
- [@patternfly/react-charts@4.9.10](https://www.npmjs.com/package/@patternfly/react-charts/v/4.9.10)
- [@patternfly/react-core@3.104.0](https://www.npmjs.com/package/@patternfly/react-core/v/3.104.0)
- [@patternfly/react-styles@3.5.22](https://www.npmjs.com/package/@patternfly/react-styles/v/3.5.22)
- [@patternfly/react-table@2.20.15](https://www.npmjs.com/package/@patternfly/react-table/v/2.20.15)
- [@patternfly/react-tokens@2.6.26](https://www.npmjs.com/package/@patternfly/react-tokens/v/2.6.26)
- [@patternfly/react-topology@2.8.34](https://www.npmjs.com/package/@patternfly/react-topology/v/2.8.34)
- [@patternfly/react-icons@3.14.2](https://www.npmjs.com/package/@patternfly/react-icons/v/3.14.2)
- [@patternfly/react-virtualized-extension@1.2.23](https://www.npmjs.com/package/@patternfly/react-virtualized-extension/v/1.2.23)
- [@patternfly/react-inline-edit-extension@2.11.35](https://www.npmjs.com/package/@patternfly/react-inline-edit-extension/v/2.11.35)

## Charts
- Adjusted legend position for axis label ([#2763](https://github.com/patternfly/patternfly-react/pull/2763))
- Added new symbol for dash/threshold ([#2884](https://github.com/patternfly/patternfly-react/pull/2884))
- **BulletChart:** Added new BulletChart type! ([#2708](https://github.com/patternfly/patternfly-react/pull/2708))
- **StackChart:** Added monthly vertical stack example ([#2625](https://github.com/patternfly/patternfly-react/pull/2625))

## Components
- **Accordion:** Allow JSX elements for content and toggle ([#2713](https://github.com/patternfly/patternfly-react/pull/2713))
- **BackgroundImage:** Fix bug on non-Chrome browsers regarding filter's width ([#2742](https://github.com/patternfly/patternfly-react/pull/2742))
- **ChipGroup:** Added defaultIsOpen prop to allow chip group to be initially expanded ([#2651](https://github.com/patternfly/patternfly-react/pull/2651))
- **ClipboardCopy:** Updated if children change ([#2849](https://github.com/patternfly/patternfly-react/pull/2849))
- **Drawer:** Expose DrawerContent components and remove panelContent prop ([#2733](https://github.com/patternfly/patternfly-react/pull/2733))
- **Dropdown:**
  - Added support for dropdown with primary button toggle ([#2857](https://github.com/patternfly/patternfly-react/pull/2857))
  - Allow custom dropdown items ([#2890](https://github.com/patternfly/patternfly-react/pull/2890))
- **EmptyState:** Fixed a bug where the correct size modifier wasn't being passed ([#2692](https://github.com/patternfly/patternfly-react/pull/2692))
- **Expandable:** Support uncontrolled expandable ([#2649](https://github.com/patternfly/patternfly-react/pull/2649))
- **FormGroup:** Fixed a bug where className was not being propogated for non-inline forms ([#2864](https://github.com/patternfly/patternfly-react/pull/2864))
- **LoginForm:** Username input field is now autofocused ([#2659](https://github.com/patternfly/patternfly-react/pull/2659))
- **Modal:**
  - Added isFooterLeftAligned prop ([#2835](https://github.com/patternfly/patternfly-react/pull/2835))
  - Added appendTo prop so component can render in element other than document.body ([#2802](https://github.com/patternfly/patternfly-react/pull/2802))
  - FocusTrap works with showClose being false ([#2774](https://github.com/patternfly/patternfly-react/pull/2774))
- **Nav:** Added dark theme modifier flag ([#2856](https://github.com/patternfly/patternfly-react/pull/2856))
- **OptionsMenu:** Now uses our Dropdown component and is consistent with it ([#2299](https://github.com/patternfly/patternfly-react/pull/2299))
- **Page:** Added dark theme modifier flag ([#2856](https://github.com/patternfly/patternfly-react/pull/2856))
- **Select:**
  - Allow creating new select items ([#2820](https://github.com/patternfly/patternfly-react/pull/2820))
  - Added support for toggle icon ([#2748](https://github.com/patternfly/patternfly-react/pull/2748))
  - Added direction prop ([#2611](https://github.com/patternfly/patternfly-react/pull/2611))
- **Spinner:** Added new experimental Spinner component! ([#2858](https://github.com/patternfly/patternfly-react/pull/2858))
- **Switch:** Changed checked property in DOM ([#2749](https://github.com/patternfly/patternfly-react/pull/2749))
- **Tab:** Allow JSX elements for Tab title ([#2681](https://github.com/patternfly/patternfly-react/pull/2681))
- **TextArea:** Support defaultValue attribute for uncontrolled TextArea ([#2712](https://github.com/patternfly/patternfly-react/pull/2712))
- **Toolbar:** Added new experimental Toolbar component! ([#2861](https://github.com/patternfly/patternfly-react/pull/2861))
- **Tooltip:**
  - Allow passing properties through to PopoverBase and hence tippy.js ([#2769](https://github.com/patternfly/patternfly-react/pull/2769))
  - Added the manual trigger option with the isVisible prop ([#2769](https://github.com/patternfly/patternfly-react/pull/2769))
- **Wizard:** Added support for in-page rendering ([#2830](https://github.com/patternfly/patternfly-react/pull/2830))

## Table
- Added new visibleOn and hiddenOn breakpoint ([#2676](https://github.com/patternfly/patternfly-react/pull/2676))

## Icons
- Added Path Missing Icon ([#2817](https://github.com/patternfly/patternfly-react/pull/2817))
- Added Azure and OpenStack icons ([#2827](https://github.com/patternfly/patternfly-react/pull/2827))
- Added Ansible Tower icon to custom icons definition ([#2735](https://github.com/patternfly/patternfly-react/pull/2735))
- Publish configs as well with icons ([#2701](https://github.com/patternfly/patternfly-react/pull/2701))

## Virtualized Extension
- Debounce resize event to fix inconsistent grid sizing ([#2754](https://github.com/patternfly/patternfly-react/pull/2754))

## PF3
- **AsyncTypeAheadSelect:** Forward ref for AsyncTypeAheadSelect ([#2760](https://github.com/patternfly/patternfly-react/pull/2760))
- **CatalogTile:**
  - Allow JSX element for CatalogTile's icon ([#2771](https://github.com/patternfly/patternfly-react/pull/2771))
  - Added iconAlt property to use for alt text for icon image ([#2715](https://github.com/patternfly/patternfly-react/pull/2715))
- **DatePicker:** Added new date picker components ([#1873](https://github.com/patternfly/patternfly-react/pull/1873))
- **HorizontalNavMenu:** Allow HorizontalNavMenuItem's title to be a node ([#2825](https://github.com/patternfly/patternfly-react/pull/2825))

# 2019.06 release notes (2019-08-13)
Packages released:
- [@patternfly/react-charts@4.7.9](https://www.npmjs.com/package/@patternfly/react-charts/v/4.7.9)
- [@patternfly/react-core@3.87.3](https://www.npmjs.com/package/@patternfly/react-core/v/3.87.3)
- [@patternfly/react-styles@3.5.13](https://www.npmjs.com/package/@patternfly/react-styles/v/3.5.13)
- [@patternfly/react-table@2.17.5](https://www.npmjs.com/package/@patternfly/react-table/v/2.17.5)
- [@patternfly/react-tokens@2.6.16](https://www.npmjs.com/package/@patternfly/react-tokens/v/2.6.16)
- [@patternfly/react-topology@2.7.31](https://www.npmjs.com/package/@patternfly/react-topology/v/2.7.31)
- [@patternfly/react-icons@3.10.14](https://www.npmjs.com/package/@patternfly/react-icons/v/3.10.14)
- [@patternfly/react-virtualized-extension@1.1.117](https://www.npmjs.com/package/@patternfly/react-virtualized-extension/v/1.1.117)
- [@patternfly/react-inline-edit-extension@2.10.5](https://www.npmjs.com/package/@patternfly/react-inline-edit-extension/v/2.10.5)

## Charts
- Used vars to enable Red Hat fonts. When the pf-m-redhat-font selector is added to the page, the Red Hat font is expected to be used instead of the default Overpass font. This change ensures that charts and its labels use the Red Hat font as expected
([#2584](https://github.com/patternfly/patternfly-react/pull/2584))
- The donut threshold chart used to generate a 'width must be a non-negative' warning when donutWidth values are zero. This change ensures the dynamic chart size is never less than zero  ([#2590](https://github.com/patternfly/patternfly-react/pull/2590))
- Fixed missing fill and stroke colors for area and line charts. Set area.style.data.fill to first color scale value in colorTheme function. Set line.style.data.stroke to first color scale value in colorTheme function ([#2626](https://github.com/patternfly/patternfly-react/pull/2626))


## Components
- **Accordion:** Added the html structure of Accordion to React  ([#2422](https://github.com/patternfly/patternfly-react/pull/2422))
- **Alert:** Added default variant for Alert  ([#2648](https://github.com/patternfly/patternfly-react/pull/2648))
- **Button:** Added 'reset' to types ([#2622](https://github.com/patternfly/patternfly-react/pull/2622))
- **Checkbox** Updated ids so none repeat. Prevents inconsistent checking behavior when labels are clicked for uncontrolled vs. controlled
examples  ([#2663](https://github.com/patternfly/patternfly-react/pull/2663))
- **Drawer:** Added the drawer component to experimental  ([#2633](https://github.com/patternfly/patternfly-react/pull/2633))
- **Dropdown:**
  - Automatically focus first dropdown item when DropdownMenu mounts  ([#2355](https://github.com/patternfly/patternfly-react/pull/2355))
  - This PR adds an aria-label to the "icon only" example of Dropdown  ([#2517](https://github.com/patternfly/patternfly-react/pull/2517))
  - Fixed missing event passthrough on internal onSelect callback ([#2657](https://github.com/patternfly/patternfly-react/pull/2657))
- **Form:** Updated Form demo to use check over radio
([#2567](https://github.com/patternfly/patternfly-react/pull/2567))
- **Modal:** Allows for custom header and/or footer in Modal component Added the showClose prop, defaulted to true. Set to false to hide the close button  ([#2120](https://github.com/patternfly/patternfly-react/pull/2120))
- **Page:**
  - Skip to content should point to primary content container ([#2519](https://github.com/patternfly/patternfly-react/pull/2519))
  - Change the defaultManagedSidebarOpen prop name for consistency ([#2664](https://github.com/patternfly/patternfly-react/pull/2664))
- **Pagination:**
  - When there is 0 items or negative number for pagination show 0th page out of 0 and disable paginating  ([#2558](https://github.com/patternfly/patternfly-react/pull/2558))
  - Added a demo of table integrated with pagination ([#2601](https://github.com/patternfly/patternfly-react/pull/2601))
  - Fixed pagination to update page count ([#2639](https://github.com/patternfly/patternfly-react/pull/2639))
  - Added disabled flag for whole component ([#2586](https://github.com/patternfly/patternfly-react/pull/2586))
- **Select:**  
  - Select menu now has consistent, open behavior on empty text input field  ([#2572](https://github.com/patternfly/patternfly-react/pull/2572))
  - Added a custom callback for the filtering function used in typeahead variants. This replaces the current search entirely, so the function must handle filtering the list of children/options and return the filtered results for the internal state to update
([#2434](https://github.com/patternfly/patternfly-react/pull/2434))
  - Added isPlain variation/prop to Select.tsx, snapshot tests, and integration ([#2588](https://github.com/patternfly/patternfly-react/pull/2588))
  - This enhancement allows a user to now pass in a user defined object to store additional data besides just the string value to a select option. The object must have a toString function that is
responsible for returning the the localized string ([#2612](https://github.com/patternfly/patternfly-react/pull/2612))
  - Disabled focus trap on checkbox select with no children. Focus Trap throws exception if no children to ref. In order to avoid this error, render the component with no Focus Trap when no children is passed  ([#2647](https://github.com/patternfly/patternfly-react/pull/2647))
  - Added disabled flag to select ([#2678](https://github.com/patternfly/patternfly-react/pull/2678))
- **Switch:** Added aria-labelledby to input
([#2468](https://github.com/patternfly/patternfly-react/pull/2468))
- **Topology:** Fixed paddings for topology control bar buttons. Removed css settings that override the paddings for the topology control bar buttons  ([#2635](https://github.com/patternfly/patternfly-react/pull/2635))

## Table
- Added the wrap modifier to react-table through transforms  ([#2615](https://github.com/patternfly/patternfly-react/pull/2615))
- Replaced lodash-es with lodash  ([#2641](https://github.com/patternfly/patternfly-react/pull/2641))

## TypeScript conversion
- **Dropdown:** ([#2502](https://github.com/patternfly/patternfly-react/pull/2502))

## Docs
- Made name column not wrap
([#2583](https://github.com/patternfly/patternfly-react/pull/2502))
- Small adjustment for Stack layout. Updated the doc to correctly read that isFilled is related to the vertical space occupied, not horizontal  ([#2605](https://github.com/patternfly/patternfly-react/pull/2605))
- Link to react-tokens page was broken. Updated to point to the Global CSS Variables page ([#2453](https://github.com/patternfly/patternfly-react/pull/2453))
- Added extension notes to Gatsby docs to improve the Gatsby doc for table extensions and add disclaimer about extension status ([#2637](https://github.com/patternfly/patternfly-react/pull/2637))
- Fixed accessibility issues in Accordion, ClipboardCopy, and DataList ([#2634](https://github.com/patternfly/patternfly-react/pull/2634))


## Other
- **Chore:**
  - Added curl command after release ([#2547](https://github.com/patternfly/patternfly-react/pull/2547))
  - Invalidate all packages if yarn.lock changes ([#2548](https://github.com/patternfly/patternfly-react/pull/2548))
  - Updated release notes to use uls ([#2604](https://github.com/patternfly/patternfly-react/pull/2604))

# 2019.05 release notes (2019-07-24)
Packages released:
- [@patternfly/react-charts@4.7.1](https://www.npmjs.com/package/@patternfly/react-charts/v/4.7.1)
- [@patternfly/react-core@3.75.2](https://www.npmjs.com/package/@patternfly/react-core/v/3.75.2)
- [@patternfly/react-styles@3.5.7](https://www.npmjs.com/package/@patternfly/react-styles/v/3.5.7)
- [@patternfly/react-table@.14.23](https://www.npmjs.com/package/@patternfly/react-table/v/2.14.23)
- [@patternfly/react-tokens@2.6.13](https://www.npmjs.com/package/@patternfly/react-tokens/v/2.6.13)
- [@patternfly/react-topology@2.6.20](https://www.npmjs.com/package/@patternfly/react-topology/v/2.7.2)
- [@patternfly/react-icons@3.10.14](https://www.npmjs.com/package/@patternfly/react-icons/v/3.10.14)
- [@patternfly/react-virtualized-extension@1.1.82](https://www.npmjs.com/package/@patternfly/react-virtualized-extension/v/1.1.82)
- [@patternfly/react-inline-edit-extension@2.9.49](https://www.npmjs.com/package/@patternfly/react-inline-edit-extension/v/2.9.49)
## Charts ([@patternfly/react-charts@4.7.1](https://www.npmjs.com/package/@patternfly/react-charts/v/4.7.1))
- Fixed runtime errors related to theme padding ([#2430](https://github.com/patternfly/patternfly-react/pull/2430))
- Added charts to react-integration tests ([#2354](https://github.com/patternfly/patternfly-react/pull/2354))
- Updated chart theme to use pf-core variables ([#2439](https://github.com/patternfly/patternfly-react/pull/2439))
- Removed invalid pf-core var ([#2463](https://github.com/patternfly/patternfly-react/pull/2463))
- Adjusted pf-core vars & added tooltip examples ([#2497](https://github.com/patternfly/patternfly-react/pull/2497))
- Updated pf-core vars ([#2480](https://github.com/patternfly/patternfly-react/pull/2480))
- Provided an accessible title and description ([#2500](https://github.com/patternfly/patternfly-react/pull/2500))
- Added bottom-left legend position ([#2442](https://github.com/patternfly/patternfly-react/pull/2442))
- Tweaked aria title for area chart ([#2510](https://github.com/patternfly/patternfly-react/pull/2510))
- Replaced prop `titleComponent` by `subTitleComponent` on donut charts ([#2488](https://github.com/patternfly/patternfly-react/pull/2488))
- Added individual padding vars for donut charts ([#2529](https://github.com/patternfly/patternfly-react/pull/2529))
- Added new mutil-color theme for ordered charts ([#2552](https://github.com/patternfly/patternfly-react/pull/2552))
- Added fixed point notation into percentage donut charts ([#2375](https://github.com/patternfly/patternfly-react/pull/2375))
- Used vars to enable Red Hat fonts ([#2584](https://github.com/patternfly/patternfly-react/pull/2584))
## Components ([@patternfly/react-core@3.75.2](https://www.npmjs.com/package/@patternfly/react-core/v/3.75.2))
- **About modal:** AboutModal and Modal both now trap focus in the browser ([#2428](https://github.com/patternfly/patternfly-react/pull/2428))
- **Accordion:** Added prop to heading level of parent component ([#2290](https://github.com/patternfly/patternfly-react/pull/2290))
- **Application launcher:** Allowed custom icon for application launcher toggle ([#2492](https://github.com/patternfly/patternfly-react/pull/2492))
- **Badge:**
  - Temporarily disabled problematic badges ([#2530](https://github.com/patternfly/patternfly-react/pull/2530))
  - Added space between badges in the examples ([#2556](https://github.com/patternfly/patternfly-react/pull/2556))
- **Breadcrumb switcher:** Fixed Autocomplete camelCase ([#2457](https://github.com/patternfly/patternfly-react/pull/2457))
- **Datalist:** Added hidden and visible breakpoints ([#2251](https://github.com/patternfly/patternfly-react/pull/2251))
- **Dropdown:** Provided option to not autofocus on first item ([#2473](https://github.com/patternfly/patternfly-react/pull/2473))
- **Empty state:** Updated EmptyStateBody to use div instead of p ([#2499](https://github.com/patternfly/patternfly-react/pull/2499))
- **Experimental features:** Added POC for experimental button and badge ([#2363](https://github.com/patternfly/patternfly-react/pull/2363))
- **Gallery:** Converted gallery to TypeScript ([#2432](https://github.com/patternfly/patternfly-react/pull/2432))
- **Login page:** Removed ariaLabel from checkbox ([#2455](https://github.com/patternfly/patternfly-react/pull/2455))
- **Modal:** Modal now traps screen reader focus ([#2406](https://github.com/patternfly/patternfly-react/pull/2406))
- **Options menu:** Updated examples to trigger select on the whole item ([#2513](https://github.com/patternfly/patternfly-react/pull/2513))
- **Pagination:**
  - Dropdown closes on click outside of menu area ([#2235](https://github.com/patternfly/patternfly-react/pull/2235))
  - Added ability to allow users to enter numbers into the input field ([#2417](https://github.com/patternfly/patternfly-react/pull/2417))
- **Select:**
  - Removed ariaLabel from grouped checkbox select ([#2456](https://github.com/patternfly/patternfly-react/pull/2456))
  - Added optional display via children to option ([#2419](https://github.com/patternfly/patternfly-react/pull/2419))
  - Updated typeahead filtered list when children change ([#2518](https://github.com/patternfly/patternfly-react/pull/2518))
- **Switch:** Added OUIA compatibility to Switch ([#2304](https://github.com/patternfly/patternfly-react/pull/2304))
- **Tabs:**
  - Allowed eventKey to accept a string ([#2493](https://github.com/patternfly/patternfly-react/pull/2493))
  - Implemented overflow styles for secondary tabs ([#2512](https://github.com/patternfly/patternfly-react/pull/2512))
- **Tooltip:** Added support for aria prop from Tippy library ([#2539](https://github.com/patternfly/patternfly-react/pull/2539))
## TypeScript conversion
- Bullseye ([#2427](https://github.com/patternfly/patternfly-react/pull/2427))
- Gallery ([#2432](https://github.com/patternfly/patternfly-react/pull/2432))
- Grid ([#2443](https://github.com/patternfly/patternfly-react/pull/2443))
- Level ([#2450](https://github.com/patternfly/patternfly-react/pull/2450))
- Pagination ([#2256](https://github.com/patternfly/patternfly-react/pull/2256))
- Split ([#2466](https://github.com/patternfly/patternfly-react/pull/2466))
- Stack ([#2412](https://github.com/patternfly/patternfly-react/pull/2412))
- Switch ([#2311](https://github.com/patternfly/patternfly-react/pull/2311))
- Toolbar ([#2475](https://github.com/patternfly/patternfly-react/pull/2475))
## Table ([@patternfly/react-table@2.14.23](https://www.npmjs.com/package/@patternfly/react-table/v/2.14.23))
- Checked empty array in areAllRowsSelected ([#2527](https://github.com/patternfly/patternfly-react/pull/2527))
- Added exports for compoundExpand ([#2554](https://github.com/patternfly/patternfly-react/pull/2554))
## Styles ([@patternfly/react-styles@3.5.7](https://www.npmjs.com/package/@patternfly/react-styles/v/3.5.7))
- Added pickProperties to react-styles utils exports ([#2481](https://github.com/patternfly/patternfly-react/pull/2481))
## Docs
- Updated link to react-tokens page in the readme ([#2453](https://github.com/patternfly/patternfly-react/pull/2453))
## Other
- **Build:**
  - Added PR comment on publishing to NPM ([#2433](https://github.com/patternfly/patternfly-react/pull/2433))
  - Added Windows support ([#2471](https://github.com/patternfly/patternfly-react/pull/2471))
- **Chore:**
  - Removed tippy-react dependency ([#2505](https://github.com/patternfly/patternfly-react/pull/2505))
  - Updated react-docs to use Red Hat font ([#2563](https://github.com/patternfly/patternfly-react/pull/2563))
- **Unit tests:** Fixed keyHandler tests in util.test.js ([#2489](https://github.com/patternfly/patternfly-react/pull/2489))

# 2019.04 release notes (2019-07-02)
Packages released:
- [@patternfly/react-core@3.58.1](https://www.npmjs.com/package/@patternfly/react-core/v/3.58.1)
- [@patternfly/react-inline-edit-extension@2.9.12](https://www.npmjs.com/package/@patternfly/react-inline-edit-extension/v/2.9.12)
- [@patternfly/react-table@2.13.43](https://www.npmjs.com/package/@patternfly/react-table/v/2.13.43)
- [@patternfly/react-topology@2.4.21](https://www.npmjs.com/package/@patternfly/react-topology/v/2.4.21)
- [@patternfly/react-virtualized-extension@1.1.45](https://www.npmjs.com/package/@patternfly/react-virtualized-extension/v/1.1.45)
- [@patternfly/react-charts@4.4.7](https://www.npmjs.com/package/@patternfly/react-charts/v/4.4.7)
- [@patternfly/react-styles@3.4.6](https://www.npmjs.com/package/@patternfly/react-styles/v/3.4.6)
- [@patternfly/react-tokens@2.6.5](https://www.npmjs.com/package/@patternfly/react-tokens/v/2.6.5)
## Charts ([@patternfly/react-charts@4.4.7](https://www.npmjs.com/package/@patternfly/react-charts/v/4.4.7))
- Added sparkline example and interpolation to area examples ([#2373](https://github.com/patternfly/patternfly-react/pull/2373))
- Fixed themes for bar chart default colors ([#2112)](https://github.com/patternfly/patternfly-react/pull/2112)
- DonutThreshold: No longer show static threshold donut tooltips by default ([#2270](https://github.com/patternfly/patternfly-react/pull/2270))
- Added support for legends and grids ([#2324](https://github.com/patternfly/patternfly-react/pull/2324))
## Components ([@patternfly/react-core@3.58.1](https://www.npmjs.com/package/@patternfly/react-core/v/3.58.1))
- **About modal:** Changed strapline element to paragraph ([#2376](https://github.com/patternfly/patternfly-react/pull/2376))
- **Breadcrumb switcher:** Disabled autocomplete ([#2407](https://github.com/patternfly/patternfly-react/pull/2407))
- **Card:** Addedcompacted card variation ([#2399](https://github.com/patternfly/patternfly-react/pull/2399))
- **Checkbox:** Added 3rd state to checkbox controlled by consumer ([#2252](https://github.com/patternfly/patternfly-react/pull/2252))
- **Chip group:** Added heading level prop to toolbar chip group label ([#2278](https://github.com/patternfly/patternfly-react/pull/2278))
- **Data list:** Added DataListRow to imports ([#2353](https://github.com/patternfly/patternfly-react/pull/2353))
- **Dropdown:** Automatically focused first dropdown item when DropdownMenu ([#2355](https://github.com/patternfly/patternfly-react/pull/2355))
- **Expandable:** Added button type to the expandable component ([#2340](https://github.com/patternfly/patternfly-react/pull/2340))
- **Label:** Added TypeScript flag to the label docs ([#2343](https://github.com/patternfly/patternfly-react/pull/2343))
- **Notification badge:** Added the notification badge component ([#2342)](https://github.com/patternfly/patternfly-react/pull/2342)
- **Options menu:** Added disabled modifier to the toggle ([#2401](https://github.com/patternfly/patternfly-react/pull/2401))
- **Page:** Added page section main nav type variant ([#2268](https://github.com/patternfly/patternfly-react/pull/2268))
- **Radio:** Fixed warning from undefined starting params ([#2292](https://github.com/patternfly/patternfly-react/pull/2292))
- **Form:**
  - Updated text in form component ([#2352](https://github.com/patternfly/patternfly-react/pull/2352))
  - Wrapped form label text in new element ([#2322](https://github.com/patternfly/patternfly-react/pull/2332))
- **Grid:**
  - Removed size props from {...props} ([#2404](https://github.com/patternfly/patternfly-react/pull/2404))
  - Updated grid layout to support new 2xl breakpoint ([#2305](https://github.com/patternfly/patternfly-react/pull/2305))
- **Tabs:**
  - Fixed TypeScript errors and revert `TabContainer` to a component ([#2402](https://github.com/patternfly/patternfly-react/pull/2402))
  - Remove comment from code ([#2351](https://github.com/patternfly/patternfly-react/pull/2351))
  - Made variant prop optional ([#2348](https://github.com/patternfly/patternfly-react/pull/2348))
## TypeScript conversion
- Copy to clipboard ([#2131](https://github.com/patternfly/patternfly-react/pull/2131))
- Progress ([#2307](https://github.com/patternfly/patternfly-react/pull/2307))
- Select ([#2201](https://github.com/patternfly/patternfly-react/pull/2201))
- Input group ([#2220](https://github.com/patternfly/patternfly-react/pull/2220))

# 2019.03 release notes (2019-06-11)
Packages released:
- [@patternfly/react-charts@4.1.5](https://www.npmjs.com/package/@patternfly/react-charts/v/4.1.5)
- [@patternfly/react-core@3.38.1](https://www.npmjs.com/package/@patternfly/react-core/v/3.38.1)
- [@patternfly/react-inline-edit-extension@2.7.7](https://www.npmjs.com/package/@patternfly/react-inline-edit-extension/v/2.7.7)
- [@patternfly/react-styles@3.3.3](https://www.npmjs.com/package/@patternfly/react-styles/v/3.3.3)
- [@patternfly/react-table@2.11.1](https://www.npmjs.com/package/@patternfly/react-table/v/2.11.1)
- [@patternfly/react-tokens@2.5.5](https://www.npmjs.com/package/@patternfly/react-tokens/v/2.5.5)
## Charts ([@patternfly/react-charts@4.1.5](https://www.npmjs.com/package/@patternfly/react-charts/v/4.1.5))
- Major bump react-charts ([#2143](https://github.com/patternfly/patternfly-react/pull/2143))
- Changed default Chart padding property to show axis
- Refactored ChartTheme colors and utils for donut utilization theme
- ChartLegend now defaults to be responsive
- Aligned label vertically and added donutHeight/Width defaults ([#2193](https://github.com/patternfly/patternfly-react/pull/2193))
- Added examples on how to use VictoryZoomContainer ([#1879](https://github.com/patternfly/patternfly-react/pull/1879))
- Apply defaults to custom legend ([#2194](https://github.com/patternfly/patternfly-react/issues/2194))
- Chart & ChartStack to use ReactNode as children type ([#2155](https://github.com/patternfly/patternfly-react/pull/2155))
- Remove ChartThemeDefinition export from index.ts ([#2149](https://github.com/patternfly/patternfly-react/pull/2149))
## Components ([@patternfly/react-core@3.38.1](https://www.npmjs.com/package/@patternfly/react-core/v/3.38.1))
- **About modal:** Support isOpen initially set true in about modal. This ensures the about modal container exists on initial load if `isOpen` is passed `true` with children contents initially ([#2153](https://github.com/patternfly/patternfly-react/pull/2153))
- **Navigation:** On NavItems, Maintain className passed to custom NavItems. Keeps classNames set on the child of a custom NavItem ([#2134](https://github.com/patternfly/patternfly-react/pull/2134))
- **Pagination:** When empty array is sent to pagination now no per page is visible. It is now possible with Per page option to hide by passing empty array of per page options ([#2175](https://github.com/patternfly/patternfly-react/pull/2175))
- **Select:** Added keyboard interaction to typeahead variants, other variants remained unchanged. Enter, with select closed, toggles open the menu. Focus should now remains on input. Arrow up and down navigates the options with a focus styling. Enter, with select opened, selects the highlighted item ([#2013](https://github.com/patternfly/patternfly-react/pull/2013))
- **Tabs:** Fixed tabs ref proptype ([#2158](https://github.com/patternfly/patternfly-react/pull/2158))
## Table ([@patternfly/react-table@2.11.1](https://www.npmjs.com/package/@patternfly/react-table/v/2.11.1))
- Added React-Virtualized PF4 tables ([#2011](https://github.com/patternfly/patternfly-react/pull/2011))
- Exported RowWrapper implementation ([#2118](https://github.com/patternfly/patternfly-react/pull/2118))
- Some props of IRow should not required Makes following props of `IRow` to optional isOpen parent props ([#2196](https://github.com/patternfly/patternfly-react/pull/2196))
- Fixed error Unknown event handler property `onCollapse`. Removed `rows` and `onCollapse` from `...props` ([#2195](https://github.com/patternfly/patternfly-react/pull/2195))
- Added support for .pf-m-grid-2xl breakpoint. Added breakpoint to list of available breakpoints and updated snapshot ([#2206](https://github.com/patternfly/patternfly-react/pull/2206))
- Reverted bodywrapper conversion to stateless-function ([#2161](https://github.com/patternfly/patternfly-react/pull/2161))
## Topology (@patternfly/react-topology)
- Added @patternfly/react-topology package ([#2170](https://github.com/patternfly/patternfly-react/pull/2170))
- Fixed esm output and converted react-virtualized-extension to TS ([#2190](https://github.com/patternfly/patternfly-react/pull/2190))
## Styles ([@patternfly/react-styles@3.3.3](https://www.npmjs.com/package/@patternfly/react-styles/v/3.3.3))
- Changed all the React css imports and added types for them. Instead of using a babel plugin to generate the JS at compile time for our CSS-in-JS solution, we statically generate it beforehand in react-styles ([#2085](https://github.com/patternfly/patternfly-react/pull/2085))
- Bumped jsdom ([#2080](https://github.com/patternfly/patternfly-react/pull/2080))
- Added sideeffects to react-styles ([#2207](https://github.com/patternfly/patternfly-react/pull/2207))
## TypeScript conversion
- Backdrop ([#2105](https://github.com/patternfly/patternfly-react/pull/2105))
- Background image ([#2070](https://github.com/patternfly/patternfly-react/pull/2070))
- Options menu ([#2002](https://github.com/patternfly/patternfly-react/pull/2002))
- Text input ([#1914](https://github.com/patternfly/patternfly-react/pull/1914))

# 2019.02 release notes (2019-06-05)
Packages released:
- [@patternfly/react-charts@3.6.4](https://www.npmjs.com/package/@patternfly/react-charts/v/3.6.4)
- [@patternfly/react-core@3.34.2](https://www.npmjs.com/package/@patternfly/react-core/v/3.34.2)
- [@patternfly/react-inline-edit-extension@2.5.2](https://www.npmjs.com/package/@patternfly/react-inline-edit-extension/v/2.5.2)
- [@patternfly/react-styles@3.2.3](https://www.npmjs.com/package/@patternfly/react-styles/v/3.2.3)
- [@patternfly/react-table@2.9.2](https://www.npmjs.com/package/@patternfly/react-table/v/2.9.2)
- [@patternfly/react-tokens@2.5.3](https://www.npmjs.com/package/@patternfly/react-tokens/v/2.5.3)
## Components ([@patternfly/react-core@3.34.2](https://www.npmjs.com/package/@patternfly/react-core/v/3.34.2))
- **About Modal:** Provided a way to set the background using props ([#1940](https://github.com/patternfly/patternfly-react/pull/1940))
- **Accordion:** Added accordion component ([#1511](https://github.com/patternfly/patternfly-react/pull/1511))
- **Background Image:** Fixed background image spacing issue ([#1923](https://github.com/patternfly/patternfly-react/pull/1923))
- **Card:** Added card is-hoverable modifier prop ([#1852](https://github.com/patternfly/patternfly-react/pull/1852))
- **Checkbox:** Set checked value correctly ([#1929](https://github.com/patternfly/patternfly-react/pull/1929))
- **Copy to Clipboard:** Fixed docs ([#1821](https://github.com/patternfly/patternfly-react/pull/1821))
  - Changed doc text ([#1823](https://github.com/patternfly/patternfly-react/pull/1823))
  - Removed textarea from clipboard copy ([#1840](https://github.com/patternfly/patternfly-react/pull/1840))
- **Dropdown:** Renamed toggle export ([#1861](https://github.com/patternfly/patternfly-react/pull/1861))
- **Grid:** Added missing props in d.ts ([#1749](https://github.com/patternfly/patternfly-react/pull/1749))
- **Icons:** Added font awesome brands icons([#1669](https://github.com/patternfly/patternfly-react/pull/1669))
- **Popover:**
  - Updated Popover max width. We made maxWidth optional ([#2110](https://github.com/patternfly/patternfly-react/pull/2110))
  - Enabled highlighting and selecting text in popover ([#1757](https://github.com/patternfly/patternfly-react/pull/1757))
  - Handled on enter focusing when options are disabled ([#2025](https://github.com/patternfly/patternfly-react/pull/2025))
  - Changed PopoverPosition from a const to an enum. This allows users to specify their choice of a string or object property for the position property value on Popover component. Also adds a test that exercises this method to ensure it doesn't regress going forward ([#2113](https://github.com/patternfly/patternfly-react/pull/2113))
- **Select:**
  - Updated the SelectProps interface to avoid a type error when importing react-core into a TypeScript application. I also removed some unnecessary code in a couple of the demo's I followed recently. Copying the code as is was creating an error. I think they were safe deletions but worth double checking ([#2107](https://github.com/patternfly/patternfly-react/pull/2107))
  - Fixed ListGroupItem import ([#1867](https://github.com/patternfly/patternfly-react/pull/1867))
  - Added user personalized icon in Select component ([#1768](https://github.com/patternfly/patternfly-react/pull/1768))
## Charts [@patternfly/react-charts@3.6.4](https://www.npmjs.com/package/@patternfly/react-charts/v/3.6.4)
- Introduced Donut utilization chart and thresholds ([#2064](https://github.com/patternfly/patternfly-react/pull/2064))
- Added example styles ([#1889](https://github.com/patternfly/patternfly-react/pull/1889))
- Fixed chart font stack to use PatternFly core sans-serif font stack ([#1865](https://github.com/patternfly/patternfly-react/pull/1865))
- Refactored themes for bar chart default colors ([#2112](https://github.com/patternfly/patternfly-react/pull/2112))
- Added default for component props ([#2103](https://github.com/patternfly/patternfly-react/pull/2103))
## Docs
- Use frontmatter for what props to show in docs ([#2072](https://github.com/patternfly/patternfly-react/pull/2072))
- If you add new imports to your MDX file, rerun yarn develop which now clears the gatsby-mdx cache and lets you be on your merry way ([#2059](https://github.com/patternfly/patternfly-react/pull/2059))
- Hide inherited TypeScript props ([#1866](https://github.com/patternfly/patternfly-react/pull/1866))
- Use MDX for docs ([#1753](https://github.com/patternfly/patternfly-react/pull/1753))
- Reverted bodywrapper conversion to stateless-function ([#2161](https://github.com/patternfly/patternfly-react/pull/2161))
## TypeScript conversion
Packages released:
We are in the process of converting all components to TypeScript to provide better types for consumers. The following components have been converted:
- Alert ([#1978](https://github.com/patternfly/patternfly-react/pull/1978))
- Badge ([#2048](https://github.com/patternfly/patternfly-react/pull/2048))
- Breadcrumb ([#1723](https://github.com/patternfly/patternfly-react/pull/1723))
- Button ([#1903](https://github.com/patternfly/patternfly-react/pull/1903))
- Brand ([#1918](https://github.com/patternfly/patternfly-react/pull/1918))
- Card ([#1885](https://github.com/patternfly/patternfly-react/pull/1885))
- Charts ([#2081](https://github.com/patternfly/patternfly-react/pull/2081))
- Empty State ([#1917](https://github.com/patternfly/patternfly-react/pull/1917))
- Label ([#1896](https://github.com/patternfly/patternfly-react/pull/1896))
- List ([#1946](https://github.com/patternfly/patternfly-react/pull/1946))
- Login Page ([#1967](https://github.com/patternfly/patternfly-react/pull/1967))
- Modal ([#1942](https://github.com/patternfly/patternfly-react/pull/1942))
- Popover ([#2023](https://github.com/patternfly/patternfly-react/pull/2023))
- Radio ([#1945](https://github.com/patternfly/patternfly-react/pull/1945))
- Text ([#1907](https://github.com/patternfly/patternfly-react/pull/1907))

# 2019.01 release notes (2019-05-02)
We don't have notes for this release yet.
