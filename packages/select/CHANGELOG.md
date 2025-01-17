# @leafygreen-ui/select

## 3.0.0

### Minor Changes

- 857a680a: Adds support for positioning popover elements relative to elements within a scroll container other than the window.
  Adds support for setting z-index on popover elements with the `zIndex` prop.

### Patch Changes

- Updated dependencies [857a680a]
- Updated dependencies [857a680a]
  - @leafygreen-ui/leafygreen-provider@2.1.0
  - @leafygreen-ui/popover@7.2.0
  - @leafygreen-ui/button@12.0.0

## 2.1.0

### Minor Changes

- 559ceb15: Support a prop to disable the option to deselect

## 2.0.5

### Patch Changes

- 83fbfa53: Updates styles for a focused Option component to improve the contrast ratio.

## 2.0.4

### Patch Changes

- 90321b36: Imports validateProps functions from `@leafygreen-ui/a11y` package.
- ab581f34: Re-released components that were erroneously released without `.d.ts` files
- Updated dependencies [ab581f34]
- Updated dependencies [90321b36]
  - @leafygreen-ui/button@11.0.2
  - @leafygreen-ui/palette@3.2.1
  - @leafygreen-ui/lib@7.0.0
  - @leafygreen-ui/icon@10.2.1
  - @leafygreen-ui/leafygreen-provider@2.0.3
  - @leafygreen-ui/popover@7.1.4
  - @leafygreen-ui/tokens@0.5.1

## 2.0.3

### Patch Changes

- 65032024: Updates component to Button v11
- Updated dependencies [65032024]
- Updated dependencies [65032024]
  - @leafygreen-ui/palette@3.2.0
  - @leafygreen-ui/button@11.0.0

## 2.0.2

### Patch Changes

- 139694ea: Removes `role="combobox"` from Select dropdown

## 2.0.1

### Patch Changes

- Updated dependencies [ec27f36e]
  - @leafygreen-ui/icon@10.0.0

## 2.0.0

### Major Changes

- cc921a0e: Consuming applications can now set the width of the select dropdown by passing a value to width through the `className` prop.

## 1.1.4

### Patch Changes

- d85f65de: Adds accessible name to ARIA input field

## 1.1.3

### Patch Changes

- Updated dependencies [f805b772]
  - @leafygreen-ui/icon@9.0.0

## 1.1.2

### Patch Changes

- bf8b83e1: Sets aria `role="presentation"` on Caret in the component's menu button
- Updated dependencies [bf8b83e1]
- Updated dependencies [dca5605b]
  - @leafygreen-ui/icon@8.0.1
  - @leafygreen-ui/popover@7.1.2

## 1.1.1

### Patch Changes

- Updated dependencies [ba56b1cc]
  - @leafygreen-ui/icon@8.0.0

## 1.1.0

### Minor Changes

- 102ebc1e: - Adds a `usePortal` prop
  - Explicitly defines `font-family` for text elements within component
  - Sets label and description display properties to `block`

### Patch Changes

- 9812c9c9: Fixes bug where when a non-centered `Option` is clicked, the component will scroll to center that element instead of being selected.
  Now, when an element is clicked, it becomes selected. When opening the dropdown later, the selected item should then be centered.
- Updated dependencies [2daf1808]
- Updated dependencies [a6360ea1]
  - @leafygreen-ui/icon@7.1.0
  - @leafygreen-ui/popover@7.1.1

## 1.0.0

### Major Changes

- 0963164a: Initial release of Select component
