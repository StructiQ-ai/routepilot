# Changelog

## 0.1.1

All six packages are released together at 0.1.1.

### Fixed

- **Typing in a text field during a tour.** While a tour runs, the scroll lock stops keys that scroll the page
  (space, arrows up/down, page up/down, home, end). In 0.1.0 it also did so inside `input`, `textarea`, `select` and
  editable elements whenever no ancestor was scrollable, so a space could not be typed there. Keys pressed in an
  editable element are now left alone (`@routepilot/react`, `@routepilot/angular`).

### Added

- **`tooltip.buttonLabels.stepCounter`**: the text of the step counter as a template with `{current}` and `{total}`,
  e.g. `'Schritt {current} von {total}'`. The default, `'Step {current} of {total}'`, is what 0.1.0 showed.
  `formatStepCounter` is exported by `@routepilot/engine`, `@routepilot/react` and `@routepilot/angular`.

### Changed

- The repository moved to https://github.com/StructiQ-ai/routepilot. Package names are unchanged.

## 0.1.0

First public release.
