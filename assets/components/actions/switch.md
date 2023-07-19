
# Switch

---

  
![switch-cover](https://studio-assets.supernova.io/design-systems/27883/c4c13c8d-1d01-48e1-9427-aff6f2bd646f.png)  
switch-cover  


## Usage

Toggle switches can be used as solo components or stacked vertically in groups. Their main function is to switch between two states with the change always being instant.

Important usage note: Toggle switches should never force users to enable an input in order for an action not to occur. This is considered bad UX. We only use toggle switches for positive and primary actions. The switch’s presence and function should be obvious and intuitive to the user.

*This component is used for:*

- Turning content or contextual information on or off

- Activating or deactivating state change events

- Displaying content or actions as enabled or disabled

- Validating and verifying states of contextual information

## States

Because this component is so simple, it only appears in two states: on and off (as represented by its corresponding color).

There are no variations of this component, only the choice between two versions of color: Default and Alternative.

When a toggle switch is active its container will have a green background. When it is inactive it will have a grey background.

### Toggle Switches exist in these states:

  
![switch off](https://studio-assets.supernova.io/design-systems/27883/49f68d9d-2830-4936-ac22-255e08d5e618.png)  
switch off  
![switch off disabled](https://studio-assets.supernova.io/design-systems/27883/f9f2a78b-54fc-4396-a88d-f86948843ae8.png)  
switch off disabled  
![switch on](https://studio-assets.supernova.io/design-systems/27883/7156e425-fd4d-4264-87bb-cd30a95f1b4b.png)  
switch on  
![switch on disabled](https://studio-assets.supernova.io/design-systems/27883/7004f92c-3fd3-490d-988f-b9605567dad3.png)  
switch on disabled  


## Anatomy

Toggle switches are very simple UI components comprised of a simple container with a filled background known as a “track” and a simple circle which acts as the “thumb” for the switch.

  
![Legend](https://studio-assets.supernova.io/design-systems/27883/9f8a7531-33a0-4304-8fbe-0f46606b1d0f.png)  
Legend, 1. Track
2. Thumb  
  


## Placement

Toggle switches are normally placed on top of cards. They can be placed next to text boxes or nested alongside other interactive elements, such as buttons. If used in groups, they can be stacked vertically (all aligned to the same Y-axis).

When grouped on a card as a list of switches, always use divider lines between each toggle switch. However, do not use a divider line above or below the top or bottom switch.

## Behavior

Toggle switches operate using a simple behavior pattern. When the switch is in its “off state”, it will be displayed in a “negative” grey color. When the switch is in its “on state” it will be displayed in an active green color.

It is important to understand that whatever the action is, the state change must be instant and obvious to the user.

## Dos & Don’ts

  
![✅ DO](https://studio-assets.supernova.io/design-systems/27883/acefea0e-97c1-42b0-a653-cfdcc3705242.png)  
✅ DO, Use toggle switch components to immediately activate or deactivate system functionality or preferences.  
  
![🚫 DON'T](https://studio-assets.supernova.io/design-systems/27883/1e680f07-85f0-4e3d-999d-7fa01ecbdf3f.png)  
🚫 DON'T, Never require the user to press “Submit” or “Save” to apply the selected state — toggle switches must provide instant actions upon interaction.  
  
![✅ DO](https://studio-assets.supernova.io/design-systems/27883/1e07c39d-b268-44fe-9381-013a8aaaef36.png)  
✅ DO, Ideally, one switch should be applied to one action. For multiple actions, use multiple switches.  
  
![🚫 DON'T](https://studio-assets.supernova.io/design-systems/27883/51a39afc-a6ed-4067-adfd-21d922efeb0e.png)  
🚫 DON'T, If you need to force the user to choose one selection from a list of multiple options, please consider using different UI elements (such as radio buttons).  
  


## Microcopy

### General

The most important thing to remember when writing toggle switch text is that it should never force users to enable an input in order for an action not to occur — so always think carefully about how the text is framed.

Users will often quickly scan text so that they can enable what they need and ignore the rest, so always use a clear and proactive tone of voice for your text labels. Promote brevity instead of using more descriptive text.

### Casing

Toggle switch text should be written in the same that regular body text is created — a mixed style of title and sentence casing.

### Punctuation

In general, punctuation should be avoided unless necessary, such as two hyphenated words, forward slashes or ampersand symbols. When using forward slashes, use a space each side to increase readability. Toggle switch text labels rarely require terminal punctuation. Ellipsis is not recommended unless a high character count truncates the text.

### Localization

Translate your toggle switch text to see if it adequately fits into the container layout. If designing in English, remember that it has one of the shortest character counts and often increases in length when translated into the main languages that Betclic products use — which are French, Polish, and Portuguese. Remember that currencies are always placed on the right side, never on the left. Use a space between the value and the symbol. Try to use the currency symbol where possible.