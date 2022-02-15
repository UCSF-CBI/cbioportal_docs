

# cBioPortal FAQs

* [General Questions](#general-questions)
  * [What is the cBioPortal for Cancer Genomics?](#what-is-the-cbioportal-for-cancer-genomics)
  * [How do I learn how to do queries in cBioPortal?](#how-do-i-learn-how-to-do-queries-in-cbioportal)
  * [What are the terms of use?](#what-are-the-terms-of-use)
  * [What data types are in the portal?](#what-data-types-are-in-the-portal)
  * [Does the portal work on all browsers and operating systems?](#does-the-portal-work-on-all-browsers-and-operating-systems)
  * [How do I cite the cBioPortal?](#how-do-i-cite-the-cbioportal)
  * [Can I use figures from the cBioPortal in my publications or presentations?](#can-i-use-figures-from-the-cbioportal-in-my-publications-or-presentations)
  * [Can I save or bookmark my results in cBioPortal?](#can-i-save-or-bookmark-my-results-in-cbioportal)
  * [Can I use cBioPortal with my own data?](#can-i-use-cbioportal-with-my-own-data)
  * [What is a Virtual Study?](#what-is-a-virtual-study)
  * [What is Group Comparison?](#what-is-group-comparison)
* [Data Questions](#data-questions)
  * [General Data](#general-data)
    * [Which resources are integrated for variant annotation?](#which-resources-are-integrated-for-variant-annotation)
    * [What version of the human reference genome is being used in cBioPortal?](#what-version-of-the-human-reference-genome-is-being-used-in-cbioportal)
    * [What are the sources of biological network data?](#what-are-the-sources-of-biological-network-data)
    * [Are there any normal tissue samples available through cBioPortal?](#are-there-any-normal-tissue-samples-available-through-cbioportal)
    * [Can I download all data at once?](#can-i-download-all-data-at-once)
    * [How current is the data in the portal?](#how-current-is-the-data-in-the-portal)
    * [The data or portal user interface today is different than the last time I looked. What happened?](#the-data-or-portal-user-interface-today-is-different-than-the-last-time-I-looked--what-happened)
    * [How do I access data from AACR Project GENIE?](#how-do-i-access-data-from-aacr-project-genie)
  * [What are the different UCSF cBioPortal Studies?](#what-are-the-different-ucsf-cbioportal-studies)
    * [UCSF500 Old Pipeline Data Freeze](#ucsf500-old-pipeline-data-freeze)
    * [UCSF500](#ucsf500)
      * [Clinical Data for UCSF500](#clinical-data-for-ucsf500)
      * [Genomic Data for UCSF500](#genomic-data-for-ucsf500)
    * [FM](#fm)
      * [Clinical Data for FM](#clinical-data-for-fm)
      * [Genomic Data for FM](#genomic-data-for-fm)
    * [How do I get access to the new pipeline data?](#how-do-i-get-access-to-the-new-pipeline-data)
  * [DNA (Mutations, Copy Number &amp; Fusions)](#dna-mutations-copy-number--fusions)
    * [Does the cBioPortal contain synonymous mutation data?](#does-the-cbioportal-contain-synonymous-mutation-data)
    * [What processing or filtering is applied to generate the mutation data?](#what-processing-or-filtering-is-applied-to-generate-the-mutation-data)
    * [What transcripts are used for annotating mutations?](#what-transcripts-are-used-for-annotating-mutations)
    * [How are protein domains in the mutational lollipop diagrams specified?](#how-are-protein-domains-in-the-mutational-lollipop-diagrams-specified)
    * [What is the difference between a “splice site” mutation and a “splice region” mutation?](#what-is-the-difference-between-a-splice-site-mutation-and-a-splice-region-mutation)
    * [Does the portal display mutation of origin annotations?](#does-the-portal-display-mutation-of-origin-annotations)
    * [How is the copy number data displayed?](#how-is-the-copy-number-data-displayed)
  * [Clinical Data](#clinical-data)
    * [What kind of clinical data is stored in the portal?](#what-kind-of-clinical-data-is-stored-in-the-portal)
    * [What is the meaning of Age and Primary Site?](#what-is-the-meaning-of-age-and-primary-site)
* [Analysis Questions](#analysis-questions)
  * [How can I query/explore a select subset of samples?](#how-can-i-queryexplore-a-select-subset-of-samples)
      * [Defining samples: Query tab on the homepage](#defining-samples-query-tab-on-the-homepage)
      * [Defining samples: Summary study view](#defining-samples-summary-study-view)
      * [Querying with your defined samples](#querying-with-your-defined-samples)
      * [Selecting for negative samples](#selecting-for-negative-samples)
  * [What is OQL?](#what-is-oql)
  * [Is it possible to determine if a particular mutation is heterozygous or homozygous in a sample? When a sample has 2 mutations in one gene, is it possible to determine whether the mutations are in cis or in trans with each other?](#is-it-possible-to-determine-if-a-particular-mutation-is-heterozygous-or-homozygous-in-a-sample-when-a-sample-has-2-mutations-in-one-gene-is-it-possible-to-determine-whether-the-mutations-are-in-cis-or-in-trans-with-each-other)
* [Results View](#results-view)
  * [OncoPrint](#oncoprint)
    * [What are OncoPrints?](#what-are-oncoprints)
    * [Can I change the order of genes in the OncoPrint?](#can-i-change-the-order-of-genes-in-the-oncoprint)
    * [Can I visualize my own data within an OncoPrint?](#can-i-visualize-my-own-data-within-an-oncoprint)
* [Other pages](#other-pages)
   * [Does the Exclusivity tab calculate its statistics using all samples/alterations or only a specific subset?](#does-the-mutual-exclusivity-tab-calculate-its-statistics-using-all-samplesalterations-or-only-a-specific-subset)
   * [What if I have other questions or comments?](#what-if-i-have-other-questions-or-comments)

# General Questions

### What is the cBioPortal for Cancer Genomics?

The cBioPortal for Cancer Genomics is a resource for the interactive exploration of multidimensional cancer genomics data sets that was developed at Memorial Sloan Kettering Cancer Center. The goal of cBioPortal is to significantly lower the barriers between complex genomic data and cancer researchers by providing rapid, intuitive, and high-quality access to molecular profiles and clinical attributes from large-scale cancer genomics projects, and therefore to empower researchers to translate these rich data sets into biologic insights and clinical applications.

The cBioPortal software is now available under an open source license via [GitHub](https://github.com/cBioPortal/cbioportal). The software is now developed and maintained by a multi-institutional team, consisting of MSK, the Dana Farber Cancer Institute, Princess Margaret Cancer Centre in Toronto, Children's Hospital of Philadelphia, [The Hyve](https://thehyve.nl/) in the Netherlands, and Bilkent University in Ankara, Turkey.

Individual institutions can create their own customizable ‘copy’ or instance of the cBioPortal tool and load their own datasets into the portal. 

Currently, the UCSF cBioPortal instance contains genomic data generated by the UCSF500 assay as well as Foundation Medicine data. Please refer to the '[What are the different UCSF cBioPortal Studies?](#what-are-the-different-ucsf-cbioportal-studies)' section for more information. 

### How do I learn how to do queries in cBioPortal?

Check out these [tutorial slides](https://www.cbioportal.org/tutorials) to get started or go through the Gao et al [tutorial paper](http://www.ncbi.nlm.nih.gov/pubmed/23550210).

You can also refer to the [Analysis Questions](#analysis-questions) section in this FAQs manual.

Additionally, we will also be working with the UCSF Library to develop a basic cBioPortal tutorial course.

### What are the terms of use?

All users must agree to the terms of use before they have access to the data:
1. I will not attempt to identify or contact individual participants from whom these data were collected by any means   without specific approval from the UCSF institutional review board.
2. I will not redistribute or share the UCSF dataset or any elements of this dataset with investigators or other individuals who are not employed by UCSF.
3. When publishing or presenting work using or referencing data from the UCSF dataset, I agree to include an acknowledgement of both the Clinical CancerGenomics Laboratory and Molecular Oncology Initiative at UCSF.

### What data types are in the portal?

The portal supports and stores non-synonymous mutation data, DNA copy-number data, fusion data, test metadata, and de-identified clinical data.

More technical information on these data types are provided in the [DNA (Mutations, Copy Number &amp; Fusions)](#dna-mutations-copy-number--fusions) section in this FAQs manual.

cBioPortal does have the ability to support additional data types including mRNA and microRNA expression data, protein-level and phosphoprotein level data (RPPA or mass spectrometry based), and DNA methylation data.

### Does the portal work on all browsers and operating systems?

The team developing and maintaining the cBioPortal software support and test on the following web browsers: Safari, Google Chrome, Firefox and Edge. As of release v3.5.4, Internet Explorer 11 is no longer supported. 

### How do I cite the cBioPortal?

Please cite the following portal papers:

* Cerami et al. The cBio Cancer Genomics Portal: An Open Platform for Exploring Multidimensional Cancer Genomics Data. Cancer Discovery. May 2012 2; 401. [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/22588877).

* Gao et al. Integrative analysis of complex cancer genomics and clinical profiles using the cBioPortal. Sci. Signal. 6, pl1 (2013). [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/23550210).

### Can I use figures from the cBioPortal in my publications or presentations?

Yes, you are free to use any of the figures from the portal in your publications or presentations (many are available in SVG or PDF format for easier scaling and editing).

Please remember to acknowledge both the Clinical Cancer Genomics Laboratory and Molecular Oncology Initiative at UCSF.

Additionally, please provide credit to the original developers of the cBioPortal application by citing:

* Cerami et al. The cBio Cancer Genomics Portal: An Open Platform for Exploring Multidimensional Cancer Genomics Data. Cancer Discovery. May 2012 2; 401. [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/22588877).

* Gao et al. Integrative analysis of complex cancer genomics and clinical profiles using the cBioPortal. Sci. Signal. 6, pl1 (2013). [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/23550210).

### Can I save or bookmark my results in cBioPortal?

You can bookmark your query results and share the URL with collaborators. We store all queries via Session IDs, and these are saved indefinitely. Use the bookmark tab to retrieve the full link or generate a short link via the bit.ly link generator.

### Can I use cBioPortal with my own data?

Both the [OncoPrint](https://cbioportal.ucsf.edu/cbioportal/oncoprinter.jsp) and [Lollipop Plot](https://cbioportal.ucsf.edu/cbioportal/mutation_mapper) visualization tools can be used with your own dataset.

If you have a dataset you want to include as a distinct study in the UCSF cBioPortal that can be analyzed using the entire suite of analysis and visualization tools, we encourage you to contact [us](mailto:ucsf.cbioportal@ucsf.edu) with the particulars of your dataset.

### What is a Virtual Study?

A virtual study is a custom study comprised of samples from one or more existing studies. The virtual study feature allows you to define a custom cohort of samples that fit your specific genomic or clinical criteria of interest. These samples can be a subset of the data available in an existing study, or result from the combination of multiple existing studies. This cohort of samples can then be queried or explored just like a traditional study, and can be returned to at a later date or shared with a collaborator. For more information and examples, see our [tutorial on virtual studies](https://www.cbioportal.org/tutorials).

### What is Group Comparison?

Group Comparison is a suite of analysis features which allows a user to compare clinical or genomic features of user-defined groups of samples. These groups can be defined based on any clinical or genomic features. For an overview, see our [tutorial on group comparison](https://www.cbioportal.org/tutorials).

# Data Questions

## General Data

### Which resources are integrated for variant annotation?

cBioPortal supports the annotation of variants from several different databases. These databases provide information about the recurrence of, or prior knowledge about, specific amino acid changes.

* For each variant, the number of occurrences of mutations at the same amino acid position present in the COSMIC database are reported.

* Variants are annotated as “hotspots” if the amino acid positions were found to be recurrent linear hotspots, as defined by the Cancer Hotspots method ([cancerhotspots.org](http://www.cancerhotspots.org/)), or three-dimensional hotspots, as defined by 3D Hotspots ([3dhotspots.org](https://www.3dhotspots.org/)).

* Prior knowledge about variants, including clinical actionability information, is provided from three different sources: OncoKB ([oncokb.org](http://oncokb.org/)), CIViC ([civicdb.org](https://civicdb.org/)), as well as My Cancer Genome [mycancergenome.org](https://www.mycancergenome.org/)).

* For OncoKB, exact levels of clinical actionability are displayed in cBioPortal, as defined by [the OncoKB](https://www.oncokb.org/levels).

* In the OncoPrint view, mutations labeled as either putative driver or unknown significance are derived from OncoKB or Cancer Hotspots. 

<img src="https://raw.githubusercontent.com/UCSF-CBC/cbioportal_docs/master/docs/images/cbio_drivers.png" width="35%">

### What version of the human reference genome is being used in cBioPortal?

cBioPortal currently uses hg19/GRCh37.

### What are the sources of biological network data?

The biological network data were retrieved from [Pathway Commons](http://www.pathwaycommons.org/).

### Are there any normal tissue samples available through cBioPortal?

No, we currently do not store any normal tissue data in our system. Our instance does include pathogenic, likely pathogenic, and possibly pathogenic germline variants, though. Please refer to the [Does the portal display mutation of origin annotations?](#does-the-portal-display-mutation-of-origin-annotations) section in this FAQs manual for more information.

### Can I download all data at once?

You can download the entire cohort, sub-cohorts, or individual patient data on the portal. Additionally, all of the figures in the portal are downloadable.

Please remember when publishing or presenting work using or referencing data from the UCSF dataset, to acknowledge both the Clinical Cancer Genomics Laboratory and Molecular Oncology Initiative at UCSF.

Please also refer to the following:

* [How do I cite the cBioPortal?](#how-do-i-cite-the-cbioportal)

* [Can I use figures from the cBioPortal in my publications or presentations?](#can-i-use-figures-from-the-cbioportal-in-my-publications-or-presentations)

### How current is the data in the portal?

Please refer to the [News](https://cbioportal.ucsf.edu/cbioportal/news) page; updates on new data added in each release will be described there. We will update the portal with additional tumor genomic testing cases every month. 

**Data releases are planned for the first full week of each month and will be announced to users via email.**

### The data or portal user interface today is different than the last time I looked. What happened?

**The user interface looks different**

The cBioPortal developers regularly release new versions of the software. Descriptions of the items in each release can be found on the GitHub [page](https://github.com/cBioPortal/cbioportal/releases) for cBioPortal.

Data refreshes of the UCSF cBioPortal will occur on a monthly basis, and we will bundle any new versions of the cBioPortal application that become available. The [News](https://cbioportal.ucsf.edu/cbioportal/news) page will summarize any new features or functionality and user interface changes that occur between versions of the portal.

**The data looks different**

We will be uploading more UCSF500 and FM cases to the portal every month so the number of samples profiled will expand over time. Additionally, we will be adding more annotations, with an emphasis on clinical data, into the portal as well.

The [News](https://cbioportal.ucsf.edu/cbioportal/news) page will summarize any new data uploads that occur between versions of the portal.

However, if you suspect that there is an error in the current version, please let us know by contacting [us](mailto:ucsf.cbioportal@ucsf.edu).

### How do I access data from AACR Project GENIE?

Data from AACR Project GENIE are provided in a [dedicated instance of cBioPortal](https://www.cbioportal.org/genie/). You can also download GENIE data from the [Synapse Platform](http://synapse.org/genie). Note that you will need to register before accessing the data.

If you have any questions or run into problems accessing the GENIE cBioPortal, please email [us](mailto:ucsf.cbioportal@ucsf.edu).

#### How is the UCSF cBioPortal instance different from the GENIE cBioPortal?

The UCSF cBioPortal currently has more UCSF500 cases than what is available on the GENIE cBioPortal, however the GENIE cBioPortal has more cases in total as it represents sequenced cases from 19 different institutions. It should be noted, however, that most of the institutions are using different panels having both different technical specifications and gene content.

Additionally, germline variants are currently not included in the GENIE cBioPortal.

The GENIE synapse platform has a data guide and bed file paired with each release of the portal that describes the panel technical and content specifications for each institution. Navigate to the ‘Files’ tab on the wiki page and then the ‘Data Releases’ folder.

## What are the different UCSF cBioPortal Studies

### UCSF500 Old Pipeline Data Freeze

This study contains UCSF500 data _only_ from assay launch (mid-2015) through end of September 2021 generated using our original pipeline. Data in this study IS NOT LINKED to de-identified Warehouse (CDW); surrogate patient identifiers in portal are different from those used for same patients in de-identified CDW.

Clinical data in this study is limited to patient diagnosis, sex, anatomic site of tumor sequenced (captured as 'Primary Site' variable) and age of patient at time of tumor collection used for sequencing. 

The pipeline used to generate the genomic data files for this study had more permissive variant filtering paramaters, such that non-reported variants (including benign variants and germline variants of uncertain significance) were included in portal. Additionally, the pipeline failed to identify and include many reported structural variants. Molecular pathologist classifications of variants is not included. 

**The data in this study will no longer be maintained and updated as of end of September 2021.** 

### UCSF500

This study contains UCSF500 data _only_ from assay launch (mid-2015) generated using our new pipeline (launched October 2021) and will be continually updated with new cases each month. Data in this study IS LINKED to de-identified Warehouse (CDW); surrogate patient identifiers in portal are the same as those used for same patients in de-identified CDW.

#### Clinical Data for UCSF500

See [Clinical Data](#clinical-data) section for information on clinical data included in portal for this study. 

#### Genomic Data for UCSF500
<p style="text-align: center;"><span style="color: #e61531;"><strong><span style="color: ##e61531;">*Important limitations of UCSF500 Genomic Data are described below*</span></strong></span></p>

The new pipeline used to generate the genomic data files has significant improvements including tighter variant filtering paramaters. This has resulted in the removal from the portal of many of the non-reported variants observed in the old pipeline. The new pipeline now only includes pathogenic, likely pathogenic, and possibly pathogenic germline variants only. 

The more stringent **variant filtering** parameters has resulted in some reported variants being excluded from portal. Currently, our pipeline includes approxmately 88% of reported single nucleotide variants (SNVs) and small indels; 2/3 of the reported variants excluded from pipeline are variants of uncertain significance.  

Similarly, our pipeline includes approximately 90% of reported **structural variants**. By clicking on 'Event Info' column in the Structural Variants table, you can see the reported structural variant name. 

We will continue to work to improve both our variant filtering and structural variant parameters.

Whole genome copy number data and discrete copy number data are currently available for most sequenced specimens. See [How is the copy number data displayed?](#how-is-the-copy-number-data-displayed) section for more information on copy number data.  

**Molecular Pathologist Classifications** for variants can be found by selecting 'Center' from the Column options on the Mutations table. The classification for a given variant represents _the most recent assigned classification_ for the variant and is not necessarily the original classification for the variant in that report. 
* The 'Not Yet Classified' classification means this variant has not yet been assigned a classification by our Molecular Pathologists but can often be considered a variant of uncertain significance. 
* The 'N/A'classification means our pipeline was unable to identify a molecular pathologist classification for variant though one may exist.
* Structural Variants table for a single sample currently does not have molecular pathologist classifications. You can get the structural variant classifications when querying for specific fusions - all samples with fusion will be in the mutation summary table; select 'Center' column to display classification.

**Mutation Origin** for variants can be found by selecting 'MS'from the Column options on the Mutations table. 
* 'S' is somatic variants from a tumor-normal report
* 'G' is germline variants from a tumor-normal report
* 'N/A' are variants from a tumor-only report

### FM

This study contains Foundation Medicine data from tests ordered by a UCSF clinician _only_ using our new pipeline (launched October 2021) and will be continually updated with new cases each month. Data in this study IS LINKED to de-identified Warehouse (CDW); surrogate patient identifiers in portal are the same as those used for same patients in de-identified CDW.

#### Clinical Data for FM

See [Clinical Data](#clinical-data) section for information on clinical data included in portal for this study. 

#### Genomic Data for FM
Genomic data is parsed directly from a xml-formatted version of the report and includes single nucleotide variants (SNVs), small indels, discrete copy number, and structural variants including fusions. 

**Mutation Origin** for variants can be found by selecting 'MS'from the Column options on the Mutations table and will be 'N/A' as Foundation Medicine is tumor-only sequencing.

**Variant Classification** for FM variants is currently not available. 

### How do I get access to the new pipeline data?

Request a de-identified CDW account and complete training requirements:
* Refer to [‘First Time Users’](https://ars.ucsf.edu/de-identified-clinical-data-warehouse) section and follow instructions for requesting a de-identified CDW account
  * Select No for Section 1 (Identified Data: Extract UCSF and/or ZSFG Data)
  * Select Yes for Section 2 (De-Identified Data: Access to De-ID CDW, De-ID OMOP, Information Commons and associated tools)
* We will grant access to data from new pipeline every Friday for those who have completed training
* We will email you when you have access to new dataset

## DNA (Mutations, Copy Number & Fusions)

### Does the cBioPortal contain synonymous mutation data?

No, the cBioPortal does not currently support synonymous mutations. This may change in the future, but there are no plans yet to add this feature by the development teams.

### What processing or filtering is applied to generate the mutation data?

The only processing we do is the standardization of mutation annotation by using [VEP](http://useast.ensembl.org/info/docs/tools/vep/index.html) with the [canonical UniProt transcript](https://github.com/mskcc/vcf2maf/blob/master/data/isoform_overrides_uniprot).

There are two levels of filtering that occurs:

1. Filtering of VCF: filtering is based on such variables as read coverage, population frequency, and known sequencing artifacts of the assay.

2. Filtering of cBioPortal staging files: variants are filtered out with silent, intron, IGR, 3’UTR, 5’UTR, 3’Flank and 5’Flank with exception for promoter mutations of the _TERT_ gene (as called by VEP).

### What transcripts are used for annotating mutations?

Prior to loading a study into cBioPortal, we run all mutation data through a standard pipeline (see above), which re-annotates all mutations to the [canonical UniProt transcript](https://github.com/mskcc/vcf2maf/blob/master/data/isoform_overrides_uniprot).

### How are protein domains in the mutational lollipop diagrams specified?

Protein domain definitions come from [PFAM](http://pfam.xfam.org/).

### What is the difference between a “splice site” mutation and a “splice region” mutation?

A “splice site” mutation occurs in an intron, in a splice acceptor or donor site (2bp into an intron adjacent to the intron/exon junction), defined by [Sequence Ontology](http://www.sequenceontology.org/browser/current_svn/term/SO:0001629).

“Splice region” mutations are mutations that occur near the intron/exon junction, defined by [Sequence Ontology](http://www.sequenceontology.org/browser/current_svn/term/SO:0001630). While synonymous mutations are generally excluded from cBioPortal, these “splice region” synonymous mutations are included due to their potential impact on splicing.

### Does the portal display mutation of origin annotations?

Somatic/germline annotations are derived directly from the VCF. Therefore, any manually adjusted mutation of origin annotations are **not** reflected in the portal.

Cases where the mutation of origin annotations might be incorrect are variants representing clonal hematopoiesis of indeterminate potential (‘CHIP’), cases where contamination of normal sample with tumor-derived samples has occurred, and cases where the germline variant is selectively lost in the tumor sample because of copy number changes/loss of heterozygosity.

### How is the copy number data displayed?
cBioPortal supports several ways to display copy number data. 

<center>
 <i>Due to a bug in cBioPortal software, Shallow Deletions and Gain alteration are currently not displayed in the Copy Number table for a sample.</i>
 </center>

### UCSF500
Both segmented copy number data and discrete copy number data are available for most UCSF500 specimens 

Segmented copy number data can be seen for entire cohorts or sub-cohorts by selecting the 'CN Segments' tab or on the summary page for individual patients. 

Discrete copy number is inferred from whole genome copy number data using <a href="https://pubmed.ncbi.nlm.nih.gov/27100738/">CNVkit</a>:

<ul>
 <li>Deep Deletion indicates a deep loss, possibly a homozygous deletion</li>
 <li>Shallow Deletion indicates a shallow loss, possibly a heterozygous deletion</li>
 <li>Gain indicates a low-level gain (a few additional copies, often broad</li>
 <li>Amplification indicate a high-level amplification (more copies, often focal)</li>
 </ul>

Note that these calls are putative. We consider the deep deletions and amplifications as biologically relevant for individual genes by default. Note that these calls are usually not manually reviewed, and due to differences in purity and ploidy between samples, there may be false positives and false negatives.

### FM
As the FM data in the portal is derived directly from xml files of the report, only discrete copy number results as reported by Foundation Medicine are included in portal. 

## Clinical Data

### What kind of clinical data is stored in the portal?

* <strong>Tumor Type:</strong> We use the [OncoTree](http://oncotree.mskcc.org/#/home) ontology for tumor type, which provides a standardized way of classifying and relating tumor types. ‘Cancer Type Detailed’ represents the most granular diagnosis for the case given available information, while ‘Cancer Type’ is a higher-level node in the ontology.

* <strong> De-Identified Clinical Data Warehouse:</strong> Race, ethnicity and vital status are derived from de-identified CDW. We will be including more structured data from de-identified CDW in the portal with future releases.
 * **Data from de-identified CDW is only available for the [UCSF500](#ucsf500) and [FM](#fm) studies**

### What is the meaning of Age and Primary Site?

* <strong>Primary Site: </strong> This is derived directly from the UCSF500 report and actually represents the _anatomic location of the biopsy_; therefore it might not represent the true primary site of the tumor per se. Future releases will include a distinction as to whether sequenced specimen is derived from primary or metastatic tumor. Tumor anatomic site is currently not standardized. As such the same term might be described differently (e.g. ‘Brain, right frontotemporal lobes’ and ‘Brain, right frontotemporal’ or ‘Kidney, left’, ‘Left Kidney’, and ‘Kidney, left lower pole’).

* <strong>Age: </strong> Is the age of the patient at the time the tumor sequenced was collected.

# Analysis Questions

### How can I query/explore a select subset of samples?

cBioPortal allows you to run a query or explore study view using a user-specified list of samples/patients.

The first step is to define your sample set. There are two pages where you can define your sample set:

#### Defining samples: Query tab on the homepage

Currently you can only select the entire cohort from this page but we are working on creating more disease-specific and other sub-cohorts of the data you can select from this view. Enter in the gene(s) you are interested in analyzing and run the query.

Click over to the “Download” tab. In the table at the top, find the row that starts with “Samples affected”, and either copy or download that list. This is your list of samples that have mutations in your gene(s) of interest. Refer to [Querying with your defined samples](#querying-with-your-defined-samples) for next steps.

#### Defining samples: Summary study view

After you select the entire cohort from the Query tab on the homepage, click on the ‘View summary’ button that will take you to the study summary page.

On the study summary page, you can select specific cancer types and/or genes by selecting the appropriate checkboxes in the Cancer Type/Cancer Type Detailed or Mutated Genes summary boxes, respectively.

- Selecting specific cancer types will automatically filter the data and the various charts will updated.

- Checking specific genes will not automatically filter the data but instead you’ll need to click the ‘Select Samples’ button to the bottom right of the Gene box.

You can also subset data using the bar graphs (e.g. Age) by placing cursor inside graph near the left-most bar you want in your dataset and ‘highlighting’ across to the right-most bar you want in your dataset.

From this view you can also click on the **Select cases by IDs button**. Within the box that pops-up, click on ‘Use selected samples/patients’; note the default setting is by sample ID but you can change this to patient ID by selecting the other radio button at bottom of box.

Once you click on ‘Use selected samples/patients’, the IDs of the cohort you defined using the study summary page will be displayed. Copy these IDs; these are your list of desired samples. Refer to [Querying with your defined samples](#querying-with-your-defined-samples) for next steps.

#### Querying with your defined samples

Return to the Query tab on the Homepage (click on the cBioPortal logo at very top left corner).

Next, select “User-defined Case List” in the **Select Patient/Case Set:** dropdown. Paste the IDs in the box below the selection bar (note again default here is by sample ID so if you used patient ID select that radio button).

Finally, you can then also layer on specific or additional gene queries by entering your desired list of genes in the **Enter Genes:** section immediately below.

#### Selecting for Negative Samples

On the Query tab of the homepage, enter the gene(s) for which you are looking for samples with no detected mutations in gene(s). Run the query. Click over to the “Download” tab. Look at the table at the top and find the row that starts with “Sample matrix”. Copy or download this data and open it in Excel.

You will see a two column table that indicates whether a given sample is altered or not, indicated by 0 or 1. Sort by the second column and then copy all the sample IDs from the first column that have a 0 in the second column. This is your list of samples that do not have mutations in your desired gene(s).

With a sample list in hand, you can now either run a query in just the selected samples (select) or explore this set of patients in study view (click “Select cases by IDs” and then create a Virtual Study restricted to just those samples).

### What is OQL?

For more information about OQL, see the [specification page](https://cbioportal.ucsf.edu/cbioportal/oql) or view the [tutorial slides](https://www.cbioportal.org/tutorials#oql).

### Is it possible to determine if a particular mutation is heterozygous or homozygous in a sample? When a sample has 2 mutations in one gene, is it possible to determine whether the mutations are in cis or in trans with each other?

There is currently no way to definitively determine whether a mutation is heterozygous/homozygous or in cis/trans with another mutation. However, you can try to infer the status of mutations by noting the copy number status of the gene and the variant allele frequency of the mutation(s) of interest relative to other mutations in the same sample. The cBioPortal patient/sample view can help you accomplish this.

# Results View

## OncoPrint

### What are OncoPrints?

OncoPrints are compact means of visualizing distinct genomic alterations, including somatic mutations, copy number alterations, and mRNA expression changes across a set of cases. They are extremely useful for visualizing gene set and pathway alterations across a set of cases, and for visually identifying trends, such as trends in mutual exclusivity or co-occurrence between gene pairs within a gene set. Individual genes are represented as rows, and individual cases or patients are represented as columns.

![image](https://github.com/UCSF-CBC/cbioportal_docs/blob/master/docs/images/oncoprint.png?raw=true)

### Can I change the order of genes in the OncoPrint?

By default, the order of genes in the OncoPrint will be the same as in your query. You can change the order by (a) clicking on the gene name and dragging it up/down or (b) clicking on the three vertical dots next to the gene name to move the gene up/down.

### Can I visualize my own data within an OncoPrint?

Yes, check out the OncoPrinter tool on our [Visualize Your Data page](https://www.cbioportal.org/tools.jsp).

## Other pages

### Does the Mutual Exclusivity tab calculate its statistics using all samples/alterations or only a specific subset?

The calculations on the Mutual Exclusivity tab are performed using all samples included in the query. A sample is defined as altered or unaltered for each gene based on the [OQL](https://www.cbioportal.org/onco_query_lang_desc.jsp) utilized in the query - by default, this will be non-synonymous mutations, fusions, amplifications and deep deletions.

# What if I have other questions or comments?

Please contact [us](mailto:ucsf.cbioportal@ucsf.edu)!

