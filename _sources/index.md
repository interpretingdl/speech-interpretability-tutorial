# Interpretability Techniques for Speech Models

Pre-trained foundation models have revolutionized speech technology like many other adjacent fields. The combination of their capability and opacity has sparked interest in researchers trying to interpret the models in various ways. While interpretability in fields such as computer vision and natural language processing has made significant progress towards understanding model internals and explaining their decisions, speech technology has lagged behind despite the widespread use of complex, black-box neural models. Recent studies have begun to address this gap, marked by a growing body of literature focused on interpretability in the speech domain. This tutorial provides a structured overview of interpretability techniques, their applications, implications, and limitations when applied to speech models, aiming to help researchers and practitioners better understand, evaluate, debug, and optimize speech models while building trust in their predictions. In hands-on sessions, participants will explore how speech models encode distinct features (e.g., linguistic information) and utilize them in their inference. By the end, attendees will be equipped with the tools and knowledge to start analyzing and interpreting speech models in their own research, potentially inspiring new directions.

```{note} 
We will present our tutorial about _Interpretability Techniques for Speech Models_ on **Sunday, August 17th** at this year's Interspeech conference in Rotterdam. <br> Check out the [preliminary programme](#interspeech-programme) below, and sign up through the [Interspeech registration form](https://www.interspeech2025.org/registration)!
```

![tutorial-overview-diagram](images/tutorial-overview.png)

(interspeech-programme)=
## Preliminary programme at Interspeech 2025

> **Introduction** to challenges of speech data for interpretability research <br>
> [Grzegorz Chrupała](https://grzegorz.chrupala.me/) 

> Tutorial on **Representational Analysis methods** for speech model interpretability, including: <br> Probing{cite}`bentumProcessingStressEndEnd2024,shen-etal-2024-encoding,deheerklootsWhatSelfsupervisedSpeech2025,cormacenglishDomainInformedProbingWav2vec2022`, Representational Similarity Analyses (RSA{cite}`chrupala-etal-2020-analyzing,shenWaveSyntaxProbing2023a`, CCA{cite}`Pasad2021`, CKA{cite}`pmlr-v97-kornblith19a`), <br> CTC & Decoder lenses{cite}`deheerklootsHumanlikeLinguisticBiases2024,langedijkDecoderLensLayerwiseInterpretation2024`, ABX tests{cite}`schatz2016,algayresDPParseFindingWord2022,seysselDiscriminatingFormMeaning2025` <br>
> [Martijn Bentum](https://www.ru.nl/personen/bentum-m), [Charlotte Pouw](https://www.illc.uva.nl/People/Table/person/5440/Charlotte-Pouw) 

> Tutorial on **Feature Importance Scoring methods** for speech model interpretability, including: <br> Context-mixing (Attention{cite}`pengWordDiscoveryVisually2022a,a-shams-etal-2024-uncovering`, Value-Zeroing{cite}`mohebbiHomophoneDisambiguationReveals2023a`), <br> Feature attribution{cite}`fucciExplainabilitySpeechModels2024` (Gradient-based{cite}`prasadHowAccentsConfound2020,guptaPhonemeDiscretizedSaliency2024` and Perturbation-based{cite}`wuExplanationsforASR2023,pastor-etal-2024-explaining`) <br>
> [Hosein Mohebbi](https://hmohebbi.github.io/), [Gaofei Shen](https://www.gaofeishen.com/)

> **Outlook** on future work in interpretability, **Discussion** of key takeaways and findings <br>
> [Marianne de Heer Kloots](https://mdhk.net/), [Tom Lentz](https://www.tilburguniversity.edu/staff/t-o-lentz), [Willem Zuidema](https://staff.fnwi.uva.nl/w.zuidema/) 

## References

```{bibliography}
:style: unsrt
```
<div>