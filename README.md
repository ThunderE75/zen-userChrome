# Zen Customization 

My userChrome.css for my Zen Browser

## Features

1. Pure Black Theme
1. Auto-dim URL Bar, Extensions & Panel Icons
2. Bottom Essentials & Auto-hide
3. Auto-dim Bottom Workspace indicator
4. Custom Dot styled Minimize, Maximize & Close Buttons

## Know Issues / Future Scope 

- [ ] Weird URL Bar Animation Behavior in Compact mode.
- [x] ~~Weird positioning of Left Tabs After the removal of workspace Indicators~~
- [x] ~~Too much height of each item in the URL Search suggestions.~~
- [x] ~~Dot styled Minimize, Maximize & Close Buttons dims individually (unexpected Behavior)~~

## Instructions

1. Paste userChrome.css into the chrome folder
2. Enable these flags in `about:config`,  So set them as `true`
   - `toolkit.legacyUserProfileCustomizations.stylesheets`
   - `zen.theme.gradient.show-custom-colors`
3. Right click on sidebar, then click `Edit Theme`, then click the `+` icon and add `#ffffff` as a custom color 
4. Now navigate to [Zen Mods](https://zen-browser.app/mods/) & download the mods listed below.

## Zen Mods Used

| Mods                                   | Github Link                                                              |
| -------------------------------------- | ------------------------------------------------------------------------ |
| Animation Plus                         | https://github.com/Anoms12/Animations-plus                               |
| Better CtrlTab Panel                   | https://github.com/psu/zen-mods                                          |
| Better Unloaded Tabs                   | https://github.com/Felkazz/zen-browser-better-unloaded-tabs              |
| Bleeding Corners Fix                   | https://github.com/rsiebertdev/zen-themes/tree/main/bleeding-corners-fix |
| Bleeding Corners FixCleaner Extensions | -                                                                        |
| Colored container tab                  | https://github.com/ocean-mars/things                                     |
| Custom uiFont                          | -                                                                        |
| Disable Rounded Corners                | -                                                                        |
| Floating Status Bar                    | https://github.com/AmirhBeigi/zen-floating-statusbar/                    |
| Only Close On Hover                    | -                                                                        |
| Pimp your PiP                          | -                                                                        |
| Right Side Glance Buttons              | https://github.com/psu/zen-mods                                          |
| SuperPins                              | -                                                                        |
| Zen Context Menu                       | https://github.com/KiKaraage/ZenMods/                                    |

## Mods Preferences

### Superpins

| Value                           | Preference                                                                                              |
| ------------------------------- | ------------------------------------------------------------------------------------------------------- |
| Normal                          | Select the general width of Essentials (The width before the Essentials start wrapping to the next row) |
| Normal                          | Select the gap between Essentials                                                                       |
| ✅                               | Adds selected width and gap styles from Essentials to pinned tabs as well                               |
| Transparent Background          | Background/Color types of Essentials                                                                    |
| ✅                               | Makes the Essentials look more box like (Less rounded edges)                                            |
| ✅                               | Makes the Essentials have the same height of Pinned Tabs                                                |
| ✅                               | Makes the Essentials auto-grow to fit the full width of its row.                                        |
| Top                             | Select the position of Essentials                                                                       |
| Essentials Only                 | Add a border around Pins/Essentials                                                                     |
| 🔳                               | Makes pinned tabs look similar                                                                          |
| 🔳                               | Makes pinned tabs auto-grow to fit the full width of its row.                                           |
| ✅                               | Adds a background to the pinned tabs                                                                    |
| 🔳                               | Shows the workspace-indicator between Essentials and Pins                                               |
| 🔳                               | Center the workspace indicator name                                                                     |
| 🔳                               | Essentials will be placed below workspace indicator when both are at the bottom                         |
| Default                         | Select the position of the workspace indicator                                                          |
| ✅                               | Loads pinned tabs only when using them, instead of loading all of them on startup                       |
| ✅                               | Keep pinned tabs at the top when scrolling                                                              |
| 🔳                               | Adds a custom background to active pinned tabs                                                          |
| ✅                               | Loads pinned tabs only when using them, instead of loading all of them on startup                       |
| ✅                               | Keep pinned tabs at the top when scrolling                                                              |
| 🔳                               | Adds a custom background to active pinned tabs                                                          |
| None                            | Custom background for active pinned tabs.                                                               |
| 🔳                               | Adds a strikethrough effect on unloaded tabs                                                            |
| ✅                               | Removes the sidebar scrollbar                                                                           |
| When there are pinned tabs only | When to display separator                                                                               |
| Icon + Text                     | Dim the selected parts of a tab when it is unloaded                                                     |
| Default                         | Height of Pinned tabs                                                                                   |
| Small                           | Size of tabs favicons                                                                                   |
| Default                         | Size of workspace icons                                                                                 |
| Default                         | Size of current workspace indicator icon                                                                |
| ✅                               | Makes Essentials have a limited amount of columns                                                       |
| 3                               | Number of slots in essentials grid.                                                                     |
| 🔳                               | Makes pinned tabs have a limited amount of columns                                                      |
| 1                               | Number of slots in pins grid.                                                                           |

### Zen Context Menu

| Value | Preferences                                                                                       |
| ----- | ------------------------------------------------------------------------------------------------- |
| ✅     | 🔁 Reorder options for tab context menu to improve ergonomics (enabled by default)                 |
| ✅     | 〰️ Hide all separators                                                                            |
| ✅     | 🔣 Restore back all icons (buggy, hit me up to suggest fixes on KiKaraage/ZenMods repo)            |
| 🔳     | 🔣 Hide all icons in context menu, except checkboxes and radio buttons, to fit current Zen styling |
| 🔳     | 🎨 Apply Zen workspace gradient (works best if your OS/DE/WM supports blur)                        |
| 🔳     | 🎨 Apply Zen accent color (the main color on your workspace gradient)                              |
| ✅     | 🔗 Prioritize 'Copy Clean Link' when possible (enabled by default)                                 |
| ✅     | 📑 🔗 Hide 'Bookmark Tab/Tabs/Link' options (enabled by default)                                    |
| 🔳     | 📑 Hide 'Mute Tab' options                                                                         |
| ✅     | 📑 Hide 'New Tab' &'New Tab Below' (enabled by default)                                            |
| ✅     | 📑 Hide 'Move Tab' options (enabled by default)                                                    |
| 🔳     | 📑 🔗 Hide 'Open Tab/Link in New Container Tab' options                                             |
| ✅     | 📑 🌐 🔗 Hide 'Send Tab/Page/Link to Device' options                                                 |
| 🔳     | 📑 Hide 'Close Tab' &'Close Duplicate Tabs'                                                        |
| 🔳     | 📑 Hide 'Close Multiple Tabs' options (enabled by default)                                         |
| 🔳     | 📑 🌐 🔤 🔗 Hide 'Ask AI chatbot' options if you enabled the feature                                  |
| 🔳     | 🔤 🔗 Hide 'Search Web for Selected Text/Link' options                                              |
| 🔳     | 🔤 🔗 Hide 'Search in a Private Window' (enabled by default)                                        |
| 🔳     | 🔤 🔗 Hide 'Translate Selection/Link Text' options                                                  |
| ✅     | 🔤 Hide 'Print Selection' (enabled by default)                                                     |
| ✅     | 🖼️ Hide 'Email Image', 'Set Image as Desktop Background', &'View Image Info' options               |
| 🔳     | 🎵 📺 Hide 'Copy Video Link', 'Copy Audio Link', 'Email Video' and 'Email Audio' options            |
| 🔳     | ⌨️ Hide 'Check Spelling' and 'Change Text/Page Direction' options while typing in text fields      |
| ✅     | 🌐 🔤 Hide 'Select All Text' option (enabled by default)                                            |
| ✅     | 📑 Hide 'Select All Tabs' (enabled by default)                                                     |
| ✅     | 📑 Hide 'Reload Tab' (enabled by default)                                                          |
| 🔳     | 📑 Hide 'Duplicate Tab'                                                                            |
| 🔳     | 📑 Hide 'Unload Tabs'                                                                              |
| ✅     | 🌐 🔤 Hide 'View Page Source' &'Inspect' options                                                    |
| 🔳     | 🌐 🔗 Hide 'Save Page/Link As' options                                                              |
| ✅     | 🌐 Hide 'Take Screenshot'                                                                          |
| 🔳     | 🖼️ 📺 Hide 'This Frame' option                                                                      |
| 🔳     | 📑 Hide 'Pin Tab' &'Add to Essentials' options                                                     |
| 🔳     | 🌐 Hide 'Back', 'Forward', 'Reload' &'Bookmark Page' options                                       |