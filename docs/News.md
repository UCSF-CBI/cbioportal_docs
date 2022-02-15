# News

## February 14th, 2022: Discrete CNA, duplicate tumor samples + data refresh
 
 <strong><i>A reminder that the UCSF500 Old Pipeline Data Freeze Study is no longer being updated or maintained so the below updates do not apply for this study</i> </strong>

Our pipeline now includes discrete copy number data for both UCSF500 and FM studies! You can learn more about this on our [FAQs page]( https://cbioportal.ucsf.edu/cbioportal/faq#how-is-the-copy-number-data-displayed).

We've also now addressed duplicate tumor samples, wherein the sequencing results from the same tumor DNA sample are in more than one test order/report. In cases such as these, our pipeline will only select for inclusion in the portal the results corresponding to the report with the <i>most recent sign-out date</i>.

This release also includes a data refresh: cases signed-out prior to 2/01/2022 are in the portal with summary stats provided below. 
  * <strong>UCSF500 Study:</strong> 8,343 patients | 8,939 samples
  * <strong>FM Study:</strong> 2,267 samples | 2,151 patients
  * Version of **UI** is 3.6.18 (no change from previous release)

## November 19th, 2021: Data Refresh/Update Only
  * <strong>UCSF500 Old Pipeline Data Freeze Study:</strong> data files generated using old pipeline and includes cases signed-out prior to 10/1/2021
    * _this study is no longer being updated_
  * <strong>UCSF500 Study:</strong> 8,110 samples | 7,568 patients
  * <strong>FM Study:</strong> 2,233 samples | 2,123 patients
  * Version of **UI** is 3.6.18 (no change from previous release)

**You can learn more about the old study and new studies as well as how to access new studies/data generated using our new pipeline on our [News Page](https://cbioportal.ucsf.edu/cbioportal/faq#what-are-the-different-ucsf-cbioportal-studies).** 
* Information on how to access new studies is also provided immediately below under October 12th News Updates; see 'ANNOUNCEMENT' section

## October 12th, 2021: RELEASE OF NEW UCSF cBIOPORTAL
New cBioPortal Pipeline released to production!
  * <strong>UCSF500 Old Pipeline Data Freeze Study:</strong> data files generated using old pipeline and includes cases signed-out prior to 10/1/2021
    * _this study will no longer be updated after this release_
  *  <strong>UCSF500 Study:</strong> data files generated using NEW pipeline and includes cases signed-out prior to 10/1/2021
  *  <strong>FM Study:</strong> data files generated using old pipeline and includes cases ordered by UCSF clinician prior to 10/1/2021
  * Version of **UI** is 3.6.18 (no change from previous release)

**Key highlights about the new version of cBioPortal:**
* UCSF500 data through September 2021
* *New* Foundation Medicine data for tests ordered by UCSF clinician through September 2021
* *New* Linkages to de-identified CDW (patient ID)
* *New* Vital status, race and ethnicity from de-identified CDW displayed in portal
* *New* Molecular pathologist assigned classification of reported variants for UCSF500
* Addressed many of the previously known problems such as missing fusions

**You can learn more about the old study and new studies as well as how to access new studies/data generated using our new pipeline on our [News Page](https://cbioportal.ucsf.edu/cbioportal/faq#what-are-the-different-ucsf-cbioportal-studies).** 
* Information on how to access new studies is also provided immediately below under the 'ANNOUNCEMENT' 


## ANNOUNCEMENT!!

We are very excited to announce that we will be launching a new version of our UCSF cBioPortal that will include de-identified clinical data elements (e.g. vital status) from de-identified clinical data warehouse (CDW) July 2021. This will allow us to enrich the genomics data in the portal with clinical data in a scalable manner. Patient de-identifiers within the portal will utilize those in de-identified CDW in this new version, which will allow you as a researcher to then obtain additional clinical data you want for your cohort directly from de-identified CDW as well.  

In our initial launch, we will be including race, ethnicity, and whether patient is alive or deceased into cBioPortal. Additional clinical data elements we plan to add this calendar year are (de-identified) dates of diagnosis, tumor collection, sequencing, last visit, and death to name a few.  

This new version of the UCSF cBioPortal will also have significant improvements in variant filtering (e.g. removing variants deemed to be benign, common polymorphisms or germline VUSes) and address long-standing issues we have had such as missing structural variants and germline variants. It will also bring in molecular pathologist assigned classification of UCSF500 variants.  We will be able to load more data into the portal with more frequency than we have before.

In other big news, this new version will also include Foundation Medicine data for UCSF patients where a UCSF clinician report.
 
THE NEW VERSION OF CBIOPORTAL WILL REQUIRE ADDITIONAL REGULATORY MEASURES TO BE MET; PLEASE READ CAREFULLY BELOW:

All users must apply for a de-identified CDW account and complete de-identified CDW onboarding if they do not have one already:
<ul>
   <li>Follow ‘First Time Users’ steps found <a href="https://ars.ucsf.edu/de-identified-clinical-data-warehouse">here.</a> Select No for Section 1 (Identified Data: Extract UCSF and/or ZSFG Data). Select Yes for Section 2 (De-Identified Data: Access to De-ID CDW, De-ID OMOP, Information Commons and associated tools)</li> 
   <li>You will need to have a current attestation form (Statement of Responsibility) on file; users will get a Docusign invitation if their form is not current or signed</li>
   <li>Three training modules need to be completed, two of which most users will likely have already completed (‘CyberSecurity Fundamentals’ & ‘HIPAA101’); the third training module, ‘Your Responsibilities when Working with Clinical Data’ should take less than 15 minutes to complete </li>
   <li>While our new pipeline connecting to de-identified CDW undergoes certification for de-identification, we will need to add all users to an existing IRB for the UCSF cBioPortal research application. For this, there is nothing you as a user need to do, this is more of a FYI. Once our pipeline is certified, which we hope will be the case in the next 3-6 months, we will no longer need to execute this step and will remove cBioPortal users from the IRB.</li>
</ul>

We will continue to remind our users about de-identified CDW training over the next few weeks prior to launch; at launch, if you have NOT completed the training/account request for de-identified CDW, you will no longer have access to data in UCSF cBioPortal.

Any questions or concerns please send to ucsf.cbioportal@ucsf.edu. The UCSF500 data currently in cBioPortal will not disappear but be stored as a separate study you can still access within the portal; we will not however be maintaining this dataset in anyway (no longer adding cases, bug fixes etc).

## June 17th, 2021
New Data Release + UI Upgrade
  * UCSF500 cases signed-out prior to 1/05/2021
    * 6,937 patients and 7,844 samples
  * Version of UI has been upgraded 3.6.18.

## February 5th, 2021
New Data Release + UI Upgrade
  * UCSF500 cases signed-out prior to 1/05/2021
    * 5,789 patients and 6,432 samples
  * Version of UI has been upgraded 3.6.3. New Features/Enhancements Include:
  
   (1) **New Feature**: Extended the _Comparison_ tab to support the comparison of altered samples per gene or alteration. In the example shown below, a query              compares NSCLC patients with 1) both mutated and amplified EGFR, 2) mutated EGFR only, and 3) amplified EGFR only
   ![image](https://user-images.githubusercontent.com/840895/78508085-3ea13f80-7752-11ea-8e87-e486061def12.png)
   
   
   (2) **New Feature**: Annotate mutations using the _Mutation Mapper Tool_ on the GRCh38 reference genome:
    [![mutation_mapper_tool_grch38](https://user-images.githubusercontent.com/1334004/79233555-07f4b480-7e37-11ea-9d0a-0cafff434fa5.png)](https://www.cbioportal.org/mutation_mapper)
    
    
   (3) **Enhancement**: using [OQL](https://www.cbioportal.org/oql#oql-modifiers) to query for mutations based on a protein position range. 
![image](https://user-images.githubusercontent.com/840895/84427197-83ce6b80-abf2-11ea-9d18-3a4f4524e545.png)


   (4) **New Feature**: you can now send the OncoPrint data to the [OncoPrinter tool](https://www.cbioportal.org/oncoprinter) for customization.
![image](https://user-images.githubusercontent.com/840895/84318326-3c85a380-ab3c-11ea-97c1-34343cb3e996.png)


   (5) **Enhancement**: Mutational spectrum data can be downloaded from OncoPrint
![image](https://user-images.githubusercontent.com/840895/84322695-68585780-ab43-11ea-9224-a965331e35fc.png)


   (6) **New Feature**: The *Mutations* tab now has the option to show mutation effects for different transcripts / isoforms. Note that some annotation features are only available for the canonical isoform.
![image](https://user-images.githubusercontent.com/840895/88306535-d95d6400-ccd8-11ea-9e64-0c6600f65e50.png)


   (7) **New Feature**: You can now share custom groups in the *Study View* 
    <img width="333" alt="" src="https://user-images.githubusercontent.com/840895/88309724-b7fe7700-ccdc-11ea-969a-28ed8551ffd7.png">
    
    
   (8) **Enhancement**: _Study View_ now allows comparing samples with mutations or copy number alterations in different genes
![image](https://user-images.githubusercontent.com/840895/99558433-ba729400-2991-11eb-9054-1d8751b4d84f.png)


   (9) **New Feature**: Add your own custom data for a sample or patient to use on the study or comparison view
    <img src="https://user-images.githubusercontent.com/1334004/104651553-ce7efd00-5685-11eb-8017-c43f24421e3f.png" width="700">
    
    
  (10) **New Feature**: Show the mutations of a patient inside a pathway schematic using PathwayMapper
   <img src="https://user-images.githubusercontent.com/1334004/104649378-9f1ac100-5682-11eb-91eb-4e0f024a4ded.png" width="700">


  (11) **New Feature**: The Plots tab on _Results View_ now allows you to group alterations by Driver and VUS
    <img src="https://user-images.githubusercontent.com/1334004/104768867-56bfd980-573c-11eb-8e03-5ad86d01f25a.png" width="700">

  
## October 11th, 2020
New Data Release + UI Upgrade
  * UCSF500 cases signed-out prior to 10/1/2020
    * 4,868 patients and 5,381 samples
  * Version of **UI** is 3.2.2 (no change from previous release)
  
## June 23rd, 2020
New Data Release + UI Upgrade
  * UCSF500 cases signed-out prior to 6/8/2020
  * Version of **UI** is 3.2.2 (no change from previous release)
   
## March 17th, 2020
New Data Release + UI Upgrade

  * Version of **data** is 2.0
    * UCSF500 cases signed-out prior to 2/24/2020
  * Version of **UI** is 3.2.2. New features include:
    * Genome Aggregation Database (gnomAD) population frequencies in the mutations table - see [example](http://bit.ly/2ISHgiu):
 ![gnomad feature news](https://user-images.githubusercontent.com/1334004/59794400-e07c9c00-92a6-11e9-97ea-a79bfc8f3885.gif)
    * Group Comparison Feature: Compare clinical and genomic features of user-defined groups of samples/patients. [View Tutorial](https://www.cbioportal.org/tutorials#group-comparison)
![group-comparison](https://user-images.githubusercontent.com/840895/59052073-40f9eb00-885c-11e9-9ddb-6d036533e5f5.png)
    * Use the new quick search tab on the homepage to more easily navigate to a study, gene or patient:
 ![quick_search_news](https://user-images.githubusercontent.com/1334004/55113078-8f4c7a00-50b4-11e9-9d95-e9a6e1dcda52.gif)
     * Bookmarking or sharing your selected samples as virtual studies with the _share_ icon on the study summary page. [Example: a virtual study of breast tumors](https://www.cbioportal.org/study?id=5a12fd57498eb8b3d5605cd4)

## August 12, 2019
Initial launch of UCSF cBioPortal released to UCSF community!
  *  Version of **data** is 1.0
  * Version of **UI** is 1.18.1
