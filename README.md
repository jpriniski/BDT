# Bayesian Decision Theoretic Framework

When reporting beliefs about social issues, where expressing a belief yields a calculable reward or cost (e.g., denying human culpability for climate change before carefully regarding the scientific facts), what distinguishes rational thinking from motivated reasoning? The Bayesian Decision Theoretic Framework provides a computational framework for distinguishing between practical reasoning, where goals guide decisions after evidence is rationally assimilated, and the oftentimes precious motivated reasoning, where goals bias how evidence is assimilated when computing beliefs about the world. We discuss the implications of these two types of reasoning in Priniski, Solanki, & Horne (2022). _A Bayesian decision-theoretic framework for studying motivated reasoning_. Find the paper here https://psyarxiv.com/ngavz

The python notebook contains two computational cognitive models that generate predictions using this framework to distinguish between the two cases. The first model produces Bayesian decisions using normative priors (practical reasoning model) and the second uses directional priors (motivated reasoning model).  Directional priors are Bayesian priors conditioned on a utility-calculus, whereas normative priors are typical Bayesian priors that constitute practically rational thinking. See section II of paper for more details. 

Outputs from these models are decision variables conditioned on (1) evidence about the state of the world and (2) a reasoner's goals. Simulations from normative and directed Bayesian posteriors can be compared to behavioral data to distinguish between cases of practical and motivated reasoning in humans. Knowing the difference can motivate how a researcher chooses to revise false beliefs (e.g., misconceptions about climate change). We discuss how in the paper. 
