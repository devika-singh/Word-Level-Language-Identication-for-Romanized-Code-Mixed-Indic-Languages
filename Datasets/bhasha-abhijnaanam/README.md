---
license: cc0-1.0

annotations_creators: []
language_creators:
- crowdsourced
- expert-generated
- machine-generated
- found
- other
language:
- asm
- ben
- brx
- guj
- hin
- kan
- kas
- kok
- mai
- mal
- mar
- mni
- nep
- ori
- pan
- san
- sat
- sid
- snd
- tam
- tel
- urd
multilinguality:
- multilingual
pretty_name: Bhasha-Abhijnaanam
size_categories: []
source_datasets:
- original
task_categories:
- text-generation
task_ids: []
---

# Dataset Card for Aksharantar

## Table of Contents
- [Table of Contents](#table-of-contents)
- [Dataset Description](#dataset-description)
  - [Dataset Summary](#dataset-summary)
  - [Supported Tasks and Leaderboards](#supported-tasks-and-leaderboards)
  - [Languages](#languages)
- [Dataset Structure](#dataset-structure)
  - [Data Instances](#data-instances)
  - [Data Fields](#data-fields)
  - [Data Splits](#data-splits)
- [Dataset Creation](#dataset-creation)
  - [Curation Rationale](#curation-rationale)
  - [Source Data](#source-data)
  - [Annotations](#annotations)
  - [Personal and Sensitive Information](#personal-and-sensitive-information)
- [Considerations for Using the Data](#considerations-for-using-the-data)
  - [Social Impact of Dataset](#social-impact-of-dataset)
  - [Discussion of Biases](#discussion-of-biases)
  - [Other Known Limitations](#other-known-limitations)
- [Additional Information](#additional-information)
  - [Dataset Curators](#dataset-curators)
  - [Licensing Information](#licensing-information)
  - [Citation Information](#citation-information)
  - [Contributions](#contributions)

## Dataset Description

- **Homepage:** 
- **Repository:** https://github.com/AI4Bharat/IndicLID
- **Paper:** [Bhasha-Abhijnaanam: Native-script and romanized Language Identification for 22 Indic languages](https://arxiv.org/abs/2305.15814)
- **Leaderboard:**
- **Point of Contact:**

### Dataset Summary

Bhasha-Abhijnaanam is a language identification test set for native-script as well as Romanized text which spans 22 Indic languages.

### Supported Tasks and Leaderboards

[More Information Needed]

### Languages

| <!-- -->  	 | <!-- --> 	  | <!-- --> 	   | <!-- -->	     | <!-- -->       | <!-- -->      |
| -------------- | -------------- | -------------- | --------------- | -------------- | ------------- |
| Assamese (asm) | Hindi (hin) 	  | Maithili (mai) | Nepali (nep)   | Sanskrit (san)  | Tamil (tam)   |
| Bengali (ben)  | Kannada (kan)  | Malayalam (mal)| Oriya (ori)    | Santali (sat)   | Telugu (tel)  | 
| Bodo(brx)      | Kashmiri (kas) | Manipuri (mni) | Punjabi (pan)  | Sindhi (snd)    | Urdu (urd)    |
| Gujarati (guj) | Konkani (kok)  | Marathi (mar) 


## Dataset Structure


### Data Instances

```
A random sample from Hindi (hin) Test dataset.
{
    "unique_identifier": "hin1", 
    "native sentence": "",
    "romanized sentence": "",
    "language": "Hindi", 
    "script": "Devanagari", 
    "source": "Dakshina",
}
```

### Data Fields

- `unique_identifier` (string): 3-letter language code followed by a unique number in Test set.
- `native sentence` (string): A sentence in Indic language.
- `romanized sentence` (string): Transliteration of native sentence in English (Romanized sentence).
- `language` (string): Language of native sentence.
- `script` (string): Script in which native sentence is written.
- `source` (string): Source of the data.

  For created data sources, depending on the destination/sampling method of a pair in a language, it will be one of:
  - Dakshina Dataset
  - Flores-200
  - Manually Romanized
  - Manually generated
  
  
  
### Data Splits

| Subset | asm | ben | brx | guj | hin | kan | kas (Perso-Arabic) | kas (Devanagari) | kok | mai | mal | mni (Bengali) | mni (Meetei Mayek) | mar | nep | ori | pan | san | sid | tam | tel | urd |
|:------:|:---:|:---:|:---:|:---:|:---:|:---:|:------------------:|:----------------:|:---:|:---:|:---:|:-------------:|:------------------:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Native | 1012 | 5606 | 1500 | 5797 | 5617 | 5859 | 2511 | 1012 | 1500 | 2512 | 5628 | 1012 | 1500 | 5611 | 2512 | 1012 | 5776 | 2510 | 2512 | 5893 | 5779 | 5751 | 6883 |
| Romanized | 512 | 4595 | 433 | 4785 | 4606 | 4848 | 450 | 0 | 444 | 439 | 4617 | 0 | 442 | 4603 | 423 | 512 | 4765 | 448 | 0 | 4881 | 4767 | 4741 | 4371 |


## Dataset Creation

Information in the paper. [Bhasha-Abhijnaanam: Native-script and romanized Language Identification for 22 Indic languages](https://arxiv.org/abs/2305.15814)

### Curation Rationale

[More Information Needed]

### Source Data

#### Initial Data Collection and Normalization

Information in the paper. [Bhasha-Abhijnaanam: Native-script and romanized Language Identification for 22 Indic languages](https://arxiv.org/abs/2305.15814)

#### Who are the source language producers?

[More Information Needed]

### Annotations

Information in the paper. [Bhasha-Abhijnaanam: Native-script and romanized Language Identification for 22 Indic languages](https://arxiv.org/abs/2305.15814)

#### Who are the annotators?

Information in the paper. [Bhasha-Abhijnaanam: Native-script and romanized Language Identification for 22 Indic languages](https://arxiv.org/abs/2305.15814)


## Considerations for Using the Data

### Social Impact of Dataset

[More Information Needed]

### Discussion of Biases

[More Information Needed]

### Other Known Limitations

[More Information Needed]

## Additional Information

### Dataset Curators

[More Information Needed]

### Licensing Information

<!-- <a rel="license" float="left" href="http://creativecommons.org/publicdomain/zero/1.0/">
  <img src="https://licensebuttons.net/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" width="100" />
  <img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/png/by.png" style="border-style: none;" alt="CC-BY" width="100" href="http://creativecommons.org/publicdomain/zero/1.0/"/>
</a>
<br/> -->


This data is released under the following licensing scheme:

- Manually collected data: Released under CC0 license. 


**CC0 License Statement**

<a rel="license" float="left" href="https://creativecommons.org/about/cclicenses/">
  <img src="https://licensebuttons.net/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" width="100"/>
</a>

<br>
<br>

- We do not own any of the text from which this data has been extracted.
- We license the actual packaging of manually collected data under the [Creative Commons CC0 license (“no rights reserved”)](http://creativecommons.org/publicdomain/zero/1.0).
- To the extent possible under law, <a rel="dct:publisher" href="https://indicnlp.ai4bharat.org/"> <span property="dct:title">AI4Bharat</span></a> has waived all copyright and related or neighboring rights to <span property="dct:title">Aksharantar</span> manually collected data and existing sources.
- This work is published from: India.

### Citation Information

```
@misc{madhani2023bhashaabhijnaanam,
      title={Bhasha-Abhijnaanam: Native-script and romanized Language Identification for 22 Indic languages}, 
      author={Yash Madhani and Mitesh M. Khapra and Anoop Kunchukuttan},
      year={2023},
      eprint={2305.15814},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```

### Contributions

---
