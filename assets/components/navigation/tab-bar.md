
# Tab-bar

The tab bar is a core element of the UI — they create a standardized and shared navigation experience across the entire application.

---

Positioned at the bottom of the UI, the tab bar offers both easy reachability and quick navigation for the user. Much like a header, the component is always sticky and is elevated above other content. They also display notifications so that the user is always aware of updates.

The tab bar offers users five different primary areas within the app to navigate to — each destination is represented by an animated icon and text label. When an icon is tapped, the user is taken to the top-level navigation destination associated with that icon.

  
![tab-bar_cover](https://studio-assets.supernova.io/design-systems/27883/22196575-c6de-4892-9e06-0345961ae9bd.png)  
tab-bar_cover  


## Usage

Tab bars are used to allow users access to the five main areas of the app (users will always be in one of these five destinations). Upon selection, the user is always taken to the top-level of the icon’s destination (regardless of the previous destination).

Much like headers, tab bars are used in the same way on every single screen (sticky and elevated above other content). The only time when they are not used is temporarily during the presentation of a full-screen ad or promo.

*Tab bars are used for:*

- Displaying notifications

- Navigation to five top-level destinations

## States

The icon within the tab bar is either selected or it is not. When an icon is selected, it means that the user is in this area of the app.

Both states of the tab bar can support notifications (if the user is logged in), which are placed towards the top right of the icon.

*The component exists in these states:*

*Selected —* the icon is colored and animated

*Not selected —* the icon is greyed-out and not animated

## Variants

Tab bars vary by region and also if they support notifications or not (depends if the user is logged in or not).

## Anatomy

Tab bars are always displayed full-width.

  
![Legend](https://studio-assets.supernova.io/design-systems/27883/a6ac8974-8f00-4c2c-8538-fae28a02d6c4.png)  
Legend, 1. Container
2. Icon
3. Text label
4. Notification icon  
  


## Placement

  
![tab-bar_placement](https://studio-assets.supernova.io/design-systems/27883/848fc07d-a399-4653-9f52-852ed6657701.png)  
tab-bar_placement  


Tab bars are anchored to the bottom of the UI and always elevated above other elements.

They are always visible. The only exception is when a temporary full-screen overlay appears, such as a promo advert.

## Behavior

Tab bars are used in a sticky fashion so that they are always above other types of content.

Because the user will always be in one of the five destinations, this means that one of the five icons will always be selected (and therefore animated). The other four icons will be unselected. Regardless of state, tab bars support notifications for logged-in users.

## Dos & Don’ts

*Do: *Always use tab bars in the same way and position on the UI.

*Don’t:* Never reorganize the icons within the tab bar — usage patterns need to remain in place for user recognition.

*Do:* Always navigate the user to the top-level of the tab bar icon’s destination.

*Don’t:* Avoid animating icons which are not selected. Only one icon can be selected at a time because the user can only be in one place at a time.

## Microcopy

In general, tab bars should be used “as-is” from the library — this means that the text labels should remain in place.

If there is a need to rewrite the labels, then please use title case and only one or two words per label.