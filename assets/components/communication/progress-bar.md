
# Progress bar

Progress bars are simple non-interactive components that provide visual feedback related to the duration and progression of various processes. 

---

  
![progress-bar-cover](https://studio-assets.supernova.io/design-systems/27883/3dae15b1-ee4b-4de8-8842-788347b025d7.png)  
progress-bar-cover  


Their presence on the UI is always use-case dependent, however, user perception of their function is well-established. So it should be obvious to a user what they are for.

In Betclic products specifically, the variety of individual use cases for progress bars is quite wide. The same goes for their anatomy, which varies depending on the variant used.

However, regardless of the individual use case or input, the general design theme for progress bars remains the same — it’s a horizontal bar that displays whether a process hasn’t started, is in progress or has finished.

## Usage

Progress bars are used to display feedback about the duration and progression of a particular process. For Betclic products, these processes generally fall into two different usage patterns:

- Affected by external sources (e.g. displaying game or betting results)

- Affected by user inputs (e.g. progressing through a tutorial or adding referrals)

There is a third popular usage pattern which could be described as “governed by the system” (e.g. transfers or loading), however, in Betclic products, we do not use progress bars for this purpose.

## States

Because progress bars are not interactive, their only significant state change is that they change color.

You can see all the different colors available in the UI Library, however, the basic principle remains the same — the background track color will eventually be replaced by the progress bar filler color.

The way that this is displayed depends on the variant of the component used. Simple progress bars will change their colour by smooth percentage amounts, whereas steppers or counter progress bars use incremental changes, such as filled container blocks for stepper progress bars.

Betclic products do not use animated “loading style” progress bars, so the user will never view the state change. They will only see this component in its current “as is” state.

  
![progress-bar-variant-A](https://studio-assets.supernova.io/design-systems/27883/daaa03fa-c698-4a8e-b1df-ba33d01698b1.png)  
progress-bar-variant-A  


  
![progress-bar-variant-B](https://studio-assets.supernova.io/design-systems/27883/d9793f14-47b7-4522-8726-31aa4ea03e9f.png)  
progress-bar-variant-B  


## Variants

Progress bars are available in the following variants:

- Trends (percentage style)

- Progress bar simple (percentage style)

- Progress bar counter (numerical increments displayed in a percentage style)

- Stepper simple (numerical increments displayed as individual units)

### Variant styles

In addition to the variants listed above, variants are available in these color options:

- Default

- Alternative

*Please note: *there is also another style of progress bar that uses a flaming emoji icon as the thumb element.

## Anatomy

Progress bars are comprised of a simple horizontal container known as a “track”. This is a static area that the progress bar indicator moves on top of. The track acts as a fixed visual reference to display the total length and duration of the process.

When the progress bar is either full or empty, the bar is displayed as one single solid colour (represented by either the track or the indicator bar). However, during use, the progress bar track will display two colours. These two colours represent the numerical or percentage difference of the element’s progression. In other words, it shows the indicator’s progress across the bar.

For the stepper variant specifically, there are individual containers that are filled with a solid color in order to represent progress.

Please be aware that some progress bar variants use additional text labels to display information, such as percentage amounts or incremental numbers (known as counters). Other variants also use a flaming emoji icon as the thumb element.

  
![Legend](https://studio-assets.supernova.io/design-systems/27883/d939bf11-f0fe-4548-b5d7-50a997b5b9ea.png)  
Legend, 1. Track
2. Progress bar
3. Thumb
4. Text label  
  


  
![progress-bar-placement-A](https://studio-assets.supernova.io/design-systems/27883/8f868fe5-4b69-4ea6-aadb-07c3786a53c2.png)  
progress-bar-placement-A  


  
![progress-bar-placement-B](https://studio-assets.supernova.io/design-systems/27883/698bd664-1d9b-4b18-b91b-36b2a1d472ec.png)  
progress-bar-placement-B  


  
![progress-bar-placement-C](https://studio-assets.supernova.io/design-systems/27883/89fe474d-b8ea-4384-9dea-e3aa64185b0f.png)  
progress-bar-placement-C  


## Placement

The position and placement of progress bars normally depend on their required function or use case. This can occur anywhere in the UI and these patterns are dictated historically by the layout design. Please only use progress bars in these patterns. Creating new patterns is not recommended.

In addition, it is worth noting that some progress bars are used inside other elements, whereas others appear on top of the screen as part of an overlay layer.

## Behavior

In Betclic products, users will never see progress bars physically move in the way they would for traditional loading screens.

Their behaviour is very consistent, largely because they are non-interactive, so the user cannot control them (and can only affect some variants, depending on their input mechanism). Progress bars always behave in similar patterns, incrementally increasing or decreasing, depending on the inputs involved.

## Dos & Don’ts

*Do:* Use progress bars in the design patterns we currently have. Different variants have different intended uses, so please use the appropriate progress bar for the correct purpose.

*Don’t:* Avoid creating new design patterns for progress bars or using them in a way that they were not intended for. Never rotate the progress bar or add extra indicators. Only use “as is” from the UI library.

*Do: *Use progress bars when the user needs feedback and validation of a process. For stepper progress bars, always consider how many “steps” are needed (maximum of 10).

*Don’t: *Avoid using progress bars simply for decorative reasons, its usage must have a specific purpose.

*Do:* Use progress bars on an overlay layer when you really need to draw attention to progress feedback (e.g. in tutorials)

*Don’t:* Never hide the progress bar under other elements or use them in a discreet way — their placement should always be obvious to the user.

## Microcopy

### General

Progress bars currently do not offer text labels, so no UI text is needed.

However, some variants offer numeric counters, so therefore take care when adding in the digits to ensure that they are logical.