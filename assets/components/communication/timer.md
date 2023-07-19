
# Timer

Timers are animated background elements that display a numerically-descending counter component that eventually counts down to zero. 

---

Timers always display two letters that represent different measurements of time, such as days, hours, minutes, seconds, etc. These letters change (in their normal order) as the timer decreases. After the timer finishes, it either turns into a tag or disappears entirely.

They are similar to the tag component because they are small, non-interactive elements and their function is to inform the user of when an upcoming game is about to start or when an event is about to go live.

  
![timer-cover](https://studio-assets.supernova.io/design-systems/27883/261ba139-e908-40c2-b253-f62081f4196e.png)  
timer-cover  


## Usage

Timers are normally used to alert the user of an upcoming game or when an event is about to go live. Despite being non-interactive, timers are extremely important to the betting experience, therefore their usage must be carefully considered. Their presence is also unique to the user because they are linked to live events that are about to take place — this means that their presence is not persistent on the UI.

## States

Timers only exist in two states:

- Ongoing

- Warning

  
![timer-example-1](https://studio-assets.supernova.io/design-systems/27883/6e440b2c-12ec-4c32-98ab-f2f556a8cfbc.png)  
timer-example-1  
![timer-example-2](https://studio-assets.supernova.io/design-systems/27883/1ccb743f-36ae-4214-94c4-be2caae210ca.png)  
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

  
![year](https://studio-assets.supernova.io/design-systems/27883/bdf13617-e64a-4334-9d40-16705c47014c.png)  
year, 3 years 9 months
3y 9mo  
  
![month](https://studio-assets.supernova.io/design-systems/27883/91d87085-f32d-495c-b6c5-de0a757f777f.png)  
month, 9 months 12 days
9mo 12d  
  
![day](https://studio-assets.supernova.io/design-systems/27883/9d1c98e9-c1fc-4728-bfa9-a13328846d8c.png)  
day, 12 days 16 hours
12d 16h  
  
![hour](https://studio-assets.supernova.io/design-systems/27883/965283fd-cfcd-4b52-9018-ead8c4db0721.png)  
hour, 16 hours 20 minutes
16h 20m  
  
![minute](https://studio-assets.supernova.io/design-systems/27883/02d86e6d-a1ab-4f12-8f53-21afb031f579.png)  
minute, 20 minutes 10 seconds
20m 10s  
  
![second](https://studio-assets.supernova.io/design-systems/27883/a0935a3f-b6b0-4920-b2cb-8b2de850c5c9.png)  
second, 0 minutes 12 seconds
0m 17s  
  


## Anatomy

Much like tags, timers are simple UI components comprised of a non-interactive colored container, a timer icon, and a text label. Their color indicates their state which is either “active” or “warning”.

  
![timer-anatomy](https://studio-assets.supernova.io/design-systems/27883/7c6428a7-0e0a-4d6e-861a-f38f7349ee32.png)  
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

  
![✅ DO](https://studio-assets.supernova.io/design-systems/27883/070cb826-b51e-4682-aadc-10a8d68d20f0.png)  
✅ DO, Use timers to display countdown information that is needed to alert the user that an important game or event is about to begin. They are designed to visually stand out on the UI.  
  
![🚫 DON'T](https://studio-assets.supernova.io/design-systems/27883/4d3a6bff-3c1b-4c52-af65-a01bdaaf9143.png)  
🚫 DON'T, Avoid using timers for any other purposes, such as marketing messages or general system info — this is not their purpose. Timers are used for start-time alerts only.  
  
![✅ DO](https://studio-assets.supernova.io/design-systems/27883/afb7bfae-3dea-45a5-ac7b-dc5194300d39.png)  
✅ DO, Use timers in their intended way only — a typical UI should only contain a timer if it is needed to alert the user. It is acceptable to have multiple timers if the design requires it, however, each timer used should be related to an individual event.  
  
![🚫 DON'T](https://studio-assets.supernova.io/design-systems/27883/31146854-fe21-42fb-af01-c29bccb7c589.png)  
🚫 DON'T, Never use timers anywhere except their normal position — user confusion can occur if there is a random placement pattern of this component. Keep their placement and position consistent throughout your layout design.  
  


## Microcopy

### *General*

Timers do not require any additional text — they are used “as is” from the UI library. The only thing to be aware of is the local language of the product, as this will dictate the language variant of the timer that you use. The full list of language variants is cited above in the “Language Variants” section of these guidelines.

For cards that include supporting text labels next to the timer, it is better to keep the text very concise, so that attention is not drawn away from the timer itself.