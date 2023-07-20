
# Header

The header is a sticky, modular element that appears across the top of the application screen. 

---

The header considered one of the most important elements on the UI because it allows the user to navigate, search, access key features of the app, etc.

  
![header-cover](https://studio-assets.supernova.io/design-systems/27883/ce3fc201-28a6-4aa2-96e8-5ca1748961ad.png)  
header-cover  


## Usage

Headers act as an access point at the top of the screen so that the user can always reach specific key features, regardless of what is currently on screen. Key features a user may wish to access include navigation, their profile (if logged-in), search bars, betting info, etc.

We use different header variants for different purposes, however, all of their usage principles are generally the same — to provide the user with a familiar access point. Headers are always used as sticky elements so that content scrolls underneath it. They are always kept updated with relevant system information, such as notifications, which are used to inform the user of updates.

*Headers are used for:*

- Navigation

- Notifications

- Search functions

- Access to betting information

- Access to profile information (if logged in)

- Log in, log out, or access sign-up opportunities

## States

Headers change state according to the interaction that takes place, e.g. using the search field or tapping the profile icon.

Headers also change state depending on whether the user is logged-in or not. Occasionally, the header element will temporarily disappear, however, this only occurs when a full-screen image appears (such as a promo ad).

  
![header-state](https://studio-assets.supernova.io/design-systems/27883/27e7d44a-d0f0-43c4-b730-2392c121c834.png)  
header-state  


*Headers exist in these states:*

- Logged-in

- Logged-out

- New user with the option to sign-up

## Variants

As mentioned, different header variants are used for different purposes or applications. It should be intuitive which header is used for which purpose (just by looking at them in the library).

  
![header-variant-1](https://studio-assets.supernova.io/design-systems/27883/2c9298a9-4df5-42c4-89f4-e6f01e2e85c0.png)  
header-variant-1  


  
![header-variant-2](https://studio-assets.supernova.io/design-systems/27883/5b53504d-b5f5-4a92-9296-2ff931d8b99f.png)  
header-variant-2  


  
![header-variant-3](https://studio-assets.supernova.io/design-systems/27883/0bb2dcf8-4435-43a3-9ef5-13f66fb17d29.png)  
header-variant-3  


## Anatomy

Headers are module-level components meaning that they are created from various atom and molecule-level components, such as containers, icons, search fields, etc.

Different header variants contain different sets of these elements, however, the basic anatomy is always the same — a header container of one color that occupies 100% of the screen width. In addition, headers are always used as a sticky element meaning that content will always scroll underneath it.

1. Container

1. Icons

1. Search field

1. Betting info

1. Notifications

## Placement

Headers are always used at the top of the screen occupying 100% width of the screen.

Headers are never used anywhere else on the screen, only at the top!

## Behavior

The main rule is that headers are always used as sticky elements. This rule never changes. However, headers do offer numerous forms of behavior because they contain different elements depending on the variant. Notifications will always be displayed in real-time.

## Dos & Don’ts

*Do:* Always use headers at the top of the screen. The only exception is for a full screen image, such as a promo ad, when the header temporarily disappears.

*Don’t:* Never use a header anywhere except at the top of the screen.

*Do:* Regardless of touchpoint, always use headers full width and in a sticky fashion.

*Don’t:* Never allow content to scroll above the header. The header is always used as a forefront element on the Z-axis.

## Microcopy

*General*

In general, headers do not require much microcopy text. Titles, tabs, search field suggestion text, etc. should all be written as concisely as possible using task-specific language. Aim to only use one word where possible.

*Casing*

Header text should be written in the same that regular body text is created — a mixed style of title and sentence casing.

*Punctuation*

In general, punctuation should be avoided unless necessary, such as two hyphenated words or ampersand symbols.

Header text labels do not require terminal punctuation. Using ellipsis is not recommended unless a high character count truncates the text.

*Localization*

Translate your header text to see if it adequately fits into the container layout. If designing in English, remember that it has one of the shortest character counts and often increases in length when translated into the main languages that Betclic products use — which are French, Polish, and Portuguese. Remember that currencies are always placed on the right side, never on the left. Use a space between the value and the symbol. Try to use the currency symbol where possible.