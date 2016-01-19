# typographic-numbers-l10n-db

> Raw data about typographic numbers

Use typographic numbers depending on your locale for proper thousand separator and decimal point.

## Install

```sh
npm install --save typographic-numbers-l10n-db
```

## Usage

Pass [ISO 639][iso-639] code to specify locale and `numbersDB` will return 2 symbols.
First is a thousand separator and second is a decimal point.

```js
import numbersDB from 'typographic-numbers-l10n-db';

numbersDB['en-us']; // ,.
numbersDB['pt-br']; // .,
```

## License

MIT

[iso-639]: http://www.wikiwand.com/en/List_of_ISO_639-1_codes
