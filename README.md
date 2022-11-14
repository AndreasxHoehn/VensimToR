# VensimToR

Vensim is an incredibly helpful tool to build complex SD models. As these models can often cover multiple sectors and higher order delays, they can be difficult to code out of the box. However, there is no smooth research flow when jumping between software for data preparation, analysis, or writing reports. Such jumping makes it more likely to make mistakes or reproducing results.

This R file provides an example how to convert SD models build with vensim for use in R. These model can then be further customised. It reduces the component of coding out of the box, and helps to ensure that all necessary parameters, flows, stocks etc. are defined. The advantages of using R is that it offers better computational performance than vensim and allows to carry out auxiliary modelling to inform the SD model building process or single parameters. In addition, using markdown and R's plotting functions etc. enable us to create output straight out of the analysis. 
