
# Chip

The purpose of a chip component is to present contextual and supplemental options that are relevant to the content on screen. 

---

As an interactive element, chips provide visual cues to users allowing them to take action or make selections. And because they are selectable, chips can either filter content or perform some other action once they have been clicked.

  
![chip-cover](https://studio-assets.supernova.io/design-systems/27883/ca3ca9bc-5028-4b71-b9f6-33ee0e657143.png)  
chip-cover  


In terms of hierarchy on the UI, the presence of a chip is similar to a button. It will supersede other elements in terms of visual importance. However, unlike buttons, chips do not perform actions that take the user to a new location. Instead, chips provide instant, on-screen interactions where the user is presented with either some new options, some filtered content, or in the case of sub-filters, some expanded information.

At a higher lever, chips represent forking paths in the user-flow experience, whereas buttons represent linear steps along a flow of consecutive screens.

## Usage

  
![chip-example-1](https://studio-assets.supernova.io/design-systems/27883/953c3bad-ddeb-498b-aa18-fb876d438519.png)  
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
| ![Img](https://studio-assets.supernova.io/design-systems/27883/30dc5f86-e151-48d2-ae49-813dfbc512ca.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/2981275a-d6c3-4ba6-97ba-ac7a236128cc.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/090682e9-7739-47f9-8d65-8c5427dc6d14.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/9778c880-640c-45c6-98be-baa87ffa2ce0.png) |  
| ![Img](https://studio-assets.supernova.io/design-systems/27883/40309211-9cff-40a6-bb14-ca19b9e5239a.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/a914630e-15e1-4ed0-8a6d-9869e31016b4.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/bb94583b-d7ba-4610-9201-a32db689e4be.png) | ![Img](https://studio-assets.supernova.io/design-systems/27883/2d8dd0eb-4f66-478d-9d9d-9c8332a898ed.png) |  
| *Unselected* | *Unselected pressed* | *Selected* | *Selected pressed* |  


Chips exist in these various states:

- On

- Off

- Pressed

- Disabled

## Variants

Chips are offered in the following variants:

- Text + icon

  
![chip-text-icon](https://studio-assets.supernova.io/design-systems/27883/4c971e85-8bf6-4de0-a8ee-e8c9a546a07a.png)  
chip-text-icon  


- Text only

  
![chip-text-only](https://studio-assets.supernova.io/design-systems/27883/e192b463-1949-4ddd-aed7-bb3a0a3ffb27.png)  
chip-text-only  


- Sub-filter

  
![chip-subfilter](https://studio-assets.supernova.io/design-systems/27883/c81359ef-9bb3-4390-9892-29b7e7720fd0.png)  
chip-subfilter  


## Anatomy

Chips are formed from a container, a text label, and an icon (which always appears on the left of the text). Some variants are formed from just a solo icon.

  
![Legend](https://studio-assets.supernova.io/design-systems/27883/c47dad58-15ad-428b-9cb6-3bac4a8dce20.png)  
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