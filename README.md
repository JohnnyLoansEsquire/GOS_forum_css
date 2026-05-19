# GrapheneOS Forum -- Readability uBlock Filters

A collection of uBlock Origin filter lists to improve readability on [discuss.grapheneos.org](https://discuss.grapheneos.org).

The filter lists here will apply cosmetic changes via css that don't modify the actual site content--only how it appears in your browser.

## Features

- **High Contrast**
- **Larger Text**
- Light Mode has **only dark text!** No more white text.
- **Toggles & Buttons** are more prominent
- **Pixel Model Color Coding**: Device support status is color coded

  💚 Green: Pixels with MTE

  🩷 Pink: Pixels without MTE

  ❤️ Red: Pixelss not supported

> Note: Color coding **will not** update automatically when devices reach [End of Life](https://endoflife.date/pixel).
> Either: edit the list yourself, check back for a new release, or don't change a thing and enjoy life.

## Screenshots

> Tip: Edit the list to keep only the changes you like!

### Dark Mode
<details>
  <summary>Click Here To View</summary>

#### Discussion - Desktop/Tablet

![Dark Mode Discussions Desktop](Screenshots/dark_discussion.png)

#### Home page - Desktop/Tablet

![Dark Mode Home Desktop](Screenshots/dark_home.png)

#### Tags - Desktop/Tablet
![Dark Mode Tags Desktop](Screenshots/dark_tags.png)

#### Settings - Desktop/Tablet
![Dark Mode Settings Desktop](Screenshots/dark_settings.png)

#### Create A New Discussion - Desktop/Tablet
1) The OK button is low contrast currently because it is disabled -- A primary tag isn't selected yet.
2) Long tag names aren't cut off
![Dark Mode Create Discussion Tags Desktop](Screenshots/dark_create.png)

### Mobile - Narrow Screens
> Note: the right image implemented a change suggested on line 9 of both 'dark' configs to make the replying person slightly darker

![Dark Mode Home mobile](Screenshots/dark_mobile.png)

</details>

### Light Mode
<details>
  <summary>Click Here To View</summary>

#### Discussion - Desktop/Tablet
![Light Mode Discussions Desktop](Screenshots/light_discussion.png)


#### Home page - Desktop/Tablet
![Light Mode Home Desktop](Screenshots/light_home.png)


#### Tags - Desktop/Tablet

![Light Mode Tags Desktop](Screenshots/light_tags.png)

#### Settings - Desktop/Tablet
![Light Mode Settings Desktop](Screenshots/light_settings.png)

#### Create A New Discussion - Desktop/Tablet
1) The OK button is low contrast currently because it is disabled -- A primary tag isn't selected yet.
2) The Names of long tags aren't cut off
![Light Mode Create Discussion Tags Desktop](Screenshots/light_create.png)

### Mobile - Narrow Screens
![Light Mode Home mobile](Screenshots/light_mobile.png)

</details>

## Installation

1. **Add The uBlock Origin Extension To Your Browser** (if you haven't already)
   - [Get uBlock Origin](https://github.com/gorhill/uBlock#ublock-origin-ubo)
   - Most Chromium and Firefox based browsers support extensions on desktop; on Android try Kiwi or IronFox, Fennec (Although, Firefox is slow on Android)

2. **Choosing One Filter List**
   - Go to [discuss.grapheneos.org](https://discuss.grapheneos.org) on your device
     - Compare if it looks like the Desktop/Tablet screenshots shown here or mobile.
       - Tip: On Tablet, you can use the Narrow screen (mobile) config for the front screen. On the big screen, make your browser take up half of the screen to make it narrow via 'split'.
   - The following files are available. **(Choose 1)**
     - `dark-desktop.txt` — Dark mode for Desktop/Tablets
     - `dark-mobile.txt` — Dark mode for phones (narrow screens)
     - `light-desktop.txt` — Light mode for Desktop/Tablets
     - `light-mobile.txt` — Light mode for phones (narrow screens)
   - At the top of this website click on the desired file name
   - Either:
     - Download the file
     - Copy the text


![Download Picture](Screenshots/download.png)


3. **Add This Filter List** (Picture instructions below)
   - In your Web Browser, Go to extensions, open uBlock Origin, and open its settings
   - At the top are tabs. Go to the one that says: "My Filters" or "Custom Filters"
   - Import your downloaded file or copy and paste the contents.
   - There is either: a save button or check mark to push before leaving this page.
   - Refresh the page or open the [website](https://discuss.grapheneos.org) in a new tab to view the changes.

### Mobile - IronFox - Adding The List
<details>
  <summary>Click Here To View The Picture Instructions</summary>

![Download Picture](Screenshots/mobile_add1.png)

![Download Picture](Screenshots/mobile_add2.png)

![Download Picture](Screenshots/mobile_add3.png)
</details>

### Desktop - Firefox - Adding The List
<details>
  <summary>Click Here To View The Picture Instructions</summary>

![Download Picture](Screenshots/desktop_add1.png)

![Download Picture](Screenshots/desktop_add2.png)
</details>

## FAQ

1) Will I get hacked and my information stolen using this?

   No, these are cosmetic only -- no scripts or changing of site data.

2) Your color and text size choices are abysmal.

   The lists are well documented for editing to your needs.

   The lists available here improve the readability for those in need. Design was a secondary consideration.

3) I could have done this better than you.

   Correct. PRs and feedback is welcome.
