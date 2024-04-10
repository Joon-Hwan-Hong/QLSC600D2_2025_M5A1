# Reproducibility of Papers from Various Scientific Fields

# Introduction

Reproducibility is a critical aspect of scientific research, and one may even argue, inherent to the definition of science itself. Publishing reproducible results not only creates a foundation of trust with the readers, but also enables others to build upon the findings in a way that can expand a communal understanding of the field. Unfortunately, concerns about a lack of reproducibility in scientific literature is ever rising, especially in the life sciences and medicine (Goodman et al., 2016). This concern is notably demonstrated through the Reproducibility Project: Cancer Biology (RPCB) (Errington et al., 2021). The project's goal was to reproduce results from 53 high-profile papers in cancer biology, involving 193 experiments. Strikingly, all experiments required author clarification of the protocols to some extent, 68% of experiments shared no data, and no analytic code was shared for 81% of experiments (Errington et al., 2021). These results shed light on the various ways in which papers can make reproducing the results challenging or even unattainable. 

Lack of reproducibility is a problem that extends beyond the field of cancer biology. Here we have set out to evaluate its extent in various specialties throughout the life sciences. To do so we had to overcome the challenge of different fields having different expectations for reproducible reporting. We will discuss our method of establishing a protocol to evaluate reproducibility that could be applied to papers from all specialties. Additionally, each evaluator has provided a discussion on the evaluation of their respective papers and any noticeable trends in the literature of their specialty. Through this process we hope to gain insight into how reproducibility compares across research specialties in the life sciences. We recognize that this evaluation is opinion based and that we did not attempt to reproduce the results ourselves, however, we hope that by evaluating papers related to our respective research topics we can provide an honest and informed opinion.


# Methods

For this analysis reviewers met twice to develop criteria for assessing research replicability. An initial meeting was conducted which identified preliminary criteria to assess research with. Reviewers were then tasked to review two papers with the preliminary criteria, and then to meet again to discuss as a group how this criteria should be revised in order to develop the final review criteria. The final review criteria was chosen for its objectivity and its ability to be applied to all fields of research within quantitative life sciences.

The criteria used for evaluating research consists of the following categories: data availability and accessibility, description of study protocol, description of data, description of tools, and overall replicability.

### Data Availability and Accessibility
Data availability and accessibility are important for scientific reproducibility since they allow results verification, transparency, collaboration, and error detection within the scientific community. Access to raw data allows other researchers to validate findings, fosters trust through transparency, and facilitates collaboration, thus preventing redundant efforts and promoting faster scientific progress. Furthermore, open and accessible data encourages scrutiny in studies among peers, aiding in identification and correction of errors. It also serves as valuable educational resources for training future quantitative life scientists in data analysis and research methodologies. For these reasons, reviewers agreed to and were tasked to evaluate how easily accessible to the public/other scientists are the data from a specific study. Specifically, the reviewers base the score for this metric on the hoops and loops other scientists need to encounter before obtaining the appropriate and sufficient data for the replicability of the study.

### Description of Study Protocol
One key to scientific reproducibility is the clarity and accuracy of the methodology written on a publication. Furthermore, a study is worthwhile reproducing, if the methodology is also appropriate in answering the important questions. Thus, the reviewers find it essential that the papers must have clear and logical methodology and analysis in their study. The study must have appropriate materials, methodologies, and analysis that are aligned to the questions being answered. Misleading research studies are confusing and unproductive for the scientific community. Moreover, for reproducibility, it is essential to specify the method used in a scientific study so that other researchers can replicate the experiments or analyses accurately. Clear documentation promotes transparency, allowing for peer scrutiny and validation of conclusions.

### Description of Data
The description of the data used in a scientific study is crucial for reproducibility, because it allows other researchers to replicate the findings, promotes transparency in research methods and analyses, and avoids ambiguity about the data source. A clear specification of data contributes to the scientific advancement of knowledge by enhancing credibility of research and facilitating faster validation of conclusions.

### Description of Tools
In order to ensure scientific reproducibility, other researchers need to know which tools(hardware, software, instruments, reagents etc.) were used for the experimental setup and/or analyses. An accurate documentation for tools facilitates peer review and validation of results, ensuring transparency. In addition, it ensures consistent procedures and reliable interpretation of findings by avoiding ambiguities and misunderstanding about equipment or materials.
Tool availability and accessibility (3pts) The reviewers also note that it is important for scientific reproducibility and replicability that tools are easily accessible for accurate study replications. By making the research tools readily accessible, other researchers are able to obtain the same equipment, software, instruments, chemical reagents, etc. similar to what were used in the study. The accessibility ensures consistency in procedures, reduces variation in results, and research transparency is enhanced. Ultimately, accessible tools increase scientific collaborations and verification.

### Overall Replicability
Overall replicability is important in scientific reproducibility because it confirms the reliability and robustness of research findings.This metric refers to how easily reviewers think other researchers can easily replicate the setup and analysis in the evaluated study. For this reason, the reviewers must be familiar or are working in the same field of research for them to fairly gauge the replicability of the study. This metric can be dependent on how the study is based on the previously mentioned metrics. Reviewers will assess how replicable the study is for those researchers with sufficient training in the same field, along with adequate resources. 
 
The specific criteria used within this study can be found in the appendix (see Appendix).
To graphically compare evaluations between different research fields, radar charts, also called spider charts, were developed. Each evaluation criteria except for overall replicability was incorporated into the radar chart as its own radii.


# Discussion

## Human Genetics In Disease Identification (Alina Tan)
Human genetics plays a pivotal role in disease identification, offering invaluable insights into the underlying causes and mechanisms of various disorders. By examining an individual's genetic makeup, scientists can pinpoint genetic mutations or variations that predispose individuals to certain diseases, ranging from rare genetic disorders to common complex diseases such as cancer, diabetes, and cardiovascular diseases. There are many different approaches to using large genome data. The selected papers span recent years from 2017 to 2024 and cover popular methods including Gnome Wide Association Studies (GWAS), polygenic risk scores, omnigenetics, and Exome Wide Association Studies (ExWAS). Out of the five papers, one of them is very likely reproducible, while two of them are reproducible under certain conditions, and one of them is unlikely to be reproducible. 

The paper by Forgetta et al. (2022) aimed to develop a novel algorithm for predicting gene loci related to certain diseases using GWAS. It scored 3/3 for data availability and accessibility, as the article provided a link to the data, and the GitHub repository contained all the data used in the study. The description of the data also received a score of 3/3, as the paper clearly explained the methods used, with the method section written in a stepwise manner. However, the paper received a score of 2/3 in the description of the data section, as it only described the data processing without providing the code. This could make it time-consuming for readers to reconstruct the code if they need to run it with a different dataset. Nonetheless, the paper described all the software used clearly, and the tools they utilized are available online and easy to find. The overall replicability score is 5, this paper can be reproduced fairly easy.

The second paper, authored by Ochoa et al. (2022), focuses on identifying genetic support for 2021 FDA-approved drugs. Regarding data availability, the paper received a full score as it provided a GitHub link in the paper, and the data used was clearly described. The method was also described in a stepwise manner, contributing to a comprehensive understanding. However, the paper received a score of 2/3 for both the description of tools and tool availability. Although the code was easy to read and follow, the authors did not specify the tools used in their code, such as "Spark" for data storage, which requires a Google Cloud account to function. Additionally, they did not mention where to find the original data for local use. Consequently, the overall replicability score is 4. Despite the limitation of not being able to use the dataset from the online storage platform, the download page of the authors' company was accessible, enabling replication of the results once the data is obtained.

The paper by Lennon et al. (2024) was published in Nature Medicine. The paper aimed to build an optimized method to generate polygenic risk scores for ten diseases. The data used in the study are provided in the paper; however, access is limited due to patient privacy. Requests need to be sent to the authors to obtain the data. Therefore, the data availability score is 2/3. The description of the method is thorough, and all the code used is available online. The data and tools they used are explained in the methods section, and they also clarified the population they used. I gave a score of 2/3 for the tool availability and accessibility section since some tools they used require licenses and it takes time to obtain these tools. I gave a score of 3/5 for the overall replicability since the code is clear and the methods are described clearly. Once we have the data and the tools, we will be able to reproduce the results, but it may take a long time.

Chen et al. (2024) compared different methods for ExWAS datasets and evaluated their performance. The data was provided in the article link. However, access to UK Biobank data requires a license. Therefore, the data availability is rated 2/3. The code to run the entire experiment is missing, but the tools are described. Data preprocessing and performance evaluation are not available. Consequently, I assigned a score of 2/3 for data description. Although we have the source of the data and tools, we need to write the code ourselves to reproduce the results. I believe it will be possible to reproduce the results since the major techniques were provided.

Boyle et al. (2017) provided insights on how to address complex traits from polygenic to omnigenic. The detailed data source is provided in the supplement file. However, accessing the original paper is necessary to find the data, resulting in a data availability score of 2/3. The objectives and methods were explained clearly. Nonetheless, the code for data preprocessing and performance evaluation is not available. Links to the tools used are provided in the supplement file. While we have access to the data source and tools, we need to write the code ourselves to reproduce the results. It might be challenging to develop the model based solely on written results. Consequently, I assigned a score of 2, indicating it's unlikely for the overall replicability.

## Medical Imaging and Segmentation (Megan Ng)

## Iron Deficiency and Blood Donation (Matthew Schinwald)
The papers related to blood donation and iron deficiency range in publication years from 2011 to 2022. Data accessibility scores were affected by the sensitive nature of health records, however one paper failed to mention the hospital where participants were collected from (Bryant et al., 2011). Most papers also didn’t appropriately specify the statistical software that was used for their analysis. Although this could be inconsequential for simple statistical techniques, neglecting to specify the software used for more advanced or novel statistical methods would harm the reproducibility of research. It could be that authors are likely to describe the software used when multiple statistical programs are involved in data collection and analysis, which would be especially true when multiple analysts are contributing to the same paper. Interestingly, the paper by Mantadakis et al. (2022) conducted the primary analysis twice using two statisticians to ensure the integrity of their analysis, however the statisticians used the same software in this study. Conversely, Karregat et al (2022) and De Kort et al. (2018) identified the use of two separate statistical software for their papers, however it was unclear which software was used for which analyses. Most studies included a detailed description of the analysis, however there was generally less detail regarding data preprocessing, such as the handling of outliers or missing data. The greatest factor influencing reproducibility within the reviewed papers was the lack of detail when describing inclusion and exclusion criteria of their study participants.
Mantadakis et al. (2022) received the highest replicability score of all the assessed papers in this category. This study benefited from using the same data as a prior randomised control trial, which was referenced in a supplemental appendix. This study might improve if the participant recruitment method was consistent. Participants in this study were recruited by email, telephone, or mail, which could influence loss-to-follow up bias.
The study by Karregat et al. (2022) used ambiguous participant eligibility criteria. To be eligible, donors must be in "good health", which was evaluated using a health questionnaire cited in a separate study. The cited study did not specify all fields of the health questionnaire, so it is unclear the exact criteria that was used to evaluate “good health”.
The paper by de Kort et al. (2018) used regression modelling in their analysis, however there was no mention of how regression model assumptions (such as the normality of residuals) were met or how variable selection was performed for multivariable modelling. Additionally, the number of observations used for the regression models was not mentioned. Overall the statistical analyses performed were not sufficiently described.

The study conducted by Bryant et al. (2011) provided sufficient detail regarding the laboratory analysis of blood samples, however the participant inclusion and exclusion criteria was not described in detail. To be eligible for this study, blood donors cannot be given a permanent blood donation deferral. Permanent blood deferrals are administered based on local blood centre criteria, however this study did not specify the criteria nor the location of the blood donation centre. This study also failed to specify which forms of blood donations were included, particularly whether all blood donations were allogenic or not. 

Similarly, the study by Krayenbuehl et al. (2011) inadequately described the data that they were working with, and provided limited detail as to their inclusion and exclusion criteria. The time period that data was collected in was not described at all, and the laboratory method for measuring serum ferritin and hemoglobin concentration was not described. To be eligible to participate in this study, participants must be using adequate methods of contraception and participants were ineligible to participate if they had mental disorders or were using specific medications. The authors of this study did not define which methods of contraception were deemed adequate, which mental disorders were unfit to participate and how the presence of mental disorders were assessed, and they also failed to specify which medications would deem a participant unfit to participate in the study. Additionally, this study included a "Short Performance Inventory" questionnaire, but there is no citation for where this questionnaire can be found, and neither is there detailed information on the content of the questionnaire.

## Bacterial Genomics in Health Settings (Monica Cella)
Over the past decade, cutting-edge sequencing technologies have allowed for the application of genomic analyses for surveillance of infectious bacteria in hospital settings. Although these technological paradigm shifts have led to improved health outcomes and mitigation measures, the “tsunami” of information resulting from complex microbial analyses must be scrutinised to ensure excellent data quality, eliminate experimental design flaws, and maintain a high degree of reproducibility across the field. This section provides a snapshot of papers in the area related to environmental surveillance of bacteria using metagenomic sequencing. These papers were selected to give an idea of ideal, typical, and even poor practice examples that are very likely, likely, and unlikely to be reproducible (respectively). The selected papers are from within the past ten years (2010 to 2024), starting with three papers as examples of typical practices found while perusing the literature, one paper that was an example of poor practice, and one example of a supposedly ideal paper. Each paper is described in more detail below:

Chng et al. (2020) performed a surveillance experiment analyzing resistant microbes in a tertiary hospital in Singapore. The paper is accompanied by a "Reporting Summary" which Nature Research, the publishing journal, implemented to improve reproducibility and transparency in their published works. This Reporting Summary very clearly outlines the life sciences study design and makes it easy for the reader to understand the design limitations and reasons why a design method was selected for the undertaken research. All equipment, software and their respective versions used are explained in detail. The statistical analyses are described and significance provided, and analyses were "performed in R" but no packages were described (if used). This paper was given a nearly perfect score across the board. However, a point was removed due to the unclear tool description: statistical analyses performed in R (no version, packages used if any) and packages in R used for analyses/visualization did not have version numbers. It should be noted that the extreme complexity (e.g. location, size, numbers of samples, participants, etc.) of this project should be factored into their total score as the authors well-described the protocol and data despite the immensity of this work. Marbouty et al. (2014) was one of the first research works to apply chromosome conformation capture (3C) to metagenomic communities of microbes, allowing a sophisticated method for analyzing genomic material from key individuals in environmental samples. The paper is very detailed, and heavily cited by other studies reproducing and building upon their results. This is a particularly important paper in the area, and the authors’ results have been reproduced by many other researchers. The conclusions are also very well-supported by the evidence, and the authors do not rely on assumptions to explain results. Although the software for statistical analyses is briefly mentioned, the statistical analyses are not in depth in the article. Overall, the paper had a very high ranking.

Kent et al. (2020) studied how antibiotic resistance genes spread among harmful bacteria within a clinical setting and revealed the contribution of microbiome bacteria to this spread. This paper is also accompanied by a "Reporting Summary" like the Chng et al. (2020) study, which Nature Research implemented. The methods section was clearly written; however, it was not as detailed as expected and reads as if there was a word limit. Additionally, the description of data was not as clear and the statistical analyses used could have been written in more detail. Upon further inspection, the publishing journal, Nature Communications, recommends that “…methods should be written as concisely as possible and typically do not exceed 3,000 words but may be longer if necessary.” The methods section of this article was less than 3,000 words. However, overall, the data was well-described and their code was made freely available on Github which was great to see for a life sciences paper.

Stalder et al. (2019) demonstrated the use of a HiC proximity ligation method could reconstruct genome-plasmid host association from an environmental microbial population. This was the only paper to receive a 2 on the tool availability and accessibility as this paper was demonstrating a method tool developed by a private company and access to the company’s proprietary tool would be needed to reproduce the results. However, the data are readily available through an accessible online database repository, and supplementary data and code for analyses that were not published in the main article are also available through OSF Home, a free open platform for data sharing, and which was provided by the private research partner. For these reasons, the paper scored a perfect rank for data availability and accessibility. The strength of the paper falls apart at the description of the protocols. The methods section fails to accurately describe a significant portion of the protocol (i.e. proximity ligation step) and which requires the reader to go to the private partner's website to try to find the method. Additionally, some experimental steps are ambiguous (such as the flow cytometry protocol for cell counts) was not described. The study conclusion appeared unrelated to the evidence collected and follow-up or additional evidence as to why this was observed or if this was a statistically significant conclusion was not provided. No discussion of the type of statistical analyses on the environmental sampling data were performed, and statistical assumptions or significance statistics were not provided. Lastly, the title is very generic and could be misleading to the reader: a more area-specific title would more accurately describe the study. This was the only paper to get a rank of 0 in any section (tool description). It is highly unlikely that results of this paper could be reproduced purely based on this paper. 
Serizay et al. (2024) describes novel data structures, computational methods, and visualization tools in R for analyzing Hi-C and other 3C-related genomic analysis data using the open-source Bioconductor project. This paper appears to be an in-depth summary of an extremely detailed project: the authors even submit an embedded link to the open-source step-by-step online book. This concept of writing results, summaries, methods, and discussions in a step-by-step book style is cutting-edge and is an interesting path for future studies to take, while publishing a “summary” of this book as a research article. Additionally, there is also a reporting summary with this paper as it is also a Nature-affiliated paper. This was the only paper to receive a perfect rank (3) across all criteria for reproducibility. 

Interestingly, the highest-ranking paper for this section (and which received a perfect score) was the study performed by Serizay et al. (2024) a computational paper describing a new bioinformatics pipeline for genomic analyses that could be applied in surveillance genomics. Comparatively, the other four papers were studies with complex environmental samples, with or without clinical patient samples, and plenty of wet lab work: one can’t help but wonder if the sheer complexity of these types of experiments contributed to missing details or unclear instructions that could hinder reproducibility studies. Of these four, three papers that ranked well (but not perfectly) all appeared to do their best to describe their respective and highly complex experiments in totality. Yet the paper that ranked poorly had glaringly obvious missing data, unclear methods, and a misleading grand title, leading one to believe this was done deliberately. Unfortunately, these four papers do compound and contribute to the reproducibility crisis in the life sciences. Though it is heartening to see trends towards accountability and reporting summaries required by publishing journals. 

##  Neuroplasticity and Perceptual Learning (Ashim Pandey)

## Cortex-wide Brain Imaging and Neural Dynamics (Rian Fritz D. Jalandoni)

In the analysis of cortex-wide brain dynamics, clear documentation of both the experimental setup and the analysis code is paramount. There should be emphasis on the clarity of the experimental setup and the thorough documentation of code analysis is crucial for fostering productive innovation in this field. The examiner FJ looks into five papers within this research domain, with one (Cuoto et al.) focusing on a novel experimental setup for widefield imaging and image analysis using MATLAB and Python, and the remaining four papers centering on the analysis of neural activity propagation in the brain.

Cuoto et al.'s (2021) study presents a detailed protocol for assembling a widefield experiment setup. It clearly explains the required instruments, chemicals, surgical procedures, and the processing of recorded videos from the widefield macroscope. The paper offers readily accessible data via an open access link, eliminating the need for authentication or formal requests. The methods are clearly articulated, aligning well with the experiment's objectives, with well-defined surgical procedures and population sizes. Data preprocessing steps are explicitly outlined, with both MATLAB and Python versions of the code provided, acknowledging the prevalent use of these languages in this type of analysis. Additionally, the paper meticulously explains imaging methods and provides sufficient details on chemicals, camera specifications, and hardware to facilitate replication of the setup.

Subsequent papers focus on the analysis of neural activity derived from widefield imaging data. In the paper by Linden et al. (2021), the authors utilize Lagrangian coherent structures, a method from fluid dynamics, for widefield imaging data analysis. While the code and data used in the study are publicly available, the code is under an open license and cannot be modified without permission. The paper provides supplementary movies and clearly states mouse population details. However, the reviewer RJ has some reluctance about the statistical tests performed and the clarity of certain steps in the extraction of Lagrangian Coherent Structures.

Afrashteh et al. (2017) introduce a MATLAB toolbox for extracting velocity vectors from widefield imaging data through optic flow analysis. The paper systematically evaluates the algorithm's performance, comparing obtained velocity fields with theoretical parameters and assessing its robustness against noise in widefield imaging data. Although mouse population details are sparse, likely due to the focus on testing the toolbox, the paper provides open-access code and distribution tools. However, there are some documentation gaps, particularly regarding algorithm explanation, despite the provision of a user manual.

Liang et al.'s (2021) paper focuses on identifying wave patterns in neural activity propagation primarily using signal processing and vector analysis. Although data accessibility is limited and requires contacting the authors, the methods and analysis are clearly explained and aligned with the study's objectives. The description of tools and imaging methods is thorough, but more details regarding the mice used would be beneficial. Although the code is not readily available online, it can be obtained from the authors via request.

Finally, Townsend et al.'s (2018) study also employs vector analysis on neural activity dynamics, but using LFP datasets. The paper references external data sources, necessitating requests for access, and provides links to detailed data information. The methods are clearly articulated, with well-defined population sizes and data preprocessing steps. However, additional details about the marmosets used would enhance clarity. The code is readily available with provided links, but the documentation lacks clarity regarding its purposes and underlying rationale, despite being accessible under license.


## Single Molecule Imaging of DNA Interacting Proteins (Lydia Hodgins)
5 papers related to single molecule tracking and analysis of the dynamics of DNA interacting proteins were evaluated as they relate to the research topic studied by contributor LH. These papers fall into the scientific fields of fundamental biology and biophysics. They range in publication years from 2019 to 2024 and represent the publication journals: Journal of Physical Chemistry, Nucleic Acids Research, Journal of Physics D: Applied Physics, eLife, and Molecular Cell. Overall, it is found that these publications perform well in the description of methods, sample population, and tools categories, but perform poorly in both the data and tool availability categories. When evaluating my personal impression of the reproducibility of these papers I found that data and tool availability had the biggest impact on my decision, resulting in most papers receiving a low score. 

Mine-Hattab et al. (2021) received the highest reproducibility score (4) and was the only paper that scored 3/3 in data availability. This study provided all raw data through a zenodo data base. Both the description of the methods and the sample populations are clear, detailed, and well organized. However, the description of the tools used in this study lacked detail such as microscope and software specifications. The study evaluated poorest in the tool availability category as all analysis programs were custom-built and not openly shared. This observation resulted in an overall reproducibility score of 4/5 as the data is available, however, analysis depends on either cooperation from the authors to share their code or use of another software chosen or developed based on the description of analysis methods. Either of which introduce uncertainty regarding the execution of reproducing the results. 

El Sayyed et al. (2024) received the next highest reproducibility score (3). This study had a very clear and detailed materials and methods section, scoring 3 across the board for description of methods, data and tools. Where this study performs poorly is the availability of both the data and tools. Only a portion of the raw data is openly accessible, which does not include the data which most significantly contributes to the conclusions. However, a statement is provided claiming, “any additional information required to reanalyze the data reported in this paper is available from the lead contact upon request” (El Sayyed et al., 2024). With respect to the tools, links are provided for any open source code and software that was used, but the software used for the core analysis is declared to be custom and is not openly shared. The limited access to both the data and analysis tools is why this paper receives an overall score of 3/5 as it is possible the results could be reproduced but this is highly dependent on the authors complying to the claim that additional data and software will be shared.

Fan et al. (2023) and Bettridge et al. (2023) both received 2/5 for their overall reproducibility scores. For Fan et al. (2023) the study performed well with respect to the description of methods and data but performed poorly when describing the tools as import specifications regarding the microscope were omitted and few to no parameters were provided for both image acquisition and analysis. Additionally, no data or custom code are openly available. Only links to open-source software and a note stating data will be provided upon request are provided. For Bettridge et al. (2023) the study provided clear and detailed descriptions of the methods, data and tools. Again for this study, no data or custom analysis code is openly accessible. No statement is provided regarding the authors’ position on sharing the data, however, it is noted that some custom code is available upon request. The heavy reliance on compliance from the authors’ to share both data and analysis code to reproduce these studies is why both received a overall score of 2/5 as it is uncertain whether compliance would be experienced. 

Lastly, Banaz et al. (2019) received the lowest reproducibility score of 1/5 and performed very poorly across the board. The study lacked a materials and methods section and instead reports poorly detailed methods throughout the main text. Additionally, specific details regarding the population sample, repeats, microscope specifications, and utilized software or code are missing. No data is openly available and no acknowledgement regarding a willingnes to share the data is provided. With respect to the software tools, more information is necessary from the authors to identify what tools were used and how to access them.

## Machine learning for biological insights from sequence modelling  (César Miguel Valdez Córdova)

The advent of artificial intelligence has breathed new life into multiple scientific disciplines through the harnessing of the vast amounts of data made available by high throughput experiments. Biology is no exception. Multiple data banks, from the broader to the phenomena-specifc have made training machine learning models at a scale not only possible, but a daunting engineering challenge in and of itself. After going through such great lengths to make the former possible, it is in a researcher’s best interest to make their models and associated tools widely available; preferably, in a state where user effort is minimal for usability or reproduction, with the intent of maximizing the model’s traction.

The five models contained in the papers described herein, in their current state, can be downloaded and trained to a usable state by those with a programming background and literacy in machine learning frameworks, given the appropriate computing resources. As judged by this discussion’s metrics, all of the work presented here meets the basic reproducibility threshold as outlined, automatically putting them at the provided classification’s maximum score. However, a further distinction must be made, which is often a cause of concern, particularly in the world of machine learning: reproducibility does not stop at making a model available. Providing model weights alongside the model is the gold standard to ensure a model will be as performant as reported, which at its base shouldn’t be necessary for reproducing the paper. The level of detail, simplicity and openness at which the components that are related to reproducing the work through a model’s execution impacts reproducibility: Model weights, container images, hyperparameter choice, randomization schemes and associated model-specific artefacts, significantly alter the levels of granularity at which complete, “true” reproducibility is achieved; proper combinations of the former may impact the overall result, even if everything is available at a first glance. Finally, a major hurdle in reproducing ML papers lies not in any of the former, but in securing the (often) costly computational resource requirements, often in the form of Graphical Processing Units (GPU) hours at diverse scales; all papers included herein describe the compute used to train the model.

Theodoris et al. (2023) present Geneformer. Alongside providing the full model used in their paper, they assemble their own dataset: Genecorpus-30M which is made available and immediately accessible from a huggingface repository, in conjunction with model weights. Thorough hyperparameter and architectural decisions are provided in the main paper, while the supplementary information details the composition of the dataset and other fine tuning details.

Nguyen et al. (2023a) makes virtual images available that can be pulled, google colab notebooks to train your own in-session models, across different model sizes, all pointing to the correct data sources. Additionally, the github repository has multiple points of contact and invitationts to enthusiast communities of this model architecture, which provides further resources to help when troubleshooting the (re)-implementation of this paper. Similarly, in Nguyen et al. (2023b), another model using the HyenaDNA architecture as its base, with model-specific improvements, makes both the model and the weights available online on a huggingface repository and are directly utilizable. 

DaSilva et al. (2024) make their model, associated training scripts and docker images available on github. While the readme isn’t as comprehensive as any of the former, following the instructions and additional hyperparameter information in the paper should allow for full reproduction of the model. No checkpoints or weights are directly provided.

Lal et al. (2024) leverages the HyenaDNA architecture to design cis-regulatory DNA elements (CREs). Thorough experimental design and tokenization schemes are described and promptly used to leverage the HyenaDNA architecture. Code clearly pointed to and model weights provided, as they depend on HyenaDNA. Their own regLM model weights, as well as the synthetic sequences used for fine tuning the models are also provided through Zenodo.

## Biomedical Engineering Methods for drug delivery and microfluidics (Ioan Duchastel)

Biomedical engineering techniques have gained a lot of traction over the past few decades. With organ-on-a-chip technologies being one way to practice in-vitro assays, there are many opportunities to develop systems that mimic real-life environment with precise accuracy. To gauge the level of detail put into making these procedures reproducible, contributor IDV reviewed 3 papers related to bioengineering methods. The publications ranged from 2014 to 2020 publication years and investigate methods for utilizing membranes to coat surfaces.

Fang et al. (2014) introduce a new method of utilizing biomimetic nanoparticles to target cancer tissues. By coating polymeric nanoparticle cores with cancerous cell membranes, they fabricated nanoparticles with a high binding affinity with tumor cells. Fortunately, the paper explains its methods down to the concentrations of each used chemical by a readily available supporting information document. Data didn’t seem to be accessible through publication sites, putting the burden on the reader to obtain it through the authors. However, this is a minor issue, as the essential details to reproduce the results is available and every tool is accessible.

Rao et al. (2016) also introduce a way to use biomimetic nanoparticles, this time to facilitate imaging of cancer tissues. By using the nanoparticles as fluorescent probes, they could image the cancer tissues, taking advantage of the strong adhesion between macrophages and cancer cells. The data presented in this report is not accessible, but, similarly to the previous one, a lot of the data comes from analyzing the images present in the report. The report provides a thorough description and makes the methods available to reproduce.

Clapis et al. (2020) used phospholipid bilayers to coat the walls of microfluidics channel. This decreases cell adhesion on the chip, benefitting flow-through assays by increasing the flow of cells. Data is unavailable for this report and seems to be only available through the authors. Besides this, the report provides detailed descriptions of the methods, making it easy to reproduce the assays described in it.


## Pathophysiological Modelling for Optic Nerve Injury (Ryan Huang)

## Neural Signal Analysis of Anesthesia-Associated Brain Dynamics Change (Ryan Huang)


# Conclusion

# References

Afrashteh, N., Inayat, S., Mohsenvand, M., & Mohajerani, M. H. (2017). Optical-flow analysis toolbox for characterization of spatiotemporal dynamics in mesoscale optical imaging of brain activity. NeuroImage, 153, 58–74. https://doi.org/10.1016/j.neuroimage.2017.03.034

Awada, A., Bakhtiari, S., & Pack, C. C. (2021). Visual perceptual learning generalizes to untrained effectors. Journal of Vision, 21(3), 10. https://doi.org/10.1167/jov.21.3.10

Banaz, N., Mäkelä, J., & Uphoff, S. (2018). Choosing the right label for single-molecule tracking in live bacteria: Side-by-side comparison of photoactivatable fluorescent protein and Halo tag dyes. _Journal of Physics D: Applied Physics, 52_(6), 064002. https://doi.org/10.1088/1361-6463/aaf255

Bettridge, K., Harris, F. E., Yehya, N., & Xiao, J. (2023). RNAP Promoter Search and Transcription Kinetics in Live E. coli Cells. _The Journal of Physical Chemistry B, 127_(17), 3816–3828. https://doi.org/10.1021/acs.jpcb.2c09142

Boyle, E. A., Li, Y. I., & Pritchard, J. K. (2017). An Expanded View of Complex Traits: From Polygenic to Omnigenic. Cell, 169(7), 1177–1186. https://doi.org/10.1016/j.cell.2017.05.038

Bryant, B. J., Yau, Y. Y., Arceo, S. M., Daniel-Johnson, J., Hopkins, J. A., & Leitman, S. F. (2012). Iron Replacement Therapy in the Routine Management of Blood Donors. Transfusion, 52(7), 1566–1575. https://doi.org/10.1111/j.1537-2995.2011.03488.x

Calì, C., Agus, M., Kare, K., Boges, D. J., Lehväslaiho, H., Hadwiger, M., & Magistretti, P. J. (2019). 3D cellular reconstruction of cortical glia and parenchymal morphometric analysis from Serial Block-Face Electron Microscopy of juvenile rat. Progress in Neurobiology, 183, 101696. https://doi.org/10.1016/j.pneurobio.2019.101696

Chen, Y., Butler-Laporte, G., Liang, K. Y. H., Ilboudo, Y., Yasmeen, S., Sasako, T., Langenberg, C., Greenwood, C. M. T., & Richards, J. B. (2024). The performance of AlphaMissense to identify genes causing disease (p. 2024.03.05.24303647). medRxiv. https://doi.org/10.1101/2024.03.05.24303647

Chng, K. R., Li, C., Bertrand, D., Ng, A. H. Q., Kwah, J. S., Low, H. M., Tong, C., Natrajan, M., Zhang, M. H., Xu, L., Ko, K. K. K., Ho, E. X. P., Av-Shalom, T. V., Teo, J. W. P., Khor, C. C., Chen, S. L., Mason, C. E., Ng, O. T., Marimuthu, K., … Nagarajan, N. (2020). Cartography of opportunistic pathogens and antibiotic resistance genes in a tertiary hospital environment. Nature Medicine, 26(6), 941–951. https://doi.org/10.1038/s41591-020-0894-4

Clapis, J. R., Fan, M. J., & Kovarik, M. L. (2021). Supported bilayer membranes for reducing cell adhesion in microfluidic devices. Analytical Methods, 13(12), 1535–1540. https://doi.org/10.1039/D0AY01992E

Couto, J., Musall, S., Sun, X. R., Khanal, A., Gluf, S., Saxena, S., Kinsella, I., Abe, T., Cunningham, J. P., Paninski, L., & Churchland, A. K. (2021). Chronic, cortex-wide imaging of specific cell populations during behavior. Nature Protocols, 16(7), 3241–3263. https://doi.org/10.1038/s41596-021-00527-z

DaSilva, L. F., Senan, S., Patel, Z. M., Reddy, A. J., Gabbita, S., Nussbaum, Z., Córdova, C. M. V., Wenteler, A., Weber, N., Tunjic, T. M., Khan, T. A., Li, Z., Smith, C., Bejan, M., Louis, L. K., Cornejo, P., Connell, W., Wong, E. S., Meuleman, W., & Pinello, L. (2024). DNA-Diffusion: Leveraging Generative Models for Controlling Chromatin Accessibility and Gene Expression via Synthetic Regulatory Elements (p. 2024.02.01.578352). bioRxiv. https://doi.org/10.1101/2024.02.01.578352

de Kort, W., Prinsze, F., Nuboer, G., Twisk, J., & Merz, E.-M. (2019). Deferral rate variability in blood donor eligibility assessment. Transfusion, 59(1), 242–249. https://doi.org/10.1111/trf.14984

Fan, J., El Sayyed, H., Pambos, O. J., Stracy, M., Kyropoulos, J., & Kapanidis, A. N. (2023). RNA polymerase redistribution supports growth in E. coli strains with a minimal number of rRNA operons. _Nucleic Acids Research, 51_(15), 8085–8101. https://doi.org/10.1093/nar/gkad511

Fang, R. H., Hu, C.-M. J., Luk, B. T., Gao, W., Copp, J. A., Tai, Y., O’Connor, D. E., & Zhang, L. (2014). Cancer Cell Membrane-Coated Nanoparticles for Anticancer Vaccination and Drug Delivery. Nano Letters, 14(4), 2181–2188. https://doi.org/10.1021/nl500618u

Forgetta, V., Jiang, L., Vulpescu, N. A., Hogan, M. S., Chen, S., Morris, J. A., Grinek, S., Benner, C., Jang, D.-K., Hoang, Q., Burtt, N., Flannick, J. A., McCarthy, M. I., Fauman, E., Greenwood, C. M. T., Maurano, M. T., & Richards, J. B. (2022). An effector index to predict target genes at GWAS loci. Human Genetics, 141(8), 1431–1447. https://doi.org/10.1007/s00439-022-02434-z

Fuller, J. T., Barnes, S., Sadun, L. A., Ajmera, P., Alexandrova, A. N., & Sadun, A. A. (2023). Coenzyme Q10 trapping in mitochondrial complex I underlies Leber’s hereditary optic neuropathy. Proceedings of the National Academy of Sciences, 120(39), e2304884120. https://doi.org/10.1073/pnas.2304884120

Hirase, H., Akther, S., Wang, X., & Oe, Y. (2019). Glycogen distribution in mouse hippocampus. Journal of Neuroscience Research, 97(8), 923–932. https://doi.org/10.1002/jnr.24386

Huxlin, K. R., Martin, T., Kelly, K., Riley, M., Friedman, D. I., Burgin, W. S., & Hayhoe, M. (2009). Perceptual Relearning of Complex Visual Motion after V1 Damage in Humans. Journal of Neuroscience, 29(13), 3981–3991. https://doi.org/10.1523/JNEUROSCI.4882-08.2009

Karregat, J., Sweegers, M. G., Quee, F. A., Weekamp, H. H., Swinkels, D. W., Novotny, V. M. J., Zaaijer, H. L., & Van Den Hurk, K. (2022). Ferritin-guided iron supplementation in whole blood donors: Optimal dosage, donor response, return and efficacy (FORTE)—a randomised controlled trial protocol. BMJ Open, 12(3), e056316. https://doi.org/10.1136/bmjopen-2021-056316

Kent, A. G., Vill, A. C., Shi, Q., Satlin, M. J., & Brito, I. L. (2020). Widespread transfer of mobile antibiotic resistance genes within individual gut microbiomes revealed through bacterial Hi-C. Nature Communications, 11(1), 4379. https://doi.org/10.1038/s41467-020-18164-7

Krayenbuehl, P.-A., Battegay, E., Breymann, C., Furrer, J., & Schulthess, G. (2011). Intravenous iron for the treatment of fatigue in nonanemic, premenopausal women with low serum ferritin concentration. Blood, 118(12), 3222–3227. https://doi.org/10.1182/blood-2011-04-346304

Lal, A., Garfield, D., Biancalani, T., & Eraslan, G. (2024). regLM: Designing realistic regulatory DNA with autoregressive language models (p. 2024.02.14.580373). bioRxiv. https://doi.org/10.1101/2024.02.14.580373

Lennon, N. J., Kottyan, L. C., Kachulis, C., Abul-Husn, N. S., Arias, J., Belbin, G., Below, J. E., Berndt, S. I., Chung, W. K., Cimino, J. J., Clayton, E. W., Connolly, J. J., Crosslin, D. R., Dikilitas, O., Velez Edwards, D. R., Feng, Q., Fisher, M., Freimuth, R. R., Ge, T., … Kenny, E. E. (2024). Selection, optimization and validation of ten chronic disease polygenic risk scores for clinical implementation in diverse US populations. Nature Medicine, 30(2), 480–487. https://doi.org/10.1038/s41591-024-02796-z

Liang, Y., Song, C., Liu, M., Gong, P., Zhou, C., & Knöpfel, T. (2021). Cortex-Wide Dynamics of Intrinsic Electrical Activities: Propagating Waves and Their Interactions. Journal of Neuroscience, 41(16), 3665–3678. https://doi.org/10.1523/JNEUROSCI.0623-20.2021

Linden, N. J., Tabuena, D. R., Steinmetz, N. A., Moody, W. J., Brunton, S. L., & Brunton, B. W. (2021). Go with the FLOW: Visualizing spatiotemporal dynamics in optical widefield calcium imaging. Journal of The Royal Society Interface, 18(181), 20210523. https://doi.org/10.1098/rsif.2021.0523

Mantadakis, E., Panagopoulou, P., Kontekaki, E., Bezirgiannidou, Z., & Martinis, G. (2022). Iron Deficiency and Blood Donation: Links, Risks and Management. Journal of Blood Medicine, 13, 775–786. https://doi.org/10.2147/JBM.S375945

Marbouty, M., Cournac, A., Flot, J.-F., Marie-Nelly, H., Mozziconacci, J., & Koszul, R. (2014). Metagenomic chromosome conformation capture (meta3C) unveils the diversity of chromosome organization in microorganisms. eLife, 3, e03318. https://doi.org/10.7554/eLife.03318

Miné-Hattab, J., Heltberg, M., Villemeur, M., Guedj, C., Mora, T., Walczak, A. M., Dahan, M., & Taddei, A. (2021). Single molecule microscopy reveals key physical features of repair foci in living cells. _eLife, 10_, e60577. https://doi.org/10.7554/eLife.60577

Nguyen, E., Poli, M., Durrant, M. G., Thomas, A. W., Kang, B., Sullivan, J., Ng, M. Y., Lewis, A., Patel, A., Lou, A., Ermon, S., Baccus, S. A., Hernandez-Boussard, T., Ré, C., Hsu, P. D., & Hie, B. L. (2024). Sequence modeling and design from molecular to genome scale with Evo (p. 2024.02.27.582234). bioRxiv. https://doi.org/10.1101/2024.02.27.582234

Nguyen, E., Poli, M., Faizi, M., Thomas, A., Birch-Sykes, C., Wornow, M., Patel, A., Rabideau, C., Massaroli, S., Bengio, Y., Ermon, S., Baccus, S. A., & Ré, C. (2023). HyenaDNA: Long-Range Genomic Sequence Modeling at Single Nucleotide Resolution (arXiv:2306.15794). arXiv. https://doi.org/10.48550/arXiv.2306.15794

Ochoa, D., Karim, M., Ghoussaini, Maya, Hulcoop, D. G., McDonagh, E. M., & Dunham, I. (2022). Human genetics evidence supports two-thirds of the 2021 FDA-approved drugs. Nature Reviews Drug Discovery, 21(8), 551–551. https://doi.org/10.1038/d41573-022-00120-3

Pan, Y., Sullivan, D., Shreiber, D. I., & Pelegri, A. A. (2013). Finite Element Modeling of CNS White Matter Kinematics: Use of a 3D RVE to Determine Material Properties. Frontiers in Bioengineering and Biotechnology, 1. https://doi.org/10.3389/fbioe.2013.00019

Plourde, G., & Arseneau, F. (2017). Attenuation of high-frequency (30–200 Hz) thalamocortical EEG rhythms as correlate of anaesthetic action: Evidence from dexmedetomidine. British Journal of Anaesthesia, 119(6), 1150–1160. https://doi.org/10.1093/bja/aex329

Rao, L., He, Z., Meng, Q.-F., Zhou, Z., Bu, L.-L., Guo, S.-S., Liu, W., & Zhao, X.-Z. (2017). Effective cancer targeting and imaging using macrophage membrane-camouflaged upconversion nanoparticles. Journal of Biomedical Materials Research Part A, 105(2), 521–530. https://doi.org/10.1002/jbm.a.35927

Rohlfing, T. (2012). Image Similarity and Tissue Overlaps as Surrogates for Image Registration Accuracy: Widely Used but Unreliable. IEEE Transactions on Medical Imaging, 31(2), 153–163. https://doi.org/10.1109/TMI.2011.2163944

Salmon, C. K., Syed, T. A., Kacerovsky, J. B., Alivodej, N., Schober, A. L., Sloan, T. F. W., Pratte, M. T., Rosen, M. P., Green, M., Chirgwin-Dasgupta, A., Mehta, S., Jilani, A., Wang, Y., Vali, H., Mandato, C. A., Siddiqi, K., & Murai, K. K. (2023). Organizing principles of astrocytic nanoarchitecture in the mouse cerebral cortex. Current Biology, 33(5), 957-972.e5. https://doi.org/10.1016/j.cub.2023.01.043

Sayyed, H. E., Pambos, O. J., Stracy, M., Gottesman, M. E., & Kapanidis, A. N. (2024). Single-molecule tracking reveals the functional allocation, in vivo interactions, and spatial organization of universal transcription factor NusG. Molecular _Cell, 84_(5), 926-937.e4. https://doi.org/10.1016/j.molcel.2024.01.025

Serizay, J., Matthey-Doret, C., Bignaud, A., Baudry, L., & Koszul, R. (2024). Orchestrating chromosome conformation capture analysis with Bioconductor. Nature Communications, 15(1), 1072. https://doi.org/10.1038/s41467-024-44761-x

Stalder, T., Press, M. O., Sullivan, S., Liachko, I., & Top, E. M. (2019). Linking the resistome and plasmidome to the microbiome. The ISME Journal, 13(10), 2437–2446. https://doi.org/10.1038/s41396-019-0446-4

Szinte, M., Jonikaitis, D., Rolfs, M., Cavanagh, P., & Deubel, H. (2016). Presaccadic motion integration between current and future retinotopic locations of attended objects. Journal of Neurophysiology, 116(4), 1592–1602. https://doi.org/10.1152/jn.00171.2016

Tesser, R. A., Niendorf, E. R., & Levin, L. A. (2003). The morphology of an infarct in nonarteritic anterior ischemic optic neuropathy. Ophthalmology, 110(10), 2031–2035. https://doi.org/10.1016/S0161-6420(03)00804-2

Theodoris, C. V., Xiao, L., Chopra, A., Chaffin, M. D., Al Sayed, Z. R., Hill, M. C., Mantineo, H., Brydon, E. M., Zeng, Z., Liu, X. S., & Ellinor, P. T. (2023). Transfer learning enables predictions in network biology. Nature, 618(7965), 616–624. https://doi.org/10.1038/s41586-023-06139-9

Townsend, R. G., & Gong, P. (2018). Detection and analysis of spatiotemporal patterns in brain activity. PLoS Computational Biology, 14(12), e1006643. https://doi.org/10.1371/journal.pcbi.1006643

Willis, H. E., Ip, I. B., Watt, A., Campbell, J., Jbabdi, S., Clarke, W. T., Cavanaugh, M. R., Huxlin, K. R., Watkins, K. E., Tamietto, M., & Bridge, H. (2023). GABA and Glutamate in hMT+ Link to Individual Differences in Residual Visual Function After Occipital Stroke. Stroke, 54(9), 2286–2295. https://doi.org/10.1161/STROKEAHA.123.043269

Xie, G., Deschamps, A., Backman, S. B., Fiset, P., Chartrand, D., Dagher, A., & Plourde, G. (2011a). Critical involvement of the thalamus and precuneus during restoration of consciousness with physostigmine in humans during propofol anaesthesia: A positron emission tomography study. British Journal of Anaesthesia, 106(4), 548–557. https://doi.org/10.1093/bja/aeq415

Xie, G., Deschamps, A., Backman, S. B., Fiset, P., Chartrand, D., Dagher, A., & Plourde, G. (2011b). Critical involvement of the thalamus and precuneus during restoration of consciousness with physostigmine in humans during propofol anaesthesia: A positron emission tomography study. British Journal of Anaesthesia, 106(4), 548–557. https://doi.org/10.1093/bja/aeq415

Yang 杨菁艺, J., Saionz, E. L., Cavanaugh, M. R., Fahrenthold, B. K., Melnick, M. D., Tadin, D., Briggs, F., Carrasco, M., & Huxlin, K. R. (2024). Limited restoration of contrast sensitivity with training after V1 damage in humans. eNeuro, 11(3), ENEURO.0020-24.2024. https://doi.org/10.1523/ENEURO.0020-24.2024


# Appendix

## Final Criteria

#### Data availability and accessibility
##### Numerical score out of 3:
   3/3 - Unfettered Access
      Immediate access, no perceived barriers
      e.g. link provided to online cache of study data, free databases used, supplemental data provided, etc.
   2/3 - Access with Barriers
      Access but uncertain timeline
      e.g. confidentiality, approving agency or subscription delays
   1/3 - Unsatisfactory Access
      Uncertain access and uncertain timeline
      e.g. must contact authors or journal
   0/3 - No Access
      Cannot get access (realistically)
      e.g. no contact information provided, broken data links

#### Description of method
##### Categorical score using yes/no check points. Sum the check marks for each section out of 3.
   ☐ Is the objective of the study clearly defined?
   ☐ Are the conclusion clearly supported by the collected evidence?
   ☐ The method protocol is detailed and clearly written.
      e.g. order of steps taken

#### Description of data
##### Categorical score using yes/no check points. Sum the check marks for each section out of 3.
   ☐ The data or sample population under study are clearly defined for each analysis.
              e.g. Sample size, metadata
   ☐ The source of the data/population is clearly defined.
   e.g. from database collection, approving agency, collected from previous experiment (or from the same study), which cell line, cite other study that you got data, etc.
   ☐ Data pre-processing or processing is clearly defined.
   e.g. missing data, outliers, data removed, sub-populations, data sets narrowed down based on different targets, biological and/or technical replicates, blinding, randomization, etc.

#### Description of tools
##### Categorical score using yes/no check points. Sum the check marks for each section out of 3.
   ☐ The tools that directly contribute to the collected evidence are identified.
   Note: literally just the name of the tool like “scanning electron microscope” or “R”.
   ☐ The tools are also clearly defined in detail.
   e.g. make/model of equipment, supplier/developer, supplier/developer location, software name, version numbers, etc.
   ☐ The parameters are defined for each tool that directly contribute to the collected evidence.
   e.g. settings, limitations, modifications, software changes, updates, adaptations, extensions, bugs/debugging, packages, etc.

#### Tool availability and accessibility
##### Numerical score out of 3:
   3/3 - Unfettered Access
      Immediate access, no perceived barriers
   e.g. no license needed, free online software, code/program available online (i.e. github, other repo).
   2/3 - Access with Barriers
      Access but uncertain timeline
      e.g. confidentiality barriers, approving agency or subscription delays.
   1/3 - Unsatisfactory Access
      Uncertain access and uncertain timeline
   e.g. must contact authors or journal, internally developed software or equipment that is not freely accessible.
   0/3 - No Access
      Cannot get access (realistically)
   e.g. no contact information provided, broken links.
   
#### Overall Replicability -Can those trained in the field can reproduce the study given the appropriate resources?
##### Numerical score out of 5:
   5/5 - Very likely
   4/5 - Likely
   3/5 - Possibly
   2/5 - Not likely
   1/5 - Very unlikey


