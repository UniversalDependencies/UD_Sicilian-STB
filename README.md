# Summary

The Sicilian Treebank is a small parallel corpus of Sicilian texts, automatically parsed and then manually revised, with Italian translations. It includes both contemporary and folkloric materials. The main focus is documenting typical morphosyntactic features of the written Sicilian.

# Introduction
Sicilian-STB is the first treebank for the Sicilian language in the Universal Dependencies framework. It is a parallel resource aligned 1:1 at the sentence level between Sicilian and Italian. The texts included in this first release come from the Panzaredda website, as well as a third text consisting of 18 diatopic variants of the Sicilian legend of Colapisci. In the CoNLL-U files, each text includes a comment line at the beginning indicating the diatopic variant and, when available, the year of publication.

For the Italian translations, we used three LLMs accessed via GPT@JRC, a tool that provides safe, AI Act-compliant access to generative AI systems. Each model generated translations using three different prompting strategies. The preferred translation version was chosen based on subjective qualitative evaluations. This version was then manually corrected by native Sicilian speakers with linguistic training. The revised translations are included in the CoNLL-U files as comment lines aligned with each Sicilian sentence.

As no previous UD-formatted treebank exists for Sicilian, we generated an initial automatic annotation using pre-trained UD models for Italian. In particular, we tested parser trained on the ISDT and POSTWITA treebanks, the two largest Italian resources in the UD repository. Gold-standard sentence segmentation was applied before parsing.
The automatic annotation was manually revised using the Arborator tool. Each of the three texts was annotated by one annotator and reviewed by a second. Problematic phenomena were discussed collaboratively among the three main annotators, with additional consultation involving the rest of the authors when necessary.

For the first release of the treebank, only the Sicilian side is annotated in UD format and fully revised. The Italian side remains automatically annotated without manual correction. 




# Acknowledgments

...

## References

* (citation)


# Changelog

* 2025-11-15 v2.17
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.17
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: fiction
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Bosco, Cristina; D'Alì, Sabrina; Di Nuovo, Elisa; Guglielmetti, Mario; Cappello, Caterina Maria
Contributing: here
Contact: cristina.bosco@unito.it
===============================================================================
</pre>
