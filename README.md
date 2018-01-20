## 5e Tools
[Go to the Camor Homebrew Compendium](https://fourteenfifteen.github.io/5etools.html)


## How to import 5etools beasts/spells/items into Roll20
1. Get Greasemonkey (Firefox) or Tampermonkey (Chrome).

2. Click [here](https://github.com/TheGiddyLimit/5etoolsR20/raw/master/5etoolsR20.user.js) and install the script.

3. Open the Roll20 game where you want the stuff imported.

4. Go to the gear icon and click on the things you want imported.

5. Let it run. The journal will start fill up with the stuff you selected. It's not too laggy but can take a long time depending on the amount of stuff you selected.

6. Bam. Done. If you are using the Shaped sheet, be sure to open up the NPC sheets and let them convert before using it.

You can convert stat blocks to JSON for importing via [this converter](converter.html).

## Dev Notes

### Style Guidelines
- Use tabs over spaces.

### JSON Cleaning
#### Trailing commas
To remove trailing commas in JSON:

Find: (.*?)(,)(:?\s*]|\s*})

Replace: $1$3

#### Character replacement:
- ’ should be replaced with '
- — should be replaced with \u2014
- “ and ” should be replaced with "

## License

This project is licensed under the terms of the MIT license.
