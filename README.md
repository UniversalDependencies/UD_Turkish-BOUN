# Summary

The Turkish dependency treebank annotated in UD style. Created by the members of [TABILAB](http://http://tabilab.cmpe.boun.edu.tr/) from Boğaziçi University.

# Introduction

This is a newly introduced Turkish dependency treebank in the Universal Dependencies (UD) annotation style. The BOUN Treebank is created by the [TABILAB](http://http://tabilab.cmpe.boun.edu.tr/) and supported by the Scientific and Technological Research Council of Turkey (TÜBİTAK) under grant number 117E971.

The BOUN Treebank includes a total of 9,761 manually annotated sentences from various topics including biographical texts, national newspapers, instructional texts, popular culture articles, and essays. The texts are taken from the [Turkish National Corpus (TNC)](https://www.tnc.org.tr/).

The dependency relations in the BOUN Treebank is manually annotated in the UD framework. The morphological features and UPOS information are first retrieved from the morphological parser of [Sak et al. (2011)](https://link.springer.com/article/10.1007/s10579-010-9128-6) and converted to UD morphology automatically using [our script](https://github.com/boun-tabi/UD_docs/blob/main/convert_sak_morp_to_ud_morp.py). The morphological features, UPOS tags, XPOS tags, and lemma forms are then manually corrected in a systematic way.


# Versions

The current UD version is adjusted for the specifications of UD and the most recent UD feature, UPOS, and the feature-value-upos combinations. Two new dependency relations (dep:der and discourse:q), new lemma forms for copula (y, i, and null), and new MISC functions (DerivedFrom=, nullcop=3p, and nullcop=3s) are introduced.  


# Acknowledgments

We are immensely grateful to Prof. Yeşim Aksan and the other members of the Turkish National Corpus Team for their tremendous help in providing us with sentences from the Turkish National Corpus.

## References

You can use the following arXiv reference for v2.11:

```
@article{marcsan2022enhancements,
  title={Enhancements to the BOUN Treebank Reflecting the Agglutinative Nature of Turkish},
  author={Mar{\c{s}}an, B{\"u}{\c{s}}ra and Akkurt, Salih Furkan and {\c{S}}en, Muhammet and G{\"u}rb{\"u}z, Merve and G{\"u}ng{\"o}r, Onur and {\"O}zate{\c{s}}, {\c{S}}aziye Bet{\"u}l and {\"U}sk{\"u}darl{\i}, Suzan and {\"O}zg{\"u}r, Arzucan and G{\"u}ng{\"o}r, Tunga and {\"O}zt{\"u}rk, Balk{\i}z},
  journal={arXiv preprint arXiv:2207.11782},
  year={2022}
}
```

You can use the following arXiv reference for the previous versions of this treebank:

```
@article{TurkEtAl2022,
  title = {Resources for {{Turkish}} Dependency Parsing: Introducing the {{BOUN Treebank}} and the {{BoAT}} Annotation Tool},
  author = {T{\"u}rk, Utku and Atmaca, Furkan and {\"O}zate{\c s}, {\c S}aziye Bet{\"u}l and Berk, G{\"o}zde and Bedir, Seyyit Talha and K{\"o}ksal, Abdullatif and Ba{\c s}aran, Balk{\i}z {\"O}zt{\"u}rk and G{\"u}ng{\"o}r, Tunga and {\"O}zg{\"u}r, Arzucan},
  year = {2022},
  month = mar,
  journal = {Language Resources and Evaluation},
  volume = {56},
  number = {1},
  pages = {259--307},
  issn = {1574-0218},
  doi = {10.1007/s10579-021-09558-0}
}

```

# Changelog

* 2022-11-02 v2.11
  * Fixed validation errors.
  * Introduced new dependency relations.
  * Manually corrected lemma forms, morphological features, UPOS and XPOS tags.
  * Fixed dependency annotations for coherency and accuracy.
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
Lemmas: manual native
UPOS: manual native
XPOS: manual native
Features: manual native
Relations: manual native
Contributors: Marşan, Büşra; Akkurt, Salih Furkan; Türk, Utku; Atmaca, Furkan; Özateş, Şaziye Betül; Berk, Gözde; Bedir, Seyyit Talha; Köksal, Abdullatif; Öztürk Başaran, Balkız; Güngör, Tunga; Özgür, Arzucan
Contributing: elsewhere
Contact: busra.marsan@boun.edu.tr or saziye.bilgin@boun.edu.tr
===============================================================================
</pre>
