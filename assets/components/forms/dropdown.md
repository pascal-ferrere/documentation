
# Dropdown

Dropdown components are interactive navigation elements. Their main goal is to allow users to select one input from a descending list of options.

---

  
![dropdown-cover](https://studio-assets.supernova.io/design-systems/27883/945be055-a371-4777-bcc5-29e10c878502.png)  
dropdown-cover  


Dropdowns are great for speeding-up user flows — this is because the user has to select a single input from a pre-defined list (such as choosing a street name within address forms) — they differ from other input field elements because the user must confirm their choice.

In basic terms, the dropdown component is a menu module in which options (hidden by default) are displayed after interacting. The user chooses an option and the flow continues.

## Usage

The main usage function of a dropdown component is to provide users with lists of predefined, selectable inputs.

We use dropdowns to save the user time (instead of inputting information manually).

For Betclic products, we use two different dropdown variants, both offering slightly-different types of functionality.

However, in broader terms, their usage patterns and outcomes are still the same — allowing users to choose a single input.

Dropdowns are used for these purposes:

- For confirming primary actions

- Providing selectable pre-filled info

- To force the user to choose one option from a list

- To allow quicker navigation when advancing through screen flows

## Variants

Dropdowns are available in two variants:

- Autocomplete

- Selector

It’s important to choose the correct variant because they behave and function differently. When choosing which variant you should think about which component will bring the most benefit to the user.

These two variants are available in the two main Betclic visual styles:

- Default

- Alternative

## States

Similar to an input field, the user must tap inside the container to begin using a dropdown. After an interaction, a list will appear below the dropdown container — this is one of the state changes of the element. The next stage of state change is that the user will select one of the options on the list which confirms the action.

The states that dropdowns exist in are:

- Empty

- Placeholder

- Pressed

- Selected

## Anatomy

Dropdowns are created from a container which expands upon interaction. They are comprised of the following atomic-level elements:

1. Container + input field

1. Suggestive text label (Autocomplete only)

1. Placeholder text label (Selector + Autocomplete)

1. Caret / Chevron icon

1. Mini circular loader

1. Dividers for the expanded list

## Placement

Dropdowns can be found across various parts of the UI — especially within forms and/or placed on top of cards.

Their placement should be obvious and purposeful — dropdowns are not used in discreet ways or hidden under other elements.

One important aspect when positioning dropdowns is to consider whether they need to be quickly reachable on the UI — for some situations, having a dropdown within the reachable area of the user’s thumb can really speed up screen flows, such as inputting and confirming betting info.

## Behavior

The basic behavior of dropdowns is that they expand after interaction.

The specific interaction differs depending on the variant used.

*Autocomplete dropdown:*

The autocomplete variant expands and offers options as soon as the user begins typing into the input field. The options offered match with the letters or numbers that were inputted. If no matches exist then no options will be displayed.

*Selector dropdown:*

The selector variant functions more like a list of radio buttons, meaning that the list of options is predefined and that only one option can be selected.

## Dos & Don’ts

> Yay:  
> Do -> Use dropdowns for their intended purpose only — dropdowns should only offer pre-selected options which are relevant to the user’s initial input.

> Please note:  
> Don’t: Avoid deviating from intended usage patterns. For example, if selecting more than one option is required, consider using a different component, such as a list of toggle switches.

> Yay:  
> Do: Use dropdowns to force the user to choose a required selection, such as providing address info or similar user data.

> Please note:  
> Don’t: Avoid using dropdowns instead of input fields if you want the user to input custom or lengthy text, such as feedback comments or messages.

> Yay:  
> Do: Place dropdowns in reachable areas of the UI such as in forms or on top of cards — try to think about how the user will reach physically the dropdown element on their phone. Is it close to a confirmation button? Ergonomics need to be consided in the layout design.

> Please note:  
> Don’t: Never hide dropdowns under other elements — their placement should always be obvious to the user.

## Microcopy

### General

For both variants of dropdown, aim to create concise label text that accurately matches the required input.

### Casing

Dropdown text should be written in the same that regular body text is created — a mixed style of title and sentence casing.

### Punctuation

In general, punctuation should be avoided unless necessary, such as two hyphenated words, forward slashes or ampersand symbols. When using forward slashes, use a space each side to increase readability. Dropdown text labels rarely require terminal punctuation. Ellipsis is not recommended unless a high character count truncates the text.

### Localization

Translate your dropdown text to see if it adequately fits into the container layout. If designing in English, remember that it has one of the shortest character counts and often increases in length when translated into the main languages that Betclic products use — which are French, Polish, and Portuguese. Remember that currencies are always placed on the right side, never on the left. Use a space between the value and the symbol. Try to use the currency symbol where possible.