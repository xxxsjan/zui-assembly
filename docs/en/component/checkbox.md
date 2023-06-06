# Checkbox

Multiple choices from a set of alternative options ✅

## Basic Usage

Used alone, it can indicate a switch between two states, and the content written in the label is the introduction after the checkbox button.

<demo src="./checkbox/checkbox-base.vue" desc="Define the v-model binding variable in the el checkbox element. In a single checkbox, the default value of the binding variable will be Boolean. If true is selected, how to set the true label and false label attributes so that the variables bound to the v-model will become their values."></demo>

## Disabled State

The checkbox is not available.

<demo src="./checkbox/checkbox-disabled.vue" desc="Set the disabled property."></demo>

## Multiple Selection BoxGroup

Applicable to scenarios where multiple check boxes are bound to the same array, indicating the selected items in this set of options by checking or not.

<demo src="./checkbox/checkbox-group.vue" desc="The checkbox group element can manage multiple checkboxes into a group, simply using the v-model to bind variables of type Array in the Group. The label attribute of the el checkbox is the value corresponding to the checkbox. If there is no content in the label, this attribute also serves as an introduction after the checkbox button. The label corresponds to the element values in the array. If a specified value exists, it is selected, otherwise it is not selected."></demo>

## Indeterminate State

The `indeterminate` attribute is used to represent the uncertain state of the checkbox, and is generally used to achieve the effect of selecting all

<demo src="./checkbox/checkbox-indeterminate.vue"></demo>

## Limitation on the number of optional items

Using the `min` and `max` attributes can limit the number of items that can be checked

<demo src="./checkbox/checkbox-min-max.vue"></demo>

## Button Style

Multiple selection combinations of button styles.

Simply replace the `z-checkbox` element with the `z-checkbox-button` element. Zui Assembly also provides the `size` attribute.

<demo src="./checkbox/checkbox-button.vue"></demo>

## With Border

Set the `border` attribute to render as a multi-selection box with a border

<demo src="./checkbox/checkbox-border.vue"></demo>
