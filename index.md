# Online Advertising Incrementality Testing: Practical Lessons And Emerging Challenges

Presented at the [CIKM 2021](https://www.kdd.org/kdd2021/).

## Authors
  - [Joel Barajas](http://www.linkedin.com/pub/joel-barajas/8/6b7/bb0), [Yahoo Research](https://research.yahoo.com/researchers/jbarajas?fr=crmas), yahoo!
  - [Narayan Bhamidipati](https://www.linkedin.com/in/narayanb), [Yahoo Research](https://research.yahoo.com/researchers/narayanb?fr=crmas), yahoo!
  - [James G. Shanahan](https://www.linkedin.com/in/jimis/), Church and Duncan Group Inc., UC Berkeley

## Abstract

Online advertising has historically been approached as an ad-to-user matching problem within sophisticated optimization algorithms. As the research and ad-tech industries have progressed, advertisers have increasingly emphasized the causal effect estimation of their ads (incrementality) using controlled experiments (A/B testing). 

With low lift effects and sparse conversion, the development of incrementality testing platforms at scale suggests tremendous engineering challenges in measurement precision. Similarly, the correct interpretation of results addressing a business goal requires significant data science and experimentation research expertise. 

We propose a practical tutorial in the incrementality testing landscape, including:
- The business need
- Literature solutions and industry practices
- Designs in the development of testing platforms
- The testing cycle, case studies, and recommendations

We provide first-hand lessons based on the development of such a platform in a major combined DSP and ad network, and after running several tests for up to two months each over recent years. 

We elaborate more on the user privacy implications in online experimentation and incrementality testing. We aim to motivate the research community to focus on solutions under these emerging constraints. 

## Outline and Presentations

1. [slides](presentations/inc_testing_part_1.pdf) The basics: context and challenges
2. [slides](presentations/inc_testing_part_2.pdf) Incrementality Testing: concepts, solutions and literature
3. [slides](presentations/inc_testing_part_3.pdf) From concept to production: platform building, challenges, case studies
4. [slides](presentations/inc_testing_part_4.pdf) Deployment at Scale: test cycle and case studies
5. [slides](presentations/inc_testing_part_5.pdf) Emerging trends: identity challenges, industry trends and solutions

Some of the papers cited in the slides are avaiable at the folder [papers](papers)

The tutorial ACM paper, which includes the detailed outline of the tutorial, is available [here](cikm2021_inc_testing_tutorial).

Feedback welcome!! 


