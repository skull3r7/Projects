# Projects
Projects I have worked on, descending chronological order

## Metal artifact reduction of computed tomography using Transformers networks
* Type: Research Project
* Status: Ongoing
* Year: 2020
* [PDF](https://github.com/skull3r7/Projects/blob/main/MetalArifactReductionTransformersExpose.pdf)

* Expose:
In this research project we investigate whether the artifacts described above can be reduced by a transformer network. The approach is an unsupervised representation learning for images where the missing pixels must be predicted by the model. This approach is promising to reduce artifacts in CBCT scans. CBCT (cone beam computed tomography) machines take in a circular orbit a high number of 2D X-ray projections and calculate a 3D-reconstruction of the target area of the human body \citep{CBCT}. This results in two different data sets: the single 2D CT-scans and the 3D-volume data of the reconstruction. Therefore both datasets are used in this project to see on which data a better reduction of artifacts can be achieved. To achieve this goal, an adequate transformer model must be realized and trained on the given data. The planned approach is that the areas with artifacts are masked and then replaced by the trained model. If the reconstruction and an associated reduction of artifacts is successful, it will also be necessary to validate whether the new data is useful from a medical point of view.

## Text Summarization using neural models based on online articles of the Süddeutschen Zeitung

* Type: Master Project
* Status: Finished
* Year: 2020
* [PDF](https://github.com/skull3r7/Projects/blob/main/TextSummarizationSZ.pdf)

* Abstract:
In this project a neural model for the extractive generation of summaries of German news articles was developed.  The data set consists of online articles of the SZ-Zeitung, where the ground truth labels were generated from introductory headwords. The model uses a pre-trained BERT encoder to calculate a sentence and document representation. Depending on the approach of the Dataloader, either sentence tokens or the entire document is encoded with BERT.  By averaging this coding, the document representation is calculated.  For the sentence representations the corresponding sentences are masked and averaged. Both flow into a classifier, which learns the probabilities of belonging to the summary. The model achieved an F1 score of 0.26 on validation data compared to the Lead3 Baseline of 0.13 of the data set used here. A manual evaluation of the results showed that the S ̈atze selected by the model can be compared with the generated ground-truth summaries of the keywords.


## Analysing News about political parties in German Online Media

* Type: Master Project
* Status: Finished
* Year: 2019
* [PDF](https://github.com/skull3r7/Projects/blob/main/NewsGermanOnlineMedia.pdf)

* Abstract:
The  political  environment  in  Germany  has  undergone  major  changes  in  recent  years.   The  major  popularparties,  the  liberal-conservative  Union  (CDU/CSU)  and  the  social-democratic  SPD,  are  losing  their  votesto the smaller and newer parties like the Greens (Alliance 90/The Greens) and the right-wing Alternative forGermany (AfD). The influence of the new media is often cited as one of the main reasons for this development.The new media are often accused of being more susceptible to manipulation and false reports than the classicmedia.  The role of these media has been the subject of much debate for some time now:  Through selectivereporting and public discussions, the media should have an influence on political events and the formationof public opinion.  This paper examines this allegation by analyzing how various parties are being reported.For this purpose, all articles about political parties were collected by selected media over a period of 5 years.This data were used for different analyses like Sentiment Detection, Language Analysis and Data Clustering.For example it was found that AfD articles have on average the longest length and have the highest negativepolarity score of all parties.  During the clustering it could be observed that all parties are reported on mostfrequently at the provincial and Federal state level.  Based on the Pearson correlation coefficient it could beshown that there is no correlation between the article scoring and survey values or Google Trend for the SPDund Green Party.  In contrast, the AfD party has a high correlation between the amount of puplished articlesand survey values.  When analysing certain events, it can be observed that attacks, whether Islamist or right-wing, have no influence on the trend of the AfD party.  No causality could be established between coverageand survey results.


## Guided Museum tours with a context-based language assistant

* Type: Bachelor Thesis
* Status: Finished
* Year: 2019

* Abstract:
The present thesis wants to show a new innovative approach for a digital language
assistant in museums. It therefore examines what the digital environment of museums
in Germany looks like and what wishes visitors have for mobile applications. It
is analysed how language assistants in general work, which components the architecture
consists of and how the museum assistant can interact with the user. Based
on these results, the museum assistant will be designed and developed. The museum
assistant will be tested using the example of Wehrtechnische Studiensammlung
in Koblenz (Germany). The developed prototype demonstrates that such a museum
assistant can be put into good practice. The museum assistant can lead to a higher
customer satisfaction, which is certainly reflected in the increase of the frequency
of museum visits.
