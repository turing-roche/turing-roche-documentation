[Structured missingness workshop: Turing-Roche](https://www.eventsforce.net/turingevents/frontend/reg/thome.csp?pageID=43439&eventID=133&CSPCHD=000001000000iAP1jPxfEIvlaeAz9nBPiVjvA9Bq1L1m_gg47Z)


## Structured Missingness Workshop Event 1

**Date**: 10th December

**Time**: 3-5pm GMT

**Agenda**: [SM workshop agenda](https://www.eventsforce.net/turingevents/frontend/reg/tAgendaWebsite.csp?pageID=43428&ef_sel_menu=630&eventID=133&mode=)


<table>
  <tr>
   <td>Time
   </td>
   <td>Activity
   </td>
  </tr>
  <tr>
   <td><strong>3:00-3:10pm (10mins)</strong>
   </td>
   <td><strong>Welcome & Outline:</strong>
<p>
(<strong>Intro &</strong> <strong>Welcome & outline</strong>)
<p>
Chris Holmes (Turing)
<p>
Ryan Copping (Roche)
<p>
Ben MacArthur (Turing)
<p>
Vicky Hellon (Turing)
<p>
Chris Harbron (Roche)
   </td>
  </tr>
  <tr>
   <td><strong>3:10-3:25pm (15mins)</strong>
   </td>
   <td><strong>Presentation:</strong>
<p>
<strong>Introduction to the Roche Clinico-Genomic Database</strong>
<p>
Sarah McGough (Roche, Data Scientist)
   </td>
  </tr>
  <tr>
   <td><strong>3:25pm-3:40pm (15mins)</strong>
   </td>
   <td><strong>Presentation:</strong>
<p>
<strong>Current state of structured missingness</strong>
<p>
Robin Mitra (Turing, Research Lead)
   </td>
  </tr>
  <tr>
   <td><strong>3:40pm-3:50pm (10mins)</strong>
   </td>
   <td><strong>BREAK</strong>
   </td>
  </tr>
  <tr>
   <td><strong>3:50pm-4:35pm (45mins)</strong>
   </td>
   <td><strong>Community discussion: identifying key themes within missingness</strong>
<p>
4 breakout rooms for high-level, collaborative conversations. Highlight problems that need to be solved.
<p>
Breakout rooms:
<ul>

<li>Prediction <em>(Making predictions from data with structured missingness)</em> Facilitated by Ben MacArthur

<li>Missing mechanisms<em> (Missing mechanisms, determining principles underpinning structured missingness) </em>Facilitated by Robin Mitra

<li>Inference <em>(Inference from data with missingness) </em>Facilitated by Chris Harbron

<li>Imputation <em>(Imputation of structured missing values) </em>Facilitated by Ryan Copping 
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td><strong>4:35pm-4:55pm (20mins)</strong>
   </td>
   <td><strong>Main room discussion:</strong>
<p>
Delegates & leads to come back to main room to discuss main topics found during community discussion.
<p>
Each room feedback for 5 mins by leads.
   </td>
  </tr>
  <tr>
   <td><strong>4:55pm-5:00pm (5mins)</strong>
   </td>
   <td>Close
<p>
<strong>All discussion points will be taken forward to build on 17<sup>th</sup> November, to define more practical issues to be discussed.</strong>
   </td>
  </tr>
</table>



## Breakout Rooms:

### Breakout room theme Prediction (Ben MacArthur lead) notes:

### Breakout room theme Missing mechanisms (Robin Mitra lead) notes:

General scheme:
1. Investigating how well existing techniques in work in practice
2. In what way do they do not work perhaps in combination (lots of different perspectives/areas of expertise)
3. Leads to identify gaps/problem to solve for further research
4. Also frame outcomes of interest, e.g. what are the goals from CGDB

Data Visualisation - known versus unknown, nice challenge might be analysis techniques to identify all patterns of missingness in CGDB, some known and some unknown, exploit visualisation techniques to determine known patterns and as a basis to determine unknown patterns in heterogenous data CGDB.

Geospatial element, do not have a record for a certain variable, can you infer, using the missing values to impute/infer other missing data. Use missing indicators as predictors to deal with missing.

How patterns exist among events, How do you incorporate structural missingness into models.

Visualisation to learn about unknown patterns/missing values

Informative structural missingness, informative sampling. Any visualisation method to find out more about this.

Impact for looking at the effective of Missingness

_Notes from the chat:_

That film is at [tinyurl.com/VizDataQuality](https://tinyurl.com/VizDataQuality)

### Breakout room theme Inference (Chris Harbron lead) notes:

Application - Decision Making Problem

Taking features from one place and apply elsewhere

Network models to identify missing links

Hierarchical model 

Clustering

Imputation 

Expectation Maximisation - Imputation

Binary v Continuous data

Robust model 

### Breakout room theme Imputation (Ryan Copping lead) notes:

Objective:  Highlight problems that need to be solved regarding imputation of structured missingness.

High level notes from discussion _(please feel free to edit/add)_

General:

* Areas of missingness folks experiencing who joined the breakout: medical imaging (imputation of images), observational clinical & genomics (e.g. genomics england - similar to CGDB), clinical trials, ML using different data modalities, exploring missing data from under represented groups 
* Synergy between this topic and prediction topic.  Prediction can be a method for imputation (synergies with prediction group).  

Problems/Opportunities that could be explored:



* Exploring modern DL approaches in imputation 
    * Imaging example link from Alex: [https://pubmed.ncbi.nlm.nih.gov/33129140/](https://pubmed.ncbi.nlm.nih.gov/33129140/) 
* When is it appropriate to do imputation? Rules when to do it and when not to? 
    * E.g. Industry guidance (gold standard), ideas around meta imputation
* Understanding limits of scope of imputation
* How to impute for different types of data and different modalities  
* What are the different modeling approaches and pipelines (e.g. imputing before modeling, or incorporating missing data imputation within training of a predictive model)    
* Is there an opportunity for external info to be fed into imputations (e.g. from literature or other datasets) and not just from the specific dataset being worked on… 
* Impact of using anonymized data when imputing (e.g. ages bucketed - how to handle, or harmonizing different rials anonymized in different ways) 
* How much can be transported from other knowledge.  E.g. using Flatiron US data to enable UK insights (generalizability) 
* Metrics for how representative a datapoint or dataset is (e.g. divergence from a certain distribution) before imputing.  Datasets of datasets - some people are addressing these kinds of problems already and we could learn more. 
* Benchmarking imputation methods against each other in different scenarios (e.g. prognostic model).  Could understand performance in actual data set as well as  introducing some synthetic missingness etc 
* Literature review (Niels) showed that there aren't many examples which use datasets with a lot of variables… still looking for methods that deal with many variables (e.g. >20).  Block missingness approaches today may not work with many variables / many blocks / many patterns 
    * Also identified an unpublished journal article implementing specific reasons for missingness    
* The importance of modelling uncertainty (and its propagation) through imputation methods 

Other points/thoughts shared



* Domain knowledge and understanding the data is really important
* Could be a link to digital twins … and imputation is essentially creating a digital twin 

_Notes from chat:_

-Example imutation in imaging pubmed.ncbi.nlm.nih.gov/33129140/

- This is an example of imputation-interpolation for image superresolution pubmed.ncbi.nlm.nih.gov/33910110/ I think there is clear overlap in data imputation, interpolation & synthesis …

- Here an example of non-statistical imputation but rather physics-informed ML nature.com/articles/s42254-021-00314-5

-From nhsx.nhs.uk/ai-lab/ai-lab-programmes/ethics/

STANDING together (STANdards for Data INclusivity and Generalisability) Dr. Xiaoxuan Liu and Professor Alastair Denniston at University Hospitals Birmingham NHS Foundation Trust. An international consensus process to develop standards for datasets underpinning AI systems, to ensure they are diverse, inclusive and can support development of AI systems which work across all demographic groups. The resulting standards will help inform regulators, commissioners, policy-makers and health data institutions on whether AI systems are underpinned by datasets which represent everyone and don’t risk leaving underrepresented and minority groups behind.

-Grand Challenges - grand-challenge.org


## Next steps:



* Next workshop on 17 November 3-5pm GMT- link will be sent to you
* Hopin platform remains open for 24 hours so you can log back on for networking/follow up opportunities 
* For longevity would recommend you join our Slack workspace- [https://join.slack.com/t/turingroche/shared_invite/zt-y5bnwynr-bN8gBb5g9c_dFHrnMggkjw](https://join.slack.com/t/turingroche/shared_invite/zt-y5bnwynr-bN8gBb5g9c_dFHrnMggkjw) 
Space to say hello in between the first and second workshops and hope it’ll be useful to help you collaborate between the second and third workshops and beyond
