Compute resources for the AusARG initiative in 2021 are supported by the ANUMAS allocation (3 million SU) awarded to Dr. Yu Lin and the ABLeS initiatve. This is a shared resource for any research projects/workflows/analyses related to the AusARG project.

# Housekeeping

There are couple of basic principles that we would request to comply with.

1. Data storage is always limited, and a growing expense. Please make sure that you make arrangements for archiving your important data files. We will have to ask users to delete all of their files from time to time if we run in to shortage of space. There are no quotas in place yet, but I think we will have to introduce some limits as userbase grows. We will collectively learn about our data storage requirements through this and hopefully systematic data management practices can be put in place in the future. For now, please be reasonable so that we can accommodate more researchers on this platform.

2. These are very expensive high-end computer systems and importantly a shared resource. Therefore, please optimise your code as much as possible before requesting large number of CPU hours. We will write documentation about this soon on GitHub. This is to ensure that the resources are not wasted. General principle is that if a task/job is going to take more than 5000 CPU hours, then go over the code multiple times to ensure that CPU cycles are not wasted. Importantly assess if the computation is actually required. This is not to limit your use but to ensure that we respect the resource that we are getting for “free”.

For the context, if we were to use Google Cloud Platform for 3 million CPU hours (our allocation), it would cost approximately $225,000. And 20Tb of storage on the GCP will cost approximately $5800 per year just to store the data.
 

# Australian BioCommons Leadership Share (ABLeS)

The intention of ABLeS is to apply computing power and related resources to construct, 
maintain and gain insights from community defined and developed data assets 
(e.g. reference genome assemblies).

It will also be used to evaluate the efficacy of digital tools and methods in relation to the species under 
investigation and/or the project aim, including the computational and data requirements 
that underpin publication outcomes.

As of December 2020, the AusARG community has been granted access to ABLeS,
and  the following resources are available via NCI:

1. The Gadi supercomputing platform, 
2. The Tenjin cloud computing platform,
3. Live data storage service (home and scratch storage), and
4. Archival data storage services.

**The AusARG allocation is co-managed by lead bioinformaticians Hardip Patel and Terry Bertozzi, who are point of contact for providing access and oversight of the allocation and the users within it.**

**Learning together**

The ABLeS journey is collaborative and involves the the BioCommons, the research community, and the facilities. Communities such as ABLeS will work to understand their tools, methods and optimal approaches to solve the bioinformatics problems at hand. It is expected that communities will engage the BioCommons in an open and collaborative manner, with regular meetups (expected frequency ~ 2 monthly). A concrete outcome of that engagement will be reports and notes on toolsets, workflows, methods, resource usage and quality assessments for derived reference data sets, to support and assist other communities. 

**Using the AusARG share**

The AusARG Steering Committee will direct the use of ABLeS, ensuring that resource consumption is aligned with the prioritise of the community. 

**AusARG priorities for 2021**

The AusARG SC has prioritised the following species and work to be undertaken through ABLeS in 2021:
1. .. 
2. .. 
3. ..

# Getting started

1. Before taking any action, please discuss your account and next steps with the AusARG bioinformatics leads (Hardip and/or Terry).
2. If you are a new NCI user, please apply for an account at https://my.nci.org.au/mancini/login?next=/mancini/ and request to join project xl04.

# Data storage

Further data management practices for the AusARG project will be listed here soon. For now,

1. Create `/g/data/xl04/userID` directory for your personal use and use that directory for your work. 
2. Publicly available data can be stored in `/g/data/xl04/publicdata/NCBItaxonomyID/`. If you download public data, please write a `readme.txt` file for others to know what the data is about. Unexplained data may be deleted if there is shortage of space.

## Bioplatforms Australia Framework Initiative data

Raw sequencing data produced by the Bioplatforms Australia Genomics nodes (AGRF, Ramaciotti Centre for Genomics, ANU-BRF) is stored alongside descriptive sample and library metadata on the [Bioplatforms Australia Data Portal](https://data.bioplatforms.com/).

The [data portal section for AusARG](https://data.bioplatforms.com/organization/ausarg) provides a way to search for, inspect and - for registered users - download the data produced by each AusARG project. Broadly, the data stored will fall under the following core activities:

- [Comparative Genomics and Evolution (Reference genomes)](https://ausargenomics.com/reference-genomes/) 
- [Phylogenomics](https://ausargenomics.com/phylogenomics/) 
- [Taxonomy and Conservation Genomics](https://ausargenomics.com/taxonomy-conservation-genomics/)

## How to access data stored by Bioplatforms?

- To access the data portal you first need to register for an account (see [How to register for an account and log-in](https://github.com/BioplatformsAustralia/dataportal-usersupport/blob/master/registration_login.md)).
- The data portal can then be accessed, and data downloaded, via the [browser interface](https://data.bioplatforms.com/organization/ausarg): see [How to find, filter and bulk download data and meta-data](https://github.com/BioplatformsAustralia/dataportal-usersupport/blob/master/find_filter_download.md).
- Several options are also available for [programmatic access to the Bioplatforms Data Portal](https://github.com/BioplatformsAustralia/dataportal-usersupport/blob/master/programmatic_access.md).

# Getting help

Direct training and help is available if you are new to HPC and/or new to NCI/Gadi. 

1. Basic information to get started with the NCI GADI for bioinformatics can be found at https://github.com/AusARG/ABLeS/wiki/temppage.
2. For NCI support, contact the NCI helpdesk directly at https://www.nci.org.au/users/nci-helpdesk
3. Queue limits and structure explained at https://opus.nci.org.au/display/Help/4.+PBS+Jobs.

# Sharing learnings

1. Discussions regarding the usage of the compute resources can be found at https://github.com/AusARG/ABLeS/discussions.
2. Please use issue tracker here if you want to raise it as an issue for these resources in this repo.
3. Please share your experiences, especially workflows in genomics here either as links to your repo, papers, descriptions in the Wiki Pages.

