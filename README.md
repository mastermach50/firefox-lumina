# Firefox Lumina
A userstylesheet dark theme for Firefox, designed for using with Tree Style Tabs.

> Wallpaper by [Glenn Carstens-Peters](https://unsplash.com/@glenncarstenspeters)

![screenshot](screenshot.png)
## Design Aspects
- The browser theme should not distract the user from the content of the page that they are viewing.
- The browser theme should mix elegantly with modern styles used by most sites.
- Vertical Tabs >>> Horizontal Tabs
- Rounded elements look better

## Installation
1. Clone the repo
```
git clone https://github.com/mastermach50/firefox-lumina.git --depth 1
```
2. Copy the `chrome` folder into your firefox user profile folder
> Remember to backup your current chrome folder if it exists

3. Go to `about:config` of firefox

4. Make sure that `toolkit.legacyUserProfileCustomizations.stylesheets` is enabled

5. Install and enable the __lumina theme__ from [here](https://addons.mozilla.org/en-US/firefox/addon/lumina-ma3/)

6. Install and enable __Tree Style Tab__ from [here](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/)

7. Set `Website Appearence` to `Dark` in `about:preferences#general`.

5. Restart the browser

6. _Optional_: If you don't want window controls then you can comment out the line at the beginning of `userChrome.css` in the `chrome` folder that imports `new-window-controls.css`. [this line](https://github.com/mastermach50/firefox-lumina/blob/main/chrome/userChrome.css#L16)

> Feel free to create an issue if something is not looking right
