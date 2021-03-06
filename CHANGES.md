# Change Log

## [v4.0.5-alpha](https://github.com/testfx/testfx/tree/v4.0.5-alpha) (2016-12-19)
[Full Changelog](https://github.com/testfx/testfx/compare/v4.0.4-alpha...v4.0.5-alpha)

**Merged pull requests:**

- \(refactor\) Moved `ShortcutKeyTest` to core package. [\#342](https://github.com/TestFX/TestFX/pull/342) ([JordanMartinez](https://github.com/JordanMartinez))
- Doc api package [\#341](https://github.com/TestFX/TestFX/pull/341) ([JordanMartinez](https://github.com/JordanMartinez))
- Doc toolkit interfaces [\#340](https://github.com/TestFX/TestFX/pull/340) ([JordanMartinez](https://github.com/JordanMartinez))
- Doc toolkit package [\#339](https://github.com/TestFX/TestFX/pull/339) ([JordanMartinez](https://github.com/JordanMartinez))
- Replace all uber jar deps [\#338](https://github.com/TestFX/TestFX/pull/338) ([SimY4](https://github.com/SimY4))
- Junit5 adapter [\#337](https://github.com/TestFX/TestFX/pull/337) ([SimY4](https://github.com/SimY4))
- \(doc\) Add documentation to TextInputControls [\#335](https://github.com/TestFX/TestFX/pull/335) ([JordanMartinez](https://github.com/JordanMartinez))
- Document support package [\#334](https://github.com/TestFX/TestFX/pull/334) ([JordanMartinez](https://github.com/JordanMartinez))
- \(fix\) Use os-independent SHORTCUT, not CONTROL keycode [\#333](https://github.com/TestFX/TestFX/pull/333) ([JordanMartinez](https://github.com/JordanMartinez))
- Document finder package [\#332](https://github.com/TestFX/TestFX/pull/332) ([JordanMartinez](https://github.com/JordanMartinez))
- Document FxRobotInterface [\#331](https://github.com/TestFX/TestFX/pull/331) ([JordanMartinez](https://github.com/JordanMartinez))
- \(refactor\) Use Java 8 Streams, not Guava [\#330](https://github.com/TestFX/TestFX/pull/330) ([JordanMartinez](https://github.com/JordanMartinez))
- \(cleanup\) Use `getWidth\(\)` and `getHeight\(\)` rather than calculate it [\#329](https://github.com/TestFX/TestFX/pull/329) ([JordanMartinez](https://github.com/JordanMartinez))
- Add javadoc to util package [\#328](https://github.com/TestFX/TestFX/pull/328) ([JordanMartinez](https://github.com/JordanMartinez))
- Add documenttion to Locator interfaces [\#327](https://github.com/TestFX/TestFX/pull/327) ([JordanMartinez](https://github.com/JordanMartinez))
- Document query-related interfaces [\#326](https://github.com/TestFX/TestFX/pull/326) ([JordanMartinez](https://github.com/JordanMartinez))
- Add basic documentation to Robot classes [\#325](https://github.com/TestFX/TestFX/pull/325) ([JordanMartinez](https://github.com/JordanMartinez))
- Re-enable Findbugs linting. [\#324](https://github.com/TestFX/TestFX/pull/324) ([brcolow](https://github.com/brcolow))
- Update gradle wrapper version to 3.2.1 \(latest\). [\#322](https://github.com/TestFX/TestFX/pull/322) ([brcolow](https://github.com/brcolow))
- Add more Checkstyle rules, cleanup accordingly. [\#321](https://github.com/TestFX/TestFX/pull/321) ([brcolow](https://github.com/brcolow))
- Convert Shortcut to os-specific shortcut key [\#320](https://github.com/TestFX/TestFX/pull/320) ([JordanMartinez](https://github.com/JordanMartinez))
- Release all pressed keys after test finishes to prevent hanging [\#319](https://github.com/TestFX/TestFX/pull/319) ([JordanMartinez](https://github.com/JordanMartinez))
- Use Java8's Optional/Predicate/Function instead of Guava's [\#318](https://github.com/TestFX/TestFX/pull/318) ([aalmiray](https://github.com/aalmiray))
- Add gitter badge, fix maven central typo. [\#316](https://github.com/TestFX/TestFX/pull/316) ([brcolow](https://github.com/brcolow))
- Update dependencies. [\#315](https://github.com/TestFX/TestFX/pull/315) ([brcolow](https://github.com/brcolow))
- Re-enable Checkstyle, removing exisiting violations. [\#314](https://github.com/TestFX/TestFX/pull/314) ([brcolow](https://github.com/brcolow))
- Add Appveyor CI build script. [\#313](https://github.com/TestFX/TestFX/pull/313) ([brcolow](https://github.com/brcolow))
- Add building on macOS to travis. [\#312](https://github.com/TestFX/TestFX/pull/312) ([brcolow](https://github.com/brcolow))
- \(docs\) fix pom formatting [\#308](https://github.com/TestFX/TestFX/pull/308) ([feldoh](https://github.com/feldoh))
- Allow for matching a table row without specifying index. [\#303](https://github.com/TestFX/TestFX/pull/303) ([brcolow](https://github.com/brcolow))
- \(fix\) Close resources with try-resource in CaptureSupport. [\#298](https://github.com/TestFX/TestFX/pull/298) ([hastebrot](https://github.com/hastebrot))
- \(fix\) Add check to cleanup for active FX Application Thread. [\#288](https://github.com/TestFX/TestFX/pull/288) ([Ortner](https://github.com/Ortner))
- Add scroll left/right to ScrollRobot [\#285](https://github.com/TestFX/TestFX/pull/285) ([aalmiray](https://github.com/aalmiray))
- Add WindowMatchers class [\#284](https://github.com/TestFX/TestFX/pull/284) ([aalmiray](https://github.com/aalmiray))
- Fixes for suggestions by @hastebrot for ComboBoxMatchers [\#270](https://github.com/TestFX/TestFX/pull/270) ([brcolow](https://github.com/brcolow))
- \(feat\) Add `ComboBoxMatchers` functionality and tests. [\#269](https://github.com/TestFX/TestFX/pull/269) ([brcolow](https://github.com/brcolow))
- Added interactFast\(...\) Method to FxRobot\(Interface\) [\#268](https://github.com/TestFX/TestFX/pull/268) ([Ortner](https://github.com/Ortner))
- \(fix\) Java 8u40: Monocle `HeadlessPlatform` class not found. [\#265](https://github.com/TestFX/TestFX/pull/265) ([brcolow](https://github.com/brcolow))
- \(refactor\) Wrap Image into functional interface. [\#263](https://github.com/TestFX/TestFX/pull/263) ([hastebrot](https://github.com/hastebrot))

## [v4.0.4-alpha](https://github.com/testfx/testfx/tree/v4.0.4-alpha) (2016-03-29)
[Full Changelog](https://github.com/testfx/testfx/compare/v4.0.3-alpha...v4.0.4-alpha)

**Merged pull requests:**

- \(feat\) Introduce `FxRobot::bounds\(\)` and `BoundsQuery`. [\#258](https://github.com/TestFX/TestFX/pull/258) ([hastebrot](https://github.com/hastebrot))
- \(refactor\) ApplicationService: Use Application instead of ApplicationFixture. [\#257](https://github.com/TestFX/TestFX/pull/257) ([hastebrot](https://github.com/hastebrot))

## [v4.0.3-alpha](https://github.com/testfx/testfx/tree/v4.0.3-alpha) (2016-03-25)
[Full Changelog](https://github.com/testfx/testfx/compare/v4.0.2-alpha...v4.0.3-alpha)

**Merged pull requests:**

- \(feat\) TextFlowMatchers: Add matchers for the text of a TextFlow. [\#259](https://github.com/TestFX/TestFX/pull/259) ([brcolow](https://github.com/brcolow))
- \(feat\) TableViewMatchers: Add containsRow\(\). [\#255](https://github.com/TestFX/TestFX/pull/255) ([brcolow](https://github.com/brcolow))
- \(feat\) ListViewMatchers: Add hasPlaceholder\(Node placeholder\). [\#252](https://github.com/TestFX/TestFX/pull/252) ([brcolow](https://github.com/brcolow))
- \(feat\) ListViewMatchers: Add isEmpty\(\). [\#251](https://github.com/TestFX/TestFX/pull/251) ([brcolow](https://github.com/brcolow))
- \(refactor\) `NodeQuery`: Rename methods to `match\(\)`, `nth\(\)` and `query\(\)`. [\#250](https://github.com/TestFX/TestFX/pull/250) ([hastebrot](https://github.com/hastebrot))
- \(feat\) Add PixelMatcher to CaptureSupport. [\#248](https://github.com/TestFX/TestFX/pull/248) ([hastebrot](https://github.com/hastebrot))

## [v4.0.2-alpha](https://github.com/testfx/testfx/tree/v4.0.2-alpha) (2016-02-22)
[Full Changelog](https://github.com/testfx/testfx/compare/v4.0.1-alpha...v4.0.2-alpha)

**Merged pull requests:**

- \(feat\) Add `FxRobot::interrupt\(\)` method to wait for the JavaFX thread. [\#240](https://github.com/TestFX/TestFX/pull/240) ([hastebrot](https://github.com/hastebrot))
- \(fix\) `WriteRobot::write\(\)` to prefer the `Scene` of the focused window. [\#239](https://github.com/TestFX/TestFX/pull/239) ([hastebrot](https://github.com/hastebrot))
- \(refactor\) Rename window methods to `targetWindow\(\)`, `listWindows\(\)`, and `window\(\)`. [\#238](https://github.com/TestFX/TestFX/pull/238) ([hastebrot](https://github.com/hastebrot))
- \(feature\) Added ApplicationRule [\#234](https://github.com/TestFX/TestFX/pull/234) ([johnzeringue](https://github.com/johnzeringue))
- \(refactor\) Improve encapsulation of classes. [\#233](https://github.com/TestFX/TestFX/pull/233) ([hastebrot](https://github.com/hastebrot))
- Fixed google group link [\#221](https://github.com/TestFX/TestFX/pull/221) ([joachimprinzbach](https://github.com/joachimprinzbach))
- \(feat\) Support for configurable timeouts in AppRobotTestBase. Useful when debugging at the application's set… [\#214](https://github.com/TestFX/TestFX/pull/214) ([naimdjon](https://github.com/naimdjon))
- \(chore\) Travis: Allow jobs without framebuffer to fail. [\#211](https://github.com/TestFX/TestFX/pull/211) ([johnzeringue](https://github.com/johnzeringue))
- \(feat\) `hasTableCell\(\)`: Match the string value of cell item. [\#210](https://github.com/TestFX/TestFX/pull/210) ([johnzeringue](https://github.com/johnzeringue))
- \(chore\) Travis: Run tests once with and once without framebuffer screen. [\#209](https://github.com/TestFX/TestFX/pull/209) ([hastebrot](https://github.com/hastebrot))

## [v4.0.1-alpha](https://github.com/testfx/testfx/tree/v4.0.1-alpha) (2015-03-04)
[Full Changelog](https://github.com/testfx/testfx/compare/v4.0.0-alpha...v4.0.1-alpha)

**Merged pull requests:**

- \(refactor\) Service: Make `NodeFinder` more familiar to JavaFX developers. [\#205](https://github.com/TestFX/TestFX/pull/205) ([hastebrot](https://github.com/hastebrot))
- \(revert\) Legacy: Revert `GuiTest` and remove `ApplicationTest`, `FxTest` and `CustomAppTest`. [\#204](https://github.com/TestFX/TestFX/pull/204) ([hastebrot](https://github.com/hastebrot))
- \(feat\) JUnit: Add support classes, including an `ApplicationTest` base test class. [\#163](https://github.com/TestFX/TestFX/pull/163) ([hastebrot](https://github.com/hastebrot))

## [v4.0.0-alpha](https://github.com/testfx/testfx/tree/v4.0.0-alpha) (2015-02-27)
[Full Changelog](https://github.com/testfx/testfx/compare/v3.1.2...v4.0.0-alpha)

**Merged pull requests:**

- \(doc\) Add Unstable annotations to classes and methods. [\#203](https://github.com/TestFX/TestFX/pull/203) ([hastebrot](https://github.com/hastebrot))
- \(feat\) ListViews provides a row selected matcher. [\#202](https://github.com/TestFX/TestFX/pull/202) ([Ciruman](https://github.com/Ciruman))
- \(chore\) Gradle: Cleanup build scripts. [\#201](https://github.com/TestFX/TestFX/pull/201) ([hastebrot](https://github.com/hastebrot))
- \(fix\) Deprecation and compile warnings caused by dependency upgrades. [\#198](https://github.com/TestFX/TestFX/pull/198) ([hastebrot](https://github.com/hastebrot))
- \(chore\) Gradle: Remove JUnit compile dependency and update Guava. [\#197](https://github.com/TestFX/TestFX/pull/197) ([hastebrot](https://github.com/hastebrot))
- \(doc\) Readme: Update `README.md`. [\#196](https://github.com/TestFX/TestFX/pull/196) ([hastebrot](https://github.com/hastebrot))
- \(feat\) Assert, Matcher: Improve type-aware matchers. [\#195](https://github.com/TestFX/TestFX/pull/195) ([hastebrot](https://github.com/hastebrot))
- \(refactor\) API: Rename pointFor\(\) to point\(\) and add pointOfVisibleNode\(\). [\#194](https://github.com/TestFX/TestFX/pull/194) ([hastebrot](https://github.com/hastebrot))
- \(refactor\) Legacy: Move org.loadui.testfx to testfx-legacy module. [\#192](https://github.com/TestFX/TestFX/pull/192) ([hastebrot](https://github.com/hastebrot))
- \(feat\) Allow instrumenting entire Applications. [\#183](https://github.com/TestFX/TestFX/pull/183) ([0x4a616e](https://github.com/0x4a616e))
- \(doc\) Toolkit: Prepare docs and tests for candidate phase. [\#176](https://github.com/TestFX/TestFX/pull/176) ([hastebrot](https://github.com/hastebrot))
- \(feat\) Service: Implement NodeQuery. [\#174](https://github.com/TestFX/TestFX/pull/174) ([hastebrot](https://github.com/hastebrot))
- \(refactor\) API: Move some org.loadui.testfx classes to org.testfx. [\#172](https://github.com/TestFX/TestFX/pull/172) ([hastebrot](https://github.com/hastebrot))
- \(refactor\) API: Move FxRobot to org.testfx.api. [\#171](https://github.com/TestFX/TestFX/pull/171) ([hastebrot](https://github.com/hastebrot))
- \(refactor\) Toolkit: Prepare API for beta phase. [\#170](https://github.com/TestFX/TestFX/pull/170) ([hastebrot](https://github.com/hastebrot))
- \(feat\) Robot: Support for Unicode strings in WriteRobot. [\#166](https://github.com/TestFX/TestFX/pull/166) ([hastebrot](https://github.com/hastebrot))
- \(refactor\) API: Introduce FxSelector and FxSelectorContext. [\#165](https://github.com/TestFX/TestFX/pull/165) ([hastebrot](https://github.com/hastebrot))
- \(feat\) Assert, Matcher: Implement type-aware matchers. [\#164](https://github.com/TestFX/TestFX/pull/164) ([hastebrot](https://github.com/hastebrot))
- \(feat\) Lifecycle, Robot: Headless support. [\#159](https://github.com/TestFX/TestFX/pull/159) ([hastebrot](https://github.com/hastebrot))
- \(feat\) Lifecycle: Implement LifecycleService. [\#156](https://github.com/TestFX/TestFX/pull/156) ([hastebrot](https://github.com/hastebrot))
- \(refactor\) Util: Enhance RunWaitUtils. [\#154](https://github.com/TestFX/TestFX/pull/154) ([hastebrot](https://github.com/hastebrot))
- \(refactor\) Framework: Extract ToolkitApplication. [\#153](https://github.com/TestFX/TestFX/pull/153) ([hastebrot](https://github.com/hastebrot))
-  \(fix\) Util: Only start waiting for boolean observable when it is false. [\#151](https://github.com/TestFX/TestFX/pull/151) ([hastebrot](https://github.com/hastebrot))
- \(feat\) Util: Provide `invokeIn...\(\)` and `waitFor...\(\)` methods. [\#150](https://github.com/TestFX/TestFX/pull/150) ([hastebrot](https://github.com/hastebrot))
- \(refactor\) Robot: Extract mouse methods to MouseRobotImpl and rename ... [\#149](https://github.com/TestFX/TestFX/pull/149) ([hastebrot](https://github.com/hastebrot))
- \(refactor\) Robot: Revise Robots related to keyboard inputs. [\#147](https://github.com/TestFX/TestFX/pull/147) ([hastebrot](https://github.com/hastebrot))
- \(feat\) Robot: Implement adapters for Awt, Glass and JavaFX robots. [\#146](https://github.com/TestFX/TestFX/pull/146) ([hastebrot](https://github.com/hastebrot))
- \(doc\) Readme: Fix broken links to source code and update links to TestFX... [\#142](https://github.com/TestFX/TestFX/pull/142) ([jotomo](https://github.com/jotomo))
- Respect headless mode instead of enforcing it [\#137](https://github.com/TestFX/TestFX/pull/137) ([sergei-ivanov](https://github.com/sergei-ivanov))
- waffle.io Badge [\#134](https://github.com/TestFX/TestFX/pull/134) ([waffle-iron](https://github.com/waffle-iron))
- make timeout configurable [\#133](https://github.com/TestFX/TestFX/pull/133) ([cwiejack](https://github.com/cwiejack))
- \(chore\) Gradle: Reintroduce BinTray support. [\#128](https://github.com/TestFX/TestFX/pull/128) ([hastebrot](https://github.com/hastebrot))
- \(chore\) Gradle: Temporarily remove BinTray support to fix Gradle view refresh in IntelliJ IDEA. [\#127](https://github.com/TestFX/TestFX/pull/127) ([hastebrot](https://github.com/hastebrot))
- \(fix\) AppLauncher could not retrieve primary Stage on OSX. [\#126](https://github.com/TestFX/TestFX/pull/126) ([hastebrot](https://github.com/hastebrot))
- \(fix\) Matcher: nodeHasLabel\(\) does not perform instance check for Text. [\#124](https://github.com/TestFX/TestFX/pull/124) ([naimdjon](https://github.com/naimdjon))
- Update build files [\#122](https://github.com/TestFX/TestFX/pull/122) ([aalmiray](https://github.com/aalmiray))
- \(chore\) Gradle: Add project.jfxrtLocation to test.classpath. [\#120](https://github.com/TestFX/TestFX/pull/120) ([hastebrot](https://github.com/hastebrot))
- \(chore\) Travis: Try to use xvfb \(X Virtual Framebuffer\). [\#119](https://github.com/TestFX/TestFX/pull/119) ([hastebrot](https://github.com/hastebrot))
- \(chore\) Travis: Add `.travis.yml`. [\#118](https://github.com/TestFX/TestFX/pull/118) ([hastebrot](https://github.com/hastebrot))
- \(chore\) Gradle: Fix missing Gradle wrapper. [\#117](https://github.com/TestFX/TestFX/pull/117) ([hastebrot](https://github.com/hastebrot))
- \(chore\) Gradle: Rerun `gradle wrapper`. [\#116](https://github.com/TestFX/TestFX/pull/116) ([hastebrot](https://github.com/hastebrot))
- \#110: jcenter is not supported in gradle \< 1.7 [\#113](https://github.com/TestFX/TestFX/pull/113) ([naimdjon](https://github.com/naimdjon))
- \(fix\) Add license header to MoveRobotImpl. [\#112](https://github.com/TestFX/TestFX/pull/112) ([hastebrot](https://github.com/hastebrot))
- Update HasLabelStringMatcher.java [\#108](https://github.com/TestFX/TestFX/pull/108) ([torakiki](https://github.com/torakiki))
- \(refactor\) Robot: Refactor FxRobot. [\#105](https://github.com/TestFX/TestFX/pull/105) ([hastebrot](https://github.com/hastebrot))
- \(fix\) Compiler warnings for deprecated JUnit methods. [\#104](https://github.com/TestFX/TestFX/pull/104) ([hastebrot](https://github.com/hastebrot))
- \(fix\) Service: Fix compatibility to Java 7 and JavaFX 2. [\#103](https://github.com/TestFX/TestFX/pull/103) ([hastebrot](https://github.com/hastebrot))
- \(refactor\) Robot: Refactor TypeRobotImpl. [\#102](https://github.com/TestFX/TestFX/pull/102) ([hastebrot](https://github.com/hastebrot))
- \(refactor\) Robot: Add regression tests and refactor KeyboardRobotImpl. [\#101](https://github.com/TestFX/TestFX/pull/101) ([hastebrot](https://github.com/hastebrot))
- \(refactor\) Robot: Add regression tests and refactor ScrollRobotImpl. [\#100](https://github.com/TestFX/TestFX/pull/100) ([hastebrot](https://github.com/hastebrot))
- \(test\) Move ScrollPaneTest from unit tests to integration tests. [\#99](https://github.com/TestFX/TestFX/pull/99) ([hastebrot](https://github.com/hastebrot))
- \(feat\) Robot: Add regression tests and create DragRobotImpl. [\#98](https://github.com/TestFX/TestFX/pull/98) ([hastebrot](https://github.com/hastebrot))
- \(feat\) Robot: Add regression tests and create ClickRobotImpl. [\#97](https://github.com/TestFX/TestFX/pull/97) ([hastebrot](https://github.com/hastebrot))
- \(feat\) Robot: Add regression tests and create MoveRobotImpl. [\#96](https://github.com/TestFX/TestFX/pull/96) ([hastebrot](https://github.com/hastebrot))
- Fix scroll direction as UP was going down \(and DOWN up\). [\#95](https://github.com/TestFX/TestFX/pull/95) ([lgringo](https://github.com/lgringo))
- \(refactor\) Robot: Add regression tests and refactor MouseRobotImpl. [\#94](https://github.com/TestFX/TestFX/pull/94) ([hastebrot](https://github.com/hastebrot))
- Extract static methods from FxRobot to GuiTest [\#91](https://github.com/TestFX/TestFX/pull/91) ([hastebrot](https://github.com/hastebrot))
- \(chore\) Gradle: Build now runs with `gradle clean jar javadocJar sourceJar test check`. [\#88](https://github.com/TestFX/TestFX/pull/88) ([hastebrot](https://github.com/hastebrot))
- \(fix\) Service: Calls to `Point2D\#add\(\)` incompatible with Java 7. [\#87](https://github.com/TestFX/TestFX/pull/87) ([hastebrot](https://github.com/hastebrot))
- Setup a multi-project Gradle build [\#71](https://github.com/TestFX/TestFX/pull/71) ([aalmiray](https://github.com/aalmiray))
- \(feat\) Implement CallableBoundsPointQuery. [\#68](https://github.com/TestFX/TestFX/pull/68) ([hastebrot](https://github.com/hastebrot))
- Fix NP in containsCell in TableViews [\#67](https://github.com/TestFX/TestFX/pull/67) ([rladstaetter](https://github.com/rladstaetter))
- No longer fixed scene size. [\#62](https://github.com/TestFX/TestFX/pull/62) ([minisu](https://github.com/minisu))
- Misc fixes + bumped version. [\#61](https://github.com/TestFX/TestFX/pull/61) ([minisu](https://github.com/minisu))
- \(refactor\) Extract robot and service classes from GuiTest. [\#39](https://github.com/TestFX/TestFX/pull/39) ([hastebrot](https://github.com/hastebrot))

## [v3.1.2](https://github.com/testfx/testfx/tree/v3.1.2) (2014-01-30)
[Full Changelog](https://github.com/testfx/testfx/compare/v3.1.0...v3.1.2)

**Merged pull requests:**

- Now releases keys/buttons on test aborted. \#23 [\#60](https://github.com/TestFX/TestFX/pull/60) ([minisu](https://github.com/minisu))
- Now aborts test on user mouse movement. Related to \#55 [\#59](https://github.com/TestFX/TestFX/pull/59) ([minisu](https://github.com/minisu))
- \#47: getVisibleNodes\(\) returns normal static Set [\#48](https://github.com/TestFX/TestFX/pull/48) ([Philipp91](https://github.com/Philipp91))
- \#43: push\(\) does not wait between press/release calls [\#45](https://github.com/TestFX/TestFX/pull/45) ([Philipp91](https://github.com/Philipp91))

## [v3.1.0](https://github.com/testfx/testfx/tree/v3.1.0) (2014-01-12)
[Full Changelog](https://github.com/testfx/testfx/compare/v3.0.0...v3.1.0)

**Merged pull requests:**

- Faster mouse movement over long distances [\#35](https://github.com/TestFX/TestFX/pull/35) ([Philipp91](https://github.com/Philipp91))

## [v3.0.0](https://github.com/testfx/testfx/tree/v3.0.0) (2013-12-23)
**Merged pull requests:**

- Add a Bitdeli Badge to README [\#26](https://github.com/TestFX/TestFX/pull/26) ([bitdeli-chef](https://github.com/bitdeli-chef))
- Corrected verifyThat\(\) to accept super-Matchers [\#22](https://github.com/TestFX/TestFX/pull/22) ([Philipp91](https://github.com/Philipp91))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*