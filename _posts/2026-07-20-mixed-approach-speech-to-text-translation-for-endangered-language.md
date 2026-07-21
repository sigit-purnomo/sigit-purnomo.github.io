---
title:  "Mixed Approach Speech-to-Text Translation for Endangered Language"
excerpt: "This study addresses the technological marginalization of endangered regional languages by evaluating speech-to-text translation for Dayak Ma’anyan, an extremely low-resource Austronesian language. It examines whether cascaded multilingual automatic speech recognition and machine translation models can provide effective Ma’anyan–Indonesian translation despite severe data scarcity."
date: 2026-07-20
permalink: /posts/2026/07/mixed-approach-speech-to-text-translation-for-endangered-language/
categories: [publication]
tags: [speech-translation, low-resource-language]
---

This article was published in [Data Technologies and Applications](https://www.scimagojr.com/journalsearch.php?q=21100857955&tip=sid) from Emerald Publishing.

**Authors:**  Benyamin Langgu Sinaga, Stephanie Pamela Adithama, Joanna Ardhyanti Mita Nugraha, Martinus Maslim, Albert William Wibisono, Yulius Denny Prabowo, **Yohanes Sigit Purnomo W.P.**, Vinindita Citrayasa

**Language:** English

**Abstract:** <br />
**Purpose** <br />
This study aims to address the technological marginalization of endangered regional languages by evaluating speech-to-text translation for Dayak Ma’anyan, an extremely low-resource Austronesian language. In particular, it seeks to examine whether cascaded multilingual automatic speech recognition and machine translation models can provide effective Ma’anyan–Indonesian translation despite severe data scarcity.

**Design/methodology/approach** <br />
This study employs a cascaded speech-to-text translation framework that combines two multilingual automatic speech recognition models, Whisper Large-v3 and SeamlessM4T v2, with two LoRA-adapted multilingual machine translation models, NLLB-200 3.3B and distilled 600M. Experiments are conducted in an extremely low-resource setting using limited parallel speech and text data. The proposed pipelines are evaluated at three levels: ASR transcription quality, machine translation performance and end-to-end semantic preservation.

**Findings** <br />
The results show that cascaded pipelines can produce semantically meaningful Ma’anyan–Indonesian translations even under high transcription error conditions. Whisper substantially outperforms SeamlessM4T at the ASR stage, achieving a lower WER of 0.464 compared with 0.812 and yielding better downstream translation quality. Among the machine translation models, LoRA-adapted NLLB-200 3.3B achieves the best performance, with BLEU 31.00, chrF 58.91 and the highest end-to-end semantic similarity, with SBERT 0.722. The findings further indicate that ASR quality is the dominant determinant of overall speech translation performance, while larger LoRA-adapted machine translation models provide stronger robustness against noisy ASR outputs.

**Originality/value** <br />
This study provides, to the best of the authors’ knowledge, the first empirical benchmark for Ma’anyan–Indonesian speech-to-text translation. It contributes a systematic evaluation of multilingual ASR and LoRA-adapted MT combinations for endangered-language technology and offers empirical insight into the relative impact of ASR quality and MT model capacity in extremely low-resource cascaded speech translation.

**Keywords:** Low-resource speech translation, Dayak Ma’anyan, Automatic speech recognition, Multilingual machine translation, LoRA fine-tuning, Cascaded ASR-MT

**DOI**: [10.1108/DTA-04-2026-0404](https://doi.org/10.1108/DTA-04-2026-0404)

**Article URL**: [https://www.emerald.com/dta/article/doi/10.1108/DTA-04-2026-0404/1388079/Mixed-approach-speech-to-text-translation-for](https://www.emerald.com/dta/article/doi/10.1108/DTA-04-2026-0404/1388079/Mixed-approach-speech-to-text-translation-for)



## How to Cite
If you extend or use this work, please cite the paper where it was introduced:
```
@article{SINAGA2026DTA0404,
	title = {Mixed approach speech-to-text translation for endangered language},
	journal = {Data Technologies and Applications},
	volume = {ahead-of-print},
	number = {ahead-of-print},
	pages = {1-21},
	year = {2026},
	issn = {2514-9288},
	doi = {https://doi.org/10.1108/DTA-04-2026-0404},
	url = {https://www.emerald.com/dta/article/doi/10.1108/DTA-04-2026-0404/1388079/Mixed-approach-speech-to-text-translation-for},
	author = {Sinaga, Benyamin Langgu and Adithama, Stephanie Pamela and Nugraha, Joanna Ardhyanti Mita and Maslim, Martinus and Wibisono, Albert William and Prabowo, Yulius Denny and Purnomo W.P., Yohanes Sigit and Citrayasa, Vinindita},
	keywords = {Low-resource speech translation, Dayak Ma’anyan, Automatic speech recognition, Multilingual machine translation, LoRA fine-tuning, Cascaded ASR-MT},
	abstract = {This study addresses the technological marginalization of endangered regional languages by evaluating speech-to-text translation for Dayak Ma’anyan, an extremely low-resource Austronesian language. It examines whether cascaded multilingual automatic speech recognition and machine translation models can provide effective Ma’anyan–Indonesian translation despite severe data scarcity.}
}
```
