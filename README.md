# homophones

`homophones.csv` is a curated list of homophones in the following format:

- each line has several words that have the same pronunciation
- each word is separated by commas (no additional formatting)
- only ASCII characters are valid. Offending lines can be found using GNU grep:
```
grep --color='auto' -P -n "[^[:ascii:]]" homophones.csv
```

Here are some sample lines:

```
bolder,boulder
bomb,balm,bombe
```

They are sort of in sorted order, but no guarantees.

# contributing

Feel free to contribute by making a pull request and following the formatting above.
