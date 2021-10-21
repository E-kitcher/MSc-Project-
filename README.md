# Quantitative Analysis of the Evolutionary GAN on Synthetic Datasets

## Aim:
Investigating the claims of the Evolutionary GAN (Generative Adverserial Network). Original paper can be found here: https://arxiv.org/pdf/1803.00657.pdf .

## Descirption:
Generative Adversarial Networks (GANs) are a type of generative model capable of producing incredibly realistic data, without the generative network ever being exposed to the data is it trying to mimic. New GAN frameworks and algorithms are being created all the time with the main focus on increase the performance and training stability. In this paper we investigate one of these new GAN frameworks, the Evolutionary- GAN (E-GAN). This framework creates and evolves a population of generators through different mutations, using a fitness function to decide which generators survive into the next generation. Authors claim that these evolutionary techniques increase generative quality and training stability. This is backed up by the use of synthetic data sets, however, no quantitative analysis was done on the generated samples from these data sets. We therefore propose further analysing the performance of E-GAN against other GANs on these synthetic data sets, using a slightly different network structure and our own metric to quantify performance. Experiments show that these claims do not to hold up. While E-GAN is able to produce comparatively good quality data, it is not noticeably different from some less computationally expensive GANs. Crucially, we find that a random version of the E-GAN, which does not utilise the proposed fitness function, is able to perform at a similar level. Although not conclusive, our work suggests the evolutionary framework is not the reason for the improved generative quality and stability.

## Documents:
The PDF document is my MSc disseration. 

The code for generating synthetic data can be found in the ipynb file.

## Note:
While the .ipynb file contains all the code for the GAN itself, it will need to be ran multiple times to replicate the analysis in the report.
