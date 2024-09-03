# HackBio-Internship_September-2024_DrPati_BioHack238688-
Frontend Bioinformatics: Basic R and ggplot2
**Stage 0 (Writing)**

**Learning Track 4: Frontend Bioinformatics**

** **

**Plotting with Base R vs. ggplot in Cancer Research**

**By: _DrPati\_BioHack238688#_**

** **

**Introduction**

Data visualization is an essential tool in cancer research, allowing scientists to comprehend complex statistics and reach relevant findings. Base R plotting (1) and ggplot2 (2) are two well-known data visualization approaches in R, one of the most popular computer languages in bioinformatics. Each has strengths and uses, especially in cancer research.

**Base R Plotting**

Base R visualization functions are integrated into R and provide an easy way to produce basic graphs including histograms, scatter plots, and boxplots. These processes are user-friendly and require little code, making them suitable for rapid, simple visualizations. For example, researchers may utilize Base R plotting to create a scatter plot comparing gene expression levels against patient survival times. This type of visualization can assist discover potential links between gene expression and clinical outcomes, serving as a starting point for additional in-depth investigation.

Despite being simple, Base R plotting is limited in terms of customization and adaptability. While it is adequate for simple, exploratory visualizations, it falls short when more complicated and creatively refined plots are required, especially in publications where visual appeal and clarity are extremely important.

**ggplot2**

In comparison, ggplot2, a R tool based on the Grammar of Graphics, provides a more powerful and adaptable method for data display. ggplot2 enables the construction of highly configurable, layered plots that may convey complex data. This is especially useful in cancer research, as multidimensional data must be presented in a way that reveals subtle linkages.\
For example, in a study looking into the effects of various mutations on cancer growth, ggplot2 can be used to generate a faceted plot showing gene expression levels across different cancer kinds. Researchers may easily compare the effects of these mutations across several datasets by representing them with different colors, shapes, and sizes.

Furthermore, ggplot2's ability to integrate statistical modifications directly into plots (for example, adding trend lines or confidence intervals) improves data interpretability. This function is especially valuable in cancer research, where determining the statistical significance of observed trends is essential.

**Case Studies in Cancer Research**

One significant use of ggplot2 in cancer research is the visualization of survival analysis data (3). ggplot2 (4) makes it simple to construct and edit Kaplan-Meier plots, which are commonly used to show patient survival rates over time. In one study, researchers utilized ggplot2 to perform clustering analysis to show survival disparities among breast cancer patients with various gene mutations (5), revealing which mutations were related with inferior outcomes.\
Another example is the use of ggplot2 to generate heatmaps that depict gene expression data across various cancer subtypes (6). This form of visualization aids in the identification of gene expression patterns that may be associated with distinct cancer behaviors or treatment responses.

**Conclusion**

Both Base R plotting and ggplot2 have applications in cancer research. While Base R is excellent for rapid, simple visualizations, ggplot2 provides the depth and flexibility required for more complicated and publishable illustrates. As cancer research generates increasingly massive and complicated datasets, the capacity to efficiently depict these data will remain an important part of the research process. By combining the characteristics of Base R with ggplot2, researchers might get greater insights into cancer's biological pathways and, ultimately, contribute to the development of more effective treatment options.

**References:**

1.     Gu, Z. (2022). Complex heatmap visualization. _Imeta_, _1_(3), e43.

2.     Vidman, L., Källberg, D., & Rydén, P. (2019). Cluster analysis on high dimensional RNA-seq data with applications to cancer research-An evaluation study. _PLoS One_, _14_(12), e0219102.

3.     Coleman, A., Bose, A., & Mitra, S. (2023). Metagenomics data visualization using R. In Metagenomic Data Analysis (pp. 359-392). New York, NY: Springer US.

4.     Karihtala, P., Kilpivaara, O., & Porvari, K. (2024). Mutational signatures and their association with cancer survival and gene expression in multiple cancer types. International Journal of Cancer.

5.     Manoharan, M., Mandloi, N., Priyadarshini, S., Patil, A., Gupta, R., Iyer, L., ... & Chaudhuri, A. (2018). A computational approach identifies immunogenic features of prognosis in human cancers. _Frontiers in immunology_, _9_, 3017.

6.     Sessler, T., Quinn, G. P., Wappett, M., Rogan, E., Sharkey, D., Ahmaderaghi, B., ... & McDade, S. S. (2023). surviveR: a flexible shiny application for patient survival analysis. _Scientific Reports_, _13_(1), 22093.
