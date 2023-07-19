
# Timer

Timers are animated background elements that display a numerically-descending counter component that eventually counts down to zero. 

---

Timers always display two letters that represent different measurements of time, such as days, hours, minutes, seconds, etc. These letters change (in their normal order) as the timer decreases. After the timer finishes, it either turns into a tag or disappears entirely.

They are similar to the tag component because they are small, non-interactive elements and their function is to inform the user of when an upcoming game is about to start or when an event is about to go live.

  
![timer-cover](https://studio-assets.supernova.io/design-systems/27883/61459e51-1206-4156-800f-d63a32f51ad3.png)  
timer-cover  


## Usage

Timers are normally used to alert the user of an upcoming game or when an event is about to go live. Despite being non-interactive, timers are extremely important to the betting experience, therefore their usage must be carefully considered. Their presence is also unique to the user because they are linked to live events that are about to take place — this means that their presence is not persistent on the UI.

## States

Timers only exist in two states:

- Ongoing

- Warning

  
![timer-example-1](https://studio-assets.supernova.io/design-systems/27883/afa32593-5f3a-4cde-85f0-2438f97e70fe.png)  
timer-example-1  
![timer-example-2](https://studio-assets.supernova.io/design-systems/27883/fac0a84f-032f-4c16-a884-7038e5fd4815.png)  
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

  
![year](https://studio-assets.supernova.io/design-systems/27883/e8b466d8-9384-4e43-9415-72f78992a7af.png)  
year, 3 years 9 months
3y 9mo  
  
![month](https://studio-assets.supernova.io/design-systems/27883/72870477-f7be-41f9-87c2-6fe79e2e0ca7.png)  
month, 9 months 12 days
9mo 12d  
  
![day](https://studio-assets.supernova.io/design-systems/27883/fbb63ce3-b7a3-4cb0-b532-791fda349468.png)  
day, 12 days 16 hours
12d 16h  
  
![hour](https://studio-assets.supernova.io/design-systems/27883/55305ac5-a0a1-4b17-b57c-554d2a5327ea.png)  
hour, 16 hours 20 minutes
16h 20m  
  
![minute](https://studio-assets.supernova.io/design-systems/27883/af2d4fe3-3f9f-4923-bc1e-495edf2fff55.png)  
minute, 20 minutes 10 seconds
20m 10s  
  
![second](https://studio-assets.supernova.io/design-systems/27883/cac4bdde-ffdc-4571-87d4-67746e35bc0b.png)  
second, 0 minutes 12 seconds
0m 17s  
  


## Anatomy

Much like tags, timers are simple UI components comprised of a non-interactive colored container, a timer icon, and a text label. Their color indicates their state which is either “active” or “warning”.

  
![timer-anatomy](https://studio-assets.supernova.io/design-systems/27883/291414f9-4d81-46ad-8dfe-ed6dc207057b.png)  
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

  
![✅ DO](https://studio-assets.supernova.io/design-systems/27883/ff03b08a-77c3-4ea5-ae48-cf04efe3c777.png)  
✅ DO, Use timers to display countdown information that is needed to alert the user that an important game or event is about to begin. They are designed to visually stand out on the UI.  
  
![🚫 DON'T](https://studio-assets.supernova.io/design-systems/27883/25c3abad-e1a2-4c83-b159-32c6d8fe99c8.png)  
🚫 DON'T, Avoid using timers for any other purposes, such as marketing messages or general system info — this is not their purpose. Timers are used for start-time alerts only.  
  
![✅ DO](https://studio-assets.supernova.io/design-systems/27883/38cb7eb0-f1ff-41d9-b733-331bb5d7f31d.png)  
✅ DO, Use timers in their intended way only — a typical UI should only contain a timer if it is needed to alert the user. It is acceptable to have multiple timers if the design requires it, however, each timer used should be related to an individual event.  
  
![🚫 DON'T](https://studio-assets.supernova.io/design-systems/27883/f30cd334-685f-483b-ae22-c3909419a619.png)  
🚫 DON'T, Never use timers anywhere except their normal position — user confusion can occur if there is a random placement pattern of this component. Keep their placement and position consistent throughout your layout design.  
  


## Microcopy

### *General*

Timers do not require any additional text — they are used “as is” from the UI library. The only thing to be aware of is the local language of the product, as this will dictate the language variant of the timer that you use. The full list of language variants is cited above in the “Language Variants” section of these guidelines.

For cards that include supporting text labels next to the timer, it is better to keep the text very concise, so that attention is not drawn away from the timer itself.