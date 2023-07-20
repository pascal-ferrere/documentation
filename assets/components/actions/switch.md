
# Switch

---

  
![switch-cover](https://studio-assets.supernova.io/design-systems/27883/5674b88e-4559-48e0-9c70-ffd407a01a23.png)  
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

  
![switch off](https://studio-assets.supernova.io/design-systems/27883/fc2a384f-afac-4a4e-a723-f2b8a4123a91.png)  
switch off  
![switch off disabled](https://studio-assets.supernova.io/design-systems/27883/0f6156d3-26fe-4762-9be0-74d8feab2994.png)  
switch off disabled  
![switch on](https://studio-assets.supernova.io/design-systems/27883/26469912-cd22-4978-b973-a2e743607dc3.png)  
switch on  
![switch on disabled](https://studio-assets.supernova.io/design-systems/27883/7a993c11-eb03-4af4-abe1-deaf9dfa6b35.png)  
switch on disabled  


## Anatomy

Toggle switches are very simple UI components comprised of a simple container with a filled background known as a “track” and a simple circle which acts as the “thumb” for the switch.

  
![Legend](https://studio-assets.supernova.io/design-systems/27883/5793a975-9e95-47ac-b30f-c9b70359b038.png)  
Legend, 1. Track
2. Thumb  
  


## Placement

Toggle switches are normally placed on top of cards. They can be placed next to text boxes or nested alongside other interactive elements, such as buttons. If used in groups, they can be stacked vertically (all aligned to the same Y-axis).

When grouped on a card as a list of switches, always use divider lines between each toggle switch. However, do not use a divider line above or below the top or bottom switch.

## Behavior

Toggle switches operate using a simple behavior pattern. When the switch is in its “off state”, it will be displayed in a “negative” grey color. When the switch is in its “on state” it will be displayed in an active green color.

It is important to understand that whatever the action is, the state change must be instant and obvious to the user.

## Dos & Don’ts

  
![✅ DO](https://studio-assets.supernova.io/design-systems/27883/dca43a32-8f1e-4768-971f-8ebdfac7cf8f.png)  
✅ DO, Use toggle switch components to immediately activate or deactivate system functionality or preferences.  
  
![🚫 DON'T](https://studio-assets.supernova.io/design-systems/27883/ccd41e7e-68c5-4ab1-9536-1290a576e528.png)  
🚫 DON'T, Never require the user to press “Submit” or “Save” to apply the selected state — toggle switches must provide instant actions upon interaction.  
  
![✅ DO](https://studio-assets.supernova.io/design-systems/27883/7f41370e-c304-4de8-8b81-0e6c2b2f1c09.png)  
✅ DO, Ideally, one switch should be applied to one action. For multiple actions, use multiple switches.  
  
![🚫 DON'T](https://studio-assets.supernova.io/design-systems/27883/baa2d496-94c3-430f-a94e-750db5d3f37c.png)  
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