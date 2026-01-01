# Vivaldi-True-Dark-Theme
Vivaldi theme file and CSS mod for proper dark theme support with accent colors

## mode 1
<img width="341" height="224" alt="2025-12-31 18_21_01-" src="https://github.com/user-attachments/assets/f7431961-ed98-4669-b76d-d4f121d062ba" />

## mode 2
<img width="341" height="224" alt="2025-12-31 18_21_32-" src="https://github.com/user-attachments/assets/4d2ae99d-6b68-4f5c-a2f0-8131a67d7239" />

## Installation
1. Clone repo or manually download files
2. Settings > Themes > Import Theme, install zip file with theme
3. Enable "Allow CSS modifications" in vivaldi://experiments
4. Settings > Appearance > Custom UI Modifications, select folder for CSS files
5. Put one CSS file in that folder (TDT_mode_1 or TDT_mode_2)
6. Restart Vivaldi and enjoy your new dark theme

_You can change accent color in Settings > Themes > Editor > Colors > Highlight_

## Advanced Customization
Visit vivaldi://themecolors to see theme color variables and edit CSS file to your own liking. 

You can also hardcode colors by using Hex codes like this:

```css
#browser .tab-position .tab.active {
    background-color: #de733e !important;
}

	.tab:not(.active) {
    background-color: #0318fc !important;
} 
```
