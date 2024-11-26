# Spanish Seed Words

The corpus is a curated dataset of Spanish words categorized by grammatical gender, intended for use in bias analysis and related fields. The words are organized into feminine and masculine categories, each containing multiple subcategories of lexical items. 

Data files are in `.csv` format, located in the `data/` directory, and are separated into subcategories as follows:

## Dataset Structure

### Feminine Words (`data/Feminine/`)
- [**00_Ignore_fem.csv**](./data/Feminine/00_Ignore_fem.csv): Words that should be excluded from processing due to their irrelevance or ambiguity in gender contexts.
- [**01_Pron_fem.csv**](./data/Feminine/01_Pron_fem.csv): Pronouns that indicate feminine gender.
- [**02_Sust_fem.csv**](./data/Feminine/02_Sust_fem.csv): Feminine nouns.
- [**03_Professions_list_fem.csv**](./data/Feminine/03_Professions_list_fem.csv): Profession names in their feminine forms.
- [**04_Nombres_fem.csv**](./data/Feminine/04_Nombres_fem.csv): Feminine names.
- [**05_Heteronimos_fem.csv**](./data/Feminine/05_Heteronimos_fem.csv): Feminine heteronyms.
- [**06_Heteronimos_adj_fem.csv**](./data/Feminine/06_Heteronimos_adj_fem.csv): Feminine heteronymous adjectives.
- [**07_Abreviaturas_fem.csv**](./data/Feminine/07_Abreviaturas_fem.csv): Abbreviations and acronyms with feminine connotations.

### Masculine Words (`data/Masculine/`)
- [**00_Ignore_masc.csv**](./data/Masculine/00_Ignore_masc.csv): Words that should be excluded from processing for similar reasons as their feminine counterparts.
- [**01_Pron_masc.csv**](./data/Masculine/01_Pron_masc.csv): Pronouns that indicate masculine gender.
- [**02_Sust_masc.csv**](./data/Masculine/02_Sust_masc.csv): Masculine nouns.
- [**03_Professions_list_masc.csv**](./data/Masculine/03_Professions_list_masc.csv): Profession names in their masculine forms.
- [**04_Nombres_masc.csv**](./data/Masculine/04_Nombres_masc.csv): Masculine names.
- [**05_Heteronimos_masc.csv**](./data/Masculine/05_Heteronimos_masc.csv): Masculine heteronyms.
- [**06_Heteronimos_adj_masc.csv**](./data/Masculine/06_Heteronimos_adj_masc.csv): Masculine heteronymous adjectives.
- [**07_Abreviaturas_masc.csv**](./data/Masculine/07_Abreviaturas_masc.csv): Abbreviations and acronyms with masculine connotations.

### Notes
Each `.csv` file contains a list of words, separated by line endings, that fall into the respective category. This structure provides a foundation for exploring linguistic patterns, gender-specific word usage, or adapting models for inclusive language processing.

### Applications
This corpus was created to support research in gender-aware language modeling and is a resource for linguists, developers, and researchers striving for inclusivity and precision in Spanish-language computational applications.

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />
<span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Spanish Seed Words Corpus</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
