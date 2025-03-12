# Epic Noir (Revisited) for ES-DE
This is a port of the Epic Noir theme (originally by [c64-dev & Chicuelo](https://github.com/c64-dev)) from RetroPie to [ES-DE](https://es-de.org/) v2.x

**All artwork and layouts were designed and created by c64-dev & Chicuelo.  I simply made changes to the XML to make the theme compatible with ES-DE. The original version of the theme can be found [here](https://github.com/c64-dev/es-theme-epicnoir)**

## Changes Made
- Redesigned the design/layout of system and gamelist views
- Removed all Retropie specific elements to make the theme compatible with ES-DE v2.x
- Updated system image names to match the standard used by ES-DE
- Added 16:10 and 4:3 Layouts Variants
- Add support for ES-DE capabilities such as badges and aspect ratio switching
- Embedded the ES-DE [system-metadata](https://gitlab.com/es-de/themes/system-metadata) repository to power system description, release year and hardware type details

## **Preview**

| System View | Gamelist View |
|----|----|
| <img alt="Screenshot 2023-03-12 at 8 53 43 PM" src="https://user-images.githubusercontent.com/1454947/224585550-a8915000-7436-4770-b8bd-7c1350a7a8d0.png"> | <img alt="Screenshot 2023-03-12 at 8 54 09 PM" src="https://user-images.githubusercontent.com/1454947/224585555-bd4ab158-b32f-45f4-8477-cb486939eafc.png"> |

## **Contributions**
- The theme has fallbacks in place for systems without artwork defined yet.
- If you see a system with missing images and you would like to contribute artwork then please create an issue or PR in this repo with your updates and any credits to original authors of the images (if they are not made by you)
- Each system references 2 images that can be added:
   - `\_inc\systems\artwork\[system.theme].jpg` - this is the background artwork displayed to the right of screen.  It should be a JPG and at least 1160x1080 in dimension.
   - `\_inc\systems\controllers\[system.theme].png` - this is the controller artwork displayed on the system view underneath the description.  It should be a transparent PNG.
   - `[system.theme]` in the above paths refers to the name of the theme value for that system in ES-DE.  Please make sure to same your images with that value (example: `tg16.jpg`)
- While its preferred that you create and submit both images; its not required.  Please feel free to contribute what you are comfortable creating.
- To see a full list of what is open to be added please check [here](https://github.com/anthonycaccese/epic-noir-revisited-es-de/issues/1)
- If you have any questions please don't hesistate to ask.

## **Credit**
All artwork and layouts were designed and created by [c64-dev & Chicuelo](https://github.com/c64-dev)

## **License**
Creative Commons CC-BY-NC-SA - https://creativecommons.org/licenses/by-nc-sa/2.0/
You are free to share and adapt this theme as long as you provide attribution back as well as share any updates you make under the same licence terms.  You may not use this theme for commercial purposes.
