
# Notification

The notification component is a small, non-interactive foreground element. Notifications only contain numbers, they never display text. After appearing on the UI, the goal of a notification is to display numeric info to the user — info that is typically related to user profiles, game activity or betting inputs.

---

Notifications do not appear when the UI is displayed in its default (non-interacted) state. Therefore, notifications are only displayed after an input or change has occurred. The presence of notifications can also be indefinite — meaning that they only disappear after they have been interacted with (depending on the notification this can be by visiting the entire related section or by visiting each related notification, e.g. viewing individual messages).

  
![notification-cover](https://studio-assets.supernova.io/design-systems/27883/adc00d40-03f6-4dad-aa38-1cb234eb3623.png)  
notification-cover  


The “freebet” variant is different from regular notifications because it is placed and used by itself to display only one type of info: monetary values. However, it is very similar in appearance and behavior to regular notifications.

## Usage

Not to be confused with “social media notifications” or any other related terms, we use UI notifications alone to display numeric info. Because this component only displays numbers related to inputs or activity, notifications are used as non-interactive elements.

The best way to think of typical notification usage is in the same way that an email provider uses them. They appear after some input has occurred (such as a message being received) but if there’s no input, then a notification is not displayed.

In general, users will recognise the usage patterns of notifications. Users will then expect to see them on specific parts of the UI, for example, floating over their Betslips or profile icon.

The “Freebet” notification is used in a slightly different way because it notifies the user of monetary values (free bets) that have become available. Freebet notifications do not float over other icons, instead, they are a self-contained, non-interactive element.

*Notifications are used for:*

Visually alerting the user of numeric information that they may wish to view (e.g. Betslips, game activity, messages, etc.)

Creating subtle and predictable usage patterns that improve the overall game experience for the user (e.g. they can be ignored indefinitely and are visually unobtrusive)

Freebet notifications are used for a single purpose — to display monetary values and free bets available to the user.

  
![notification-variant](https://studio-assets.supernova.io/design-systems/27883/ca3baa7a-62ed-4d34-ab27-7795531dc8d7.png)  
notification-variant  


  
![notification-example-B](https://studio-assets.supernova.io/design-systems/27883/aeeab643-9bc6-4270-84fe-84cfb99a0bb8.png)  
notification-example-B  


## Variants

Default notifications are available in two different sizes: Small & Large.

The other variant is the “Freebet notification” which is used for another purpose — it contains an icon and is a different color. It is only available in one variant.

## States

Notification components do not change state because they are not interactive — their state and color always remain consistent.

The only visible change is the number inside the element which alters the physical shape of the container element in two incremental width changes (it becomes wider as 2 or 3 characters are displayed).

## Anatomy

The container and number are displayed in the colors designated by the UI library color styles (dark grey and white).

Standard notifications are comprised of a circular colored container with a single or double-digit number displayed inside it. An optional “+” icon appears after a third digit is required but not displayed, e.g. 99+ which increases the character count to 3, thus widening the container. A corner radius of 16 px is used.

  
![Legend](https://studio-assets.supernova.io/design-systems/27883/515cbacf-31e1-4733-b5ae-75196c0add7a.png)  
Legend, 1. Container
2. Number (text label)  
  


## Placement

Users will always expect to find notifications consistently located in the same place above related icons. They are placed in a floating style above other elements, such as profile icons, inboxes, chat icons, “My Bets”, Betslips, etc.

Typically, we place notifications in the top right of an icon in a temporary “floating” style. Even for larger elements, such as Betslip icons, the notification is placed in the top right corner.

Another placement option is on the side of a text element (usually within the row of a list). Always ensure that a notification does or can not cover any other important piece of UI information. If you are designing a UI with icons that use notifications, you should visually check that your layout is not impaired by the appearance of a notification.

Above all — please always maintain placement patterns for notification components. Consistent UI behavior creates smooth gaming experiences.

  
![Legend](https://studio-assets.supernova.io/design-systems/27883/071bcd0c-1b4c-46f9-8879-c900cb492155.png)  
Legend  


## Behavior

Notifications are not part of a default UI. They are meant to be temporary and only appear after some activity or input has occurred. For this reason, notifications never display the value of “0” (zero). When a notification reaches zero it disappears from the UI. Despite this, notifications can be displayed indefinitely if their associated icon is never interacted with (e.g. unread messages).

In terms of when a notification will disappear, this depends on where the notification is used. For example, multiple notifications in the “News” section will all disappear simply by visiting the News section. However, for notifications related to messages, these are only removed incrementally as each individual message is opened and read (like an email inbox).

Single-digit notifications are displayed in a circular container. For numbers larger than 9, the notification container morphs into a rectangle with rounded corners. When a container with two digits exceeds a value of 99, a “+” character is added.

Unlike normal notifications, Freebet icons display currency, and can therefore display a value of zero. Regarding maximum value behavior, Freebet notifications behave like normal notifications.

## Dos & Don’ts

  
![✅ DO](https://studio-assets.supernova.io/design-systems/27883/2d9d9d5d-9ce6-48b3-82ca-11a21ecbc513.png)  
✅ DO, Use notifications to subtly alert the user to numeric information, such as “number of messages” or “My Bets”.  
  
![🚫 DON'T](https://studio-assets.supernova.io/design-systems/27883/49f2fa47-0af4-462b-a1b7-4e9f02d80be7.png)  
🚫 DON'T, Avoid using notifications to display text info — they should only contain numbers 1-99. Numbers higher than 99 are not displayed, only the “+” symbol is added to the value, 99.  
  
![✅ DO](https://studio-assets.supernova.io/design-systems/27883/0134c693-8c5c-4658-806d-ca2b818090cd.png)  
✅ DO, Place notifications in recognisable patterns — this would normally be floating over the top right corner of an interactive icon.  
  
![🚫 DON'T](https://studio-assets.supernova.io/design-systems/27883/a6afa443-4128-4520-abc7-40e24074a1be.png)  
🚫 DON'T, Never use default notifications to display “0”. We remove notifications from the UI after its related icon has been interacted with and its content viewed. It behaves in the same way as your email inbox.  
  
![✅ DO](https://studio-assets.supernova.io/design-systems/27883/28da15f9-fdf3-4270-a4cb-b9998bd65295.png)  
✅ DO, Use notifications for useful objectives, such as displaying how many bets are placed. Notifications can be ignored by the user, but the user should always understand that notifications are related to something important.  
  
![🚫 DON'T](https://studio-assets.supernova.io/design-systems/27883/26339fa8-7207-4241-bd93-49aeb7abeaa3.png)  
🚫 DON'T, Avoid using notifications to display info that is not important or relevant to the overall gaming experience. The presence of a notification is to alert the user that there is some new information that they should view.  
  


## Microcopy

### General

Notifications do not require any text at all — they are used “as is” from the UI library.