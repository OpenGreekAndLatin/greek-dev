greek-dev
==========

A collection of OCR'd and machine-corrected Greek texts. This base repository contains Git submodules for the different works and an inventory with full names and meta data for each submodule.

The current state is: *to be manually corrected*. The TOC is ordered according to priority.

===============

##### TOC:

1. [Libanius (1903-63). Opera. Recensuit Richardus Foerster 1, pt. 1](https://www.github.com/OpenGreekAndLatin/2013-08-15-07-51_operarecensuitri01libauoft_jp2_Kaibel_Round_4_3)
* [Libanius (1903-63). Opera. Recensuit Richardus Foerster 1, pt.2](https://www.github.com/OpenGreekAndLatin/2013-08-18-13-55_pt2operarecensu01libauoft_jp2_Kaibel_Round_4_3)
* [Libanius (1903-63). Opera. Recensuit Richardus Foerster 2](https://www.github.com/OpenGreekAndLatin/2013-08-23-09-17_operarecensuitri02libauoft_jp2_Kaibel_Round_4_3)
* [Libanius (1903-63). Opera. Recensuit Richardus Foerster 3](https://www.github.com/OpenGreekAndLatin/2013-08-23-09-15_operarecensuitri03libauoft_jp2_Kaibel_Round_4_3)
* [Libanius et al. (1903). Libanii Opera; 4](https://www.github.com/OpenGreekAndLatin/2013-07-30-08-23_libaniiopera01libagoog_jp2_Kaibel_Round_4_2)
* [Libanius (1903-63). Opera. Recensuit Richardus Foerster 5](https://www.github.com/OpenGreekAndLatin/2013-08-26-14-21_operarecensuitri05libauoft_jp2_Kaibel_Round_4_3)
* [Libanius (1903-63). Opera. Recensuit Richardus Foerster 6](https://www.github.com/OpenGreekAndLatin/2013-08-26-14-21_operarecensuitri06libauoft_jp2_Kaibel_Round_4_3)
* [Libanius (1903-63). Opera. Recensuit Richardus Foerster 7](https://www.github.com/OpenGreekAndLatin/2013-08-23-09-14_operarecensuitri07libauoft_jp2_Kaibel_Round_4_3)
* [Libanius (1903-63). Opera. Recensuit Richardus Foerster 9](https://www.github.com/OpenGreekAndLatin/2013-08-23-09-15_operarecensuitri09libauoft_jp2_Kaibel_Round_4_3)
* [Libanius (1903-63). Opera. Recensuit Richardus Foerster 10](https://www.github.com/OpenGreekAndLatin/2013-07-26-07-41_operarecensuitri10libauoft_jp2_Kaibel_Round_4)
* [Libanios, Eberhard Richtsteig, Richardus Foerster (1906). Libanii Opera;](https://www.github.com/OpenGreekAndLatin/2013-07-26-16-29_libaniiopera02foergoog_jp2_Kaibel_Round_4)
* [Libanios, Eberhard Richtsteig, Richardus Foerster (1903). Libanii Opera;](https://www.github.com/OpenGreekAndLatin/2013-07-26-16-41_libaniiopera00foergoog_jp2_Kaibel_Round_4)
* [Athenaeus, of Naucratis et al. (1887). Athenaei Navcratitae Dipnosophistarvm libri 15, recensvit Georgivs Kaibel 1](https://www.github.com/OpenGreekAndLatin/2013-10-05-15-44_athenaeinavcrati01atheuoft_jp2_Kaibel_Round_4_3)
* [Athenaeus, of Naucratis et al. (1887). Athenaei Navcratitae Dipnosophistarvm libri 15, recensvit Georgivs Kaibel 2](https://www.github.com/OpenGreekAndLatin/2013-10-05-15-45_athenaeinavcrati02atheuoft_jp2_Kaibel_Round_4_3)
* [Athenaeus, of Naucratis et al. (1887). Athenaei Navcratitae Dipnosophistarvm libri 15, recensvit Georgivs Kaibel 3](https://www.github.com/OpenGreekAndLatin/2013-08-17-11-05_athenaeinavcrati03atheuoft_jp2_Kaibel_Round_4_3)
* [Akademie der Wissenschaften, Berlin (1882-1909). Commentaria in Aristotelem graeca. Edita consilio et auctoritate Academiae litterarum regiae borussicae 09](https://www.github.com/OpenGreekAndLatin/2013-11-24-17-53_commentariaina09akaduoft_jp2_Philo_Gamera_34)
* [Philo, of Alexandria (1896). Opera quae supersunt; 04](https://www.github.com/OpenGreekAndLatin/2013-07-18-09-02_operaquaesupersu04phil_jp2_Philo_Gamera_34)
* [Gloag, Paton J. (Paton James), 1823-1906 (1870). A critical and exegetical commentary on the Acts of the Apostles 2](https://www.github.com/OpenGreekAndLatin/2013-10-24-14-51_acriticalandexe02gloauoft_jp2_OCT7_acriticalandexe02gloauoft)
* [Migne, J.-P. (Jacques-Paul), 1800-1875 (1857). Patrologiae cursus completus... Series graeca... Accurante J.P. Migne 16, pt.3](https://www.github.com/OpenGreekAndLatin/2013-10-22-08-36_pt3patrologiaecur16mign_jp2_Migne4)

Currently w/o inventory:

3.  Libanius (1903-63). Opera. Recensuit Richardus Foerster 2
13. Athenaeus, of Naucratis et al. (1887). Athenaei Navcratitae Dipnosophistarvm libri 15, recensvit Georgivs Kaibel 1

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