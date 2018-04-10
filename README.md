# Hate Speech Twitter Datasets
This repository contains a collection of more than 28K hate speech tweets. All tweets in this repository were categorized and annotated as hate speech tweets using various methods detailed in our papers - 
* Mai ElSherief, Shirin Nilizadeh, Dana Nguyen, Giovanni Vigna and Elizabeth Belding, "Peer to Peer Hate: Hate Speech Instigators and Their Targets", International AAAI Conference on Web and Social Media (ICWSM), June 2018.
* Mai ElSherief, Vivek Kulkarni, Dana Nguyen, William Wang and Elizabeth Belding, "Hate Lingo: A Target-based Linguistic Analysis of Hate Speech in Social Media", International AAAI Conference on Web and Social Media (ICWSM), June 2018. 

## Datasets
Our hate speech Twitter datasets are available as CSV files. The files are named by their "hate" keyword and hate speech category (Class, Sexual Orientation (sexorient), Disability, Gender, Ethnicity (ethn), Nationality (nation), Religion (rel), Archaic). The collection of the 51 keywords that we annotated as most likely to contain hate speech from the Hatebase repository (https://www.hatebase.org/) can be found in the text file, `hate_keywords.txt`.  All the Twitter datasets contain Twitter IDs that can be queried and fetched using the Twitter API. The Twitter key-phrase based hate tweets are located in the folder `twitter_key_phrase_based_datasets`. The Twitter hashtag-based hate tweets are located in the folder `twitter_hashtag_based_datasets`.

We also provide a dataset that we annotated and classified into hate speech categories from the No Hate Soeech Movement website (https://www.nohatespeechmovement.org/hate-speech-watch) in the folder `nhsm_datasets`. These datasets contain tweets available in text files. The files are named by their hate speech categories.

The following public hate speech datasets that were also used in our paper, "Hate Lingo: A Target-based Linguistic Analysis of Hate Speech in Social Media" included:
* Waseem and Hovy, "Hate Speech Twitter annotations": https://github.com/zeerakw/hatespeech
* Davidson and Warmsley and Macy and Weber, "Automated Hate Speech Detection and the Problem of Offensive Language": https://github.com/t-davidson/hate-speech-and-offensive-language

## Citing our Repository
**If  `hate_keywords.txt` and/or `twitter_key_phrase_based_datasets` are used in any work, please cite both of our papers by using the following:**
~~~
@inproceedings{peertopeerhate,
  title = {Peer to Peer Hate: Hate Instigators and Their Targets},
  author = {ElSherief, Mai and Nilizadeh, Shirin and Nguyen, Dana and Vigna, Giovanni, and Belding, Elizabeth}, 
  booktitle = {Proceedings of the 12th International AAAI Conference on Web and Social Media},
  series = {ICWSM '18},
  year = {2018},
  location = {Stanford, California},
  }
~~~
~~~
@inproceedings{hatelingo,
  title = {Hate Lingo: A Target-based Linguistic Analysis of Hate Speech in Social Media},
  author = {ElSherief, Mai and Kulkarni, Vivek and Nguyen, Dana and Wang, William Y., and Belding, Elizabeth}, 
  booktitle = {Proceedings of the 12th International AAAI Conference on Web and Social Media},
  series = {ICWSM '18},
  year = {2018},
  location = {Stanford, California}
  }
~~~
**If `twitter_hashtag_based_datasets` and/or `nhsm_datasets` are used in any work, please cite our paper by using the following:**
~~~
@inproceedings{hatelingo,
  title = {Hate Lingo: A Target-based Linguistic Analysis of Hate Speech in Social Media},
  author = {ElSherief, Mai and Kulkarni, Vivek and Nguyen, Dana and Wang, William Y., and Belding, Elizabeth}, 
  booktitle = {Proceedings of the 12th International AAAI Conference on Web and Social Media},
  series = {ICWSM '18},
  year = {2018},
  location = {Stanford, California}
  }
~~~

We would also appreciate it if you could let us know how you plan to use these datasets in your work by filling out this short [form](https://docs.google.com/forms/d/e/1FAIpQLSdim89217NRlQHFY7umd11Ty_qRoyfPYbsQ0itoLHugYZtSgQ/viewform).

 ## Authors
"Peer to Peer Hate: Hate Speech Instigators and Their Targets"
* Mai ElSherief, University of California - Santa Barbara, mayelsherif at ucsb dot edu
* Shirin Nilizadeh, Carnegie Mellon Univeristy - Silicon Valley, shirin dot nilizadeh at sv dot cmu dot edu
* Dana Nguyen, University of California - Santa Barbara, dananguyen at ucsb dot edu
* Giovanni Vigna, University of California - Santa Barbara, vigna at ucsb dot edu
* Elizabeth Belding, University of California - Santa Barbara, ebelding at ucsb dot edu

"Hate Lingo: A Target-based Linguistic Analysis of Hate Speech in Social Media"
* Mai ElSherief, University of California - Santa Barbara, mayelsherif at ucsb dot edu
* Vivek Kulkarni, University of California - Santa Barbara, vvkulkarni at ucsb dot edu
* Dana Nguyen, University of California - Santa Barbara, dananguyen at ucsb dot edu
* William Y. Wang, University of California - Santa Barbara, william at ucsb dot edu
* Elizabeth Belding, University of California - Santa Barbara, ebelding at ucsb dot edu


