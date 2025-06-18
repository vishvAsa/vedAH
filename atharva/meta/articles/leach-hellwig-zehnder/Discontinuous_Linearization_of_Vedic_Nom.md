+++
title = "Discontinuous Linearization of Vedic Nominal Expressions"

+++

**Abstract:** This paper explores the linearization of syntactic structures in Vedic Sanskrit. Recent research indicates that word order variation is influenced by cognitive factors, grammar, and language history, and ancient languages like Vedic Sanskrit provide valuable insights into these dynamics. Leveraging the recent availability of comprehensive linguistic resources, this study presents a corpus-based survey 

of Vedic word order variation in nominal expressions, examining noun-modifier 

pairs across different Vedic texts. The goals are to survey continuity in linearization and to compare the Atharvaveda to other Vedic texts using statistical tests of significance. 

**Introduction**

The strict linearization of syntactic structure imposed by communication modalities in human language has attracted much interest in many linguistic disciplines, theoretical, psycholinguistic, and diachronic, among others. Recent research generally agrees that variation in word order is shaped and constrained by interacting and 

competing principles of cognition, communication, grammar, and language history 

\(Tomlin 1986; Dunn et al. 2011; Culbertson, Smolensky, and Legendre 2012; Napoli 

and Sutton-Spence 2014; Maurits and Griffiths 2014; Levshina 2019; Sauppe et al. 

2021\). In addition to experimental data, this line of research relies on various kinds of observational data: thorough descriptions of inventories in grammars or, more 

importantly, patterns of usage and frequency found in corpora. Ancient languages, in particular those as well attested as Vedic Sanskrit, are relevant for understanding the diachronic behavior of linearization because when assessing the dynamics 

of change, they enhance the estimates by providing calibration points. At the same time they open a window into sociocultural environments that differ drastically 

from modern ones. This enables us to control, e.g., for effects of general literacy. 

Until recently, large scale empirical research on Vedic word order variation 

was limited by data availability and general replicability. For example, the thorough studies of Delbrück \(1878\), Schäufele \(1990\), and Reinöhl \(2020\) are largely based on samples from a single text, and the data is not available for follow-up investigations. Fortunately, the recent progress made in building linguistic resources with computer-assisted procedures has dramatically changed the field. In this article, we Open Access. © 2025 the author\(s\), published by De Gruyter. 

This work is licensed under the Creative 

Commons Attribution-NonCommercial-NoDerivatives 4.0 International License. 

https://doi.org/10.1515/9783111244433-003

**58** 

Paul Widmer and Oliver Hellwig

capitalize on these recent advancements and present a corpus-based exploratory 

survey of Vedic word order variation in nominal expressions, in particular word 

pairs consisting of a modified noun and a modifier noun or adjective from all Vedic strata. 

Descriptions of Sanskrit and Vedic syntax generally acknowledge that Vedic 

exhibits a high degree of free ordering both of constituents and elements within 

constituents \(Hock 2013; Viti 2015; Luraghi 2010\). While most scholars follow linguistic traditions that start from a basic order of hierarchically organized structures \(Delbrück 1888; Speyer 1896; Schäufele 1990, etc.\), others adopt the idea of flat structures that lack linear order at all \(Gillon and Shaer 2005; Gillon 2006\). 

Departing from Pāṇinian methodology \(“state a majority rule and find casuistic 

explanations for each deviation”\), another recently championed strand of research focuses on diversity and distribution and tries to identify functional and structural correlates \(e.g. Delbrück 1888; Louagie and Reinöhl 2021; Reinöhl 2020\). Given the theoretical interest in configurationality as a structural correlate of communication channel restrictions, we focus on variation with respect to linear continuity and discontinuity in complex nominal expressions, i.e. noun–modifier pairs. 

Surprisingly little is known about the distribution of Vedic word order vari-

ants, while the factors that are assumed to drive variation have attracted much 

more attention. For example, it is generally assumed that metrical texts exhibit 

more variation than prose texts \(Brereton and Jamison 2020\), and earlier stages 

of the language more than later ones \(Delbrück 1888; Viti 2015\). Moreover, it is 

well known that not all types of relation between modified and modifier behave 

alike, and that the length of a modifier constrains the placement relative to the modified and the clause \(Delbrück 1888; Reinöhl 2020; Jing, Widmer, and Bickel 

2021\). Another important factor is information structure \(Delbrück 1888\). Based on a sample of ca. 1,000 clauses from the prose parts of the Vedic Maitrāyaṇī-Saṁhitā 

and qualitative descriptions of three Australian languages, Reinöhl \(2020\) proposes that in most, if not all languages \(including Vedic Sanskrit\) a particular continuous order with functionally determined slots is the default. Deviations from such “functional templates” in continuous nominal expressions are assumed to be associated 

with needs related to information structure or with modifier heaviness. For dis-

continuity of nominal expressions Reinöhl discerns three patterns: the placement 

of an element at or near the left edge of the clause, Wackernagel positioning of 

pronominals, and, only in Vedic, discontinuity caused by conjunctions. Moreover, it is suggested that discontinuity is associated with information structure. 

Research on word order in complex nominal expressions has reached similar 

results for other ancient languages, although the results found for ancient written languages such as Latin and post-Homeric Greek may not be fully applicable for 

Vedic which was transmitted orally. For example, information structure is con-

Discontinuous Linearization of Vedic Nominal Expressions 

[[59]]

sidered a major source for word order variation in nominal expressions in Latin 

\(Spevak 2014\) and Ancient Greek \(Devine and Stephens 2000\). While we fully 

acknowledge the relevance of information structure with concepts such as promi-

nence, focus or topic, it is also true that this approach comes at a high cost – namely, it is extremely difficult to operationalize these concepts because of our limited understanding of ancient cultures, grammars, and narrative conventions. Scholars 

tend not to agree on the definition of these concepts and their application, and 

judgements of information structure often run the risk of circularity. Moreover, it is crucial to control for genre, register, and style because variation patterns are notoriously associated with content and textual conventions \(Biber 2012; Szmrecsanyi 

2019\). Therefore, in order to get a sound grasp of the full range of variation and other potential confounding factors, such as heaviness of modifiers mentioned 

by Reinöhl \(2020: 85–86\), a large amount of data from as many genres and reg-

isters as possible is needed. This stands in contrast with restrictions of time and resources. Annotating larger portions of text with information structure requires an enormous amount of philological scrutiny and time. This is why in this paper, we complement previous qualitative work that focused on semantics but used a small 

number of data points with an investigation that considers some formal criteria 

driving word order variation on as many data points as possible. 

The goals of this article are, first, to give, for the first time in Vedic studies, a broad survey of continuity in the linearization of complex nominal expressions 

on an empirical basis, and second, to compare the Atharvaveda to other metrical 

Vedic texts. To do so, we extract 8,789 complex nominal expressions from a corpus of dependency-annotated Vedic texts covering various textual and chronological 

layers. On these observations we carry out standard frequentist statistical tests of significance to get an impression of the interactions between continuity and two 

properties of the modifier \(word class and length\), the placement of the modifier relative to the modified noun, and the textual layer. 

In the next section we describe data and methods. The subsequent section 

reports our results for a sample from the Vedic corpus over its entire temporal span and for the oldest layer of metrical texts. The final section summarizes the paper. 

**Data and Methods**

The data for this contribution are extracted from the Vedic Treebank \(VTB\), a database of Vedic sentences which are syntactically annotated according to the Uni-

versal Dependency \(UD\) standard \(Nivre et al. 2016\). With about 17,300 sentences 

with 130,000 word tokens, the version of the VTB used for this paper is significantly 

**60** 

Paul Widmer and Oliver Hellwig

larger than the versions described in Hellwig et al. \(2020\) and Biagetti et al. \(2021\). 

The improved coverage of the Vedic corpus is due to the availability of a syntactic parser of Vedic Sanskrit which has been developed in the research project Chron-BMM1 and which significantly accelerates the process of data acquisition \(Hellwig, Nehrdich, and Sellmer, n.d.\). 

Using the syntactic annotations provided by the VTB, it is easy to find the 

complex nominal expressions required for this study. We select all nominal expressions that are modified either by another nominal expression or an adjectival 

phrase. Continuity is determined by inspecting whether any elements that do not 

belong to the complex nominal expression are inserted between the modified noun 

and the modifier. One such case is displayed in Figure 1. In addition, we consider the following variables which are suspected to interact with continuity:

**Modifier Type**

We make a binary distinction between adjectives \(labeled amod\), which agree with 

the modified noun in gender, number, and case, and nominal modifiers \(nmod\), 

which usually take the genitive case. 

**Position**

The placement of the modifiers relative to the modified noun: modifiers either 

precede \(left\) or follow the modified noun \(right\). 

**Length**

The length of the modifier in orthographic units separated by a space, i.e. the modifier including all elements which syntactically depend on it. We collapse all lengths greater than four, which results in four binned integers in the interval \[1–4\]. 

**1** Project funded by the German Federal Ministry of Education and Research, FKZ 01UG2121; see 

https://chronbmm.phil.hhu.de/. 



Discontinuous Linearization of Vedic Nominal Expressions 

[[61]]

**Layer**

In order to correlate changes in linearization with the historical structure of the Vedic corpus, we record the diachronic layer of each observation according to a 

system derived from \(Kümmel 2000: 5f.\) and \(Witzel 1989\):

1. Early Vedic \[= 1-RV\]: RV 2–7, 9

2. Old Vedic \[= 2-MA\]: RV 1, 8, 10 and the metrical portions of the Atharvaveda- 

and Yajurveda-Saṁhitās \(‘Mantra language’\)

3. Middle Vedic \[= 3-PO\]: the prose portions of the Saṁhitās, and the older parts of the Brāhmaṇas, Āraṇyakas, and Upaniṣads

4. Young Vedic \[= 4-PL\]: the younger parts of the Brāhmaṇas, Āraṇyakas, and 

Upaniṣads

5. Late Vedic \[= 5-SU\]: the Sūtra texts of the Vedāṅgas

Compartments 2–5 of Table 1 show that these variables occur with sufficient fre-

quency in our sample which facilitates the application of standard statistical tests of significance. 

**Figure 1:** RV 10.5.2d \(“They have placed in hiding the highest names”, Jamison and Brereton 2014, p. 1374\) as an example for discontinuous placement: The verb dadhire is inserted between the noun nā́māni and its modifier párāṇi. 

We assess possible differences in the distributions using standard frequentist statistical tests of significance for count data \(see e.g. Agresti 2007\). Hellwig, Scarlata, and Widmer \(2021\) describe the application of relevant methods in the context of Vedic studies, and the reader may refer to this publication for a more detailed, practical introduction to the statistical tests applied here. 

**62** 

Paul Widmer and Oliver Hellwig

**Table 1:** Distribution of the considered variables in the data 

sample used in this study. 

**Linearization**

continuous

6316

2473

**Modifier type**

amod

nmod

2953

5836

**Position**

left

right

7037

1752

**Length**

1

2

3

≥ 4

6199

1582

567

441

**Layer**

1-RV

2-MA

3-PO

4-PL

5-SU

980

2693

1052

2100

1964

**Results and Discussion**

**General Observations**

Before focusing on the Atharvaveda and the other oldest metrical texts, we explore which patterns emerge when we consider the entire timespan of the Vedic literature. As described in the preceding section, the collected data relate the \(dis-\)continuous placement of nominal expressions to their syntactic labels, their relative positions, their lengths, and the diachronic layer of the containing texts. We start the evaluation by exploring the relationships between each of these four possible explanatory variables and \(dis-\)continuous linearization in the whole data set, and consider increasingly complex interactions as our evaluation proceeds. 

**Table 2:** Results of G-tests for the basic interactions 

between continuous and discontinuous linearization 

and four influence variables considered in this paper; 

see also the graphical display in Figure 2. 

**Infl. Factor**

**Statistics**

**DF**

**p-value**

Label

G = 44.691

1

0.001

Position

G = 390.772

1

0.001

Length

G = 6946.096

3

0.001

Layer

G = 428.548

4

0.001



Discontinuous Linearization of Vedic Nominal Expressions 

[[63]]

**Figure 2:** Basic interactions with continuous and discontinuous complex nominal expressions; top left: interaction with the label; top right: with position; bottom left: with the length of the dependent; bottom right: with the chronological layer. Test results are reported in Table 2. 

Figure 2 graphically displays these interactions, and the test results of the underlying count data are reported in Table 2. Overall, we observe statistically highly significant differences for all explanatory features. The weakest, but still highly significant effect concerns the modifier type \(Figure 2, top left\). This effect fits the intuition via the interaction with modifier length: nominal expressions tend to be more complex, which favors discontinuity. We also observe strong effects for the relative positions \(Figure 2, top right\). Nominal expressions with the modifiers placed to the right of the modified are significantly more often discontinuous than those with modifiers placed to the left. The strongest statistical effect is observed for the lengths of the modifier: Figure 2 \(bottom left\) shows that continuous linearization is largely restricted to modifiers that consist of 



**64** 

Paul Widmer and Oliver Hellwig

only one word. Notably, the diachronic layers also interact with \(dis-\)continuous linearization to a highly significant degree as the number of continuous placements increases nearly monotonically over the period considered here \(Figure 2, bottom right\). While a Cochran-Armitage test shows that this trend is also statistically highly significant \( Z = 

18.431, dim: 5, p < 0.001\), this result does not necessarily point to systematic changes in discontinuity patterns. When we plot the diachronic distribution of the lengths of the dependents \(see Figure 3\), our data display a diachronic trend towards using shorter dependents over the Vedic period, which is again statistically highly significant.2

**Figure 3:** Lengths of the modifiers, grouped by diachronic layers. The bottom-right subplot in Figure 2 

can largely be explained as a combination of the trend shown in this plot and the distribution in the bottom-left subplot in Figure 2. 

At first view, the trend observed in Figure 2 \(bottom right\) results from an interaction of \(at least\) two elements: Later Vedic texts prefer shorter modifiers \(Figure 3\), and modi-2 For this Cochran-Armitage test, we distribute the lengths of the dependents into two classes ‘1ʹ 

and ‘>1ʹ and assess the distribution of this dichotomized variable over the five diachronic layers. 

The test yields a highly significant result of Z = –16.332, dim: 5, p = 0.001. 

Discontinuous Linearization of Vedic Nominal Expressions 

[[65]]

fiers of length 1 are in general found in continuous linearization \(Figure 2, bottom left\). 

Surprisingly, however, such an interpretation is not fully endorsed by a CMH test that uses the lengths of the dependents as the control variable when assessing differences in \(dis-\)continuous linearization in the diachronic layers of the Vedic corpus.3 Even if we control for the length of the modifiers, the test yields a highly significant result of M 2 = 

108.56, DF: 4, p < 0.001 and thus points to substantial differences in how \(dis-\)continuous linearization is distributed over the diachronic layers. Cochran-Armitage tests of the three 5 × 2 sub-tables of the 5 × 2 × 3 tensor \(five diachronic layers × \(dis-\)continuous linearization × length classes 1–3; also see Footnote 3\) show significant monotonic trends for dependents of length 1 and 2 \(results in Table 3\). This result indicates that over the Vedic period, there are significant changes in the linearization of complex nominal expressions with modifiers of the length 1 and 2, but not with longer ones. 

**Table 3:** Results of Cochran-Armitage 

tests for dependents of fixed length 

\(column one\). The tests show 

significant monotonic trends only for 

modifiers of length one and two. 

**Length**

**Z**

**DF**

**p**

1

4.553

5

< 0.001

2

7.477

5

< 0.001

3

0.074

5

0.941

As the tests that include an additional control variable have revealed relevant temporal interactions, we repeat this kind of evaluation for the data plotted in Figure 2 

\(top right\) and Figure 2 \(bottom left\) by expanding the 5 × 2 diachronic table into 5 × 2 × 2 tensors for the two types \(amod, nmod\) and the two relative positions. 

While the CMH tests of these two tensors yield highly significant results,4 the plot of the proportions in Figure 4 displays relevant diachronic trends only for modifiers placed to the left of the modified. While the proportions of discontinuous nominal expressions decrease quite monotonically with both modifier types placed to the 

left of the modified, no such trend is discernible for modifiers of any modifier type to the right of the modified. We leave the examination of these complex interactions for future work applying more refined methodology. 

**3** We do not consider the length class ≥ 4, as there are no such cases with continuous linearization in our data. 

**4** Modifier type: M 2 = 406.12, df: 4, p < 0.001; position: M 2 = 254.78, df: 4, p < 0.001. 



**66** 

Paul Widmer and Oliver Hellwig

**Figure 4:** Diachronic trends in continuous and discontinuous complex nominal expressions, split by modifier type and position of the modifier relative to the modified. While complex nominal expressions with modifiers placed to the left of the modified show an increasing preference for continuous linearization \(top row\), those with the modifier to the right of the modified do not \(bottom row\). 

**\(Dis-\)continuity in the Old Metrical Texts**

Given the topic of these proceedings, we now restrain the evaluation to the oldest metrical texts and test if the metrical parts of the AV differ from RV 2–7, 9 and the Mantra level material of other Saṁhitās with regard to \(dis-\)continuous linearization. This evaluation offers the additional advantage that we do not need to account for interactions with register type as all texts considered in this section are metrical. Table 4 reports the results of tests that compare counts of \(dis-\)continuous nominal expressions in all three substrata. 

Discontinuous Linearization of Vedic Nominal Expressions 

[[67]]

**Table 4:** Differences between the three 

old layers with regard to the use of 

\(dis-\)continuous linearization. 

**Control Statistics**

**DF p**

G = 12.028

2

0.002

Label

M 2 = 14.900

2 < 0.001

Position

M 2 = 9.724

2

0.008

Length

M 2 = 7.191

2

0.027

As the result of the G-test in its first row shows, the distribution in the overall 3 × 2 

table \(three strata, continuous vs. discontinuous\) points to significant differences between the strata. The picture changes when additional control variables are considered using CMH tests \(rows 2ff. in Table 4\). While the differences get even more pronounced when modifier types are distinguished \(‘label’\), modifier position 

and length increase the p-values of the tests and thus make systematic differences between the three strata less probable; the increase is most pronounced for length. 

Table 5 offers a refined pairwise evaluation of the same data. 

**Table 5:** Pairwise comparison of the three old layers. The first row of each compartment gives the result of a G-test of the full table, and the subsequent 

rows give the results for CMH tests with the respective control variable in 

the third column \( M 2\). See the graphical representations in Figure 5. 

**Group 1**

**Group 2**

**Control**

**Statistics**

**DF**

**p**

RV

AV

G = 12.024

1

< 0.001

Label

M 2 = 15.650

1

< 0.001

Position

M 2 = 9.357

1

0.002

Length

M 2 = 6.447

1

0.011

RV

Mantra

G = 3.247

1

0.072

Label

M 2 = 3.524

1

0.061

Position

M 2 = 2.482

1

0.115

Length

M 2 = 1.109

1

0.292

AV

Mantra

G = 5.089

1

0.024

Label

M 2 = 6.213

1

0.013

Position

M 2 = 3.968

1

0.046

Length

M 2 = 3.596

1

0.058



**68** 

Paul Widmer and Oliver Hellwig

**Figure 5:** Interactions with \(dis-\)continuous linearization in texts from the Rigveda and the Mantra period. Test results in Table 4 and Table 5. 

It contrasts the three pairs RV-AV, RV-Mantra and AV-Mantra using the same meth-

odology applied to generate Table 4. The refined evaluation confirms the general 

trends observed in Table 4. While the pairwise differences tend to disappear when position and length are considered, we do observe \(highly\) significant differences when controlling for the modifier type. This observation gets support from the 

visual inspection of the proportions of continuous and discontinuous nominal 

Discontinuous Linearization of Vedic Nominal Expressions 

[[69]]

expressions in Figure 5: across layers they are largely indistinguishable when splitting by position \(middle\) and length \(bottom\), but are rather pronounced, espe-

cially between RV and AV, when controlling for modifier type \(top\). From among 

the three early groups, the AV has the lowest proportion of discontinuous nominal expressions but shows a similarly clear differentiation between adjectives and 

nouns as does the RV proper. This differentiation between modifier types is virtually non-existent for the Mantra texts. 

**Conclusions**

In this exploratory survey of continuity in the linearization of complex nominal 

expressions, we found evidence that in the history of Vedic as represented by five commonly assumed diachronic strata, discontinuity decreases monotonically. Modifier type as well as relative position of modifier and modified interact significantly with the overall decreasing amount of discontinuity. Modifier length contributes 

significantly as well, but only for modifiers consisting of less than three words. 

Applying the same methods to the two earliest, metrical layers of our corpus, 

i.e. Early Vedic \(RV books 2–7, 9\) and Old Vedic \(RV books 1, 8, 10, metrical portions of the Atharvaveda- and Yajurveda-Saṁhitās\) we observe slightly different patterns of interaction. Contrasting Early Vedic with two subsamples of Old Vedic, we find that overall, there are significant differences between the three groups. However, only the modifier type contributes significantly to the difference, modifier position less so, and modifier length is not particularly remarkable. The pairwise comparison of strata discloses a more nuanced picture: Overall, the differences between the AV and the other two strata stand out as being highly significant when compared to Old Vedic and still interesting when compared to Early Vedic. In both comparisons, the modifier type contributes most and the position to a lesser extent. 

These findings suggest that with respect to continuity in the linearization of 

complex nominal expressions, differences cannot be explained by chronological 

stratification alone. In its difference to the oldest Rigvedic layer, the Atharvaveda clearly diverges from other Old Vedic texts. With all due caution, we interpret this as evidence for differences in content and narrative conventions, which encom-passes, of course, differences in syntactic and informational structuring of the text. 

Future research on such syntactic phenomena will certainly take semantic and 

other additional syntactic predictors into account – e.g. type of element causing discontinuity, mutual interaction of multiple modifiers – but it should also integrate the lexical and semantic structure of passages under consideration. 

**70** 

Paul Widmer and Oliver Hellwig

**References**

Agresti, Alan \(2007\). An Introduction to Categorical Data Analysis. Hoboken, New Jersey: John Wiley & Sons. 

Biagetti, Erica, Oliver Hellwig, Elia Ackermann, Paul Widmer, and Salvatore Scarlata \(2021\). “Evaluating Syntactic Annotation of Ancient Languages. Lessons from the Vedic Treebank.” In: Old World 1: 1–32. 

Biber, Douglas \(2012\). “Register as a Predictor of Linguistic Variation.” In: Corpus Linguistics and Linguistic Theory 8 \(1\): 9–37. https://doi.org/10.1515/cllt-2012-0002. 

Brereton, Joel P., and Stephanie W. Jamison \(2020\). The Rigveda: A Guide. New York: Oxford University Press. 

Culbertson, Jennifer, Paul Smolensky, and Géraldine Legendre \(2012\). “Learning Biases Predict a Word Order Universal.” In: Cognition 122 \(3\): 306–329. 

Delbrück, Berthold \(1878\). Die Altindische Wortfolge aus dem çatapathabrāhmaṇa. Halle a. d. S.: Buchhandlung des Waisenhauses. 

Delbrück, Berthold \(1888\). Altindische Syntax. Halle: Verlag der Buchhandlung des Waisenhauses. 

Devine, A. M., and Laurence D. Stephens \(2000\). Discontinuous Syntax. Hyperbaton in Greek. Oxford: Oxford University Press. 

Dunn, Michael, Simon J. Greenhill, Stephen C. Levinson, and Russell D. Gray \(2011\). “Evolved Structure of Language Shows Lineage-Specific Trends in Word-Order Universals.” In: Nature 473 \(7345\): 79–82. 

Gillon, Brendan \(2006\). “Word Order in Classical Sanskrit.” In: Indian Linguistics 57: 1–36. 

Gillon, Brendan, and Benjamin Shaer \(2005\). “Classical Sanskrit, ‘Wild Trees’, and the Properties of Free Word Order Languages.” In: Katalin Kiss \(ed.\): Classical Languages and Generative Linguistics. 

Amsterdam & Philadelphia: Benjamins: 281–317. 

Hellwig, Oliver, Sebastian Nehrdich, and Sven Sellmer. n.d. “Data-Driven Dependency Parsing of Vedic Sanskrit.” Submitted to: Journal of Language Resources and Evaluation. 

Hellwig, Oliver, Salvatore Scarlata, Elia Ackermann, and Paul Widmer \(2020\). “The Treebank of Vedic Sanskrit.” In: Nicoletta Calzolari et al. \(ed.\): Proceedings of the LREC: 5139–5148. 

Hellwig, Oliver, Salvatore Scarlata, and Paul Widmer \(2021\). “Reassessing Rigvedic Strata.” In: Journal of the American Oriental Society, 141.4: 847–866. 

Hock, Hans Henrich \(2013\). “Some Issues in Sanskrit Syntax.” In: Peter M. Scharf and Gérard Huet \(eds.\): Proceedings of the Seminar on Sanskrit Syntax and Discourse Structures. Paris: 1–52. 

Jing, Yingqi, Paul Widmer, and Balthasar Bickel \(2021\). “Word Order Variation Is Partially Constrained by Syntactic Complexity.” In: Cognititive Science 45: e13056. 

Kümmel, Martin Joachim \(2000\). Das Perfekt im Indoiranischen. Wiesbaden: Reichert. 

Levshina, Natalia \(2019\). “Token-Based Typology and Word Order Entropy: A Study Based on Universal Dependencies.” In: Linguistic Typology 23 \(3\): 533–572. 

Louagie, Dana, and Uta Reinöhl \(2021\). “Typologizing Nominal Expressions: The Noun Phrase and Beyond.” In: Linguistics 59. https://doi.org/doi:10.1515/ling-2020-0147. 

Luraghi, Silvia \(2010\). “The Rise \(and Possible Downfall\) of Configurationality.” In: Silvia Luraghi and Vit Bubenik \(eds.\): Continuum Companion to Historical Linguistics. London: Continuum: 212–229. 

Maurits, Luke, and Thomas L Griffiths \(2014\). “Tracing the Roots of Syntax with Bayesian Phylogenetics.” In: Proceedings of the National Academy of Sciences 111.37: 13576–13581. 

Napoli, Donna Jo, and Rachel Sutton-Spence \(2014\). “Order of the Major Constituents in Sign Languages: Implications for All Language.” In: Frontiers in Psychology 5: 376. 

Discontinuous Linearization of Vedic Nominal Expressions 

[[71]]

Nivre, Joakim, Marie-Catherine De Marneffe, Filip Ginter, Yoav Goldberg, Jan Hajic, Christopher D. 

Manning, Ryan McDonald, et al. \(2016\). “Universal Dependencies V1: A Multilingual Treebank Collection.” In: Proceedings of the Tenth International Conference on Language Resources and Evaluation, 1659–1666. 

Reinöhl, Uta \(2020\). “Continuous and Discontinuous Nominal Expressions in Flexible \(or ‘Free’\) Word Order Languages: Patterns and Correlates.” In: Linguistic Typology 24.1: 71–111. 

Sauppe, Sebastian, Kamal K. Choudhary, Nathalie Giroud, Damián E. Blasi, Elisabeth Norcliffe, Shikha Bhattamishra, Mahima Gulati, et al. \(2021\). “Neural Signatures of Syntactic Variation in Speech Planning.” In: PLoS Biology 19.1: e3001038. 

Schäufele, Steven William \(1990\). Free Word-Order Syntax: The Challenge from Vedic Sanskrit to Contemporary Formal Syntactic Theory. Ann Arbor, Mich.: UMI. 

Spevak, Olga \(2014\). The Noun Phrase in Classical Latin Prose. Leiden: Brill. 

Speyer, J. S. \(1896\). Vedische und Sanskrit-Syntax. Strassburg: Trübner. 

Szmrecsanyi, Benedikt \(2019\). “Register in Variationist Linguistics.” In: Register Studies 1.1: 76–99. 

Tomlin, R.S. \(1986\). Basic Word Order: Functional Principles. Croom Helm. 

Viti, Carlotta \(2015\). Variation und Wandel in der Syntax der alten Indogermanischen Sprachen. Tübingen: Narr. 

Witzel, Michael \(1989\). “Tracing the Vedic dialects.” In: Colette Caillat \(ed.\): Dialectes dans les littératures indo-aryennes. Paris: Collège de France: 97–265. 

Alexander Lubotsky
