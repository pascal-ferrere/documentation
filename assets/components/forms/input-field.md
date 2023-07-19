
# Input field

Input fields allow users to enter editable text or numeric values into the UI. 

---

  
![input-field-cover](https://studio-assets.supernova.io/design-systems/27883/902896ca-1c89-47a3-b729-a93160fbbb56.png)  
input-field-cover  


This component typically appears in forms and dialogs. Their function forms an integral part of the Betclic digital experience because they allow users to add customized information. Having been used for decades, input fields are considered a very traditional component, both in terms of design and user interactions. Their visual design and placement inside forms should indicate to the user that they need to input some information into the UI. The visual state of the input field signals to the user what is happening and whether their input was a success or not.

## Usage

Input fields allow users to enter editable text or numeric values into the UI. This could be situations such as filling in personal details, addresses, or payment information. Typically, the design of an input field signifies to the user that information needs to be inputted from them in order to continue with the screen flow.

Depending on the variant, Input fields should be accompanied by “suggestive” input or label text, e.g. “First name” or “Street name” to help guide the user with the inputs. Supportive text underneath the input field can also help the user correct any potential mistakes, e.g. “Invalid email” or “Username taken”.

In addition, the visual state of an input field is crucial for signaling to the user what is happening, e.g. upload success or error.

## Variants

We use three types of input fields:

- *One line *— large / small

- *Two line* — large / small

- *Special *— large only

  
| Column 1 | Column 2 |  
| --- | --- |  
| ![Img](https://studio-assets.supernova.io/design-systems/27883/3889a31e-98ad-41b8-b8d0-3d81d0c1b7d3.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/e6192adb-d11c-4378-b7d6-bc906aa2e8c8.png) |  
|  |  |  
| ![Img](https://studio-assets.supernova.io/design-systems/27883/b948243b-3224-4390-8bf1-f8c10c7bae93.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/5a468f50-e3c1-4d16-9f62-980fed45df6d.png) |  
|  |  |  


### Variants usage

All types of input fields use a container to provide a visual cue for interaction and provide the same functionality, which means that the user can click on the element and expect to input textual or numeric information.

*One line input fields* — provide suggestive text that disappears upon inputting new text. Used when there is only one field.

*Two line input fields* — provide suggestive text that stays above the inputted text. Used when there are multiple fields.

*Special input fields* — only allow the user to input numeric values. They offer zero as the placeholder text and do not offer suggestive text because it is obvious that a numeric value needs to be inputted.

## States

  
| Column 1 | Column 2 |  
| --- | --- |  
| ![Img](https://studio-assets.supernova.io/design-systems/27883/c2d51258-2a85-4fc7-8fcf-80324c568682.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/dfc2fbb7-5495-4a8d-81c0-4e9195eb74df.png) |  
| *Placeholder* | *Selected* |  
| ![Img](https://studio-assets.supernova.io/design-systems/27883/35a5ff82-4c31-4d75-bc45-c71b3675326d.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/d3194f95-4002-4ce6-9a68-0aa98537512c.png) |  
| *Validation steps* | *Neutral message* |  
| ![Img](https://studio-assets.supernova.io/design-systems/27883/5949a0b7-c6b0-49cb-b059-9ca7faa1cde5.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/a5ffd660-8ca2-4fdc-b44b-9346257045df.png) |  
| *Positive message* | *Error* |  
| ![Img](https://studio-assets.supernova.io/design-systems/27883/533ab18e-14a6-4392-ab78-bff47886783e.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/0e3f23b7-3a44-4133-88d9-5e63a789d389.png) |  
| *Error + alert* | *Error + alert + message* |  
| ![Img](https://studio-assets.supernova.io/design-systems/27883/8b9f0713-5aed-49e2-bfc7-5b0d64323902.png) |  |  
| *Disabled* |  |  


Supporting and suggestive text for input fields are offered in these states:

- *Positive (Green)* — for confirming input actions.

- *Neutral (Grey)* — for normal, non-confirming, and neutral actions.

- *Negative (Red) *— for incorrect inputs which may not allow the user to advance.

## Anatomy

Depending on the input field variant, the anatomy will be comprised of some or all of the following elements:

1. Container (enabled) 

1. Leading icon (optional) 

1. Label text (unpopulated)

1. Label text (populated)

1. Trailing icon (optional)

1. Active Indicator (focused)

1. Text cursor symbol

1. Input text

1. Supporting text (optional)

1. Active indicator (enabled)

### Additional anatomy

- Active icons can exist on the left or right side of the input, or both.

- The color of the icon must follow the color of the label inside the input field.

### Special input fields currency info:

Betclic products are offered in these currencies:

- Euro - €

- Polish złoty - zł

- French CFA - FCFA

Currencies are always placed on the right side, never on the left. Use a space between the value and the symbol. Try to use the currency symbol where possible.

## Placement

Input fields are typically used inside forms or other types of containers where the user needs to input some information.

The placement of input fields should be logical and according to best practices, especially when it comes to inputting user info, such as address forms. Research the best practices for the region you are creating for.

For mobile UI, most input fields are typically stacked in single rows. However, this is not a strict rule, for example, a short input field could be placed next to a single answer dropdown menu or vice versa with a padding of 8 px — it depends on the use-case.

Remember to always place the confirmation button in a clear and logical fashion at the bottom of the container.

*Regarding padding and spacing between elements, please refer to the diagram below:*

## Behavior

In any mobile UI, the entire input field should be interactive and tappable, not just the text label or icon, but everything inside the field’s container.

In general, for most forms, the user will need to “submit” the information via a confirmation button. If there is an error with the information, this must be displayed via a negative (red) supporting text label with a clear explanation of what is needed.

In terms of responsive layout, for scaling layouts, text input fields should adapt their visual presentation, alignment, and arrangement to fit different contexts and user needs. Input fields should always scale with their parent container.

## Dos & Don’ts

> Yay:  
> *Do: *Use input fields to allow the user to enter single or multiple rows of information required for the user to advance through the screen flows. If you have multiple rows, such as on an address form, please use logical best practices to structure your hierarchy of information.

> Please note:  
> *Don’t: *Avoid placing rows of input fields in random or illogical patterns.

> Yay:  
> *Do:* Use supporting and/or suggestive text label text to help the user understand what information is needed. If a negative response is entered, use clear language to describe what is needed to proceed, e.g. “Please enter numbers only — no symbols.”

> Please note:  
> *Don’t:* Avoid using a passive voice or vague language for your input field text labels. Use task-specific, concise language only. You should also avoid using using ellipsis in text labels because it is used for displaying truncated text which we do not do for input fields.

## Microcopy

### General

Always aim to keep supporting or suggestive label text as concise as possible using task-specific language that describes the needs of the input field. Avoid passive and vague tonality. In addition, always try to use consistent patterns in your text labels.

### Wordcount

For the input field text label, one to four words is the ideal amount, anything longer is probably too long. You should never allow your input field text label to wrap or truncate. If your text label wraps or truncates, then your text is probably too long.

### Casing

Input field label text (supporting and suggestive) should be written in sentence case. Exceptions include: proper nouns, Betclic products or features, and popular abbreviations or acronyms.

### Punctuation

In general, punctuation and terminal punctuation is not needed for short pieces of text, however, if the supportive text contains punctuation such as commas, or full stops (such as “e.g.”) then it is better to use terminal punctuation to show the user that the sentence is finished. Question marks or exclamation marks may be appropriate in some situations. Avoid using ellipsis because it is used for displaying truncated text.

### Localization

Translate your input field text label to see if it adequately fits into the container layout. English has one of the shortest character counts and often increases in length when translated into the main languages that Betclic products use — which is French, Polish, and Portuguese. Remember that currencies are always placed on the right side, never on the left. Use a space between the value and the symbol. Try to use the currency symbol where possible.