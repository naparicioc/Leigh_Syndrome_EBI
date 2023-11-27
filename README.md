# Leigh Syndrome EBI Project

## Introduction

Leigh syndrome is a rare hereditary neurological condition that primarily affects infants aged 3 to 12 months, although it can also occur in teenagers and adults [1]. Symptoms include difficulty with sucking, loss of head control, loss of appetite, vomiting, irritability, persistent crying, and seizures. Over time, patients develop weakness, lack of muscle tone, spasticity, coordination difficulties, developmental delay, ocular disorders, and feeding difficulties [1].

Leigh syndrome involves mutations (point mutations such as substitutions, insertions, or deletions) in different genes at the level of nuclear DNA (nDNA) or mitochondrial DNA (mtDNA) [2]. Generally, most affected genes are involved in energy production processes within the mitochondria through oxidative phosphorylation. This process consists of five protein complexes: complex I, complex II, complex III, complex IV, and complex V. Accordingly, different mutations in Leigh syndrome can affect the proteins of these complexes, reducing or eliminating the activity of each protein set. Therefore, identifying the mutation and diagnosing the syndrome is critical for establishing clinical intervention.

The use of bioinformatics for the study of orphan diseases has gained importance in recent years, mainly due to the absence of identification of patterns or point mutations that can be categorized as responsible for the disease [3]. Computational tools are crucial for analyzing large sets of genetic and molecular data, facilitating the detection of mutations and genetic variants associated with the disease [4]. Additionally, this discipline helps identify potential therapeutic targets and develop more effective treatments through the analysis of DNA sequences and the identification of genes involved in the pathogenesis of the disease. This work aims to determine the impact of various mutations associated with Leigh syndrome on gene expression, protein function, and interactions, as well as metabolic pathways, to propose future research directions for therapeutic development from a bioinformatic approach.

![image](https://github.com/naparicioc/Leigh_Syndrome_EBI/assets/85712714/2769b04b-eb66-4a63-9409-a068165cbd3f)

## Experimental Design

![image](https://github.com/naparicioc/Leigh_Syndrome_EBI/assets/85712714/9a18450e-ad6b-498e-ace6-1d56a49f0f04)

## Filtering Criteria

Leigh syndrome can be caused by mutations in a large group of genes. Five genes were selected for this study considering the following aspects:

1. The most common genes and the most relevant causes for the manifestation of Leigh syndrome, according to [5].

2. The availability of the information in different bioinformatics tools.

3. Maintaining the heterogeneity of the mutations and the location of the genes at both the nuclear and mitochondrial DNA levels.

Different searches were performed in databases such as Europe PMC by means of the following command lines:

```
"Leigh syndrome" date:2019-2023
```

```
("Leigh syndrome" OR "Leigh disease") AND ("genetic diseases" OR "neurology" OR "responsible genes") date:2019-2023
```

```
"BCS1L" AND "complex III" AND "Leigh" date:2019-2023
```

## Chosen Genes and Their Mutations

The following tables display the genes that were considered for this study with reported mutations associated with Leigh syndrome and other clinical presentations.

![image](https://github.com/naparicioc/Leigh_Syndrome_EBI/assets/85712714/80b460fe-18b5-42af-9bf8-9af4245d314a)

![image](https://github.com/naparicioc/Leigh_Syndrome_EBI/assets/85712714/4cfb80bf-839c-4b84-9117-4e29cf72b657)

## Gene Expression Across Diverse Tissues

![image](https://github.com/naparicioc/Leigh_Syndrome_EBI/assets/85712714/44c91c14-936b-4ffb-ad0d-16f9d1ff307d)

We discovered that genes *BCS1L*, *SURF1*, and *PDSS2* have low tissue specificity. On the contrary, *MT-ATP6* and *PDHB* present specificity in heart muscle and tongue tissue, respectively. We also determined that mitochondrial dysfunction is an important cause of heritable vision loss. Primary optic nerve atrophy resulting from the death of retinal ganglion cells is the most prominent ocular manifestation of mitochondrial disease [6]. Actually, retinal dystrophy is presented in 23% of children with Leigh syndrome [6]. 

Finally, we understood the relationship between Leigh syndrome and renal pathologies. Of four patients with Leigh syndrome due to a mutation in the *SURF1* gene, three had significant proximal RTA (Renal Tubular Acidosis) [6]. In a neonate with Leigh syndrome due to a mutation in the *ACAD9* gene, an autopsy revealed hyperplasia of mitochondria in renal tubular cells [7]. In a patient with Leigh syndrome, due to a mutation in the ND5 gene, renal salt loss was responsible for secondary hyponatremia [8].

## Protein Function and the Presence of Mutations

![image](https://github.com/naparicioc/Leigh_Syndrome_EBI/assets/85712714/e8f949e5-1fa8-4b40-b350-0c1ab0fcdef7)

We identified the domains for all the proteins encoded by the genes previously discussed. In this way, we found out that the majority of the mutations related to Leigh syndrome and other clinical presentations are mostly located in important domains of protein function and result mostly in protein, mitochondrial complex III [9], and Cytochrome-c oxidase deficiency [10]

## References 

[1] Rahman, S., & Thorburn, D. (2015). Nuclear gene-encoded Leigh syndrome overview. GeneReviews®, ed. Seattle, WA: University of Washington.

[2] Finsterer, J. (2008). Leigh and Leigh-like syndrome in children and adults. Pediatric neurology, 39(4), 223-235. 

[3] Thorburn, D. R., Rahman, J., & Rahman, S. (2017). Mitochondrial DNA-associated Leigh syndrome and NARP.

[4] Lago Sampedro, A. M., & García Escobar, E. (2022). Importancia de la bioinformática en la medicina actual. Importancia de la bioinformática en la medicina actual. ¿Es realmente necesaria la bioinformática en la práctica clínica?

[5] Ruhoy, I. S., & Saneto, R. P. (2014). The genetics of Leigh syndrome and its implications for clinical practice and risk management. The application of clinical genetics, 221-234.

[6] Gospe, S. M., Travis, A. M., Kolesnikov, A. V., Klingeborn, M., Wang, L., Kefalov, V. J., & Arshavsky, V. Y. (2019). Photoreceptors in a mouse model of Leigh syndrome are capable of normal light-evoked signaling. Journal of Biological Chemistry, 294(33), 12432-12443.

[7] Leslie, N., Wang, X., Peng, Y., Valencia, C. A., Khuchua, Z., Hata, J., ... & Bove, K. E. (2016). Neonatal multiorgan failure due to ACAD9 mutation and complex I deficiency with mitochondrial hyperplasia in liver, cardiac myocytes, skeletal muscle, and renal tubules. Human Pathology, 49, 27-32.

[8] Brecht, M., Richardson, M., Taranath, A., Grist, S., Thorburn, D., & Bratkovic, D. (2015). Leigh syndrome caused by the MT-ND5 m. 13513G> A mutation: a case presenting with WPW-like conduction defect, cardiomyopathy, hypertension and hyponatraemia. JIMD Reports, Volume 19, 95-100.

[9] Castagna, A. E., Addis, J., McInnes, R. R., Clarke, J. T., Ashby, P., Blaser, S., & Robinson, B. H. (2007). Late onset Leigh syndrome and ataxia due to a T to C mutation at bp 9,185 of mitochondrial DNA. American Journal of Medical Genetics Part A, 143(8), 808-816.

[10] Lee, I. C., El‐Hattab, A. W., Wang, J., Li, F. Y., Weng, S. W., Craigen, W. J., & Wong, L. J. C. (2012). SURF1‐associated leigh syndrome: a case series and novel mutations. Human mutation, 33(8), 1192-1200.
