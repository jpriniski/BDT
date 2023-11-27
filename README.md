# Bayesian Decision Theoretic Framework

When reporting beliefs about social issues, where expressing a belief may yield a reward or cost (e.g., denying human culpability for climate change before carefully regarding the scientific facts), what distinguishes rational thinking from motivated reasoning? The Bayesian Decision Theoretic Framework is a computational model that can help behavioral scientists distinguish between cases of practical reasoning, where goals guide decisions through an expected utility calculation after evidence is rationally assimilated via Bayesian updating, and cases of motivated reasoning, where goals bias priors before evidence is assimilated into posteriors. We discuss the implications of these two types of reasoning in the preprint Priniski, Solanki, & Horne (2022). _A Bayesian decision-theoretic framework for studying motivated reasoning_. Find the preprint here https://psyarxiv.com/ngavz

This repository contains a python notebook describing and implementing two computational models for generating decision variables in line with this framework's assumptions; model outputs can be comapred to behavioral data to distinguish between the two cases of reasoning and guide interventions. The first model produces Bayesian decisions using normative priors (practical reasoning model) and the second uses directional priors (motivated reasoning model).  Directional priors are Bayesian priors conditioned on a utility function, whereas normative priors are not conditioned on utility information. See section II of paper for more details. 

Outputs from these models are decision variables conditioned on (1) evidence about the state of the world and (2) a reasoner's goals. Simulations from normative and directed Bayesian posteriors can be compared to behavioral data to distinguish between cases of practical and motivated reasoning in humans. Knowing the difference can motivate how a researcher chooses to revise false beliefs (e.g., misconceptions about climate change). We discuss how in the paper. 
