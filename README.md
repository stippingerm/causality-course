# Causal Analysis (Kauzalitásvizsgálat)

## Course codes

* BME: BMETEEFMsFBIOV-00 (Bevezetés az idősoros okságvizsgálatba / Introduction to causal analysis of time series)

## Contents
1. Introduction [slides](https://wigner.hu/~stippinger/courses/causality-2025/01_Cause_and_Probability.pdf) [notebook](http://colab.research.google.com/github/stippingerm/causality-course/blob/main/Structure_based_methods/01_probability_statistics_structure.ipynb)
  * Definition of causality in philosophy
  * Foundations of statistics
  * Causality deduced from the examination of function form
2. Examination of samples, events [slides](https://wigner.hu/~stippinger/courses/causality-2025/02_Samples_and_Experiments.pdf)
  * Chapters from the book Causal Inference: What If?
  * Randomized experiment
  * Concept of confounder
  * Bayesian inference
3. Graphical models [slides](https://wigner.hu/~stippinger/courses/causality-2025/03_Graphical_models.pdf)
  * Confounder, collider
  * D-separation
  * Judea Pearl's definition
4. Inference of causal graphs [slides](https://wigner.hu/~stippinger/courses/causality-2025/04_Inference_of_Causal_Graphs.pdf) [notebook](http://colab.research.google.com/github/stippingerm/causality-course/blob/main/Structure_based_methods/04_inference_causal_graphs.ipynb)
  * Directed acyclic graphs
  * PC algorithm and its extensions
  * Equivalence classes of causal graphs, undecidable cases
5. Causality on stochastic time series [slides](https://wigner.hu/~stippinger/courses/causality-2025/05_Granger_causality.pdf) [notebook](http://colab.research.google.com/github/stippingerm/causality-course/blob/main/Time_series_methods/05_granger_causality.ipynb)
  * Vector autoregressive processes
  * Granger causality
  * Transfer entropy
6. Causality on stochastic time series II.
  * Conditional Granger causality
  * Spectral Granger causality
7. Causality on stochastic time series III.
  * Application of the Markov property
  * Significance and surrogate generation
8. Causality in dynamical systems
  * Chaos and ergodicity definitions
  * Takens' embedding theorem
  * Causal discovery
  * Convergent cross-mapping
9. Causality in dynamical systems II.
  * Recurrence maps
  * Convergent cross-sorting
10. Causality in dynamical systems III.
  * Dimensional causality
  * Artificial neural network methods
11. Anomaly detection [slides](http://cneuro.rmki.kfki.hu/wp-content/uploads/2024/12/Neurinfo-Anomaly-detection-SM.pdf) [notebook](http://colab.research.google.com/github/stippingerm/causality-course/blob/main/Time_series_methods/Anomaly_detection.ipynb)
  * Concept of anomaly in statistics and time series
  * Classical machine learning methods (one-class SVM, isolation forest, local spread factor, temporal spread factor)
  * Deep neural network methods (autoencoder, BiGAN, LSTM)
12. Presentation of independently processed articles and applications
  * Student evaluation

### Contents (Hungarian)
1. Bevezetés
  * okság definíciója a filozófiában
  * statisztika alapozás
  * függvény forma vizsgálatából levezethető okság
2. Minták, események vizsgálata
  * fejezetek a Causal Inference: What If? könyvből
  * randomizált kísérlet
  * confounder fogalma
  * Bayes-i inferencia
3. Grafikus modellek
  * confounder, collider
  * d-szeparáció
  * Judea Pearl féle definíció
4. Kauzális gráfok inferenciája
  * irányított aciklikus gráfok
  * PC-algoritmus és kiterjesztései
  * kauzális gráfok ekvivalenciaosztályai, eldönthetetlen esetek
5. Kauzalitás sztochasztikus idősorokon
  * vektor autoregresszív folyamatok
  * Granger-féle kauzalitás
  * transzfer entrópia
6. Kauzalitás sztochasztikus idősorokon II.
  * feltételes Granger-féle kauzalitás
  * spektrális Granger-féle kauzalitás
7. Kauzalitás sztochasztikus idősorokon III.
  * a Markov-tulajdonság alkalmazása
  * Szignifikancia és surrogate készítés
8. Kauzalitás dinamikai rendszerekben
  * káosz és ergodicitás definíciók
  * Takens beágyazási tétele
  * kauzális felfedezés (causal discovery)
  * konvergens keresztleképezés
9. Kauzalitás dinamikai rendszerekben II.
  * rekurrencia térképek
  * konvergens keresztrendezés
10. Kauzalitás dinamikai rendszerekben III.
  * dimenziós kauzalitás
  * mesterséges neurális háló módszerek
11. Anomáliadetekció [slides](http://cneuro.rmki.kfki.hu/wp-content/uploads/2024/12/Neurinfo-Anomaly-detection-SM.pdf) [notebook](http://colab.research.google.com/github/stippingerm/causality-course/blob/main/Time_series_methods/Anomaly_detection.ipynb)
  * anomália fogalma statisztikában és idősorokon
  * klasszikus gépi tanulási módszerek (egyosztályos SVM, izolációs erdő, helyi kiszóró faktor, időbeli kiszóró faktor)
  * mély neurális hálós módszerek (autoenkóder, BiGAN, LSTM)
12. Önállóan feldolgozott cikkek és alkalmazások ismertetése
  * hallgatók értékelése

## References (Ajánlott irodalom)
* Hernan, Miguel A, and James M Robins. „Causal Inference: What If” (2020), Boca Raton: Chapman & Hall/CRC. [Online version](https://miguelhernan.org/whatifbook).
* Assaad, Charles K., Emilie Devijver, and Eric Gaussier. „Survey and Evaluation of Causal Discovery Methods for Time Series”. Journal of Artificial Intelligence Research 73 (2022. február 28.): 767–819. [doi: 10.1613/jair.1.13428](https://doi.org/10.1613/jair.1.13428).
* Glymour, Clark, Kun Zhang, and Peter Spirtes. „Review of Causal Discovery Methods Based on Graphical Models”. Frontiers in Genetics 10 (2019. június 4.): 524. [doi: 10.3389/fgene.2019.00524](https://doi.org/10.3389/fgene.2019.00524).
