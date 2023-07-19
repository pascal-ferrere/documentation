
# Bottom Sheet

The bottom sheet is an interactive container situated at the bottom of the screen. 

---

The bottom sheets presents supplementary content useful to the user flow, as well as allowing users to quickly take additional actions if needed.

Its presence is decided by the user. This means they can be quickly removed or redeployed depending on the needs of the user — this makes them particularly useful for specific actions or goals.

  
![bottom-sheet-cover](https://studio-assets.supernova.io/design-systems/27883/0535dcfd-48a5-4a53-9775-27b81637cded.png)  
bottom-sheet-cover  


## Usage

Bottom sheets allow the user to focus on interacting with a short message and possibly take some action related to the message. Since bottom sheets swipe up from the bottom of the screen as an overlay, they can also be hidden easliy too.

We use bottom sheets for four distinct usage patterns. These patterns are further explain below in the “Variants styles” section.

### Bottom sheets are used for:

- Quick primary actions

- Placing or increasing bets

- Actions that need to be quick due to reachability

## States

Bottom sheets do not have different states because they are either active on screen or they are not visible.

  
![bottom-sheet-variant-A](https://studio-assets.supernova.io/design-systems/27883/2a7a9289-8dfb-4c50-847d-44f4dc1a3129.png)  
bottom-sheet-variant-A  


  
![bottom-sheet-variant-B](https://studio-assets.supernova.io/design-systems/27883/61ea29db-683e-42a9-a235-738f3f5ca99a.png)  
bottom-sheet-variant-B  


## Variants

Bottom sheets have two main varaint differences:

- With an action

- Without an action

## Variant styles

There are also eight different variant styles of the two main variants:

Text only

Positive - Text

Negative - Text

Pending - Text

Deposit - Positive

Promo - Positive

Bet - Positive

Empty (used for custom designs)

## Anatomy

Bottom sheets display various types of content, ranging from list items to supplemental content tailored to a specific use case. Content from a bottom sheet that initially appears below the screen edge can become visible when the sheet is pulled into view.

Bottom sheets always stretch their width to the edge of the screen, they don’t scale vertically. All the encapsulated content inside the bottom sheet follows its own responsive behaviour.

As an overview, a bottom sheet will be comprised of the following elements:

  
![Legend](https://studio-assets.supernova.io/design-systems/27883/c6a0804f-942e-4857-9c96-71a1021a67d6.png)  
Legend, 1. Container
2. Content (such as text boxes, buttons, input fields, etc.)  
  


## Placement

Bottom sheets are anchored to the bottom edge of the screen. They will never be placed anywhere else on the UI.

When used, they are elevated above all underlying content with the exception of pop-up dialogs, on-screen keyboard, and snackbars.

## Behavior

Bottom sheets respond to the user’s interaction. They remain displayed until interacted with or dismissed.

In general, bottom sheets co-exist with the screen’s main UI region allowing for simultaneously viewing and interacting between both areas.

## Dos & Don’ts

Do: Bottom sheets are always elevated above the main UI region because it is understood that its presence will be a temporary interaction and that their content is somehow related to the on screen content.

Don’t: Never design bottom sheets in a way that implies their placement is permanent. Try to keep their content relevant to what is happening on the screen in the user flow.