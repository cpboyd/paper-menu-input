_[Demo and API Docs](https://elements.polymer-project.org/elements/iron-menu-behavior)_


##&lt;paper-menu-input&gt;

Material design: [Menus](https://www.google.com/design/spec/components/menus.html)

`<paper-menu-input>` implements an accessible menu control with Material Design styling. The focused item
is highlighted, and the selected item has bolded text.

```html
<paper-menu-input name="input" label="Label">
  <paper-item>Item 1</paper-item>
  <paper-item>Item 2</paper-item>
</paper-menu-input>
```

An initial selection can be specified with the `selected` attribute.

```html
<paper-menu-input name="input" label="Label" selected="0">
  <paper-item>Item 1</paper-item>
  <paper-item>Item 2</paper-item>
</paper-menu-input>
```

Make a multi-select menu with the `multi` attribute. Items in a multi-select menu can be deselected,
and multiple items can be selected.

```html
<paper-menu-input name="input" label="Label" multi>
  <paper-item>Item 1</paper-item>
  <paper-item>Item 2</paper-item>
</paper-menu-input>
```

`<paper-menubar-input>` implements an accessible menubar control with Material Design styling. The focused item
is highlighted, and the selected item has bolded text.

```html
<paper-menubar-input name="input" label="Label">
  <paper-item>Item 1</paper-item>
  <paper-item>Item 2</paper-item>
</paper-menubar-input>
```

An initial selection can be specified with the `selected` attribute.

```html
<paper-menubar-input name="input" label="Label" selected="0">
  <paper-item>Item 1</paper-item>
  <paper-item>Item 2</paper-item>
</paper-menubar-input>
```

Make a multi-select menu with the `multi` attribute. Items in a multi-select menu can be deselected,
and multiple items can be selected.

```html
<paper-menubar-input name="input" label="Label" multi>
  <paper-item>Item 1</paper-item>
  <paper-item>Item 2</paper-item>
</paper-menubar-input>
```

### Styling

The following custom properties and mixins are available for styling:

| Custom property | Description | Default |
| --- | --- | --- |
| `--paper-menu-background-color` | Menu background color | `--primary-background-color` |
| `--paper-menu-color` | Menu foreground color | `--primary-text-color` |
| `--paper-menu-disabled-color` | Foreground color for a disabled item | `--disabled-text-color` |
| `--paper-menu` | Mixin applied to the menu | `{}` |
| `--paper-menu-selected-item` | Mixin applied to the selected item | `{}` |
| `--paper-menu-focused-item` | Mixin applied to the focused item | `{}` |
| `--paper-menu-focused-item-after` | Mixin applied to the ::after pseudo-element for the focused item | `{}` |

### Accessibility

`<paper-menu-input>` has `role="menu"` by default. `<paper-menubar-input>` has `role="menubar"` by default. A multi-select menu will also have
`aria-multiselectable` set. It implements key bindings to navigate through the menu with the up and
down arrow keys, esc to exit the menu, and enter to activate a menu item. Typing the first letter
of a menu item will also focus it.


