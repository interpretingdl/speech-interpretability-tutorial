<head><meta property="og:image" content="https://raw.githubusercontent.com/interpretingdl/speech-interpretability-tutorial/refs/heads/main/book/images/tutorial-overview.png"></head>

# Interpretability Techniques for Speech Models

Pre-trained foundation models have revolutionized speech technology like many other adjacent fields. The combination of their capability and opacity has sparked interest in researchers trying to interpret the models in various ways. While interpretability in fields such as computer vision and natural language processing has made significant progress towards understanding model internals and explaining their decisions, speech technology has lagged behind despite the widespread use of complex, black-box neural models. Recent studies have begun to address this gap, marked by a growing body of literature focused on interpretability in the speech domain. This tutorial provides a structured overview of interpretability techniques, their applications, implications, and limitations when applied to speech models, aiming to help researchers and practitioners better understand, evaluate, debug, and optimize speech models while building trust in their predictions. In hands-on sessions, participants will explore how speech models encode distinct features (e.g., linguistic information) and utilize them in their inference. By the end, attendees will be equipped with the tools and knowledge to start analyzing and interpreting speech models in their own research, potentially inspiring new directions.

```{note} 
We will present our tutorial about _Interpretability Techniques for Speech Models_ on **Sunday, August 17th** at this year's Interspeech conference in Rotterdam. <br> Check out the [programme](#interspeech-programme) below, and browse the materials through the sidebar menu.
```

![tutorial-overview-diagram](images/tutorial-overview.png)

(interspeech-programme)=
## Programme at Interspeech 2025

| **Time**      | **Topic**                                                                                                                                                                                                                                                                       | **Presenter**                                                                              |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| 15:30         | Welcome                                                                                                                                                                                                                                                                         | [Tom Lentz](https://www.tilburguniversity.edu/staff/t-o-lentz)                             |
| 15:30 - 15:50 | Introduction to the challenges of speech data for interpretability research                                                                                                                                                                                                     | [Grzegorz Chrupała](https://grzegorz.chrupala.me/)                                         |
|               | _Part I: Representation Understanding_                                                                                                                                                                                                                                          |                                                                                            |
| 15:50 - 16:15 | Lecture on representational analysis techniques for analyzing speech model internals, including: <br> <ul><li>Dimensionality reduction</li><li>Diagnostic probes & lenses</li><li>Representation space comparisons</li></ul>                                                    | [Martijn Bentum](https://www.ru.nl/personen/bentum-m)                                      |
| 16:15 - 16:30 | Walkthrough on Probing                                                                                                                                                                                                                                                          | [Charlotte Pouw](https://www.illc.uva.nl/People/Table/person/5440/Charlotte-Pouw)          |
| 16:30 - 16:40 | Walkthrough on Representation space comparisons (CKA)                                                                                                                                                                                                                           | [Marianne de Heer Kloots](https://mdhk.net/)                                               |
| 16:40 - 17:05 | Break                                                                                                                                                                                                                                                                           |                                                                                            |
|               | _Part II: Feature Importance Scoring_                                                                                                                                                                                                                                           |                                                                                            |
| 17:05 - 17:30 | Lecture on Context Mixing, including: <br> <ul><li>Analyzing the pattern of attention in speech Transformers</li><li>Limitations of interpreting raw attention as a measure of context-mixing</li><li>Expanding the scope of context-mixing analysis beyond attention</li></ul> | [Hosein Mohebbi](https://hmohebbi.github.io/)                                              |
| 17:30 - 17:45 | Lecture on Feature Attribution, including: <br> <ul><li>Gradient-based methods</li><li>Perturbation-based methods</li></ul>                                                                                                                                                     | [Gaofei Shen](https://www.gaofeishen.com/)                                                 |
| 17:45 - 18:00 | Walkthroughs on Context Mixing & Feature Attribution                                                                                                                                                                                                                            | [Gaofei Shen](https://www.gaofeishen.com/) & [Hosein Mohebbi](https://hmohebbi.github.io/) |
|               | _Discussion_                                                                                                                                                                                                                                                                    |                                                                                            |
| 18:00 - 18:10 | Key takeaways and outlook on future work in interpretability                                                                                                                                                                                                                    | [Marianne de Heer Kloots](https://mdhk.net/)                                               |
| 18:10 - 18:30 | Panel discussion with all organizers: <br> _Tom Lentz, Grzegorz Chrupała,  Martijn Bentum, Charlotte Pouw, Marianne de Heer Kloots, Hosein Mohebbi, Gaofei Shen_                                                                                                                | [Willem Zuidema](https://staff.fnwi.uva.nl/w.zuidema/)                                     |

## Tutorial contents

**Representational Analysis methods**: 
- Probing{cite}`cormacenglishDomainInformedProbingWav2vec2022, choEvidenceVocalTract2023,bentumProcessingStressEndEnd2024,shen-etal-2024-encoding,bentum25_interspeech,deheerklootsWhatSelfsupervisedSpeech2025,cormacenglishDomainInformedProbingWav2vec2022`
- Representation space comparisons: RSA{cite}`chrupala-etal-2020-analyzing,shenWaveSyntaxProbing2023a`, CCA{cite}`Pasad2021`, CKA{cite}`pmlr-v97-kornblith19a`
- CTC & Decoder lenses{cite}`deheerklootsHumanlikeLinguisticBiases2024,langedijkDecoderLensLayerwiseInterpretation2024` 
- Embedding similarities (ABX tests){cite}`schatz2016,algayresDPParseFindingWord2022,seysselDiscriminatingFormMeaning2025` 

**Feature Importance Scoring methods**: 
- Context-mixing: Attention{cite}`yangUnderstandingSelfAttentionSelfSupervised2020a,shimUNDERSTANDINGROLESELF2022,alastrueyLocalityAttentionDirect2022,audhkhasiAnalysisSelfAttentionHead2022`, Attention Norm{cite}`kobayashiAttentionNotOnly2020a`, Value-Zeroing {cite}`mohebbiHomophoneDisambiguationReveals2023a`
- Feature attribution{cite}`fucciExplainabilitySpeechModels2024,shenReliabilityFeatureAttribution2025`: Gradient-based{cite}`prasadHowAccentsConfound2020,guptaPhonemeDiscretizedSaliency2024` & Perturbation-based{cite}`wuExplanationsforASR2023,pastor-etal-2024-explaining`

## References

```{bibliography}
:style: unsrt
```
<div>