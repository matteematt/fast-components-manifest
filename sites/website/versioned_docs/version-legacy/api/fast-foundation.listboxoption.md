---
id: fast-foundation.listboxoption
title: ListboxOption class
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[@microsoft/fast-foundation](./fast-foundation.md) &gt; [ListboxOption](./fast-foundation.listboxoption.md)

## ListboxOption class

An Option Custom HTML Element. Implements [ARIA option](https://www.w3.org/TR/wai-aria-1.1/#option)<!-- -->.


start - Content which can be provided before the listbox option content


end - Content which can be provided after the listbox option content


- The default slot for listbox option content


content - Wraps the listbox option content

<b>Signature:</b>

```typescript
export declare class ListboxOption extends FoundationElement 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(text, value, defaultSelected, selected)](./fast-foundation.listboxoption._constructor_.md) |  | Constructs a new instance of the <code>ListboxOption</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [checked](./fast-foundation.listboxoption.checked.md) |  | boolean | The checked state is used when the parent listbox is in multiple selection mode. To avoid accessibility conflicts, the checked state should not be present in single selection mode. |
|  [content](./fast-foundation.listboxoption.content.md) |  | Node\[\] | The default slotted content. |
|  [defaultSelected](./fast-foundation.listboxoption.defaultselected.md) |  | boolean | The defaultSelected state of the option. |
|  [dirtyValue](./fast-foundation.listboxoption.dirtyvalue.md) |  | boolean | Track whether the value has been changed from the initial value |
|  [disabled](./fast-foundation.listboxoption.disabled.md) |  | boolean | The disabled state of the option. |
|  [form](./fast-foundation.listboxoption.form.md) |  | HTMLFormElement \| null |  |
|  [initialValue](./fast-foundation.listboxoption.initialvalue.md) |  | string | The initial value of the option. This value sets the <code>value</code> property only when the <code>value</code> property has not been explicitly set. |
|  [label](./fast-foundation.listboxoption.label.md) |  | string |  |
|  [selected](./fast-foundation.listboxoption.selected.md) |  | boolean | The checked state of the control. |
|  [selectedAttribute](./fast-foundation.listboxoption.selectedattribute.md) |  | boolean | The selected attribute value. This sets the initial selected value. |
|  [text](./fast-foundation.listboxoption.text.md) |  | string |  |
|  [value](./fast-foundation.listboxoption.value.md) |  | string |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [checkedChanged(prev, next)](./fast-foundation.listboxoption.checkedchanged.md) |  | Updates the ariaChecked property when the checked property changes. |
|  [defaultSelectedChanged()](./fast-foundation.listboxoption.defaultselectedchanged.md) |  |  |
|  [disabledChanged(prev, next)](./fast-foundation.listboxoption.disabledchanged.md) |  |  |
|  [initialValueChanged(previous, next)](./fast-foundation.listboxoption.initialvaluechanged.md) |  |  |
|  [selectedAttributeChanged()](./fast-foundation.listboxoption.selectedattributechanged.md) |  |  |
|  [selectedChanged()](./fast-foundation.listboxoption.selectedchanged.md) |  |  |