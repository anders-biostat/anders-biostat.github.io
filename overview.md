Bioinformatics tools for omics data
-----------------------------------

Thanks to maodern assay techniques, biology is transforming into a "data-rich" science. With high-throughput sequencing, mass spectrometry, automated perturbation screens and other "big data" assay technologies, we can now get at the same time a "bird's eye" overview as well as plenty of detail on a set of biological samples. The vast amount of raw data produced this way is, however, of little use without powerful bioinformatics and biostatistics methods to process, analyse, and interpret them.

The new bioinformatics group that I am setting up ZMBH focuses on developing the computational tools that biologists need to find the needles of biological insights in the haystacks of high-throughput assay data.

For a mroe detailled description of our lab, see our projects page []

**Research strategy:** 

Computational scientists provide crucial expertise to research in molecular biologist that is complementary to the skill set that a typical biologist or clinical researcher has learned in her or his studies: We know how how to process, organise and explore big data sets, and transform data such that it can be viewed from "just the right angle" to gain new insights into biological systems (exploratory data analysis, EDA) and we know how to ensure that findings are true and reproducible rather than the result of random chance or wishful thinking (inferential statistics).

Exploring big data requires tight collaboration, and especially effective communication, between computational scientists and biologists. While only the latter have the in-depth knowledge and intuition of the system under study to know which specific questions should be asked, we know how what questions can be asked from a big data set, and, importantly, we can invent new investigative strategies to ask entirely new kinds of questions that were not accessible before.

For my group, I aim to assemble an interdisciplinary team, drawing not only from bioinformatics and statistics, but also from computer science, physics, engineering and other quantitative subjects, in order to cover a broad field of expertise on methods that can be translated, adapted and expanded for use in molecular medicine.

We will strive to strike a balance between two modes of research: On the one hand, we will craft tailored analysis methods for specific advanced experiments carried out by our wet-lab and clinical colleagues in Heidelberg and elsewhere. On the other hand, we will package such approaches into generally useable software tools that are modular, documented well and easy to use, to ensure that even research group with little or no biostatistics expertise can download and use them, thus making cutting-edge biostatistical methodology available to the research community at large.


**Topics and projects:**


*Interactive visualization of high-dimensional data*

Exploratory data analysis is as much of an art as it is a science. As, unfortunately, our brains cannot conceive high-dimensional data directly, we use many techniques to reduce them to two-dimensional visual representations: scatter plots, biplots, heatmaps, dendrograms, parallel coordinate plots, etc. Nearly all of these are static: optimized to be printed onto a piece of paper and distributed in a printed journal. With the computer mouse being invented more than 50 years ago, it is certainly time for more interactive visualizations, in which we can turn, slice and dice data, look at it from all angles, squeeze and warp and move it to look at specific aspects or corners of our huge data set. We are working on innovative new ways of allowing scientists to explore their data.

The linked-charts frame work: 

To give a simple example: Ordination and clustering methods try to find data points (e.g. patients), that are similar -- but similar with respect to what? A clinician may want to interactively explore how the similarity of the patient she is treating right now to other patients in the cohort changes if the dimension reduction method does not use all data but puts emphasis (weight) on gene expression data from a specific pathway, drug sensitivity data from a specific drug class or the like.
Developing interactive data exploration tools that are not mere gimmicks but actually useful and help with patient care requires tight collaboration between users (doctors, biologists) and developers (bioinformaticians) -- and FIMM is the right place for this. We will search for creative and novel approaches to shed new light on our data, and we will use them not only for FIMM's own project, but also distribute them as powerful but lightweight software tools.

*Data analysis for high-throughput sequencing*

My eralier work was focused on statistical methods for RNA-Seq analysis; specifically, I developed various tools for inference of differential expression (DESeq, DESeq2, DEXSeq) and data sequencing processing (HTSeq). Now, we have collaborations with several wet-lab groups who use novel or customized sequencing techniques to study aspects of cell biology and functional genomics, such as Tag-Seq to assess alternative polyadenylation and ribosomal profiling to understand regulation of translation.


*Cohort-scale transcriptomics and proteomics in medical research*



*Transcriptomics:* 
