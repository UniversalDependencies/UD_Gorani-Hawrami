# Summary

UD Gorani-Hawrami is a preliminary conversion of one spoken Hewramî narrative, ZB (_zaroɫe û bizê_, “The baby and the goat”), from Masoud Mohammadirad’s published Hewramî recordings and glossed text.

# Introduction

This is the first Universal Dependencies treebank of Gorani (ISO 639-3: `hac`), in the Hawrami / Hewramî variety. The current release contains a single complete oral narrative, kept in source order rather than shuffled. Sentence ids `hwr-rec-zb-001`–`hwr-rec-zb-061` correspond one-to-one to source annotation units ZB.1–ZB.61. Those units are intonation units from the source recording, so one UD sentence may contain more than one clause.

The underlying text and interlinear morphology come from:

* Masoud Mohammadirad, _A corpus of Hewramî recordings, time-aligned with transcription and translation_ (2025), Zenodo, [10.5281/zenodo.15419952](https://doi.org/10.5281/zenodo.15419952). Audio timing follows the ELAN alignment in that archive. The archive is not redistributed here.
* Masoud Mohammadirad, _Echoes of the past: Hewramî narratives_ (Language Science Press, 2025), [10.5281/zenodo.17140764](https://doi.org/10.5281/zenodo.17140764). This published glossed edition is the canonical transcription and the source of the English translation. It is licensed CC BY 4.0.

Persian translations (`text_fa`) were added in the [Hawrami corpus](https://github.com/zaniarghaderi/hawrami-corpus) project and still need human review. Lemmas and UD tags are mapped from the published interlinear glossing and glossary. Dependency trees are a machine-assisted first conversion. The CoNLL-U comments mark the layer as preliminary silver data; it is not gold annotation.

The treebank has 61 sentences and about 520 words, below the threshold for a train/dev/test split. All sentences are in `hac_hawrami-ud-test.conllu`. There is no separate training or development file.

# Acknowledgments

The source recordings, transcription, and interlinear glossing were created by Masoud Mohammadirad. The Universal Dependencies conversion was prepared by Amirhossein Mojiri Foroushani and Zaniar Ghaderi in the [Hawrami corpus](https://github.com/zaniarghaderi/hawrami-corpus) project. We thank Masoud Mohammadirad for publishing the Hewramî narrative and its glossed analysis.

## References

* Mohammadirad, Masoud. 2025. _Echoes of the past: Hewramî narratives_. Language Science Press. [https://doi.org/10.5281/zenodo.17140764](https://doi.org/10.5281/zenodo.17140764)
* Mohammadirad, Masoud. 2025. _A corpus of Hewramî recordings, time-aligned with transcription and translation_. Zenodo. [https://doi.org/10.5281/zenodo.15419952](https://doi.org/10.5281/zenodo.15419952)

# Changelog

* 2026-11-15 v2.19
  * Initial release in Universal Dependencies.
  * Added the spoken narrative ZB (61 sentences) as test data.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.19
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: spoken
Lemmas: converted from manual
UPOS: converted from manual
XPOS: not available
Features: converted from manual
Relations: converted from manual
Contributors: Mojiri Foroushani, Amirhossein; Ghaderi, Zaniar
Contributing: here
Contact: amojiry@gmail.com, zaniargh42@gmail.com
===============================================================================
</pre>
