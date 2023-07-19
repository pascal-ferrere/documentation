
# Input field

Input fields allow users to enter editable text or numeric values into the UI. 

---

  
![input-field-cover](https://studio-assets.supernova.io/design-systems/27883/36644bc9-0d35-4dbe-82f1-32f1bddef2d3.png)  
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
| ![Img](https://studio-assets.supernova.io/design-systems/27883/a281f7b8-cdf7-4812-9bea-ae648af6082f.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/da471fd6-a34d-4ee5-8256-481304b6b88c.png) |  
|  |  |  
| ![Img](https://studio-assets.supernova.io/design-systems/27883/21f501c2-4804-409d-8e3f-9c24fe0fdad2.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/f1e58504-1b15-4fe8-8820-afe3123a2d4a.png) |  
|  |  |  


### Variants usage

All types of input fields use a container to provide a visual cue for interaction and provide the same functionality, which means that the user can click on the element and expect to input textual or numeric information.

*One line input fields* — provide suggestive text that disappears upon inputting new text. Used when there is only one field.

*Two line input fields* — provide suggestive text that stays above the inputted text. Used when there are multiple fields.

*Special input fields* — only allow the user to input numeric values. They offer zero as the placeholder text and do not offer suggestive text because it is obvious that a numeric value needs to be inputted.

## States

  
| Column 1 | Column 2 |  
| --- | --- |  
| ![Img](https://studio-assets.supernova.io/design-systems/27883/ca8135c5-170a-44c3-b63a-489f74a737a1.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/e61d407f-372f-4a07-b606-40254f9d120a.png) |  
| *Placeholder* | *Selected* |  
| ![Img](https://studio-assets.supernova.io/design-systems/27883/476e1be8-9831-4e9d-b053-e0ac911639ab.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/bbc13273-8b6b-40d9-9bd3-b5b1a1c42c9a.png) |  
| *Validation steps* | *Neutral message* |  
| ![Img](https://studio-assets.supernova.io/design-systems/27883/3a0cc79f-9cb2-4b51-9406-cd191d49268c.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/396a0da7-71b4-4ebf-9a95-7fdb54ba03fb.png) |  
| *Positive message* | *Error* |  
| ![Img](https://studio-assets.supernova.io/design-systems/27883/dc6c07bc-a903-4be1-99ed-b6257e633bd1.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/d1065344-98d7-4898-a519-96bb5f8d012b.png) |  
| *Error + alert* | *Error + alert + message* |  
| ![Img](https://studio-assets.supernova.io/design-systems/27883/fc264e3c-fc79-4f38-994d-c3df56770535.png) |  |  
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