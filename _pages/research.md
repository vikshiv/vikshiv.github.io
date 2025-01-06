---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=LiuMoYgAAAAJ&hl=en).


## Nanopore signal classification with pangenome indexes



Nanopore sequencing generates reads by measuring electrical current signal that is converted to nucleic acid sequences typically with a neural network. This basecalling step is a bottleneck in real-time classification pipelines. We developed a novel nanopore signal-based read classification method that uses the [r-index](https://www.cell.com/iscience/fulltext/S2589-0042(21)00664-7?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS2589004221006647%3Fshowall%3Dtrue), a full-text index that scales to pangenomes. This method, **Sigmoni**, is significantly faster and more accurate than existing methods for classifying nanopore reads against large pangenomes.

- [Sigmoni paper](https://doi.org/10.1093/bioinformatics/btae213) ([pdf](https://watermark.silverchair.com/btae213.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAA4QwggOABgkqhkiG9w0BBwagggNxMIIDbQIBADCCA2YGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQM35Hu05bj8MBFzZAQAgEQgIIDN-_HZVpDvlpDkdqT69qCKjVVx7zoKku6EnAYkR2-wm_7cSkpNb1l_rQt-o1U9KYazAV-KtsZopWB8LWuSkPoDO82lR4YB1XgCI0UAcR9AgV7xXyqB4s2wsrMpqv9s46MeAnquCi367vpBY-q7fG0kwnp_JzmFsm2VEEVIUsT7jyOgbRu7Sp1gDdJtS-nJnZfhHnrVEDOgWELGHy2XyLwsBkeYqncKxNK84V70ncRfGh4pL4PqOzxVMd9e-RvMUNh0S_kEwkBlbeTGLpX1bmiwj6TJn0NHPP_KD-z1q0e5HKoehY5w-DiCsYnmg183QtcC_AH8mCz0Nr_MNQ6v78iDnxT9o1TRKJkJxRJ6LeZzThJZXtHB28koANkOi9eBaIIk-EmB-flz3FOFahxUKPSEqYoSGfPkbSwJLJXi8F38CwvzaoJkWo7qzJnoTCiCfVizd9ODdHFsMx5ar95mskh32TLxqJTyksrcZI1RmTRPV9RfwWOmqzGN5x0c81YLLle6QbVEwvzOjE1pnRWkR7DaHyD7Hm3Cuf6pSK8SvubSW-XaJpZ0d4LQ4iMwxfGxPCcMxhBLSp4L2ETiATXdcy8vmPhOwP_hcJ8YjNaYAyda8JgWFTsqm-aMRylJDLPc4r2Atljl0EeivBgf0j4uEWKkFxt5-Snq0GdVv2A_geqAnbe5tIRr9IsmmO24NSePi-L2Y7g4pdUx_XhaJJSbxfBkJsfeHhDTZ4wSEYoT_KpTaR6Rvamvi07txYE-hpeN5quaHv0nhj2CNw7tSx7CheJj2X7zDbFCPc5K8k2PEmxh4thW_9XtxHakNbAsNbG4HzCbGyvr3T8sHniP3yt7OeU9nX8XyH3wnGitMq7QdDurb-b-jwLyYgBWDKbixG8Lc-RPpTdKfvuAj9btDNVQg7ctyUsxnTbKX_zDWC1Me0TImUUqbwHFfuQ5ROiNjrj2WPdaW5qOi5xCditDxriZn3pkmN3mId6XUTXbPH-G-zOAgpDJD1x1_LGEC9CT9Ti7XpEidrAQoKaQKOo2IAs9igGfP4HAYykC1XLlE94Av_QhsRHswkBr6RrIIuDk5cOVekEGlBzejfhrgs)), published in 2024 in Bioinformatics (ISMB 2024)

- [RECOMB-seq talk](https://www.youtube.com/watch?v=Gzm2fMEtmUI), in Istanbul, Türkiye (April 2023) - 🏆 **RECOMB-seq Best Poster/Short Talk**

- [ISMB talk slides](http://vikshiv.github.io/files/sigmoni.pdf), in Montreal, Quebec (July 2024) - 🏆 **ISMB HitSeq Best Talk**

## Building and visualizing pangenomes

<img src="../images/polaroid_tattoo.png" alt="mumemto" width="150" align="left" style="margin-right: 15px;"/> Pangenomes require an underlying alignment for interpretability and usability. This structure can take the form of a multiple alignment or graph, but these are impractical to compute. We developed a novel method, **Mumemto**, to compute maximal unique matches (multi-MUMs), commonly used as anchors for alignment, at the scale of hundreds of human genomes. Mumemto can visualize pangenome synteny, accelerate graph construction, identify misassemblies, and even improve full-text index-based classification ([see further work](https://www.biorxiv.org/content/10.1101/2024.10.29.620953v1.full.pdf)).

- Software on [github](https://github.com/vikshiv/mumemto)
- Preprint on [BioRxiv](https://www.biorxiv.org/content/10.1101/2025.01.05.631388v1)