
# Chip

The purpose of a chip component is to present contextual and supplemental options that are relevant to the content on screen. 

---

As an interactive element, chips provide visual cues to users allowing them to take action or make selections. And because they are selectable, chips can either filter content or perform some other action once they have been clicked.

  
![chip-cover](https://studio-assets.supernova.io/design-systems/27883/9721f00c-9a3f-4d31-b1ca-553904577884.png)  
chip-cover  


In terms of hierarchy on the UI, the presence of a chip is similar to a button. It will supersede other elements in terms of visual importance. However, unlike buttons, chips do not perform actions that take the user to a new location. Instead, chips provide instant, on-screen interactions where the user is presented with either some new options, some filtered content, or in the case of sub-filters, some expanded information.

At a higher lever, chips represent forking paths in the user-flow experience, whereas buttons represent linear steps along a flow of consecutive screens.

## Usage

  
![chip-example-1](https://studio-assets.supernova.io/design-systems/27883/09ef78aa-6159-41c7-9ced-1fd4020a67e8.png)  
chip-example-1  


Chips are used as an interactive UI element. They provide a visual hint to the user that they are selectable and that they can confirm selections, filter content into different parts, or provide an expanded display of information.

Visually, a chip’s presence is similar to a button. However, unlike a button, chips do not confirm actions, nor do they navigate the user to a new screen — instead, chips offer decision-based interactions where the user remains on the same page or screen.

When selected, chips display content related to it, or they highlight some other useful contextual information.

*Chips are mainly used for:*

- Sorting or filtering on-screen content

- Selecting specific content on the same page

- Viewing expanded information (using the sub-filter chip)

## States

  
| Column 1 | Column 2 | Column 3 | Column 4 |  
| --- | --- | --- | --- |  
| ![Img](https://studio-assets.supernova.io/design-systems/27883/1902664f-d4a7-4c4e-8911-999c36386029.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/adc3847e-4856-40e0-9602-55564857ea61.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/7e651701-2a8f-4105-b8c4-dfbec2c4bfe2.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/273cdd40-86e1-425c-9eee-4c83e6173aa9.png) |  
| ![Img](https://studio-assets.supernova.io/design-systems/27883/11fc7be1-a1ea-47f5-8396-0d70504a8bda.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/544638e1-3c39-44a4-8292-e03516281a23.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/00ca1ae8-c4e2-41dc-bd9c-7f1ab42d62d3.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/54037c38-77a8-4d38-8a41-8727eafbeffa.png) |  
| *Unselected* | *Unselected pressed* | *Selected* | *Selected pressed* |  


Chips exist in these various states:

- On

- Off

- Pressed

- Disabled

## Variants

Chips are offered in the following variants:

- Text + icon

  
![chip-text-icon](https://studio-assets.supernova.io/design-systems/27883/fca6509c-5fd7-40a1-84f9-88f6e23480d8.png)  
chip-text-icon  


- Text only

  
![chip-text-only](https://studio-assets.supernova.io/design-systems/27883/88e56718-da54-40f2-a5ce-fa719db98ff5.png)  
chip-text-only  


- Sub-filter

  
![chip-subfilter](https://studio-assets.supernova.io/design-systems/27883/92784cff-1f37-4bd7-85bf-bdc7d64c4c89.png)  
chip-subfilter  


## Anatomy

Chips are formed from a container, a text label, and an icon (which always appears on the left of the text). Some variants are formed from just a solo icon.

  
![Legend](https://studio-assets.supernova.io/design-systems/27883/106671d9-fb56-4f0c-9068-e64f56101795.png)  
Legend, 1. Container
2. Text label
3. Optional or solo icon  
  


*Spec:* Containers always have a corner radius of 8 px. Icons are positioned 8 px away from the text label.

## Placement

Chips can be placed by themselves or in groups. They are normally placed into horizontal arrangements which can further be stacked if necessary.

When using sub-filter chips, you must remember to include an icon-only chip so that the user can close the selected sub-filters.

## Behavior

When interacted with, chips are expected to display instant changes to the user — whether that’s a selected chip filtering content or an expanded dialog box from a sub-filter — the state change behavior of chips is intended to be instant while keeping the user in the same position on the same screen.

When adding groups of chips horizontally that extend off-screen, it is expected to offer functionality that allows the user ability to scroll through the entire group.

## Dos & Don’ts

*Do: *Use chips for sorting or filtering content — outcomes should always be obvious to the user.

*Don’t:* Avoid using chips for other purposes such as confirming actions or inputting information.

*Do:* In general, chips should be grouped to give alternative options, unless there is an obvious reason not to do so.

*Don’t: *Never ungroup or reorder elements within the chip. Scale them appropriately.

*Do: *For readability, keep chip text labels as short as possible (see Microcopy rules for more info).

*Don’t:* Chip text labels should never wrap — they may truncate in some circumstances, such as for long words or translations.

## Microcopy

### General

Aim to keep chip label text as concise as possible using task-specific language that describes the outcome of the chip’s function clearly and simply to the user. Avoid passive and vague tonality at all costs — short and direct language is far easier to understand. The speed of the betting experience should not be impacted by users having to read long or vague text.

### Wordcount

In the text label, one to four words is the ideal amount, anything longer is probably too long. Keeping the text label as short as possible will help the user navigate the content more quickly. We advise that you shorten players’ first names to their first initial, e.g. “Lionel Messi” becomes “L. Messi”.

### Casing

Chip text labels should be written in title case. Small verbs and prepositions can be written in sentence case to improve readability, e.g. to, the, from, you, it, was, etc.

### Punctuation

In general, punctuation should be avoided unless necessary, such as two hyphenated words or ampersand symbols. Button text labels do not require terminal punctuation at all, however, occasionally, a question mark or exclamation mark may be appropriate in some rare situations. If you are shortening player names, it is acceptable to use their first name initial followed by a full stop to save on pixel space.

### Localization

Translate your chip text label to see if it adequately fits into the container layout. If designing in English, remember that it has one of the shortest character counts and often increases in length when translated into the main languages that Betclic products use — which are French, Polish, and Portuguese.