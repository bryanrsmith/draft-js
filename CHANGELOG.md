# Changelog

Notable changes to Draft.js will be documented in this file.

Changes to `src` are live in production on facebook.com at the time of release.

## 0.3.0 (March 22, 2016)

### Fixed

* Properly extract custom inline styles for `convertToRaw`
* Fix internal paste behavior to better handle copied custom blocks

### Added

* Export `getVisibleSelectionRect`
* Export `convertFromHTML`
* Export `DraftEditorBlock`

## 0.2.2 (March 9, 2016)

### Fixed

* Build before publish to get the warning suppression in place correctly

## 0.2.1 (March 9, 2016)

### Added

* React 15 RC as peer/dev dependency, provide `suppressContentEditableWarning`

## 0.2.0 (March 8, 2016)

### Added

* Move `white-space: pre-wrap` into inline style to resolve insertion issues
* `handleDrop` prop method for `Editor` to allow manual drop management
* `decoratedText` prop for decorator components
* `getVisibleSelectionRect`, to provide Rect for DOM selection
* Export `KeyBindingUtil` and `getDefaultKeyBinding`

### Fixed

* Triple-clicks followed by block type changes now only affect first block
* `DraftEditorLeaf` now re-renders correctly when its styles change
* Backspace behavior within empty code blocks

## 0.1.0 (February 22, 2016)

* Initial public release
