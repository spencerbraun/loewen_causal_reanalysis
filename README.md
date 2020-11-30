# Causal Reanalysis of Loewen et al.

A reanalysis of the paper "A Natural Experiment in Proposal Power and Electoral Success" by Loewen et al. using causal inference frameworks. All R code used to produce the reanalysis is located in the "scripts" directory, while the "stata" directory contains the code and output as provided by the original authors on Harvard's Dataverse. 

The original analysis claimed that members of the Canadian House of Commons with the power to propose legislation and were members of the governing party received a higher vote share in elections that those without this power. Its reliance on a randomization mechanism, a lottery to determine who received the power the propose, was not unreasonable and led to quite simple statistical techniques to gauge effect. Our analysis finds smaller, non-signficant effects once we control for covariates. Methods employed include exact matching, propensity score subclassification, and inverse propensity score estimators.

The full analysis can be read in the file "Loewen_Causal_Reanalysis.pdf"
