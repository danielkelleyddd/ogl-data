ogl-data
========

hOCR results from the Open Greek And Latin Project

This is a test repo used to communicate our data formats to third parties.

===============

##### TOC:

1. [Akademie der Wissenschaften, Berlin (1882-1909). Commentaria in Aristotelem graeca. Edita consilio et auctoritate Academiae litterarum regiae borussicae 09](../../tree/master/2013-11-24-17-53_commentariaina09akaduoft_jp2_Philo_Gamera_34)
* [Philo, of Alexandria (1896). Opera quae supersunt; 04](../../tree/master/2013-07-18-09-02_operaquaesupersu04phil_jp2_Philo_Gamera_34)
* [Gloag, Paton J. (Paton James), 1823-1906 (1870). A critical and exegetical commentary on the Acts of the Apostles 2](../../tree/master/2013-10-24-14-51_acriticalandexe02gloauoft_jp2_OCT7_acriticalandexe02gloauoft)
* [Migne, J.-P. (Jacques-Paul), 1800-1875 (1857). Patrologiae cursus completus... Series graeca... Accurante J.P. Migne 16, pt.3](../../tree/master/2013-10-22-08-36_pt3patrologiaecur16mign_jp2_Migne4)

================
##### Legend for NLP attributes:

**1.00** WORD: spell-checked word (e.g. ψυχή)

**0.99** CORRWORD: word provided by alignment with another edition

**0.98** UCWORD: word that is correctly spell-checked only in upper-case (i.e. accents can be wrong - e.g. αληθεία --> ΑΛΗΘΕΙΑ)

**0.97** SYLLABICSEQ: well-formed syllabic sequence, not found by the previous spellcheckers (e.g. καταλάβοκος)

**0.96** CHARSEQ: sequence of Greek characters, which is not a well-formed syllabic sequence (e.g. γδτσαλλ)

**0.95** BADONE: single bad character (e.g. ^) 

**0.94** BADMANY: random sequence of Greek and Latin characters (e.g. αbγm)

**0.90, 0.89, 0.88, 0.87, 0.86** etc.: suggestions from the spellchecker, in the order provided by the spellchecker

**0.70** same meaning as **0.99** (CORRWORD), after automatic correction

**0.10** Latin character sequence, which usually is a correct Latin (or English) word, but which is not spell-checked.