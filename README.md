# Collateral facilitation in humans and language models

This repository contains the code and statistical analysis for the paper 'Collateral facilitation in humans and language models', accepted to CoNLL 2022.

* The stimuli from the original experiments by Metusalem et al. (2012), Ito et al. (2016), and DeLong et al. (2019) are included in the `stimuli` folder. 
* The outputs of the models are included in the `surprisal` folder.
* The code used to run the experiment is included in the `code` folder. We use version 0.2.0 of [PsychFormers](https://github.com/jmichaelov/PsychFormers), which is included in this repository for compatibility as `psychformers.py`. PsychFormers is run using the command line, and a bash script to run the relevant experiments is provided: `run_experiment.sh`.
* The statistical analyses are included in the `statistics` folder. The statistical analysis code is included in `StatisticalAnalysis.Rmd`, the output of which is included as `StatisticalAnalysis.html`.


## References
* DeLong, K. A., Chan, W. H., & Kutas, M. (2019). [Similar time courses for word form and meaning preactivation during sentence comprehension](https://doi.org/10.1111/psyp.13312). *Psychophysiology, 56*(4), e13312.
* Ito, A., Corley, M., Pickering, M. J., Martin, A. E., & Nieuwland, M. S. (2016). [Predicting form and meaning: Evidence from brain potentials](https://doi.org/10.1016/j.jml.2015.10.007). *Journal of Memory and Language, 86*, 157-171.
* Metusalem, R., Kutas, M., Urbach, T. P., Hare, M., McRae, K., & Elman, J. L. (2012). [Generalized event knowledge activation during online sentence comprehension](https://doi.org/10.1016/j.jml.2012.01.001). *Journal of Memory and Language*, 66(4), 545-567.