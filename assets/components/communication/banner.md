
# Banner

Banners display short, important messages to the user. 

---

Their appearance and message content is meant to be purposeful and task-specific, related to the system or betting experience in a way that is informative to the user. We do not use banners for marketing messages, their purpose is to either enhance the gaming experience or to inform the user of something important.

  
![banner-cover](https://studio-assets.supernova.io/design-systems/27883/90f4310c-a219-4d75-aa25-ab41340b53d7.png)  
banner-cover  


---

## Usage

Banners are used to display important messages on the UI. The content of the message must always remain useful, be task-specific, and be relevant to the system or gaming experience — we do not use banners for marketing or any other generic purpose. Banners can be both positive and informative, or they can be for warnings, alerts, and negative information related to the system or something that is happening in the app itself. In general, they are supposed to stay on screen unless some interaction occurs somewhere else in the UI which causes the system to update.

## Variants

Banners come in three variants:

- Floating

- Sticky

- Special

### Floating banners

In general, floating banners are meant to stay on screen. Their main goal is to prompt the user to take some additional action expressed in the text label, for example, a floating banner could indicate to the user that they can get a bonus by adding an additional selection to their existing bet.

  
![banner-variant-floating](https://studio-assets.supernova.io/design-systems/27883/bcac32f8-5736-411d-beb1-a2f2a92e87f3.png)  
banner-variant-floating  


### Sticky banners

Sticky banners are meant to stay on screen. They are larger and very prominent. They are always placed at a specific spot within the UI, allowing content to scroll underneath. For error or negative messages, they can indicate why a negative state is happening, for example, why a bet is not valid. Sticky banners cannot be directly dismissed by the user, however, they will normally disappear after an action or state change occurs elsewhere.

  
![banner-variant-sticky](https://studio-assets.supernova.io/design-systems/27883/0365ca86-3aa5-4bd9-b692-cf5d46dfd901.png)  
banner-variant-sticky  


### Special banners 

For specific use cases. Special banners are used to temporarily display an event that is happening during a game. For example "Big opportunity for PSG", or to indicate that a game is on hold, for example, if the referee is checking for a potential penalty.

  
![banner-variant-special](https://studio-assets.supernova.io/design-systems/27883/0c476766-aebd-474c-b44b-f4a85de92be4.png)  
banner-variant-special  


## States

The color of banners informs the user of its state (and therefore, its purpose). Users will become familiar with the color patterns of banners and therefore recognize their purpose.

Banners exist in these states:

  
![Informative — Blue](https://studio-assets.supernova.io/design-systems/27883/3b938fed-3dc6-42ea-bd0e-0ddc2da36d7e.png)  
Informative — Blue  
![Multiplus (Floating only) — Orange](https://studio-assets.supernova.io/design-systems/27883/44efa5f2-5cd3-42f3-8821-fb1821b91b67.png)  
Multiplus (Floating only) — Orange  
![Negative — Red](https://studio-assets.supernova.io/design-systems/27883/87da68a5-e88d-4ffc-a6e8-2b182d328bae.png)  
Negative — Red  
![Positive — Green](https://studio-assets.supernova.io/design-systems/27883/c4ea9bce-e827-445a-a442-569df5c6afd9.png)  
Positive — Green  
![Warning — Yellow](https://studio-assets.supernova.io/design-systems/27883/70d007fe-b8b7-40d6-9e70-3174907f677b.png)  
Warning — Yellow  


## Anatomy

Banners are comprised of a rectangle-shaped container with a text label. The color of the container represents the purpose of the banner (its state).

  
![Legend](https://studio-assets.supernova.io/design-systems/27883/7f22254d-c404-467a-a350-d5a872e07738.png)  
Legend, 1. Container
2. Text label*
3. Icon**  
  


> Some extra info:  
> * View the Microcopy rules for guidelines on the text label’s message content.
** Icons are applied in specific use cases only — they are placed 8 px away from the text label.

## Placement

Banners are generally placed at the top of the screen, however, there are some situations where they are placed in other positions. Their placement is always separate from other pieces of content.

## Behavior

In general, banners are not interactive and their behavior is defined by the type of banner used.

- *Floating *— Content will generally scroll next to the banner, not underneath it. Floating banners generally stay in place unless the user performs some action related to the banner’s message.

- *Sticky *— Content will generally scroll underneath the banner, not above it or next to it. Sticky banners also generally stay in place unless the user performs some action related to the banner’s message.

## Dos & Don’ts

  
![✅ DO](https://studio-assets.supernova.io/design-systems/27883/b7575f67-cabb-4431-8a00-1383666fd844.png)  
✅ DO, Use banners to display a short, concise message to the user. It can either just be advisory (such as a prompt) or it can require them to take some action somewhere else in the UI (banners are generally not interactive).  
  
![⛔️ DON'T](https://studio-assets.supernova.io/design-systems/27883/1ebe7c27-8279-4cb8-bf1a-aab5b5a566ba.png)  
⛔️ DON'T, Never use an ellipsis to truncate a message in a banner — this is not how we use banners. If your message is too long, you need to revise and edit it.  
  
![✅ DO](https://studio-assets.supernova.io/design-systems/27883/75f868e8-41e0-461c-9492-c920fdef548f.png)  
✅ DO, Use banners to display messages that are related to the system or gaming experience in a useful and meaningful way. We want our users to understand the patterns that banners are used in so that they learn not to ignore them.  
  
![⛔️ DON'T](https://studio-assets.supernova.io/design-systems/27883/dca8f7bb-1ee4-4b79-929a-92c915ea483e.png)  
⛔️ DON'T, We do not use banners for generic marketing messages — this is not the purpose of banners.  
  


## Microcopy

### General

Banner label text should be short and concise. The text label must always fit inside the banner. We do not truncate banner text labels as this is confusing for the user. Therefore, your text label should ideally be one line in length, however, it can stretch up to three lines if necessary.

### Casing

Banner messages should always be written in sentence case with the exception of proper nouns, Betclic products or features which can be written in title case to highlight their importance. Popular abbreviations or acronyms related to the gaming experience, e.g. PSG, T&Cs, BOG, etc. can be written in uppercase.

### Punctuation

Terminal punctuation is required for banners. The use of ellipsis is forbidden because your message should always fit inside the label and should not indicate to the user that there could be a longer hidden message. This is not how we use banners.