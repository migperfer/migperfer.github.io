---
title: "Refining audio-to-score alignment for singing voice transcription"
collection: publications
permalink: /publication/2025-smc-alignment
excerpt: 'Audio-to-score alignment based on iterative alignment of discrete events'
date: 2025-06-03
venue: 'Proceedings of the 22nd Sound and Music Computing Conference'
paperurl: 'https://zenodo.org/records/15838731'
citation: 'Perez, Miguel & Kirchhoff, Holger & Grosche, Peter & Serra, Xavier (2025) &quot;Refining audio-to-score alignment for singing voice transcription&quot; <i>Proceedings of the 22nd Sound and Music Computing Conference, Graz (Austria)</i>.'
---
Singing voice transcription is a very popular task in MIR which consists of obtaining the notes being sung in a given excerpt of music audio. 
Data is essential for state-of-the-art methods, but annotating it is labor-intensive, requiring musical expertise.
Moreover, in cases such as pop music, sharing such data is even more challenging due to copyright and data distribution rights. 
We present in this paper a data augmentation technique leveraging AI-generated music audio to alleviate the aforementioned data-related difficulties. 
Specifically, we generate the music accompanying the vocals for which target notes are already known. 
In this way, we create new mixes that maintain the harmony of the original piece while providing large variations in the audio content. 
We conducted a set of cross-dataset experiments and discovered that our proposed approach with harmonic-matching mixes yields the best results compared to other augmentation strategies.
The employed tools for this augmentation are open-source and ready to be used by the research community.
