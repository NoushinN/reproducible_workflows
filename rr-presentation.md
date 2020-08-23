reproducible research workshop
========================================================
author: Noushin Nabavi & Monica Granados
date: 
autosize: true

learning outcomes
========================================================

- 1. explain what is reproducible research 
- 2. tools that can help make research more reproducible
- 3. components of a reproducible project
- 4. use of rmarkdown for reproducible research 
- 5. use of github for reproducible research 

What is reproducible research
========================================================

- Reproducible research means that future you and anyone else will be able to pick up your analysis and reproduce the same results, including figures and tables. 

- This implies well-documented research, well commented codes and documents and reasoning behind analyses

- Also, the communication aspect should not be an afterthought, it should be recorded with the analysis as you are going through it.

Rmarkdown is a way of literate programing that keeps code, words and sentences together. The ability to easily collaborate and share your analysis goes hand-in-hand with good record-keeping and reproducibility. 

Reproducible research tools
========================================================

- Software tool: R / RStudio
- Communication tools: Markdown / Rmarkdown
- Version control tools: Git / Github


Markdown reproducible research
========================================================

Markdown or Rmardown (when built in R environment) is a way of literate programing that keeps code, words and sentences together. 

The ability to easily collaborate and share your analysis goes hand-in-hand with good record-keeping and reproducibility. 


Github reproducible research
========================================================

- We can repurpose the git version control tool and leverage the GitHub remote hosting provider for managing and sharing our work. 

- Git + GitHub will provide a very powerful resource for global collaboration and exposure of your work. 
- In this workshop, we are going to use version control our work and push it to github, which can then be accessed by your collaborators and supervisors. 

- Git + GitHub should become an integral part of your workflow.

Making table summaries reproducible
========================================================


```r
summary(cars)
```

```
     speed           dist       
 Min.   : 4.0   Min.   :  2.00  
 1st Qu.:12.0   1st Qu.: 26.00  
 Median :15.0   Median : 36.00  
 Mean   :15.4   Mean   : 42.98  
 3rd Qu.:19.0   3rd Qu.: 56.00  
 Max.   :25.0   Max.   :120.00  
```

Making plots reproducible
========================================================

![plot of chunk unnamed-chunk-2](rr-presentation-figure/unnamed-chunk-2-1.png)
