# avr-boards
Arduino IDE platform

## Add to your Arduino IDE

1. Open Preferences using the menu **Arduino>Preferences**
2. Copy the link `https://git.ahem.net.au/package_ahem_index.json` then paste it into the *Additional Boards Manager URLs* section
3. Select **OK**
4. Open the Boards Manager by selecting **Tools>Board: "...">Boards Manager...**
5. Scroll through the available boards, or search `Ahem` to find the package called *Ahem Engineering AVR Boards*
6. Click **Install**
7. Click **Close**

You have now installed the Ahem Engineering Arduino IDE Boards profile. Before you upload to your new microcontroller, make sure you select your board by going to **Tools>Board: "..."** and selecting the correct model.

## Version
Versions are numbered using [Semantic Versioning](https://www.semver.org)

- First number indicates **Major** versions. This means there may be major changes to the board selection, library selection, introduction of new core types, etc. This may potentially break older Arduino sketches or require reviewing the board settings you have selected for your project. New major versions will be forked.
- Second number indicates **Minor** versions. This means changes add functionality and may include additional examples or libraries, however none will be removed from previous minor versions. Items which will be removed from the next major release will be marked *deprecated* or similar.
- Third number indicated **Patch** version. This means changes have been made to increase compatibility, fix broken inclusions, add optimisations or fix other small errors.

## Coming soon
- Libraries
- Examples
