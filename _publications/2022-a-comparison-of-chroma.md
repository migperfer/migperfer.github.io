---
title: "A Comparison of Pitch Chroma Extraction Algorithms"
collection: publications
permalink: /publication/2022-a-comparison-of-chroma
excerpt: 'A paper in which we compare qualitative the behaviour of different chroma algorithms, be these based on deep learning or signal processing techniques.'
date: 2022-06-07
venue: 'Proceedings of the 19th Sound and Music Computing Conference'
paperurl: 'https://zenodo.org/records/6573083'
citation: 'Perez, Miguel & Kirchhoff, Holger & Serra, Xavier (2022) &quot;A Comparison of Pitch Chroma Extraction Algorithms &quot; <i>Proceedings of the 19th Sound and Music Computing Conference, Saint-Étienne (France)</i>.'
---
The pitch chroma is a popular way to represent pitch information in an octave independent way, with applications in 
automatic chord recognition, cover song identification, audio-to-score alignment, and others. Early chroma extraction 
algorithms employed expert knowledge to derive pitch chromas from short-time spectra. With the rise of deep learning, 
the emphasis moved from algorithm design to the structure of the network and the selection of appropriate training data.
The approaches perform differently for various types of audio input. We conducted a set of experiments in order to 
explore the qualitative properties that each algorithm exhibits. These include how the number of concurrent pitches 
influences the chroma representation, and how noise or unpitched percussion can degrade the performance of the 
algorithms. We performed a quantitative analysis of various algorithms under these scenarios. The results show that 
chromas based on deep learning show huge potential, especially when it comes to noise reduction and ignoring non-tonal 
aspects of the music. However, we also found that some deep learning based chromas fail to accurately detect pitches at 
lower polyphony levels. We reflect on these results and discuss some paths to improvements for future chroma extraction 
algorithms.

