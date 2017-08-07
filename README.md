# POS-tagged AncientGreek texts (v1.2.0)

This repository contains the POS-tagged (CTSized) texts of the Ancient Greek Literature contained in the two repositories:

* https://github.com/PerseusDL/canonical-greekLit/releases/tag/0.0.236
* https://github.com/OpenGreekAndLatin/First1KGreek/releases/tag/1.1.1802

The POS-tagging has been generated (completely) automatically by using the MATE tagger, which has been trained on Perseus treebank data:

* https://perseusdl.github.io/treebank_data/

The tagger achieved an accuracy of 88%. More details can be found in the article:

* Celano, Giuseppe G. A, Gregory Crane, Saeed Majidi. 2016. Part of Speech Tagging for Ancient Greek. Open Linguistics 2:393–399. https://doi.org/10.1515/opli-2016-0020

# Changes from previous releases
Release 1.2.0:
* New Texts have been added. Tokenization now detects capital letter abbreviations such as ΑΠΟΛ.

Release 1.1.0:
* Correction to the cts-urn structure by considering the elements seg and p (currently div, seg, p, and l are considered)

# Cite
Cite the following work thus:

* Giuseppe G. A. Celano. (2017). POS-tagged Ancient Greek texts (v1.2.0) [Data set]. 

# License
<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
