# Summary

The largest Turkish dependency treebank annotated in UD style. Created by the members of [TABILAB](http://http://tabilab.cmpe.boun.edu.tr/) from Boğaziçi University.

# Introduction

This is a newly introduced Turkish dependency treebank in the Universal Dependencies (UD) annotation style. The BOUN Treebank is created by the [TABILAB](http://http://tabilab.cmpe.boun.edu.tr/) and supported by the Scientific and Technological Research Council of Turkey (TÜBİTAK) under grant number 117E971.

The BOUN Treebank includes a total of 9,761 manually annotated sentences from various topics including biographical texts, national newspapers, instructional texts, popular culture articles, and essays. The texts are taken from the [Turkish National Corpus (TNC)](https://www.tnc.org.tr/).

The dependency relations in the BOUN Treebank is manually annotated in the UD framework. However, the morphological features and UPOS information are retrieved from the morphological parser of [Sak et al. (2011)](https://link.springer.com/article/10.1007/s10579-010-9128-6) and converted to UD morphology automatically using [our script](https://github.com/boun-tabi/UD_docs/blob/main/convert_sak_morp_to_ud_morp.py).

Currently, we are manually annotating the morphologial features, UPOS, and XPOS information.

# Versions

The current UD version is adjusted for the specifications of UD and the most recent UD feature, UPOS, and the feature-value-upos combinations. We masked the morphological features that violated feature-value-upos combinations changes that are introduced 10 hours before the data freeze. You can find unaltered version of the BOUN Treebank [here](https://github.com/boun-tabi/UD_Turkish-BOUN).


# Acknowledgments

We are immensely grateful to Prof. Yeşim Aksan and the other members of the Turkish National Corpus Team for their tremendous help in providing us with sentences from the Turkish National Corpus.

## References

For now, you can use arXiv reference for this treebank:
```
@misc{trk2020resources,
    title={Resources for Turkish Dependency Parsing: Introducing the BOUN Treebank and the BoAT Annotation Tool},
    author={Utku T{\”{u}}rk and
    Furkan Atmaca and
    {\c{S}aziye Bet{\"{u}}l {\"{O}}zate{\c{s}} and
    G{\"{o}}zde Berk and
    Seyyit Talha Bedir and
    Abdullatif K{\"{o}}ksal and
    Balk{\i}z {\"{O}}zt{\"{u}}rk Ba{\c{s}}aran and
    Tunga G{\"{u}}ng{\"{o}}r and
    Arzucan {\"{O}}zg{\"{u}}r},
    year={2020},
    eprint={2002.10416},
    archivePrefix={arXiv},
    primaryClass={cs.CL}
}
```

# Changelog

* 2021-05-15 v2.8
  * Fixed many newly discovered validation errors.
  * Made the Turkish treebanks converge to more harmonized annotation.
* 2020-11-15 v2.7
  * Initial release in Universal Dependencies.

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.7
License: CC BY-SA 4.0
Includes text: yes
Genre: nonfiction news
Lemmas: automatic with corrections
UPOS: automatic with corrections
XPOS: automatic with corrections
Features: automatic with corrections
Relations: manual native
Contributors: Türk, Utku; Atmaca, Furkan; Özateş, Şaziye Betül; Berk, Gözde; Bedir, Seyyit Talha; Köksal, Abdullatif; Öztürk Başaran, Balkız; Güngör, Tunga; Özgür, Arzucan
Contributing: elsewhere
Contact: saziye.bilgin@boun.edu.tr
===============================================================================
</pre>
