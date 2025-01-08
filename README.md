This dataset contains translations structured as `I am [demonym]` in English, with corresponding translations into **German (deu)**, **Spanish (spa)**, **French (fra)**, and **Italian (it)**. The dataset is organized by language in the `data/` folder.


## Source

The translations were sourced from the following references:

0. English https://github.com/mledoze/countries/tree/master
1. French https://github.com/mledoze/countries/tree/master
2. German https://deutsch.lingolia.com/en/vocabulary/laender-nationalitaeten
3. Italian https://www.theintrepidguide.com/nationalities-in-italian/?utm_source=chatgpt.com
4. Spanish https://espanol.lingolia.com/en/vocabulary/countries

## File Format

Each file contains the following columns:

| Column Name        | Description                                            |
|--------------------|--------------------------------------------------------|
| `eng`              | The source sentence in English (e.g., `I am American.`)|
| `<lang>_m`         | The masculine form of the translation (if applicable)  |
| `<lang>_f`         | The feminine form of the translation (if applicable)   |
| `<lang>_n`         | The neuter form of the translation (if applicable)     |

### Example

| eng              | it_m               | it_f               | it_n        | 
|-------------------|--------------------|--------------------|------------|
| I am Austrian.    |Sono austriaco.	 | Sono austriaca.    |            |
| I am Belgian.     |                    |                    | Sono belga.|
