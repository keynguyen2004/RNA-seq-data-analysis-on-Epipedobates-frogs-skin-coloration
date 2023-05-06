# RNA-seq-data-analysis-on-Epipedobates-frogs-skin-coloration

### Project goal
The genus of poison dart frogs Epipedobates, native to Columbia and Ecuador, are known to sequester alkaloids into their skin, which act as a chemical defense against predators. There are species of Epipedobates that are

1. Aposematic - use bright color to warn predators it's poisonous
2. Cryptic - dull color


The project aims to perform a comparative transcriptomics study using RNA-sequencing (Tag-Seq) that focuses on Epipedobates’ gene expression relative to their alkaloid uptake and pinpoint the differentiated genes behind the frogs' aposematism.


### Hypothesis
The project used RNA transcriptomes in the liver, a focal site of metabolism, of wild-caught Epipedobates - 2 cryptic species and 2 aposematic species. We hypothesize that the difference between cryptic and aposematic skin coloration of Epipedobates is due to differential gene expression in the frogs’ livers
 

### Workflow
Below is the diagram outlining the main steps of the project's workflow

![Poison Frog Livers Workflow](https://user-images.githubusercontent.com/110079224/236591103-d986baa0-d858-4670-b2eb-681416ac4d57.png)


### Data analysis
We'll be focusing on the following four data analysis methods to extract a pattern that differentiated the two groups 

1. Principal Component Analysis (PCA)
2. Differential Gene Expression (DGE) Analysis
3. Gene Ontology (GO) Analysis
4. Discriminant Analysis of Principal Components (DAPC)

Using the results produced from these data analyses, we can identify the differentially expressed genes that separate cryptic and aposematic species. 


### Results
Overall, our data analysis shows no clear separation between cryptic and aposematic species. 

1. The PCA does not show any clusters that differentiated cryptic and aposematic species
2. The DGE analysis showing differentially expressed genes have no particular pattern as it occurred independent of the skin coloration. 
3. The DAPC returns the genes that’s responsible for the separation between cryptic and aposematic species that are either common genes or those not found in the DGE and GO analysis. 

All together, we cannot attribute the differential gene expression of the frogs’ livers to its difference in skin coloration. Therefore, our hypothesis is not supported.


### Evaluation and further consideration
To begin with, the project has some limitations. Firstly, we were dealing with limited samples as we can only perform data analysis on 2 cryptics and 2 aposematics species of Epipedobates. Secondly, our results were not verify and that could raise some issues regarding the reliability of our conclusion.

Going forward, we would also wanted to approach the data analysis using different factors such as sex, which have been found to potentially cause the difference between cryptic and aposematic species of Epipedobates.
