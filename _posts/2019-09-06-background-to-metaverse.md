---
layout: post
title:  "Welcome to R/metaverse!"
subtitle: A team project to integrate and expand the number and utility of functions for systematic review and meta-analysis in R
author: Martin Westgate
date:   2019-09-06 09:00:00 +1000
categories: updates
background: "/assets/img/banners/metaverse_background.jpg"
---
Hello world, welcome to R/metaverse!

You're probably wondering what <code>metaverse</code> is. Basically,  <code>metaverse</code> is an R package that acts like <code>tidyverse</code>; it imports a set of R packages that work together to deliver a set of related tools. While packages that are part of the <code>tidyverse</code> provide tools for data cleaning, modelling and visualisation, <code>metaverse</code> packages all relate to 'evidence synthesis', which is the process of summarizing scientific information for improved policy or practice. Evidence synthesis incorporates a range of methods including systematic review and meta-analysis, and is increasingly important in a range of fields of research.

Why is <code>metaverse</code> needed? After all, there is already a very effective <a href="https://cran.r-project.org/view=MetaAnalysis">CRAN task view</a> on meta-analysis. There are a few answers to this.

First is that - as with <code>tidyverse</code> - <code>metaverse</code> is opinionated. There are hundreds of meta-analysis packages on CRAN, and this makes it difficult to determine which are the best ones to use, especially for new users. The goal of metaverse is to provide a smaller number of packages that users can rely on, and that work together in a fairly seamless manner. Therefore, <code>metaverse</code> isn't intended to cover all the needs of every advanced user. Instead, it will be a standardised starting point from which people can branch out as needed.

Second, although R has a lot of meta-analysis packages, it remains difficult to run an evidence synthesis project entirely within R. There are many stages of the process - from searching for literature in a consistent way, to screening out irrelevant information, to extracting results for meta-analysis - that have only recently become possible in R, and others that remain impossible. Therefore, one goal of <code>metaverse</code> is to develop new packages that allow a complete, start-to-finish workflow.

Third, the meta-analysis infrastructure in R is fairly individualistic, and it would be nice to develop a community of practice that could work together to make R packages that function cohesively. Therefore, our final goal is to facilitate community discussions what meta-analytic tools are needed and how they should work.

Of course, achieving all of these goals is a large task, and getting <code>metaverse</code> the stage where it achieves these milestones will take some time. However, we are confident that this can be achieved because of the excellent support we have received so far, both from individual developers, and from funding organisations. Particularly important has been funding from the R Consortium, who <a href="https://www.r-consortium.org/blog/2019/08/23/50000-in-new-grants-approved">have funded dedicated developer time</a> to expand the codebase for <code>metaverse</code>. Also invaluable has been funding from the <a href="https://www.eshackathon.org">Evidence Synthesis Hackathon</a> series, which allowed us to bring together a development team to build the <code>metaverse</code> prototype in April of this year. As the project expands we hope to bring in additional sources of funding to ensure that we can continue our work.

That's all for now, but we've got a lot of stuff planned, including aiming for a CRAN-ready version of <code>metaverse</code> by December 2019. Until then, feel free to check the <a href="https://github.com/rmetaverse">GitHub</a> repo for updates, or check back here again soon!