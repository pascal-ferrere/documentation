
# Button

Buttons are simple, atom-level components — we consider them to be one of the most important interactive elements on the mobile UI. This is because they are one of the first interactive elements that a user will be visually drawn to when faced with a new screen. 

---

For this reason, they form an integral part of the Betclic digital experience because they allow users to make quick decisions regarding initiating actions and achieving their intended goals — therefore we must be considerate and purposeful with their usage, placement, and function. When creating text labels we must be concise because the speed of the betting experience should not be impacted by users having to read lengthy button text.

  
![button-cover](https://studio-assets.supernova.io/design-systems/27883/da857c2d-549d-477b-8cce-a5c5b9a0a2ac.png)  
button-cover  


## Usage

When users interact with Betclic products, they do so in the understanding that a button’s function is going to be important — that these elements are used in a deeper and more complex way than in a regular app. This is because buttons allow users to initiate actions and thus, engage deeper in the gaming and betting experience. Betclic buttons are used to confirm inputs, cancel processes, place bets, and above all — make quick decisions in the gaming environment often where live events are taking place.

Therefore, when choosing and placing buttons in the UI, we need to carefully consider their usage and function with regard to their purpose and outcome — everything should be intuitive and obvious to the user. Nothing should be left to chance when it comes to buttons.

Users should never have to guess a button’s function or outcome. We never promote dark UX patterns, especially when it comes to interactive elements. The Betclic digital experience should empower users to recognize the reliable usage patterns of the buttons we use. And in turn, these interaction patterns help users achieve their desired goals quickly and efficiently.

It is best practice for placing primary buttons that they are accompanied by a secondary button and/or a ghost if needed. The user must be given a choice of options, even if the second option is only to cancel.

In terms of usage, the main thing to be aware of is that Betclic buttons fall into two distinct functionality patterns:

- *System buttons *— interactions related to system functions and processes

- *Betting buttons *— interactions related to gaming and betting functionality

### *System button functions*

- All primary actions or inputs

- Secondary actions or inputs

- Canceling inputs or closing information

- Advancing through screen flows

- Confirming inputted information

- Discreet actions or confirmations

### *Betting button functions*

- Committing to a betting or gaming action

- Cashing out (buying back bets)

## Variants

Betclic buttons are offered in many variants and sub-variants, as well as different visual options and sizes. These are all used in different ways depending on the product. Icons are always added to the left of text labels.

### System button variants

  
![button-variant](https://studio-assets.supernova.io/design-systems/27883/7850ab74-fbd2-40b9-b602-1185adef117b.png)  
button-variant  


These buttons are specifically used to help users navigate through the UI.

- *Primary* — large / medium / both sizes available with or without supporting icons

- *Secondary* — large / medium / both sizes available with or without supporting icons

- *Ghost* — large / medium / both sizes available with or without supporting icons

System buttons are all offered in the following visual options (differentiated by color):

- *Default* — large / medium / both sizes available with or without supporting icons

- *Alternative* — large / medium / both sizes available with or without supporting icons

- *Live* — large / medium / both sizes available with or without supporting icons

In addition to this, all system buttons listed above are offered in the following icon-only sub-variants (each in 3 different sizes):

- *Icon-only Default* — large / medium / small

- *Icon-only Alternative* — large / medium / small

- *Icon-only Live* — large / medium / small

### Betting button variants

These buttons are functionally and visually different from System buttons because they allow users to take actions specifically related to betting and gaming. They are normally used in yellow so that they visually stand out on the UI.

- *Default (Trend up/Trend down)* — large (text + value) / medium (text only) / icon-only

- *Cashout* — large + icon / medium + icon

Default Betting buttons are also available in two different visual options:

- *Standard* — large / medium / icon-only

- *Live* — large / medium / icon-only

Cashout buttons always contain an icon and are available in these three visual options:

- *Default* — large + icon / medium + icon

- *Alternative* — large + icon / medium + icon

- *Live* — large + icon / medium + icon

### Variants usage

*Primary* — used for positive actions such as confirmations or advancing through flows. In Betclic products, the primary button is by far the most important, which is why its default state is offered in the brand color.

*Secondary* — used for secondary actions such as choosing an alternative option or canceling inputs or closing dialogs.

*Ghost *— to be used when a third option or a discreet selection is needed. It can be placed on a background without a container, which will become visible once it is interacted with.

*Betting* — allows users to place bets. During usage, this button temporarily turns green (Trend up) or red (Trend down) for one second in order to indicate to the user that the bet value went up or down. After one second has elapsed, the button turns back to yellow (its default color).

*Cashout* — only used in very specific cases, such as when the user has placed a bet and wants to buy the bet back in order to recover some of the used funds.

## States

All Betclic buttons exist in various states. Each state is represented by a slightly different variation of its default state color.

  
![button-system-state](https://studio-assets.supernova.io/design-systems/27883/6543e973-b85c-4f31-9f5c-9022d2fd57da.png)  
button-system-state  


*System button states:*

- Default

- Pressed

- Selected

- Loading (represented by circular spinner)

- Disabled

- Countdown (represented by horizontal loading bar)

  
![button-betting-state](https://studio-assets.supernova.io/design-systems/27883/1bf06548-6ed3-42dd-b04d-76243393f429.png)  
button-betting-state  


*Betting button states:*

- Default

- Pressed

- Selected

- Default - disabled

- Selected - disabled

- Suspended

  
![button-cashout-state](https://studio-assets.supernova.io/design-systems/27883/c311967e-ef45-47c3-996d-13c626a5ee2d.png)  
button-cashout-state  


*Cashout button states:*

- Default

- Pressed

- Selected

- Loading (represented by circular spinner)

- Disabled

- Countdown (represented by horizontal loading bar)

## Anatomy

Most Betclic buttons are formed from a container, label text (and optional numeric values), and an optional icon (which always appears on the left or on top). Some buttons are formed from an icon alone. In general, the anatomy of our buttons is as follows:

  
![Legend](https://studio-assets.supernova.io/design-systems/27883/58f077a5-afd5-4d9a-9291-795e8e4ed89b.png)  
Legend, 1. Container
2. Text and/or Numeric value label
3. Optional icon  
  


*Spec: *Containers always have a corner radius of 8 px. Icons are positioned 8 px away from the text label. System buttons never wrap, however, Betting buttons’ text labels can wrap if there is a numeric value included.

For both System and Betting buttons, icons are always placed on the left side or on top of the text label, never to the right of it.

Regardless of button style, never ungroup the elements within a button.

## Placement

System buttons should be grouped in specific ways on the UI — they are normally placed in containers such as cards or dialogs, placed in a manner that makes them stand out as an interactive element.

Try to avoid placing buttons in solo arrangements unless it’s obvious that there is only one outcome. Ideally, their visual arrangement should focus attention on a primary action, while also offering alternatives.

Groups of horizontally-stacked buttons are placed 8 px distance from each other. Buttons are only placed horizontally in groups of 2 or 3 depending on the use case. Never more than 3 are used. We also vertically stack buttons in some situations, such as in modals or in bottom sheet components.

Betting buttons are grouped into 2 or 3 buttons per set — this arrangement is outlined in the UI library.

The ideal alignment for buttons is always centered.

## Behavior

In any mobile UI, the entire button should be interactive and tappable, not just the text label or icon.

Button actions must be instant and be visually represented by a pressed state button or similar.

In terms of responsive layout, for scaling layouts, buttons should adapt their visual presentation, alignment, and arrangement to fit different formats and user needs. Buttons should always scale with their parent container.

## Dos & Don’ts

*Do: *Use a primary button to confirm positive actions — outcomes should always be obvious to the user.

*Don’t:* Never place two primary or secondary buttons together — this could be confusing for the user.

*Do:* In general, a primary button should be accompanied by a secondary button unless there is an obvious reason not to do so.

*Don’t:* Never ungroup or reorder elements within the button. Scale them appropriately.

*Do:* For readability, keep button text labels as short as possible (see Microcopy rules for more info).

*Don’t:* Button text labels should never truncate or wrap.

# Microcopy

### General

Always aim to keep the button label text as concise as possible using task-specific language that describes the outcome of the button’s function clearly and simply to the user. Avoid passive and vague tonality at all costs — short and direct language is far easier to understand. The speed of the betting experience should not be impacted by users having to read long button text.

In addition, always try to use consistent patterns in your text labels. For example, if you have always used the phrase: “OK” on your buttons, don’t suddenly use the similar phrase “Okay” or “Got it” as this will break the user’s recognition pattern and slow down the user’s flow.

### Wordcount

In the text label, one to four words is the ideal amount, anything longer is probably too long. Remember that a button is often one of the first elements on a new screen that a user will see. Therefore keeping the text label as short as possible will help the user navigate the screen flows more quickly.

Even if a button has two lines of text (one for numeric values) you should never allow your button text label to wrap. If your text label wraps, then your message is too long and will need revising.

### Casing

Buttons should be written in title case. Small verbs and prepositions can be written in sentence case to improve readability, e.g. to, the, from, you, it, was, etc.

### Punctuation

In general, punctuation should be avoided unless necessary, such as two hyphenated words or ampersand symbols. Button text labels do not require terminal punctuation at all, however, occasionally, a question mark or exclamation mark may be appropriate in some situations.

### Localization

Translate your button text label to see if it adequately fits into the container layout. If designing in English, remember that it has one of the shortest character counts and often increases in length when translated into the main languages that Betclic products use — which is French, Polish, and Portuguese. Remember that currencies are always placed on the right side, never on the left. Use a space between the value and the symbol. Try to use the currency symbol where possible.