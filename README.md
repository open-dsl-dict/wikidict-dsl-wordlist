# wikidict-dsl-wordlist - Wikidata Monolingual DSL Reference (wordlists)

This repository makes available a collection of bilingual wordlist dictionaries in DSL format derived from interwiki links (links between article titles in different languages) in Wikipedia. The data has been extracted from [Wikidata](https://www.wikidata.org/).

## Format

ABBYY Lingvo DSL is a flexible dictionary format that can be read by dictionary applications such as [Goldendict](https://github.com/goldendict/goldendict) and converted to other formats using tools such as [pyglossary](https://github.com/ilius/pyglossary). There are also a number of tools for creating DSL format dictionaries available in the [dsl-tools](https://github.com/dohliam/dsl-tools) project.

DSL files *must* be saved as UTF-16 to be usable by dictionary programs. The raw source files in this repository are saved in UTF-8 format, which is both significantly smaller in terms of file size, and also readable (and diffable) by git. However, there are fully encoded and compressed `.dsl.dz` dictionaries ready for use available in the [Releases](https://github.com/open-dsl-dict/wikidict-dsl-wordlist/releases) section.

You can also use the `rezip_dsl.rb` and `unzip_dsl.rb` [scripts](https://github.com/dohliam/dsl-tools/tree/master/zip_unzip) provided by the [dsl-tools](https://github.com/dohliam/dsl-tools) repo to encode/compress and decode/uncompress the dictionaries either individually or as a group.

## Data

The data directory contains the bilingual dictionaries in pairs according to [ISO language code](http://en.wikipedia.org/wiki/ISO_639-1).

The basic filename pattern is `[ISO]-wordlist_wikidict.dsl`, with `[ISO]` being the source language ISO code. A list of all language pairs is [below](#available-language-pairs).

## Available language pairs

Language codes | Language names
-------------- | --------------
`af-wordlist_wiki-wordlist.dsl` | Afrikaans => wordlist
`am-wordlist_wiki-wordlist.dsl` | Amharic => wordlist
`ang-wordlist_wiki-wordlist.dsl` | Anglo-Saxon => wordlist
`ar-wordlist_wiki-wordlist.dsl` | Arabic => wordlist
`arc-wordlist_wiki-wordlist.dsl` | Aramaic => wordlist
`bg-wordlist_wiki-wordlist.dsl` | Bulgarian => wordlist
`bi-wordlist_wiki-wordlist.dsl` | Bislama => wordlist
`bn-wordlist_wiki-wordlist.dsl` | Bengali => wordlist
`bo-wordlist_wiki-wordlist.dsl` | Tibetan => wordlist
`br-wordlist_wiki-wordlist.dsl` | Breton => wordlist
`bs-wordlist_wiki-wordlist.dsl` | Bosnian => wordlist
`ca-wordlist_wiki-wordlist.dsl` | Catalan => wordlist
`cdo-wordlist_wiki-wordlist.dsl` | Min Dong => wordlist
`chr-wordlist_wiki-wordlist.dsl` | Cherokee => wordlist
`chy-wordlist_wiki-wordlist.dsl` | Cheyenne => wordlist
`cr-wordlist_wiki-wordlist.dsl` | Cree => wordlist
`cs-wordlist_wiki-wordlist.dsl` | Czech => wordlist
`cy-wordlist_wiki-wordlist.dsl` | Welsh => wordlist
`da-wordlist_wiki-wordlist.dsl` | Danish => wordlist
`de-wordlist_wiki-wordlist.dsl` | German => wordlist
`el-wordlist_wiki-wordlist.dsl` | Greek => wordlist
`en-wordlist_wiki-wordlist.dsl` | English => wordlist
`eo-wordlist_wiki-wordlist.dsl` | Esperanto => wordlist
`es-wordlist_wiki-wordlist.dsl` | Spanish => wordlist
`et-wordlist_wiki-wordlist.dsl` | Estonian => wordlist
`eu-wordlist_wiki-wordlist.dsl` | Basque => wordlist
`fa-wordlist_wiki-wordlist.dsl` | Persian => wordlist
`ff-wordlist_wiki-wordlist.dsl` | Fula => wordlist
`fi-wordlist_wiki-wordlist.dsl` | Finnish => wordlist
`fr-wordlist_wiki-wordlist.dsl` | French => wordlist
`ga-wordlist_wiki-wordlist.dsl` | Irish => wordlist
`gan-wordlist_wiki-wordlist.dsl` | Gan => wordlist
`gd-wordlist_wiki-wordlist.dsl` | Scottish Gaelic => wordlist
`gu-wordlist_wiki-wordlist.dsl` | Gujarati => wordlist
`gv-wordlist_wiki-wordlist.dsl` | Manx => wordlist
`ha-wordlist_wiki-wordlist.dsl` | Hausa => wordlist
`hak-wordlist_wiki-wordlist.dsl` | Hakka => wordlist
`haw-wordlist_wiki-wordlist.dsl` | Hawaiian => wordlist
`he-wordlist_wiki-wordlist.dsl` | Hebrew => wordlist
`hi-wordlist_wiki-wordlist.dsl` | Hindi => wordlist
`hr-wordlist_wiki-wordlist.dsl` | Croatian => wordlist
`ht-wordlist_wiki-wordlist.dsl` | Haitian => wordlist
`hu-wordlist_wiki-wordlist.dsl` | Hungarian => wordlist
`hy-wordlist_wiki-wordlist.dsl` | Armenian => wordlist
`id-wordlist_wiki-wordlist.dsl` | Indonesian => wordlist
`ig-wordlist_wiki-wordlist.dsl` | Igbo => wordlist
`is-wordlist_wiki-wordlist.dsl` | Icelandic => wordlist
`it-wordlist_wiki-wordlist.dsl` | Italian => wordlist
`iu-wordlist_wiki-wordlist.dsl` | Inuktitut => wordlist
`ja-wordlist_wiki-wordlist.dsl` | Japanese => wordlist
`jbo-wordlist_wiki-wordlist.dsl` | Lojban => wordlist
`jv-wordlist_wiki-wordlist.dsl` | Javanese => wordlist
`ka-wordlist_wiki-wordlist.dsl` | Georgian => wordlist
`kg-wordlist_wiki-wordlist.dsl` | Kongo => wordlist
`ki-wordlist_wiki-wordlist.dsl` | Kikuyu => wordlist
`kl-wordlist_wiki-wordlist.dsl` | Greenlandic => wordlist
`km-wordlist_wiki-wordlist.dsl` | Khmer => wordlist
`ko-wordlist_wiki-wordlist.dsl` | Korean => wordlist
`la-wordlist_wiki-wordlist.dsl` | Latin => wordlist
`lg-wordlist_wiki-wordlist.dsl` | Luganda => wordlist
`lo-wordlist_wiki-wordlist.dsl` | Lao => wordlist
`lt-wordlist_wiki-wordlist.dsl` | Lithuanian => wordlist
`lv-wordlist_wiki-wordlist.dsl` | Latvian => wordlist
`mg-wordlist_wiki-wordlist.dsl` | Malagasy => wordlist
`mi-wordlist_wiki-wordlist.dsl` | Maori => wordlist
`mn-wordlist_wiki-wordlist.dsl` | Mongolian => wordlist
`ms-wordlist_wiki-wordlist.dsl` | Malay => wordlist
`mt-wordlist_wiki-wordlist.dsl` | Maltese => wordlist
`nah-wordlist_wiki-wordlist.dsl` | Nahuatl => wordlist
`ne-wordlist_wiki-wordlist.dsl` | Nepali => wordlist
`nl-wordlist_wiki-wordlist.dsl` | Dutch => wordlist
`nn-wordlist_wiki-wordlist.dsl` | Norwegian (Nynorsk) => wordlist
`no-wordlist_wiki-wordlist.dsl` | Norwegian => wordlist
`nv-wordlist_wiki-wordlist.dsl` | Navajo => wordlist
`ny-wordlist_wiki-wordlist.dsl` | Chichewa => wordlist
`oc-wordlist_wiki-wordlist.dsl` | Occitan => wordlist
`pa-wordlist_wiki-wordlist.dsl` | Punjabi => wordlist
`pi-wordlist_wiki-wordlist.dsl` | Pali => wordlist
`pl-wordlist_wiki-wordlist.dsl` | Polish => wordlist
`ps-wordlist_wiki-wordlist.dsl` | Pashto => wordlist
`pt-wordlist_wiki-wordlist.dsl` | Portuguese => wordlist
`qu-wordlist_wiki-wordlist.dsl` | Quechua => wordlist
`ro-wordlist_wiki-wordlist.dsl` | Romanian => wordlist
`ru-wordlist_wiki-wordlist.dsl` | Russian => wordlist
`sa-wordlist_wiki-wordlist.dsl` | Sanskrit => wordlist
`se-wordlist_wiki-wordlist.dsl` | Northern Sami => wordlist
`sh-wordlist_wiki-wordlist.dsl` | Serbo-Croatian => wordlist
`sk-wordlist_wiki-wordlist.dsl` | Slovak => wordlist
`sl-wordlist_wiki-wordlist.dsl` | Slovenian => wordlist
`sn-wordlist_wiki-wordlist.dsl` | Shona => wordlist
`so-wordlist_wiki-wordlist.dsl` | Somali => wordlist
`sq-wordlist_wiki-wordlist.dsl` | Albanian => wordlist
`sr-wordlist_wiki-wordlist.dsl` | Serbian => wordlist
`sv-wordlist_wiki-wordlist.dsl` | Swedish => wordlist
`sw-wordlist_wiki-wordlist.dsl` | Kiswahili => wordlist
`ta-wordlist_wiki-wordlist.dsl` | Tamil => wordlist
`te-wordlist_wiki-wordlist.dsl` | Telugu => wordlist
`th-wordlist_wiki-wordlist.dsl` | Thai => wordlist
`tl-wordlist_wiki-wordlist.dsl` | Tagalog => wordlist
`tpi-wordlist_wiki-wordlist.dsl` | Tok Pisin => wordlist
`tr-wordlist_wiki-wordlist.dsl` | Turkish => wordlist
`ug-wordlist_wiki-wordlist.dsl` | Uyghur => wordlist
`uk-wordlist_wiki-wordlist.dsl` | Ukrainian => wordlist
`ur-wordlist_wiki-wordlist.dsl` | Urdu => wordlist
`vi-wordlist_wiki-wordlist.dsl` | Vietnamese => wordlist
`wo-wordlist_wiki-wordlist.dsl` | Wolof => wordlist
`wuu-wordlist_wiki-wordlist.dsl` | Wu => wordlist
`xh-wordlist_wiki-wordlist.dsl` | Xhosa => wordlist
`yi-wordlist_wiki-wordlist.dsl` | Yiddish => wordlist
`yo-wordlist_wiki-wordlist.dsl` | Yoruba => wordlist
`za-wordlist_wiki-wordlist.dsl` | Zhuang => wordlist
`zh-wordlist_wiki-wordlist.dsl` | Chinese (Mandarin) => wordlist
`zh_classical-wordlist_wiki-wordlist.dsl` | Classical Chinese => wordlist
`zh_min_nan-wordlist_wiki-wordlist.dsl` | Min Nan => wordlist
`zh_yue-wordlist_wiki-wordlist.dsl` | Cantonese => wordlist
`zu-wordlist_wiki-wordlist.dsl` | Zulu => wordlist

## Statistics

### Dictionary size

Language pair | # of entries
------------- | ------------
`af-wordlist_wiki-wordlist.dsl` | 33599
`am-wordlist_wiki-wordlist.dsl` | 11014
`ang-wordlist_wiki-wordlist.dsl` | 2977
`ar-wordlist_wiki-wordlist.dsl` | 446845
`arc-wordlist_wiki-wordlist.dsl` | 1829
`bg-wordlist_wiki-wordlist.dsl` | 225573
`bi-wordlist_wiki-wordlist.dsl` | 490
`bn-wordlist_wiki-wordlist.dsl` | 59121
`bo-wordlist_wiki-wordlist.dsl` | 2929
`br-wordlist_wiki-wordlist.dsl` | 49865
`bs-wordlist_wiki-wordlist.dsl` | 64229
`ca-wordlist_wiki-wordlist.dsl` | 438072
`cdo-wordlist_wiki-wordlist.dsl` | 2909
`chr-wordlist_wiki-wordlist.dsl` | 492
`chy-wordlist_wiki-wordlist.dsl` | 710
`cr-wordlist_wiki-wordlist.dsl` | 70
`cs-wordlist_wiki-wordlist.dsl` | 327321
`cy-wordlist_wiki-wordlist.dsl` | 52130
`da-wordlist_wiki-wordlist.dsl` | 196279
`de-wordlist_wiki-wordlist.dsl` | 1787961
`el-wordlist_wiki-wordlist.dsl` | 136650
`en-wordlist_wiki-wordlist.dsl` | 4798378
`eo-wordlist_wiki-wordlist.dsl` | 209308
`es-wordlist_wiki-wordlist.dsl` | 1346715
`et-wordlist_wiki-wordlist.dsl` | 124124
`eu-wordlist_wiki-wordlist.dsl` | 203027
`fa-wordlist_wiki-wordlist.dsl` | 744454
`ff-wordlist_wiki-wordlist.dsl` | 464
`fi-wordlist_wiki-wordlist.dsl` | 363265
`fr-wordlist_wiki-wordlist.dsl` | 1862431
`ga-wordlist_wiki-wordlist.dsl` | 35768
`gan-wordlist_wiki-wordlist.dsl` | 14253
`gd-wordlist_wiki-wordlist.dsl` | 15561
`gu-wordlist_wiki-wordlist.dsl` | 27615
`gv-wordlist_wiki-wordlist.dsl` | 4723
`ha-wordlist_wiki-wordlist.dsl` | 518
`hak-wordlist_wiki-wordlist.dsl` | 4123
`haw-wordlist_wiki-wordlist.dsl` | 2009
`he-wordlist_wiki-wordlist.dsl` | 209505
`hi-wordlist_wiki-wordlist.dsl` | 120411
`hr-wordlist_wiki-wordlist.dsl` | 139555
`ht-wordlist_wiki-wordlist.dsl` | 45669
`hu-wordlist_wiki-wordlist.dsl` | 323069
`hy-wordlist_wiki-wordlist.dsl` | 161719
`id-wordlist_wiki-wordlist.dsl` | 338477
`ig-wordlist_wiki-wordlist.dsl` | 1075
`is-wordlist_wiki-wordlist.dsl` | 39429
`it-wordlist_wiki-wordlist.dsl` | 1183116
`iu-wordlist_wiki-wordlist.dsl` | 383
`ja-wordlist_wiki-wordlist.dsl` | 951498
`jbo-wordlist_wiki-wordlist.dsl` | 1179
`jv-wordlist_wiki-wordlist.dsl` | 45722
`ka-wordlist_wiki-wordlist.dsl` | 118968
`kg-wordlist_wiki-wordlist.dsl` | 868
`ki-wordlist_wiki-wordlist.dsl` | 311
`kl-wordlist_wiki-wordlist.dsl` | 1839
`km-wordlist_wiki-wordlist.dsl` | 4713
`ko-wordlist_wiki-wordlist.dsl` | 446200
`la-wordlist_wiki-wordlist.dsl` | 111691
`lg-wordlist_wiki-wordlist.dsl` | 179
`lo-wordlist_wiki-wordlist.dsl` | 1913
`lt-wordlist_wiki-wordlist.dsl` | 173148
`lv-wordlist_wiki-wordlist.dsl` | 58016
`mg-wordlist_wiki-wordlist.dsl` | 77182
`mi-wordlist_wiki-wordlist.dsl` | 2579
`mn-wordlist_wiki-wordlist.dsl` | 18668
`ms-wordlist_wiki-wordlist.dsl` | 245936
`mt-wordlist_wiki-wordlist.dsl` | 2981
`nah-wordlist_wiki-wordlist.dsl` | 10519
`ne-wordlist_wiki-wordlist.dsl` | 24961
`nl-wordlist_wiki-wordlist.dsl` | 1812937
`nn-wordlist_wiki-wordlist.dsl` | 117294
`no-wordlist_wiki-wordlist.dsl` | 403749
`nv-wordlist_wiki-wordlist.dsl` | 3887
`ny-wordlist_wiki-wordlist.dsl` | 170
`oc-wordlist_wiki-wordlist.dsl` | 88788
`pa-wordlist_wiki-wordlist.dsl` | 14042
`pi-wordlist_wiki-wordlist.dsl` | 2759
`pl-wordlist_wiki-wordlist.dsl` | 1088821
`ps-wordlist_wiki-wordlist.dsl` | 5148
`pt-wordlist_wiki-wordlist.dsl` | 866567
`qu-wordlist_wiki-wordlist.dsl` | 18494
`ro-wordlist_wiki-wordlist.dsl` | 264609
`ru-wordlist_wiki-wordlist.dsl` | 1461243
`sa-wordlist_wiki-wordlist.dsl` | 12256
`se-wordlist_wiki-wordlist.dsl` | 7216
`sh-wordlist_wiki-wordlist.dsl` | 284238
`sk-wordlist_wiki-wordlist.dsl` | 269048
`sl-wordlist_wiki-wordlist.dsl` | 132095
`sn-wordlist_wiki-wordlist.dsl` | 1671
`so-wordlist_wiki-wordlist.dsl` | 2760
`sq-wordlist_wiki-wordlist.dsl` | 53553
`sr-wordlist_wiki-wordlist.dsl` | 351888
`sv-wordlist_wiki-wordlist.dsl` | 1954061
`sw-wordlist_wiki-wordlist.dsl` | 26694
`ta-wordlist_wiki-wordlist.dsl` | 80394
`te-wordlist_wiki-wordlist.dsl` | 63860
`th-wordlist_wiki-wordlist.dsl` | 134176
`tl-wordlist_wiki-wordlist.dsl` | 57983
`tpi-wordlist_wiki-wordlist.dsl` | 1336
`tr-wordlist_wiki-wordlist.dsl` | 247607
`ug-wordlist_wiki-wordlist.dsl` | 2596
`uk-wordlist_wiki-wordlist.dsl` | 638342
`ur-wordlist_wiki-wordlist.dsl` | 125182
`vi-wordlist_wiki-wordlist.dsl` | 1241500
`wo-wordlist_wiki-wordlist.dsl` | 1636
`wuu-wordlist_wiki-wordlist.dsl` | 5032
`xh-wordlist_wiki-wordlist.dsl` | 319
`yi-wordlist_wiki-wordlist.dsl` | 12575
`yo-wordlist_wiki-wordlist.dsl` | 35053
`za-wordlist_wiki-wordlist.dsl` | 808
`zh-wordlist_wiki-wordlist.dsl` | 804107
`zh_classical-wordlist_wiki-wordlist.dsl` | 3855
`zh_min_nan-wordlist_wiki-wordlist.dsl` | 14851
`zh_yue-wordlist_wiki-wordlist.dsl` | 32062
`zu-wordlist_wiki-wordlist.dsl` | 689

### Top ten dictionaries by number of entries

Language pair | # of entries
------------- | ------------
`en-wordlist` | 4798378
`sv-wordlist` | 1954061
`fr-wordlist` | 1862431
`nl-wordlist` | 1812937
`de-wordlist` | 1787961
`ru-wordlist` | 1461243
`es-wordlist` | 1346715
`vi-wordlist` | 1241500
`it-wordlist` | 1183116
`pl-wordlist` | 1088821

## License

According to the Wikidata website:

> All structured data from the main and property namespace is available under the Creative Commons CC0 License

The data in this repository is therefore made available under the same [Creative Commons CC0 License](https://creativecommons.org/publicdomain/zero/1.0/) as that used by the Wikidata project. All of the data has been derived from the Wikidata JSON format [database dumps](https://dumps.wikimedia.org/wikidatawiki/entities/).
