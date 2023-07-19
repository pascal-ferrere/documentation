
# Modal

Modals focus the user's attention towards a single piece of information or request. They are an interface element that appears over other content.

---

Their main feature is that they require a user interaction in order to be removed. They do not appear randomly, they only appear after specific system changes (e.g. navigating through screen flows) or if user inputs are needed (e.g. confirming information is understood).

Visually, modals are normally displayed centralised, with the rest of the background content placed underneath a temporary overlay layer (to make it appear less prominent). This behavior blocks interaction with the rest of the application and forces the user to interact with the modal (otherwise the element is considered a dialog component).

  
![modal-cover](https://studio-assets.supernova.io/design-systems/27883/a191121a-f284-4080-b51d-a235d6c06348.png)  
modal-cover  


## Usage

Modals appear on the UI because the user needs to interact with them — they force the user to confirm a selection.

Their usage criteria can be fairly wide, however, no hierarchy is applied to their visual appearance. Modals are used “as is” from the library.

Modals can cause mild frustration because they interrupt the user’s experience, so therefore, their usage must be carefully considered.

*Modals are used for:*

- To force a response from the user

- To require the user to interact with a selection (either a button selection or enter text into an input field)

## States

Unlike most other interactive elements, a modal does not change its physical state. This is because it either exists on the UI or it disappears after an interaction. In addition to this, disabled or greyed-out modal states are not used.

Please note: despite modals not having different states, designers should pay close attention to the states of the interactive elements contained inside them as they will have a big impact on the user flow.

## Variants

Modals appear in two different variants (basic/branded) with two different styles of those variants:

- Single action - Text

- Double action - Text

## Anatomy

The four different variant styles of modals is based upon the same anatomy.

The modal’s container and interactive elements are displayed in the colors designated by the UI library color styles (which vary based on the product). The width size is fixed, however, the height can be adjusted according to the text size or added elements.

  
![Legend](https://studio-assets.supernova.io/design-systems/27883/82aa51fe-fb4c-4b29-a139-a830b4daf270.png)  
Legend, 1. Container
2. Optional body text — if needed (based on the variant used)
3. Interactive element — could be buttons (single or stacked) or an input field for adding user text
4. Background scrim — placed behind the modal but used in front of the rest of the UI to disable it  
  


## Placement

Modals consistently appear in the center of the screen as the only interactive foreground element. The position is always the same and never changes. The remaining background UI content also remains in the same place (it is then placed underneath a temporary overlay layer so that the user cannot interact with it until the modal disappears).

## Behavior

Modal behavior is very consistent because it only operates in two ways — it either exists on the UI or it does not — there is no other behavior style to account for.

As mentioned, when a modal appears on the UI it becomes the only interactive element available, so therefore it forces the user to interact with it in order for it to close.   In general, this behavior is instant allowing the user an immediate return to where they left off.

## Dos & Don’ts

*Do:* Think carefully about how and why the user needs to interact with a modal. Their usage should be meaningful and purposeful because they halt the user’s progress and engagement with the gaming experience.

*Don’t:* Avoid using modals to display non-critical messages such as reminders, marketing info, or general notifications.

*Do: *Place modals consistently in the center of the screen as a foreground element. Use an overlay layer to block off background content.

*Don’t: *Never embed modals in random parts of the UI — they are used and placed in one specific way only.

*Do: *Always provide an interactive element inside the modal’s container so that the user has an obvious way to interact with (and therefore remove) the modal quickly and easily.

*Don’t: *Use modals in a consecutive way so that they appear one after another repetively. If the user flow is repeatedly interupted, users may become frustrated. So please think carefully about when to implement a modal.

## Microcopy

### *General*

Always aim to keep the modal body text as concise as possible using task-specific language that describes the needs of the modal. Avoid passive and vague tonality because a modal interupts the user experience.

### *Wordcount*

For modal body text, keep the message as concise as possible. The user will already be midly frustrated, so they will want to read quickly why their experience was interupted.

### *Casing*

Like most pieces of body text, modal text should be written in sentence case. Exceptions include: proper nouns, Betclic products or features, and popular abbreviations or acronyms. Uppercase is not recommended unless the message is very serious.

### *Punctuation*

In general, punctuation and terminal punctuation should be used to create the body text in the same way that you would create any normal body text.

### *Localization*

Translate all modal text to see if it adequately fits into the container layout and any interactive elements that are included. English has one of the shortest character counts and often increases in length when translated into the main languages that Betclic products use — which are French, Polish, and Portuguese.