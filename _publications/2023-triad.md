---
title: "TriAD: Capturing harmonics with 3D convolutions"
collection: publications
permalink: /publication/triad-ismir-2023-11-05
excerpt: 'In this paper we present a novel architecture capable of capturing the harmonic series using 3D convolutions'
date: 2023-11-05
venue: 'Proceedings of the 24th International Society for Music Information Retrieval Conference'
paperurl: 'http://ismir2023program.ismir.net/poster_11.html'
citation: 'Perez, Miguel & Kirchhoff, Holger & Serra, Xavier (2023). &quot;TriAD: Capturing harmonics with 3D convolutions.&quot; <i>Proceedings of the 24th Int. Society for Music Information Retrieval Conference, Milan (Italy)</i>.'
---
Thanks to advancements in deep learning (DL), automatic music transcription (AMT) systems recently outperformed 
previous ones fully based on manual feature design. Many of these highly capable DL models, however, are computationally
expensive. Researchers are moving towards smaller models capable of maintaining state-of-the-art (SOTA) results by 
embedding musical knowledge in the network architecture. Existing approaches employ convolutional blocks specifically 
designed to capture the harmonic structure. These approaches, however, require either large kernels or multiple kernels,
with each kernel aiming to capture a different harmonic. We present TriAD, a convolutional block that achieves an 
unequally distanced dilation over the frequency axis. This allows our method to capture multiple harmonics with a single
yet small kernel. We compare TriAD with other methods of capturing harmonics, and we observe that our approach maintains
SOTA results while reducing the number of parameters required. We also conduct an ablation study showing that our 
proposed method effectively relies on harmonic information.

[Code available at github](https://github.com/migperfer/TriAD-ISMIR2023)