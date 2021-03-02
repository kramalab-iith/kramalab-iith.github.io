---
layout: page-fullwidth
title: "Research"
meta_title: ""
subheadline: ""
teaser: ""
permalink: "/research/"
header:
    image_fullwidth: "graph.jpg"
---
<div data-magellan-expedition="fixed">
  <ul class="sub-nav">
    <li data-magellan-arrival="Overview"><a href="#Overview">Overview</a></li>
    <li data-magellan-arrival="Topological_Data_Analysis_(TDA)"><a href="#Topological-Data_Analysis_(TDA)">Topological Data Analysis (TDA)</a></li>
    <li data-magellan-arrival="Liver_cancer_genomics"><a href="#Liver_cancer_genomics">Liver cancer</a></li>
    <li data-magellan-arrival="Lung_cancer_genomics"><a href="#Lung_cancer_genomics">Lung cancer</a></li>
    <li data-magellan-arrival="Lymphoma_genomics"><a href="#Lymphoma_genomics">Lymphoma</a></li>
    <li data-magellan-arrival="Head_and_neck_cancer_genomics"><a href="#Head_and_neck_cancer_genomics">Head and neck cancer</a></li>
    <li data-magellan-arrival="Immunogenomics"><a href="#Immunogenomics">Immunogenomics</a></li>
    <li data-magellan-arrival="Variant_interpretation"><a href="#Variant_interpretation">Variant interpretation</a></li>
    <li data-magellan-arrival="Precision_medicine"><a href="#Precision_medicine">Precision medicine</a></li>
  </ul>
</div>

<h2 data-magellan-destination="Overview">Overview</h2>
<a name="Overview"></a>

The Griffith lab is a combined research group driven by the interests of twin scientists [Malachi Griffith](http://malachigriffith.org/) and [Obi Griffith](http://obigriffith.org/). The focus of the lab is on developing methods of applied bioinformatics for personalized medicine and improved cancer care.

Our research is committed to development of open access and open source resources for cancer genome analysis. Research projects cover a wide spectrum of cancer informatics and clinical statistics with an emphasis on translation and application. Specifically, we use computational methods for the analysis of large cancer datasets at the molecular level (DNA, RNA and protein) to identify markers for diagnosis, prognosis and drug response prediction in cancer. We have contributed to the early development of methods for analysis of transcriptional regulation (ORegAnno) and RNA-seq analysis and visualization (ALEXA-seq Platform).

The group is engaged in a large number of tumor sequencing projects for breast, lymphoma, glioblastoma, lung, and other cancers, investigating primary, relapse and drug resistant tumors. To this end we have worked with others at the [McDonnell Genome Institute](http://genome.wustl.edu/) to develop end-to-end pipelines for clinical cancer sequencing that automate state-of-the-art methods for sequence alignment, somatic variation detection, RNA sequence analysis, and the integration of these data types into user-friendly reports of the most clinically relevant genome and transcriptome changes in a tumor or cohort of tumors ([Genome Modeling System](https://github.com/genome/gms/wiki)). To aid in this effort our group has developed software, databases, knowledgebases, and web tools for interrogation of the druggable genome ([DGIdb](http://dgidb.org/)), identification of cancer driver mutations ([DoCM](http://docm.info/)), interpretation of clinically actionable variants in cancer ([CIViC](http://civicdb.org)), and genomic visualization ([GenVisR](https://bioconductor.org/packages/release/bioc/html/GenVisR.html)). The group is also actively involved in the identification and scoring of tumor neoantigens and development of related software for design of human cancer vaccines ([pVACtools](http://pvactools.org)). We are also working with organizations such as the Global Alliance for Genomics Health (GA4GH) to help define data models and standard for clinical translation of genomics data, in particular through our leadership of the driver project: [Variant Interpretation for Cancer Consortium](http://cancervariants.org).

In addition to our basic and clinical research interests, we are also passionate about the scholarship of teaching and learning. We have made substantial contributions to the training and education of tomorrow's bioinformaticians through our involvement in [CBW](https://bioinformatics.ca/), [CSHL](http://meetings.cshl.edu/courses.aspx?course=C-SEQTEC&year=18) workshops and the [BioStars](https://www.biostars.org/) forum. We have developed online courses for [RNA sequence analysis](http://rnabio.org), [Genomic Visualization in R](http://genviz.org), and [precision/personalized medicine bioinformatics](http://pmbio.org).

<hr>

<h2 data-magellan-destination="Topological_Data Analysis_(TDA)">Topological Data Analysis (TDA)</h2><a name="Topological_Data_Analysis_(TDA)"></a>

{% include project
title="“Blue Brain Project” in Neuroscience"

description="
<p>
<h4>Task:</h4>
To build a biologically detailed digital reconstruction and simulation of the mouse brain to better understand multi-level structures and functions of the brain.
</p>

<p>
<h4>Benefits:</h4>
Contribution to the development of new computing technology – neurorobotics and neuromorphic computing. Understanding the brain is essential to diagnosing and treating brain diseases that are imposing a rapidly increasing burden on the world's ageing populations.
</p>

<p>
<h4>Role of TDA:</h4>
How can the shapes of neurons be classified using mathematical methods from the field of algebraic topology. Can we predict future formations? What is the “shape” structure of neurons telling us?
</p>

<p>
<h4>Research Challenges:</h4>
The main challenge is to reduce the complexity of neuron models (e.g. dimensionality reduction) while retaining their key input/output functions and their computational capabilities. The other challenge is whether 2 similar neurons belong to different types or to a continuum of the same type.
</p>

<p>
<h4>What can we do?:</h4>
We can use TDA and Deep Learning (DL) to classify pyramidal cells (PC) [1], i.e., “higher-order” structures / relations in the neurons. We can construct an efficient topological representation from a neuronal tree which can be further incorporated into a DL architecture to objectively classify cortical PCs.
</p>
"
image="/assets/img/research/blue_brain_combined.jpg"

%}

{% include project
title="Financial Market analysis with Time Series data"

description="
<p>
<h4>Task:</h4>
Store market data to identify historical trends and correlations using statistical methods and generate trading signals. In investing, a time series tracks the movement of the chosen data points, such as a security’s price, over a specified period of time with data points recorded at regular intervals
</p>

<p>
<h4>Benefits:</h4>
Analysis can be useful to see how a given asset, security, or economic variable changes over time. It can also be used to examine how the changes associated with the chosen data point compared to shifts in other variables over the same time period.
</p>

<p>
<h4>Role of TDA:</h4>
Can construct informative and robust features based on topological data analysis, without any time-dependent structural, or probabilistic assumptions on the data generating process. Specifically, systematic procedure where one can successfully harness topological features of the attractor of the underlying dynamical system for an observed time series with favorable theoretical properties.
</p>

<p>
<h4>Research Challenges:</h4>
Forecasting stock prices is a very difficult and challenging task in the financial market because the trends of stock prices are in fact “non-linear” and “non-stationary” time-series data.

</p>

<p>
<h4>What can we do?:</h4>
We can apply TDA for feature extraction in time series data by leveraging tools from topological data analysis. These TDA-based features are robust to sampling noise and can be used for classification and anomaly detection (either directly or using DL) [1][2][3].

</p>
"
image="/assets/img/research/blue_brain_combined.jpg"

%}

<h2 data-magellan-destination="Liver_cancer_genomics">Liver cancer genomics</h2>
<a name="Liver_cancer_genomics"></a>

{% include project
title="A genomic case study of mixed fibrolamellar hepatocellular carcinoma"

task="To build a biologically detailed digital reconstruction and simulation of the mouse brain to better understand multi-level structures and functions of the brain."

benefits="Contribution to the development of new computing technology – neurorobotics and neuromorphic computing. Understanding the brain is essential to diagnosing and treating brain diseases that are imposing a rapidly increasing burden on the world's ageing populations."

team="Obi Griffith, Malachi Griffith, Kilannin Krysiak, Avinash Ramu, Zachary Skidmore, Jason Kunisaki"

image="/assets/img/research/HCC32_combined.png"

citation="Griffith, Griffith, Krysiak et al. 2016. Annals of Oncology. 27(6):1148-54."

pmid="27029710"
%}

<h2 data-magellan-destination="Lung_cancer_genomics">Lung cancer genomics</h2>
<a name="Lung_cancer_genomics"></a>

{% include project
title="Recurrent WNT Pathway Alterations are Frequent in Relapsed Small Cell Lung Cancer"

description="Nearly all patients with small cell lung cancer (SCLC) eventually relapse with chemotherapy resistant disease. The molecular mechanisms driving chemotherapy resistance in SCLC remain to be characterized. We performed whole-exome sequencing of paired SCLC tumor samples procured at diagnosis (treatment-naive samples) and relapse (relapse samples) from 12 patients, along with unpaired relapse samples obtained from 18 additional patients. We observed multiple somatic copy number alterations including gains in ABCC1, and deletions in MYCL, MSH2, and MSH6 among relapse samples. Relapse samples also showed recurrent mutations in regulators of WNT signaling such as CHD8 and APC. Analysis of RNA-sequencing data suggested an enrichment for “ASCL1-low” expression subtype and WNT activation in relapse samples. Activation of WNT signaling in chemotherapy sensitive human SCLC cell lines through APC knockdown induced chemotherapy resistance. Additionally, in vitro-derived chemotherapy resistant cell lines demonstrated increased WNT activity. Our results support a role for WNT signaling activation as a mechanism of chemotherapy resistance in relapsed SCLC."

team="Alex Wagner, Zach Skidmore, Kilannin Krysiak, Avinash Ramu, Lee Trani, Jason Kunisaki, Nick Spies"

image="/assets/img/research/SCLC_figure_1b.png"

citation="Wagner, Devarakonda, et al. Recurrent WNT pathway alterations are frequent in relapsed small cell lung cancer. Nat Commun. 2018 Sep 17;9(1):3787."

pmid="30224629"

%}

<h2 data-magellan-destination="Lymphoma_genomics">Lymphoma genomics</h2>
<a name="Lymphoma_genomics"></a>

{% include project
title="Recurrent somatic mutations affecting B-cell receptor signaling pathway genes in follicular lymphoma"

description="Follicular lymphoma (FL) is the most common form of indolent non-Hodgkin lymphoma, yet it remains only partially characterized at the genomic level. To improve our understanding of the genetic underpinnings of this incurable and clinically heterogeneous disease, whole-exome sequencing was performed on tumor/normal pairs from a discovery cohort of 24 patients with FL. Using these data and mutations identified in other B-cell malignancies, 1716 genes were sequenced in 113 FL tumor samples from 105 primarily treatment-naive individuals. We identified 39 genes that were mutated significantly above background mutation rates. CREBBP mutations were associated with inferior PFS. In contrast, mutations in previously unreported HVCN1, a voltage-gated proton channel-encoding gene and B-cell receptor signaling modulator, were associated with improved PFS. In total, 47 (44.8%) patients harbor mutations in the interconnected B-cell receptor (BCR) and CXCR4 signaling pathways. Histone gene mutations were more frequent than previously reported (identified in 43.8% of patients) and often co-occurred (17.1% of patients). A novel, recurrent hotspot was identified at a posttranslationally modified residue in the histone H2B family. This study expands the number of mutated genes described in several known signaling pathways and complexes involved in lymphoma pathogenesis (BCR, Notch, SWitch/sucrose nonfermentable (SWI/SNF), vacuolar ATPases) and identified novel recurrent mutations (EGR1/2, POU2AF1, BTK, ZNF608, HVCN1) that require further investigation in the context of FL biology, prognosis, and treatment."

team="Kilannin Krysiak, Felicia Gomez, Matthew Matlock, Lee Trani, Malachi Griffith, Obi Griffith"

image="/assets/img/research/FL_Histone_CoOccurence.png"

citation="Krysiak et al. 2017. Recurrent somatic mutations affecting B-cell receptor signaling pathway genes in follicular lymphoma. Blood. 129(4):473-483."

pmid="28064239"
%}

<h2 data-magellan-destination="Head_and_neck_cancer_genomics">Head and neck cancer genomics</h2>
<a name="Head_and_neck_cancer_genomics"></a>

{% include project
title="Oral cavity squamous cell carcinoma xenografts"

description="Comprehensive genomic analysis was performed on patient derived xenografts for oral squamous cell carcinomas (OSCC). We found PDX samples were largely correlative with the primary tumors from which they were derived. PDX models were able to retain the heterogeneous mutational landscape and clonal architecture of tumors. Somatic differences between the PDX and corresponding OSCC primary samples consisted primarily of low-frequency mutations, making these xenografts ideal models for exploring OSCC tumor biology."

team="Katie Campbell, Zachary Skidmore, Erica Barnell, Malachi Griffith, Obi Griffith"

image="/assets/img/research/oscc_pdx_graphical_abstract.png"

citation="Campbell, Lin T, Zolkind P, et al. Oral Cavity Squamous Cell Carcinoma Xenografts Retain Complex Genotypes and Intertumor Molecular Heterogeneity. Cell Rep. 2018 Aug 21;24(8):2167-2178."

pmid="30134176"

%}

<h2 data-magellan-destination="Immunogenomics">Immunogenomics</h2>
<a name="Immunogenomics"></a>

{% include project
title="Neoantigen characterization and personalized cancer vaccine design"

description="In support of several clinical trials we are creating and applying new immunogenomics tools to help predict response to checkpoint blockade inhibition therapies and design personalized cancer vaccines."

team="Jasreet Hundal, Katie Campbell, Yang-Yang Feng, Connor Liu, Joshua McMichael, Susanna Kiwala, Obi Griffith, Malachi Griffith"

image="/assets/img/research/immunogenomics.png"

citation="Hundal et al. Genome Med. 2016 Jan 29;8(1):11."

pmid="26825632"
%}

<h2 data-magellan-destination="Variant_interpretation">Variant interpretation</h2>
<a name="Variant_interpretation"></a>

{% include project
title="CIViC: a community knowledgebase for expert crowdsourcing the clinical interpretation of variants in cancer"

description="CIViC is an expert-crowdsourced knowledgebase for Clinical Interpretation of Variants in Cancer describing the therapeutic, prognostic, diagnostic and predisposing relevance of inherited and somatic variants of all types. CIViC is committed to open-source code, open-access content, public application programming interfaces (APIs) and provenance of supporting evidence to allow for the transparent creation of current and accurate variant interpretations for use in cancer precision medicine."

team="Malachi Griffith, Nicholas Spies, Kilannin Krysiak, Josh McMichael, Adam Coffman, Arpad Danos, Benjamin Ainscough, Cody Ramirez, Lynzey Kujan, Erica Barnell, Alex Wagner, Zachary Skidmore, Connor Liu, Rachel Bilski, Robert Lesurf, Yang Yang Feng, Lee Trani, Matt Matlock, Avinash Ramu, Katie Campbell, Greg Spies, Aaron Graubert, Jason Walker, Obi Griffith"

image="/assets/img/research/GP-127_CIViC_simplified-overview_v2d.png"

citation="Griffith, Spies, Krysiak et al. 2017. Nature Genetics. 49(2):170–174."

pmid="28138153"

%}

<h2 data-magellan-destination="Precision_medicine">Precision medicine</h2>
<a name="Precision_medicine"></a>

{% include project
title="Genome analysis of relapsed adult ALL case reveals personalized therapeutic strategy"

description="Extensive genomic analyses were performed in an adult with post-allo relapsed B-ALL. Mutations were found in EP300, NF1, IKZF1, SETD2, RB1, PAX5, NF1, ETV6, and ZNF384. Transcriptome analysis identified aberrant overexpression of the FLT3 gene. Treatment with the FLT3 inhibitor sunitinib induced a rapid clinical and molecular response. This study demonstrates a powerful proof-of-principle that comprehensive genomic studies can sometimes reveal unexpected clinically actionable therapeutic targets."

team="Malachi Griffith, Obi Griffith, Kilannin Krysiak, Zachary Skidmore, Avinash Ramu, Alex Wagner, Katie Campbell, Robert Lesurf, Jasreet Hundal, Nicholas Spies, Benjamin Ainscough, Jason Walker"

image="/assets/img/research/ALL1_GraphicalAbstract_neutral.png"
citation="Griffith et al. 2016. Experimental Hematology. 44(7):603-13."

pmid="27181063"
%}

{% include project
title="Optimizing Cancer Genome Sequencing and Analysis"

description="Tumors are typically sequenced to depths of 75-100x (exome) or 30-50x (whole genome). We demonstrated that current sequencing paradigms are inadequate for tumors that are impure, aneuploid or clonally heterogeneous. To reassess optimal sequencing strategies, we performed ultra-deep (up to ~312x) whole genome sequencing (WGS) and exome capture (up to ~433x) of a primary acute myeloid leukemia, its subsequent relapse, and a matched normal skin sample. We tested multiple alignment and variant calling algorithms and validated ~200,000 putative SNVs by sequencing them to depths of ~1,000x. Additional targeted sequencing provided over 10,000× coverage and ddPCR assays provided up to ~250,000x sampling of selected sites. We evaluated the effects of different library generation approaches, depth of sequencing, and analysis strategies on the ability to effectively characterize a complex tumor. This dataset, representing the most comprehensively sequenced tumor described to date, serves as an invaluable community resource."

team="Malachi Griffith, Obi Griffith, Kilannin Krysiak, Zach Skidmore, Avinash Ramu, Jason Walker, Lee Trani"

image="/assets/img/research/AML31_Slider_Image.png"
citation="Griffith, Miller et al. 2015. Cell Systems. 1(3):210-223."

pmid="26645048"
%}
