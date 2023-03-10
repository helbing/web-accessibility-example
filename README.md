# Web Accessibilty Example

[WCAG](https://www.w3.org/TR/WCAG21/) has nearly 100 rules, which are boring and difficult to understand. This repository offer some examples for developer to learn Web Accessibilty.

## Accessibilty software(aka screen reader)

Before you learnning WCAG, you have to try Accessibilty software, such as:

- [VoiceOver](https://www.apple.com/accessibility/)(macOS/iOS builtin)
- [TalkBack](https://play.google.com/store/apps/details?id=com.google.android.marvin.talkback&hl=zh&gl=US)
- [Windows Accessibility](https://support.microsoft.com/en-us/accessibility)(builtin)

## Catalog

### Axe Checker

WACG has so many rules, we don't need to learn rule by rule, we can learn and fix them when axe-checker report errors.

- [Axe Rules and Remediation Advice](https://dequeuniversity.com/rules/axe/)
- If you're a developer, you can use:
  - [dequelabs/axe-core](https://github.com/dequelabs/axe-core)
  - ESlint: [eslint-plugin-jsx-a11y](https://www.npmjs.com/package/eslint-plugin-jsx-a11y)
  - React developer: [@axe-core/react](https://www.npmjs.com/package/@axe-core/react)
  - Vuejs developer: [vue-axe@next](https://github.com/vue-a11y/vue-axe-next)

## ARIA

HTML standard components have good support for Web Accessibilty, but when we develop custom component, how make it support Web Accessibilty. That why we need [ARIA](https://www.w3.org/WAI/standards-guidelines/aria/). ARIA is an HTML extension that provides a set of HTML attributes to help user can use the screen reader correctly. W3C provides a tutorial: [ARIA Authoring Practices Guide (APG)](https://www.w3.org/WAI/ARIA/apg/) that contains some examples, such as:

- [Accordion](./aria/accordion/)
- [Alert](./aria/alert/)
- [Alert and Message Dialogs](./aria/alertdialog/)
- [Breadcrumb](./aria/breadcrumb/)
- [Button](./aria/button/)
- [Carousel](./aria/carousel/)
- [Checkbox](./aria//checkbox/)
- [Combobox](./aria/combobox/)
- [Dialog](./aria/dialog/)
- [Disclosure](./aria/disclosure/)
- Feed
- Grids
- Landmarks
- [Link](./aria/link/)
- [Listbox](./aria/listbox/)
- [Menu or Menu bar](./aria/menubar/)
- [Menu Button](./aria/menubutton/)
- [Meter](./aria/meter/)
- [Radio Group](./aria/radio/)
- [Slider](./aria/slider/)
- Slider (Multi-Thumb)
- [Spinbutton](./aria/spinbutton/)
- [Switch](./aria/switch/)
- Table
- [Tabs](./aria/tabs/)
- [Toolbar](./aria/toolbar/)
- Tooltip Widget
- [Tree View](./aria/treeview/)
- [Treegrid](./aria/treegrid/)
- Window Splitter

## The end

[No ARIA is better than Bad ARIA](https://www.w3.org/WAI/ARIA/apg/practices/read-me-first/). Some people want to help people with disabilities, also I, but after learning WCAG, I realize that making our website accessible is not an easy thing. This means that we need to constantly learn about web accessibility and always remember that No ARIA is better than Bad ARIA.
