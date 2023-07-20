
# Counter

The counter component allows users to increase or decrease values quickly and easily.

---

This interactive component is similar to an input field in appearance, however, rather than its value being directly editable, it is controlled via two selectable plus and minus elements. Its visual design is intuitive to use by the user during the betting experience and as a consequence, its placement must be carefully considered on the UI.

  
![counter-cover](https://studio-assets.supernova.io/design-systems/27883/7b6ad438-3145-41bd-ad86-9127588d0b42.png)  
counter-cover  


## Usage

The counter component allows users to increase or decrease values quickly and easily. This component is used within a wide variety of various forms, tables, widgets, and other locations where numeric values need to be quickly adjusted by the user.

Another aspect of the counter component, compared to an input field, is that it represents a way for us to control the numeric values entered by the user, simply because they can't manually enter a random value themselves.

## States

A counter’s state is generally determined by the numeric values that it is currently using. Its minimum and default values could be zero, but not always, as this is dependent on the context of the UI and betting experience.

Counters exist in these states:

- Default

- Minimum

- Maximum

- Disabled

## Variants

Counters are available in these variants:

- *Default* — Large Left / Large Right

- *Default* — Small Left / Small Right

- *Alternative* — Large Left / Large Right

- *Alternative* — Small Left / Small Right

*Please note: *the variation of “left or right” determines which side the numeric value appears on.

## Anatomy

The counter’s anatomy is fairly similar to an input field’s anatomy — it is a simple container with a non-editable field for displaying a value. The value is displayed on the left or right according to the variant used. Large variants can display supporting text and an optional icon, whereas small variants only display the main numeric value.

The main difference between input fields and counters is the selectable input controls that are used to increase or decrease the values. These are always paired in plus and minus configurations with the minus on the left and the plus on the right side of the input.

## Placement

  
![counter-placement](https://studio-assets.supernova.io/design-systems/27883/778e12ff-e42d-489f-a1dc-724c7191ea76.png)  
counter-placement  


Typically placed in visually obvious locations, counters are always placed singularly, within larger containers or modules.

If needed, counters can be accompanied by additional buttons situated close by (normally below the counter). For this use case, it is to help the user quickly input pre-set numerical figures into the counter’s display field, e.g. €1, €5, €10, Max, etc.

## Behavior

In general, the behavior of a counter is quite simple. Its interactions occur by using the +/– controls to adjust the numeric value.

This input adjustment operates in two ways, by inputting single taps or via a “long press” (holding down the button). The easiest way to think of how both of these interactions work is to think of how the analogue UI of a radio or stereo operates when you are skipping through tracks or stations.

Tapping the selection control allows for slower incremental adjustments, normally in increments of single digits. Whereas with a long press, the longer the selection control is held down, the quicker the value adjustment increases or decreases.

Both these behavior styles will become immediately known to the user after they have interacted with the component.

Starting values:

- *Sports Betting* — the default starting value is 0.

- *Turf Betting* — the default starting value is 1.

(these values are always the same regardless of currency)

## Dos & Don’ts

*Do:* Use counters in the UI to allow users to make quick adjustments to numeric values — especially if they improve the speed or quality of the betting experience.

*Don’t:* Avoid using multiple counters together — they are normally used singularly.

*Do:* Use sensible maximum numeric values that will be realistically used in the betting experience.

*Don’t:* Avoid using decimal points or fractions of whole numbers unless it is absolutely vital to the betting experience.

## Microcopy

### *General*

Counters don’t normally require text. However, any supporting text labels should be clear and concise.

### *Casing*

Supporting text labels should be written in sentence case.

### *Punctuation*

Text label punctuation should be avoided unless necessary, such as two hyphenated words. Text labels do not require terminal punctuation at all, however, occasionally, a question mark or exclamation mark may be appropriate in some situations.

### *Localization*

Translate your text labels to see if they adequately fit into the container layout. If designing in English, remember that it has one of the shortest character counts and often increases in length when translated into the main languages that Betclic products use — which is French, Polish, and Portuguese.