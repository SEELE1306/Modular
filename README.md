# Modular - A theme made for Vesktop

## Introduction

This is one of the first themes that is made exclusively for **Vencord's own client, Vesktop**. 

> [!IMPORTANT]
> This theme is only guaranteed to work on Vesktop. Get the latest build here: [Releases - Vencord/Vesktop](https://github.com/Vencord/Vesktop/releases)

## Features

- High customizability:
  + ***Add a pre-made Nitro theme or background of your choice*** and adjust the brightness, blur as well as transparency
  + **Client global accent** using the HSL scheme
  + A **second accent color** to highlight important elements and add style
  + **Modules** (user panel, member list, guild list etc.) that can be flipped around
  + Adjustable **chat bubble and status colors**
  + Adjustable **primary and code font**
  + **Add a custom name on the titlebar** to make the layout more personal
    
- **A revamped look** for many elements, including profile panels and modals, Spotify controls, guild list and many more!
- **Compatibility and quality of life changes** for many of Vesktop's existing plugins
- Several ***add-ons*** are available separately in the `modular.theme.css` file
- Active support (to my ability)
- Some of the elements of this theme are available separately as snippets. Check them out [here](https://github.com/SEELE1306/SEELE1306.github.io/tree/main/Snippets).

## Images

### This is what you will see upon loading the theme for the first time:

![First Load](https://github.com/SEELE1306/Modular/assets/131888424/3b4a3047-774c-4a0b-8740-b1976a0771c3)

### Layouts can be customized to something like this:

![Layout Sample](https://github.com/SEELE1306/Modular/assets/131888424/0e858838-8a88-4183-8574-c949d1c7a947)

## Apply and customize

### Apply
> [!WARNING]
> Before installing, please make sure you have sufficient hardware to handle the laggyness this theme might bring.

There are several methods to apply this theme:

<details>
  
<summary>Via Local Themes:</summary>

  + Download the file `modular.theme.css` from this repository.
  + Open Settings > Vencord > Themes > Local Themes > Open Themes Folder.
  + Paste the downloaded file into the **themes** folder.

</details>

<details>
  
<summary>Via Online Themes</summary>

  + Open Settings > Vencord > Themes > Online Themes.
  + Paste the following link into **Theme Links**: `https://seele1306.github.io/Modular/modular.theme.css`
  + Enter or mouse-click outside the Online Themes box to apply

</details>

<details>

<summary>Via QuickCSS</summary>

  + Open Settings > Vencord > Vencord > Open QuickCSS File
  + Paste the following line as your **first line (ahead of any other custom CSS)**: `@import url(https://seele1306.github.io/Modular/modular.theme.css);`.

</details>

### Customization
A large part of the following guide is also available inside the `modular.theme.css` file.

To start customizing your layout, copy and paste the file `modular.theme.css` into your QuickCSS.

Additional supported add-ons are available in `modular.theme.css`. You can comment out any add-ons that you don't need by adding `/*` at the beginning and `*/` at the end. 

- To apply a **Catppuchin color**, use the following format: `var(--ctp-{scheme}-{color})`.
  For example, the color Latte Sapphire `#209FB5` would be `var(--ctp-latte-sapphire)`.

  More about how the colors look like can be found [here](https://github.com/catppuccin/catppuccin).

- To apply a **Nitro gradient** as a background, use the following format: `var(--{gradient-name})`.

##  Special thanks to
My theme, at the end of the day, is just a compilation of the many snippets that I have found. I will try my best to credit all the users whose snippets I have ultilized, but if your name does not show up here, feel free to contact me.

### Credits
[coolesding](https://github.com/coolesding), [Saltssaumure](https://github.com/Saltssaumure), [DaBluLite](https://github.com/DaBluLite), [Vendicated](https://github.com/Vendicated), [CodeF53](https://github.com/CodeF53), AkiraSimplex (`akirasimplex` on Discord)

## Issues
You tell me!

