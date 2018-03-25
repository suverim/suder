# suder-v1.0
Turkish News Collections for Text Categorization

## Unarchiving
Join the parts:
```
cat suder-v1.tar.gz.parta* > suder-v1.tar.gz
```
Decompress:
```
tar zxfv suder-v1.tar.gz
```
## Corpus info

There are two different collections obtained from www.cumhuriyet.com.tr annd www.sabah.com.tr, categories are different for these two different collections

csv files contain the meta information including the titles, json files contain texts without the titles.

TextId column in csv files map to the corresponding key in the json files.

Data that do not contain category information are removed from the meta data but kept in the json files.
