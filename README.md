
# *Alignment collection name*

<!-- Replace the title of the repository -->
*Short description of the collections*.

## Content summary
<!-- 1. Update the number of segments and files. 2. Add or delete languages as needed. 3. Update the number of segments for each language. -->

- **123** Tibetan segments 
- **123** files 

| Languages: |   bo-en   |   bo-es  |   bo-fr  |   bo-de  |  bo-it |  bo-nl |   bo-zh  |  bo-pt |
|:------------:|:------:|:-----:|:-----:|:-----:|:---:|:---:|:-----:|:---:|
| Segments:     | 1 | 2 | 3| 4 | 5 | 6 | 7 | 8 |

<!-- Update the names and URLs of sources -->

- Included texts: See the collection's [catalog](/text-pairs-catalog)
- Sources: [Source 1](link), [Source 2](link), [Source 3](link), ...

## File structure

This collection presents the same data in two views: text pairs and TMs.

### View 1 - Text pairs

#### What it is

[Plain text pairs](https://github.com/OpenPecha-Data/C0A2DD042/tree/main/text-pairs) in .txt format ([see detailed catalog](https://github.com/OpenPecha-Data/C0A2DD042/blob/main/text-pairs-catalog.csv)).

<details >
<summary>More</summary>

Text pairs consist of matching sets of `.txt` files. They include a file containing a Tibetan text with one chunk of text per line and one or more `.txt` files of translations of the text into other languages. Translation files are also split into lines to correspond to the line breaks in the Tibetan file.

Titles of any file can be found on line 1 of the file or by searching for a file's identifying number (e.g. A00023033) in the corpus's [text pairs catalog](https://github.com/OpenPecha-Data/C0A2DD042/blob/main/text-pairs-catalog.csv).

Text pairs or groups share the same identifying number and differ only in the ending language tag.

Example:
- A00023033-bo.txt
- A00023033-en.txt
- A00023033-fr.txt

As stated above, these files are aligned by line to match the Tibetan version. 

Example:
Tibetan text
```
1 ༄༅། །འཆི་མེད་འཕགས་མའི་སྙིང་ཐིག་གི་བརྒྱུད་པའི་གསོལ་འདེབས་ཚེ་དབང་བཅུད་འཛིན་ཞེས་བྱ་བ་བཞུགས་སོ། །
2 རང་བྱུང་རྟག་པའི་རྡོ་རྗེ་ཚེ་དཔག་མེད། །
3 འཆི་བདག་བདུད་འཇོམས་གཙུག་ཏོར་རྣམ་པར་རྒྱལ། །
```
English text
```
1 The Fount of Longevity Chimé Phakmé Nyingtik Lineage Prayer
2 Amitāyus, Boundless Life, natural, everlasting and indestructible,
3 Uṣṇīṣa-Vijayā, Victorious Conqueror of māra , Lord of Death,
```
French text
```
1 La Fontaine de longévité La prière à la lignée de Chimé p'akmé nyingthik
2 Existant par lui-même et éternel, indestructible Amitāyus,
3 Celle qui triomphe du démon Seigneur de la mort, Uṣṇīṣa Vijayā,
```

</details>

#### Who it's for

View 1 is intended for developers who want to train a translation model.

**How to use it**

This data can be fed into machine translation training pipelines such as using this and that.

### View 2 - TMs

#### What it is

[TM files](https://github.com/OpenPecha-Data/C0A2DD042/tree/main/tmx) in .tmx format ([see detailed catalog](https://github.com/OpenPecha-Data/C0A2DD042/blob/main/tmx-catalog.csv)). 

> **Note**: If you need a different format, check the <a href="#how-to-get-help">how to get help</a> section below.

#### Who it's for

View 2 is intended for developers who want to train a translation model.

**How to use it**

This data can be fed into machine translation training pipelines such as using this and that.



## Detailed content description

<!-- Update all info. Add or remove sections to match the number of sources. -->

### Source 1
| Source URL: | https:source1.com/ |
| --- | --- |
|Pairs: | 123 | 
|Files: | 123 |
|Accessed on: |  |
|Crawler: | [name](link) |
|Parser: | [name](link) |
|Layers: | **Base** + `Segments` |
|Included texts: |[See text pairs catalog](/text-pairs-catalog.csv)|

| Languages: |   bo-en   |   bo-es  |   bo-fr  |   bo-de  |  bo-it |  bo-nl |   bo-zh  |  bo-pt |
|:------------:|:------:|:-----:|:-----:|:-----:|:---:|:---:|:-----:|:---:|
| Segments:     |  |  |  |  |  |  |  |  |

### Source 2
| Source URL: | https:source1.com/ |
| --- | --- |
|Pairs: | 123 | 
|Files: | 123 |
|Accessed on: |  |
|Crawler: | [name](link) |
|Parser: | [name](link) |
|Layers: | **Base** + `Segments` |
|Included texts: |[See text pairs catalog](/text-pairs-catalog.csv)|

| Languages: |   bo-en   |   bo-es  |   bo-fr  |   bo-de  |  bo-it |  bo-nl |   bo-zh  |  bo-pt |
|:------------:|:------:|:-----:|:-----:|:-----:|:---:|:---:|:-----:|:---:|
| Segments:     |  |  |  |  |  |  |  |  |




## Questions about this collection?
* Email us at openpecha[at]gmail.com.
* Join our [Discord](https://discord.com/invite/7GFpPFSTeA).
* File an issue.

## Acknowledgments

Thanks to the following organizations for providing data for this collection:

<!-- Delete organizations that are part of this collection -->

![BDRC logo](https://user-images.githubusercontent.com/51434640/194739598-8a630a40-b83e-46cd-9f52-3f746db9864f.png)

![Lotsawa House logo](https://user-images.githubusercontent.com/51434640/213625878-94b44c11-87f6-4fab-82d7-2a77d9e32547.png)

## Terms of use

This collection is provided by OpenPecha under the [CC0 Public Domain Dedication](/LICENSE.md).
