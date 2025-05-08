---
title: "What is Reproducible Research?"
teaching: 10
exercises: 0
---


## For our workshop today....


For our workshop today, as the training was designed to be relevant to all disciplines, we are using the UKRN's broad definition of reproducibility:

"Research that is sufficiently transparent that someone with the relevant expertise
can clearly follow, as relevant for different types of research:

- how it was done;

- why it was done in that way;

- the evidence that it established;

- the reasoning and/or judgements that were used; and

- how all of that led justifiably to the research findings and conclusions." 


In most discussions of reproducible research, especially in STEM disciplines, reproducible research is the concept that someone can, given your data and methods, redo your research and come to the same conclusion.

We expect that anyone conducting the same research should always come to the same conclusion. This enables us to trust that the knowledge derived from this research can be accepted as fact.



## Replicability and Repeatability

There are a number of terms you may hear when we talk about reproducible. Replicable and Repeatable are two common terms that may arise.

The Turing Way offers the following descriptions:



::: tab


### Reproducible
A result is reproducible when the same analysis steps performed on the same dataset consistently produces the same answer.

### Replicable
A result is replicable when the same analysis performed on different datasets produces qualitatively similar answers.

### Robust
A result is robust when the same dataset is subjected to different analysis workflows to answer the same research question (for example one pipeline written in R and another written in Python) and a qualitatively similar or identical answer is produced. Robust results show that the work is not dependent on the specificities of the programming language chosen to perform the analysis.

### Generalisable
Combining replicable and robust findings allow us to form generalisable results. Note that running an analysis on a different software implementation and with a different dataset does not provide generalised results. There will be many more steps to know how well the work applies to all the different aspects of the research question. Generalisation is an important step towards understanding that the result is not dependent on a particular dataset nor a particular version of the analysis pipeline.

:::

![](https://the-turing-way.netlify.app/_images/reproducible-definition-grid.svg){alt='A grid showing the above 4 definitions'}

::: tab

## How did we get here?
> “It can be proven that most claimed research findings are false.” (Ioannidis, 2005)

### In 2010...
- Daryl Bem publishes a paper in a very reputable journal “Journal of Personality and Social Psychology’ providing evidence for precognition (people are psychic!)
  - Investigated well-established effects in psychology, and time-reversed them (outcome/effect precedes the cause)
- Problem: Precognition is outside of the realm of reality, especially the consistent results of finding evidence for precognition across 9 consecutive studies
- Researchers respond to Bem via replication
  - Galak (2012) found no effect of precognition across 7 studies (N = 3289)
  - Ritchie et al., 2012 also failed to replicate these results in three studies, but when they submitted their paper to the same journal that accepted Bem’s research, their paper was rejected because they “do not publish straight replications”
 
### In 2011... 
- Simmons (2011) publishes a paper on flexibility in design, analysis and reporting that affects significance of your results
- They mention various, common "Questionnable Research Practices (QRPs)" that inflate *false positives*
    - Example: Researcher is interested in the relationship between listening to music and memory performance 
        - Control Group 1: No music, matched task e.g. colouring 
        - Experimental Groups: Pop, Rock, Classical, R&B, Hip-hop, Jazz, Country, Blues 
    - Only find a significant relationship between listening to rock music and memory performance
    - QRP 1: Researcher writes up the results, *ignoring all the other conditions* and concludes that music affects memory
    - QRP 2: Researcher *changes their predictions*, initally thought music would improve memory, but finds opposite results
  
>“If there are participants you don’t like, or trials, observers, or interviewers who gave you anomalous results, drop them […]. Go on a fishing expedition for something—anything—interesting.” (Bem, 2003) 

### 2012... How common are QRPs?
- John et al. (2012) asked ~2000 researchers, (1) how many QRPs they enagage in, and (2) how many QRPs their collegues engage in
  - ~60% admitted to not reporting all of their dependent variables (outcome variables)
  -  ~40% admitted to only reporting experiments that had worked
  -  ~50% admitted to engaging in optional stopping (collecting more data if you don't find statistically significant results)
- **These were research norms at the time** 

## Since then... 
- Various efforts across disciplines to replicate studies

### The Reproducibility Project: Cancer Biology
-  8-year effort to replicate experiments from high-impact cancer biology papers published between 2010 and 2012. The project was a collaboration between the Center of Open Science and Science Exchange.
  
When preparing replications of 193 experiments from 53 papers there were a number of challenges that affected the project.
- 2% of experiments had open data
- 0% of protocols completely described
- 32% of experiments, the original authors were not helpful or unresponsive
- 41% of experiments, the original authors were very helpful

Let's talk about this:
On unresponsive authors, it's not always malicious:
- Authors do move institutes
- Can drop out of academia
- May be research students who didn't continue with research
- Data may have left with research students and supervisor may lack details or data on how the experiment was done

## The bottom line...
- Replication issues aren't always products of malicious intent
- honest errors happen... a lot!
- (Although, check out Data Colada's blog posts on Harvard Univeristy professor researching honesty, who was caught for falsifying their data) 


:::


Let's look now on why this is important.



::::::::::::::::::::::::::::::::::::::::::::::: callout

## References

Reference: Definitions — The Turing Way Community. (2022). The Turing Way: A handbook for reproducible, ethical and collaborative research (Version 1.1.0) [Computer software]. https://doi.org/10.5281/zenodo.3233853 licenced as CC-BY

The Turing Way Community. This illustration is created by Scriberia with The Turing Way community, used under a CC-BY 4.0 licence. DOI: https://doi.org/10.5281/zenodo.3332807

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::


::::::::::::::::::::::::::::::::::::::::::::::: keypoints

In this lesson, we have learnt:

- What is reproducible research?

- The different terms around reproducibility

:::::::::::::::::::::::::::::::::::::::::::::::


