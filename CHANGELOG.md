# Changelog

## [v0.9.6](https://github.com/codeforamerica/honeycrisp-gem/tree/v0.9.6) (2021-03-02)

[Full Changelog](https://github.com/codeforamerica/honeycrisp-gem/compare/v0.9.5...v0.9.6)

**Implemented enhancements:**

- Compact button [\#205](https://github.com/codeforamerica/honeycrisp-gem/issues/205)
- Remove example pills pattern and documentation  [\#170](https://github.com/codeforamerica/honeycrisp-gem/issues/170)
- Make tab bar selected state match background color [\#152](https://github.com/codeforamerica/honeycrisp-gem/issues/152)

**Fixed bugs:**

- Accordion and Reveal js not working [\#247](https://github.com/codeforamerica/honeycrisp-gem/issues/247)
- Help text has the wrong class in the documentation [\#240](https://github.com/codeforamerica/honeycrisp-gem/issues/240)
- question-with-follow-up doesn't quite work for checkbox lists [\#219](https://github.com/codeforamerica/honeycrisp-gem/issues/219)

**Closed issues:**

- Update material icon font [\#222](https://github.com/codeforamerica/honeycrisp-gem/issues/222)

**Merged pull requests:**

- Add .header--sortable to honeycrisp\_compact data-table [\#257](https://github.com/codeforamerica/honeycrisp-gem/pull/257) ([tdooner](https://github.com/tdooner))
- Uses variable $color-white instead of \#fff or \#FFFFFF [\#253](https://github.com/codeforamerica/honeycrisp-gem/pull/253) ([ash-rc](https://github.com/ash-rc))
- Use text--help for help text in Honeycrisp guide [\#252](https://github.com/codeforamerica/honeycrisp-gem/pull/252) ([ash-rc](https://github.com/ash-rc))
- Fix checkbox set with followup so that selecting additional checkboxes leaves followup open [\#251](https://github.com/codeforamerica/honeycrisp-gem/pull/251) ([wschaefer](https://github.com/wschaefer))
- Darkens unselected tabs by 5% in tab bar [\#249](https://github.com/codeforamerica/honeycrisp-gem/pull/249) ([ash-rc](https://github.com/ash-rc))
- Remove double init of honeycrisp javascript. [\#248](https://github.com/codeforamerica/honeycrisp-gem/pull/248) ([bytheway875](https://github.com/bytheway875))
- Update readme with bundler troubleshooting [\#246](https://github.com/codeforamerica/honeycrisp-gem/pull/246) ([wschaefer](https://github.com/wschaefer))
- Remove example pills pattern and documentation [\#244](https://github.com/codeforamerica/honeycrisp-gem/pull/244) ([wschaefer](https://github.com/wschaefer))
- Pull JS in main sprockets file into its own file \(honeycrisp.js\) [\#241](https://github.com/codeforamerica/honeycrisp-gem/pull/241) ([bytheway875](https://github.com/bytheway875))

## [v0.9.5](https://github.com/codeforamerica/honeycrisp-gem/tree/v0.9.5) (2021-02-12)

[Full Changelog](https://github.com/codeforamerica/honeycrisp-gem/compare/v0.9.4...v0.9.5)

**Fixed bugs:**

- Footer is shifted left by 25rem when there's no sidebar [\#236](https://github.com/codeforamerica/honeycrisp-gem/issues/236)
- Footer is offset for all tablet-up screens [\#212](https://github.com/codeforamerica/honeycrisp-gem/issues/212)

**Closed issues:**

- Need to relax "neat" gem dependency to allow usage in Rails 6.1 [\#232](https://github.com/codeforamerica/honeycrisp-gem/issues/232)

**Merged pull requests:**

- Updating honeycrisp compact styles  [\#238](https://github.com/codeforamerica/honeycrisp-gem/pull/238) ([ash-rc](https://github.com/ash-rc))
- Namespace sidebar-specific styles [\#237](https://github.com/codeforamerica/honeycrisp-gem/pull/237) ([hartsick](https://github.com/hartsick))

## [v0.9.4](https://github.com/codeforamerica/honeycrisp-gem/tree/v0.9.4) (2021-01-26)

[Full Changelog](https://github.com/codeforamerica/honeycrisp-gem/compare/v0.9.3...v0.9.4)

**Implemented enhancements:**

- Auto formatting for phone number and SSN [\#216](https://github.com/codeforamerica/honeycrisp-gem/issues/216)
- Introduce Honeycrisp Compact [\#211](https://github.com/codeforamerica/honeycrisp-gem/issues/211)
- Compact footer [\#203](https://github.com/codeforamerica/honeycrisp-gem/issues/203)
- Compact style inputs [\#202](https://github.com/codeforamerica/honeycrisp-gem/issues/202)
- How can we add a new icon to the icon set? [\#154](https://github.com/codeforamerica/honeycrisp-gem/issues/154)
- Add sidebar navigation to styleguide page [\#112](https://github.com/codeforamerica/honeycrisp-gem/issues/112)

**Fixed bugs:**

- Tab bar does not work as described [\#214](https://github.com/codeforamerica/honeycrisp-gem/issues/214)
- "Slab Layout" section behaves differently from others [\#206](https://github.com/codeforamerica/honeycrisp-gem/issues/206)

**Closed issues:**

- Discussion: Should sidebar navigation update its contents for different pages? [\#224](https://github.com/codeforamerica/honeycrisp-gem/issues/224)
- Upgrade version of jQuery [\#217](https://github.com/codeforamerica/honeycrisp-gem/issues/217)
- Documentation page for Compact Honeycrisp [\#208](https://github.com/codeforamerica/honeycrisp-gem/issues/208)
- Document links styled like buttons [\#165](https://github.com/codeforamerica/honeycrisp-gem/issues/165)

**Merged pull requests:**

- Upgrade percy agent, associated js dependencies, and nokogiri to appease dependabot [\#234](https://github.com/codeforamerica/honeycrisp-gem/pull/234) ([tgrathwell](https://github.com/tgrathwell))
- vendorize `neat` 1.8.0 to relax dependency on old thor [\#233](https://github.com/codeforamerica/honeycrisp-gem/pull/233) ([tgrathwell](https://github.com/tgrathwell))
- Fix - Readd incrementer.init\(\) [\#231](https://github.com/codeforamerica/honeycrisp-gem/pull/231) ([sree-cfa](https://github.com/sree-cfa))
- Add compact text input styling [\#228](https://github.com/codeforamerica/honeycrisp-gem/pull/228) ([bengolder](https://github.com/bengolder))
- Add labels to form input examples [\#227](https://github.com/codeforamerica/honeycrisp-gem/pull/227) ([bengolder](https://github.com/bengolder))
- Add compact drop down and button styles [\#226](https://github.com/codeforamerica/honeycrisp-gem/pull/226) ([bengolder](https://github.com/bengolder))
- Honeycrisp compact [\#225](https://github.com/codeforamerica/honeycrisp-gem/pull/225) ([bengolder](https://github.com/bengolder))
- MaterialIcon update [\#223](https://github.com/codeforamerica/honeycrisp-gem/pull/223) ([sree-cfa](https://github.com/sree-cfa))
- Upgrade jquery and other dependencies to address security vulnerabilities [\#221](https://github.com/codeforamerica/honeycrisp-gem/pull/221) ([lkogler](https://github.com/lkogler))
- Autoformatted inputs [\#218](https://github.com/codeforamerica/honeycrisp-gem/pull/218) ([bengolder](https://github.com/bengolder))
- Use existing selected tab style [\#215](https://github.com/codeforamerica/honeycrisp-gem/pull/215) ([bengolder](https://github.com/bengolder))
- Create `main-footer\_\_compact` class for compact footer [\#209](https://github.com/codeforamerica/honeycrisp-gem/pull/209) ([anule](https://github.com/anule))
- Fix some issues with sidebar formatting and selection state [\#201](https://github.com/codeforamerica/honeycrisp-gem/pull/201) ([lkogler](https://github.com/lkogler))
- Bump lodash from 4.17.14 to 4.17.20 [\#200](https://github.com/codeforamerica/honeycrisp-gem/pull/200) ([dependabot[bot]](https://github.com/apps/dependabot))
- Add fast wheelchair emoji and fast wheelchair with money emoji pair [\#197](https://github.com/codeforamerica/honeycrisp-gem/pull/197) ([stroopwafel79](https://github.com/stroopwafel79))
- Style disabled buttons directly via disabled property [\#195](https://github.com/codeforamerica/honeycrisp-gem/pull/195) ([bensheldon](https://github.com/bensheldon))
- None checkbox default checked, line above and function for multiple fieldsets [\#193](https://github.com/codeforamerica/honeycrisp-gem/pull/193) ([embarnard](https://github.com/embarnard))
- Bump rails version to fix some CVEs [\#191](https://github.com/codeforamerica/honeycrisp-gem/pull/191) ([lkogler](https://github.com/lkogler))
- Material icon font [\#190](https://github.com/codeforamerica/honeycrisp-gem/pull/190) ([lkogler](https://github.com/lkogler))
- Add variables for link colors [\#188](https://github.com/codeforamerica/honeycrisp-gem/pull/188) ([jenny-heath](https://github.com/jenny-heath))
- Clean up extraneous viewport charset tag and close html element  [\#166](https://github.com/codeforamerica/honeycrisp-gem/pull/166) ([bensheldon](https://github.com/bensheldon))

## [v0.9.3](https://github.com/codeforamerica/honeycrisp-gem/tree/v0.9.3) (2020-06-05)

[Full Changelog](https://github.com/codeforamerica/honeycrisp-gem/compare/v0.9.2...v0.9.3)

**Fixed bugs:**

- Outline isn't showing up for progress indicator [\#151](https://github.com/codeforamerica/honeycrisp-gem/issues/151)
- Postfix in follow up question conflicts with follow up question styling [\#144](https://github.com/codeforamerica/honeycrisp-gem/issues/144)

**Closed issues:**

- Compile static assets into /dist directory [\#176](https://github.com/codeforamerica/honeycrisp-gem/issues/176)

**Merged pull requests:**

- I18n for strings in form builder [\#187](https://github.com/codeforamerica/honeycrisp-gem/pull/187) ([loumoore](https://github.com/loumoore))
- Generate compiled stylesheets / js [\#183](https://github.com/codeforamerica/honeycrisp-gem/pull/183) ([bencalegari](https://github.com/bencalegari))
- Fix ruby version for Heroku deployment [\#182](https://github.com/codeforamerica/honeycrisp-gem/pull/182) ([lkogler](https://github.com/lkogler))
- Security upgrades [\#180](https://github.com/codeforamerica/honeycrisp-gem/pull/180) ([lkogler](https://github.com/lkogler))
- Use `identifier` to return a path for desired template. [\#178](https://github.com/codeforamerica/honeycrisp-gem/pull/178) ([anule](https://github.com/anule))
- Bump nokogiri from 1.10.5 to 1.10.8 [\#174](https://github.com/codeforamerica/honeycrisp-gem/pull/174) ([dependabot[bot]](https://github.com/apps/dependabot))
- Fixed spacing on text input groups [\#169](https://github.com/codeforamerica/honeycrisp-gem/pull/169) ([SymonneSingleton](https://github.com/SymonneSingleton))
- Fix z-index on Progress Indicator Bar [\#168](https://github.com/codeforamerica/honeycrisp-gem/pull/168) ([SymonneSingleton](https://github.com/SymonneSingleton))
- Update release instructions [\#164](https://github.com/codeforamerica/honeycrisp-gem/pull/164) ([mrotondo](https://github.com/mrotondo))
- Add sidebar nav [\#156](https://github.com/codeforamerica/honeycrisp-gem/pull/156) ([akingcfa](https://github.com/akingcfa))

## [v0.9.2](https://github.com/codeforamerica/honeycrisp-gem/tree/v0.9.2) (2020-01-14)

[Full Changelog](https://github.com/codeforamerica/honeycrisp-gem/compare/v0.9.1...v0.9.2)

**Implemented enhancements:**

- Update documentation display template [\#121](https://github.com/codeforamerica/honeycrisp-gem/issues/121)
- Move labels and extraneous button types to admin-specific file [\#115](https://github.com/codeforamerica/honeycrisp-gem/issues/115)
- Display names and hex codes on color samples [\#104](https://github.com/codeforamerica/honeycrisp-gem/issues/104)

**Closed issues:**

- Documentation for pagination HTML should show links, not buttons [\#149](https://github.com/codeforamerica/honeycrisp-gem/issues/149)
- Add documentation to progress indicators [\#148](https://github.com/codeforamerica/honeycrisp-gem/issues/148)

**Merged pull requests:**

- Update github\_changelog\_generator gem [\#163](https://github.com/codeforamerica/honeycrisp-gem/pull/163) ([mrotondo](https://github.com/mrotondo))
- Update Rack dependency to 2.0.8 for security issue [\#162](https://github.com/codeforamerica/honeycrisp-gem/pull/162) ([mrotondo](https://github.com/mrotondo))
- Adjusts how upload buttons are highlighted on focus. [\#161](https://github.com/codeforamerica/honeycrisp-gem/pull/161) ([mrotondo](https://github.com/mrotondo))
- Change from \<button\> to \<a\> elements for pagination [\#153](https://github.com/codeforamerica/honeycrisp-gem/pull/153) ([lkogler](https://github.com/lkogler))
- Add documentation to progress indicators [\#150](https://github.com/codeforamerica/honeycrisp-gem/pull/150) ([lkogler](https://github.com/lkogler))
- Button cleanup [\#147](https://github.com/codeforamerica/honeycrisp-gem/pull/147) ([mrotondo](https://github.com/mrotondo))
- Update Colors section of styleguide  [\#146](https://github.com/codeforamerica/honeycrisp-gem/pull/146) ([mrotondo](https://github.com/mrotondo))
- Add tabs to code examples for different languages \(html, erb\) [\#139](https://github.com/codeforamerica/honeycrisp-gem/pull/139) ([jenny-heath](https://github.com/jenny-heath))

## [v0.9.1](https://github.com/codeforamerica/honeycrisp-gem/tree/v0.9.1) (2019-12-10)

[Full Changelog](https://github.com/codeforamerica/honeycrisp-gem/compare/v0.9.0...v0.9.1)

**Implemented enhancements:**

- Put spacing examples into two columns [\#132](https://github.com/codeforamerica/honeycrisp-gem/issues/132)
- Add Honeycrisp branding  [\#122](https://github.com/codeforamerica/honeycrisp-gem/issues/122)
- Add development instructions to README [\#34](https://github.com/codeforamerica/honeycrisp-gem/issues/34)
- Make padding classes more flexible. [\#20](https://github.com/codeforamerica/honeycrisp-gem/issues/20)

**Fixed bugs:**

- Spacing issues with date fields and the last question on a page [\#13](https://github.com/codeforamerica/honeycrisp-gem/issues/13)

**Closed issues:**

- Active state on Upload button is larger than button boundaries on Chrome [\#142](https://github.com/codeforamerica/honeycrisp-gem/issues/142)

**Merged pull requests:**

- Remove margins around `.button` in `.file-upload` so outline is snug  [\#143](https://github.com/codeforamerica/honeycrisp-gem/pull/143) ([anule](https://github.com/anule))
- Spacing two columns [\#138](https://github.com/codeforamerica/honeycrisp-gem/pull/138) ([hartsick](https://github.com/hartsick))
- Use variables instead of hard-coded pixel values [\#137](https://github.com/codeforamerica/honeycrisp-gem/pull/137) ([lkogler](https://github.com/lkogler))
- Update branding to Honeycrisp [\#136](https://github.com/codeforamerica/honeycrisp-gem/pull/136) ([hartsick](https://github.com/hartsick))
- Bump loofah from 2.2.3 to 2.3.1 [\#133](https://github.com/codeforamerica/honeycrisp-gem/pull/133) ([dependabot[bot]](https://github.com/apps/dependabot))
- Vendorize prism [\#131](https://github.com/codeforamerica/honeycrisp-gem/pull/131) ([hartsick](https://github.com/hartsick))

## [v0.9.0](https://github.com/codeforamerica/honeycrisp-gem/tree/v0.9.0) (2019-11-05)

[Full Changelog](https://github.com/codeforamerica/honeycrisp-gem/compare/v0.8.0...v0.9.0)

**Fixed bugs:**

- Syntax highlighting incorrect for embedded ruby in styleguide reference [\#106](https://github.com/codeforamerica/honeycrisp-gem/issues/106)

**Merged pull requests:**

- Add migration guide [\#130](https://github.com/codeforamerica/honeycrisp-gem/pull/130) ([hartsick](https://github.com/hartsick))
- Documentation page: display explanation between example and code [\#128](https://github.com/codeforamerica/honeycrisp-gem/pull/128) ([jenny-heath](https://github.com/jenny-heath))
- Accessibility design details [\#123](https://github.com/codeforamerica/honeycrisp-gem/pull/123) ([norrishung](https://github.com/norrishung))

## [v0.8.0](https://github.com/codeforamerica/honeycrisp-gem/tree/v0.8.0) (2019-10-10)

[Full Changelog](https://github.com/codeforamerica/honeycrisp-gem/compare/v0.7.1...v0.8.0)

**Merged pull requests:**

- Add crossmark and checkmark list patterns to design system [\#127](https://github.com/codeforamerica/honeycrisp-gem/pull/127) ([norrishung](https://github.com/norrishung))

## [v0.7.1](https://github.com/codeforamerica/honeycrisp-gem/tree/v0.7.1) (2019-10-09)

[Full Changelog](https://github.com/codeforamerica/honeycrisp-gem/compare/v0.7.0...v0.7.1)

**Merged pull requests:**

- Bump rubyzip from 1.2.2 to 1.3.0 [\#126](https://github.com/codeforamerica/honeycrisp-gem/pull/126) ([dependabot[bot]](https://github.com/apps/dependabot))

## [v0.7.0](https://github.com/codeforamerica/honeycrisp-gem/tree/v0.7.0) (2019-10-08)

[Full Changelog](https://github.com/codeforamerica/honeycrisp-gem/compare/v0.6.5...v0.7.0)

**Implemented enhancements:**

- Add more documentation of spacing classes [\#114](https://github.com/codeforamerica/honeycrisp-gem/issues/114)
- Add optional text label for step progress bar [\#105](https://github.com/codeforamerica/honeycrisp-gem/issues/105)

**Merged pull requests:**

- Adding an accordion pattern [\#125](https://github.com/codeforamerica/honeycrisp-gem/pull/125) ([norrishung](https://github.com/norrishung))
- Hide unchecked follow up questions on page load [\#119](https://github.com/codeforamerica/honeycrisp-gem/pull/119) ([tdooner](https://github.com/tdooner))
- Fix follow-up to work for single checkbox [\#118](https://github.com/codeforamerica/honeycrisp-gem/pull/118) ([tdooner](https://github.com/tdooner))

## [v0.6.5](https://github.com/codeforamerica/honeycrisp-gem/tree/v0.6.5) (2019-07-15)

[Full Changelog](https://github.com/codeforamerica/honeycrisp-gem/compare/v0.6.4...v0.6.5)

**Implemented enhancements:**

- Explore screenshot testing [\#51](https://github.com/codeforamerica/honeycrisp-gem/issues/51)

**Merged pull requests:**

- Upgrade lodash to address CVE [\#117](https://github.com/codeforamerica/honeycrisp-gem/pull/117) ([hartsick](https://github.com/hartsick))
- Update toolbar for new GCF behaviors [\#116](https://github.com/codeforamerica/honeycrisp-gem/pull/116) ([tdooner](https://github.com/tdooner))
- Add a section about spacing to reference page [\#111](https://github.com/codeforamerica/honeycrisp-gem/pull/111) ([jenny-heath](https://github.com/jenny-heath))

## [v0.6.4](https://github.com/codeforamerica/honeycrisp-gem/tree/v0.6.4) (2019-07-01)

[Full Changelog](https://github.com/codeforamerica/honeycrisp-gem/compare/v0.6.2...v0.6.4)

**Merged pull requests:**

- Simplified step-bar-description [\#113](https://github.com/codeforamerica/honeycrisp-gem/pull/113) ([embarnard](https://github.com/embarnard))
- added student pair emoji [\#109](https://github.com/codeforamerica/honeycrisp-gem/pull/109) ([embarnard](https://github.com/embarnard))

## [v0.6.2](https://github.com/codeforamerica/honeycrisp-gem/tree/v0.6.2) (2019-06-25)

[Full Changelog](https://github.com/codeforamerica/honeycrisp-gem/compare/v0.6.1...v0.6.2)

**Merged pull requests:**

- Add emoji for "older man and woman" [\#108](https://github.com/codeforamerica/honeycrisp-gem/pull/108) ([tdooner](https://github.com/tdooner))
- Add support for optional progress step bar labels [\#107](https://github.com/codeforamerica/honeycrisp-gem/pull/107) ([hartsick](https://github.com/hartsick))

## [v0.6.1](https://github.com/codeforamerica/honeycrisp-gem/tree/v0.6.1) (2019-06-06)

[Full Changelog](https://github.com/codeforamerica/honeycrisp-gem/compare/v0.6.0...v0.6.1)

**Merged pull requests:**

- Fix bug on step progress bar: increment current\_step on a 0 index system [\#110](https://github.com/codeforamerica/honeycrisp-gem/pull/110) ([embarnard](https://github.com/embarnard))
- Add new type of notice [\#103](https://github.com/codeforamerica/honeycrisp-gem/pull/103) ([jenny-heath](https://github.com/jenny-heath))

## [v0.6.0](https://github.com/codeforamerica/honeycrisp-gem/tree/v0.6.0) (2019-05-21)

[Full Changelog](https://github.com/codeforamerica/honeycrisp-gem/compare/v0.5.11...v0.6.0)

**Merged pull requests:**

- Accessibility improvements from GCF audit [\#101](https://github.com/codeforamerica/honeycrisp-gem/pull/101) ([hartsick](https://github.com/hartsick))

## [v0.5.11](https://github.com/codeforamerica/honeycrisp-gem/tree/v0.5.11) (2019-04-04)

[Full Changelog](https://github.com/codeforamerica/honeycrisp-gem/compare/v0.5.10...v0.5.11)

**Fixed bugs:**

- Incrementer has vestigial arrows in Firefox [\#94](https://github.com/codeforamerica/honeycrisp-gem/issues/94)
- Hitting Command+0 in Firefox causes the page footer to move [\#14](https://github.com/codeforamerica/honeycrisp-gem/issues/14)

**Merged pull requests:**

- Remove stepper arrows for number input on Firefox [\#95](https://github.com/codeforamerica/honeycrisp-gem/pull/95) ([hartsick](https://github.com/hartsick))
- Add Percy snapshot to CircleCI [\#93](https://github.com/codeforamerica/honeycrisp-gem/pull/93) ([bensheldon](https://github.com/bensheldon))
- Refactor all styleguide examples to use partial; add link to isolated example [\#89](https://github.com/codeforamerica/honeycrisp-gem/pull/89) ([bensheldon](https://github.com/bensheldon))
- Add link to Github repo and issue submission [\#88](https://github.com/codeforamerica/honeycrisp-gem/pull/88) ([hartsick](https://github.com/hartsick))
- Make accessibility improvements [\#83](https://github.com/codeforamerica/honeycrisp-gem/pull/83) ([bensheldon](https://github.com/bensheldon))

## [v0.5.10](https://github.com/codeforamerica/honeycrisp-gem/tree/v0.5.10) (2019-02-16)

[Full Changelog](https://github.com/codeforamerica/honeycrisp-gem/compare/v0.5.9...v0.5.10)

**Implemented enhancements:**

- Set up rubocop and add to CI [\#86](https://github.com/codeforamerica/honeycrisp-gem/issues/86)
- Create links to individual components on reference page [\#53](https://github.com/codeforamerica/honeycrisp-gem/issues/53)
- Add gem release rake task [\#52](https://github.com/codeforamerica/honeycrisp-gem/issues/52)
- Add show-more component [\#30](https://github.com/codeforamerica/honeycrisp-gem/issues/30)

**Merged pull requests:**

- Add rubocop [\#87](https://github.com/codeforamerica/honeycrisp-gem/pull/87) ([hartsick](https://github.com/hartsick))
- Add show more pattern to molecules [\#82](https://github.com/codeforamerica/honeycrisp-gem/pull/82) ([anule](https://github.com/anule))
- Add anchorlink to individual examples [\#81](https://github.com/codeforamerica/honeycrisp-gem/pull/81) ([bensheldon](https://github.com/bensheldon))
- Add Brewfile and instructions for Chromedriver [\#80](https://github.com/codeforamerica/honeycrisp-gem/pull/80) ([bensheldon](https://github.com/bensheldon))
- Add changelog generation and instructions [\#73](https://github.com/codeforamerica/honeycrisp-gem/pull/73) ([hartsick](https://github.com/hartsick))

## [v0.5.9](https://github.com/codeforamerica/honeycrisp-gem/tree/v0.5.9) (2019-02-08)

[Full Changelog](https://github.com/codeforamerica/honeycrisp-gem/compare/03e893bd371986a17bada20d5fb49c3550dd3d77...v0.5.9)

**Implemented enhancements:**

- Update error message examples [\#62](https://github.com/codeforamerica/honeycrisp-gem/issues/62)
- Audit styleguide references to find unused pages [\#58](https://github.com/codeforamerica/honeycrisp-gem/issues/58)
- Make styleguide Sass variables available for use in host application [\#55](https://github.com/codeforamerica/honeycrisp-gem/issues/55)
- Add link to non-index styleguide pages [\#39](https://github.com/codeforamerica/honeycrisp-gem/issues/39)
- Create a styleguide reference for form builder [\#27](https://github.com/codeforamerica/honeycrisp-gem/issues/27)
- Create an emoji index [\#24](https://github.com/codeforamerica/honeycrisp-gem/issues/24)
- Update form organisms  [\#22](https://github.com/codeforamerica/honeycrisp-gem/issues/22)
- Allow for overriding variables [\#17](https://github.com/codeforamerica/honeycrisp-gem/issues/17)
- Set up CI [\#4](https://github.com/codeforamerica/honeycrisp-gem/issues/4)
- Form cards are missing top border [\#2](https://github.com/codeforamerica/honeycrisp-gem/issues/2)

**Fixed bugs:**

- Fix reveal pattern code [\#43](https://github.com/codeforamerica/honeycrisp-gem/issues/43)
- Teal primary button fails accessibility contrast check [\#18](https://github.com/codeforamerica/honeycrisp-gem/issues/18)

**Closed issues:**

- Delete unused styleguide pages and fix navigation [\#65](https://github.com/codeforamerica/honeycrisp-gem/issues/65)
- Create deployed styleguide [\#56](https://github.com/codeforamerica/honeycrisp-gem/issues/56)
- Make a step progress bar pattern [\#33](https://github.com/codeforamerica/honeycrisp-gem/issues/33)
- Gem doesn't provide its own layout file [\#9](https://github.com/codeforamerica/honeycrisp-gem/issues/9)
- Fix dropdown text wrapping [\#8](https://github.com/codeforamerica/honeycrisp-gem/issues/8)

**Merged pull requests:**

- Add axe-matchers; test all examples for accessibility [\#69](https://github.com/codeforamerica/honeycrisp-gem/pull/69) ([bensheldon](https://github.com/bensheldon))
- Add note about changes required to enable variable usage [\#68](https://github.com/codeforamerica/honeycrisp-gem/pull/68) ([zaksoup](https://github.com/zaksoup))
- Allow overriding variables [\#67](https://github.com/codeforamerica/honeycrisp-gem/pull/67) ([bengolder](https://github.com/bengolder))
- Remove unused styleguide pages [\#66](https://github.com/codeforamerica/honeycrisp-gem/pull/66) ([hartsick](https://github.com/hartsick))
- Add an emoji index [\#64](https://github.com/codeforamerica/honeycrisp-gem/pull/64) ([anule](https://github.com/anule))
- Update styleguide error message [\#63](https://github.com/codeforamerica/honeycrisp-gem/pull/63) ([hartsick](https://github.com/hartsick))
- Add detective woman emoji [\#61](https://github.com/codeforamerica/honeycrisp-gem/pull/61) ([zaksoup](https://github.com/zaksoup))
- Transition to using system tests [\#59](https://github.com/codeforamerica/honeycrisp-gem/pull/59) ([hartsick](https://github.com/hartsick))
- Add version number to page title [\#57](https://github.com/codeforamerica/honeycrisp-gem/pull/57) ([hartsick](https://github.com/hartsick))
- Add cfa\_select to the form builder [\#50](https://github.com/codeforamerica/honeycrisp-gem/pull/50) ([wschaefer-cfa](https://github.com/wschaefer-cfa))
- Create reusable components for molecules and atoms [\#49](https://github.com/codeforamerica/honeycrisp-gem/pull/49) ([bensheldon](https://github.com/bensheldon))
- Include single tap button examples in the form builder section [\#48](https://github.com/codeforamerica/honeycrisp-gem/pull/48) ([wschaefer-cfa](https://github.com/wschaefer-cfa))
- Add validations to form builder examples [\#47](https://github.com/codeforamerica/honeycrisp-gem/pull/47) ([hartsick](https://github.com/hartsick))
- Use example partials for form builder [\#45](https://github.com/codeforamerica/honeycrisp-gem/pull/45) ([wschaefer-cfa](https://github.com/wschaefer-cfa))
- Formbuilder styleguide reference [\#44](https://github.com/codeforamerica/honeycrisp-gem/pull/44) ([wschaefer-cfa](https://github.com/wschaefer-cfa))
- Add links to other styleguide pages [\#41](https://github.com/codeforamerica/honeycrisp-gem/pull/41) ([hartsick](https://github.com/hartsick))
- Add progress step bar [\#40](https://github.com/codeforamerica/honeycrisp-gem/pull/40) ([wschaefer-cfa](https://github.com/wschaefer-cfa))
- Add development Rails server and update development instructions [\#37](https://github.com/codeforamerica/honeycrisp-gem/pull/37) ([bensheldon](https://github.com/bensheldon))
- Add js for checkbox set with none [\#35](https://github.com/codeforamerica/honeycrisp-gem/pull/35) ([wschaefer-cfa](https://github.com/wschaefer-cfa))
- Add cfa\_single\_tap\_button to FormBuilder [\#32](https://github.com/codeforamerica/honeycrisp-gem/pull/32) ([hartsick](https://github.com/hartsick))
- Update gems [\#31](https://github.com/codeforamerica/honeycrisp-gem/pull/31) ([hartsick](https://github.com/hartsick))
- Add cfa\_checkbox\_set to form builder [\#29](https://github.com/codeforamerica/honeycrisp-gem/pull/29) ([wschaefer-cfa](https://github.com/wschaefer-cfa))
- Add CfaFormBuilder [\#26](https://github.com/codeforamerica/honeycrisp-gem/pull/26) ([wschaefer-cfa](https://github.com/wschaefer-cfa))
- bump rack due to security vulnerability [\#25](https://github.com/codeforamerica/honeycrisp-gem/pull/25) ([wschaefer-cfa](https://github.com/wschaefer-cfa))
- Bump gem version [\#23](https://github.com/codeforamerica/honeycrisp-gem/pull/23) ([hartsick](https://github.com/hartsick))
- Pull in latest GCF styleguide [\#12](https://github.com/codeforamerica/honeycrisp-gem/pull/12) ([hartsick](https://github.com/hartsick))
- Fix styling on non-main styleguide pages [\#11](https://github.com/codeforamerica/honeycrisp-gem/pull/11) ([hartsick](https://github.com/hartsick))
- Declare layout for Styleguide [\#10](https://github.com/codeforamerica/honeycrisp-gem/pull/10) ([hartsick](https://github.com/hartsick))
- Make radio button 'is-selected' more permissive wrt HTML structure [\#7](https://github.com/codeforamerica/honeycrisp-gem/pull/7) ([hartsick](https://github.com/hartsick))
- Add CircleCI config [\#5](https://github.com/codeforamerica/honeycrisp-gem/pull/5) ([hartsick](https://github.com/hartsick))
- Fold in latest changes from GCF styleguide [\#3](https://github.com/codeforamerica/honeycrisp-gem/pull/3) ([hartsick](https://github.com/hartsick))
- Modify javascript for inclusion in gem [\#1](https://github.com/codeforamerica/honeycrisp-gem/pull/1) ([hartsick](https://github.com/hartsick))



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
