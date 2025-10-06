# blucheck for CEXI

blucheck is a helper addon for Ashita that assists with tracking learned Blue Mage (BLU) spells in Final Fantasy XI. It provides an in-game UI to help players monitor which spells they have learned and which ones are still missing, along with information about the monsters and zones where spells can be learned.

This version of blucheck is modified for usage on [CatsEyeXI](https://www.catseyexi.com/), with two enhancements:
- Spell List & Zone Helper zone list places your current zone on top
- "Hide Known Spells" button to reduce clutter in the spell list

**Note**: Since CatsEyeXI is a 75-cap server, the spell list is modified to only show spells that are level 75 or lower. All [custom adjusted spells](https://www.bg-wiki.com/ffxi/CatsEyeXI_Systems/Jobs#Spells) are labelled as level 75. **Some spells over level 75 can be learned but cannot be used**.

## Features

- In-game UI for tracking BLU spell progress.
- Displays spell details, including range, area, and known status.
- Lists monsters and zones where each spell can be learned.
- Easy toggling of the UI with `/blucheck` command.

## Usage

This addon is designed for use with Ashita. Simply place the files in your Ashita addons directory. There is no need to build or execute anything manually.

To open or close the blucheck UI, use the following command in-game:
```
/blucheck
```

## File Structure

- `blucheck.lua` – Main addon entry point and event registration.
- `ui.lua` – Handles the user interface and spell display logic.
- `data/spells.json` – Contains spell data, including monster and zone mappings.
- `README.md` – Project documentation.

## Credits

- Author: atom0s
- Ashita Development Team

## License

This project is licensed under the GNU General Public License v3.0. See the source files for details.

For more information, visit [Ashita](https://ashitaxi.com/).