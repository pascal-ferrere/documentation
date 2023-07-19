
# Timer

Timers are animated background elements that display a numerically-descending counter component that eventually counts down to zero. 

---

Timers always display two letters that represent different measurements of time, such as days, hours, minutes, seconds, etc. These letters change (in their normal order) as the timer decreases. After the timer finishes, it either turns into a tag or disappears entirely.

They are similar to the tag component because they are small, non-interactive elements and their function is to inform the user of when an upcoming game is about to start or when an event is about to go live.

  
![timer-cover](https://studio-assets.supernova.io/design-systems/27883/06c41f72-8d16-4ec7-95d0-5b0ace0aeabb.png)  
timer-cover  


## Usage

Timers are normally used to alert the user of an upcoming game or when an event is about to go live. Despite being non-interactive, timers are extremely important to the betting experience, therefore their usage must be carefully considered. Their presence is also unique to the user because they are linked to live events that are about to take place — this means that their presence is not persistent on the UI.

## States

Timers only exist in two states:

- Ongoing

- Warning

  
![timer-example-1](https://studio-assets.supernova.io/design-systems/27883/4ad96508-47fc-4137-80a1-7ebcb3f0ea8f.png)  
timer-example-1  
![timer-example-2](https://studio-assets.supernova.io/design-systems/27883/ba9089a6-21ac-4f47-a932-4c8e89dcb213.png)  
timer-example-2  


## Variants

Timers are offered in three variants:

- *Default *— large only

- *Alternative* — large only

- *Live *— small only

## Language Variants

Timers are always used in their regional language, these are the following abbreviated variants:

- *EN *— 3y 10mo 22d 19h 20m 17s

- *FR *— 3a 10m 22j 19h 20min 17s

- *PT *— 3 anos 10 meses 22 dias 19 h 20 min 17s

- *PL *— 3 l. 10 m-cy 22 dn. 19h 20min 17s

*Please note:* the abbreviated versions are always used for all new products. They are displayed using only two values, depending on the duration of time left until the timer expires.

For clarity, this list explains the formatting style of abbreviations in English:

  
![year](https://studio-assets.supernova.io/design-systems/27883/2b13127a-4267-4b09-be9b-79facfb00e50.png)  
year, 3 years 9 months
3y 9mo  
  
![month](https://studio-assets.supernova.io/design-systems/27883/cd86aea9-ee6c-4464-9d60-0db3ba5fb0d0.png)  
month, 9 months 12 days
9mo 12d  
  
![day](https://studio-assets.supernova.io/design-systems/27883/acc0968d-4c98-47cc-8392-332f5b14446c.png)  
day, 12 days 16 hours
12d 16h  
  
![hour](https://studio-assets.supernova.io/design-systems/27883/c5946fca-c8b9-4887-b62f-62dedf9d977f.png)  
hour, 16 hours 20 minutes
16h 20m  
  
![minute](https://studio-assets.supernova.io/design-systems/27883/d03e5dc1-5d01-4cc6-aec7-e064c4f2bddc.png)  
minute, 20 minutes 10 seconds
20m 10s  
  
![second](https://studio-assets.supernova.io/design-systems/27883/93d77688-d8eb-416a-9a2b-19cb87ee79e0.png)  
second, 0 minutes 12 seconds
0m 17s  
  


## Anatomy

Much like tags, timers are simple UI components comprised of a non-interactive colored container, a timer icon, and a text label. Their color indicates their state which is either “active” or “warning”.

  
![timer-anatomy](https://studio-assets.supernova.io/design-systems/27883/ce800594-b75e-45f5-93d4-906a416036d4.png)  
timer-anatomy, 1. Container — available in two colors used to display two different states.
2. Timer icon — icons are placed 8 px to the left side of the text label.
3. Text label — displays two numeric and text values.  
  


## Placement

Timers are normally placed on top of cards or sometimes banners, and they are normally positioned in the top left of the card or banner for Casino products. For Turf products, you can place the timer component at the bottom or top right of a card. Placement will be decided by the style of the card you use.

Regardless of where you place timers, placement patterns should always be maintained to avoid user confusion. Random placement is not allowed.

It’s okay to use more than one timer per screen, such as on multiple cards, however, always use the timer in a purposeful way. This is because each timer that you implement creates an additional distraction for the user.

## Behavior

The format of the timer is quite simple, it only uses two decreasing values which eventually lead to zero (we no longer use the 00:00:00 format when time is less than 24 hours). The pattern of the representational letters must always remain consistent, meaning that the values decrease consecutively in the order you would expect them to: D > H > M > S. Do not deviate from this pattern.

After reaching zero, the time will either disappear or it will turn into a tag component notifying the user that the game has started.

## Dos & Don’ts

  
![✅ DO](https://studio-assets.supernova.io/design-systems/27883/1f375011-675d-4657-87ea-d97a9fe97dde.png)  
✅ DO, Use timers to display countdown information that is needed to alert the user that an important game or event is about to begin. They are designed to visually stand out on the UI.  
  
![🚫 DON'T](https://studio-assets.supernova.io/design-systems/27883/d1286cfb-f4f1-4136-8044-3f6f5420b0e9.png)  
🚫 DON'T, Avoid using timers for any other purposes, such as marketing messages or general system info — this is not their purpose. Timers are used for start-time alerts only.  
  
![✅ DO](https://studio-assets.supernova.io/design-systems/27883/928b119f-668a-4fed-b519-57203dcf107f.png)  
✅ DO, Use timers in their intended way only — a typical UI should only contain a timer if it is needed to alert the user. It is acceptable to have multiple timers if the design requires it, however, each timer used should be related to an individual event.  
  
![🚫 DON'T](https://studio-assets.supernova.io/design-systems/27883/b90c5179-9f5c-41ca-9975-3161aae9ff68.png)  
🚫 DON'T, Never use timers anywhere except their normal position — user confusion can occur if there is a random placement pattern of this component. Keep their placement and position consistent throughout your layout design.  
  


## Microcopy

### *General*

Timers do not require any additional text — they are used “as is” from the UI library. The only thing to be aware of is the local language of the product, as this will dictate the language variant of the timer that you use. The full list of language variants is cited above in the “Language Variants” section of these guidelines.

For cards that include supporting text labels next to the timer, it is better to keep the text very concise, so that attention is not drawn away from the timer itself.