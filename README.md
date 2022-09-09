This scripts in this repository were used to analyze a selection experiment. Specifically, I artificially selected tapeworms for 4 generations to develop faster or slower in their first host.

# Introduction

Some parasite strategies seem suboptimal. For instance, parasitic worms with complex life cycles typically risk developing for weeks in small, short-lived first intermediate hosts, despite being able to grow faster, larger, and safer in their subsequent hosts. Why do parasites risk prolonged development in first host with low life expectancy? To understand this, I selected a tapeworm (*Schistocephalus solidus*) for faster larval development in its copepod first host. Among tapeworms, *S. solidus* and its relatives have some of the shortest developmental times (see analysis [here](analyses/01macroevol_pattern.md)), albeit not as short as optimality models might predict, so selection pushed a conserved-but-counterintuitive phenotype towards a limit on known strategies. My goals were to test whether faster development can evolve and to assess why it has not.

# Results

The response to selection over time was analysed [here](analyses/02testing_selection_response.Rmd). Faster parasite development evolved and enabled earlier infectivity to the next host, sticklebacks.

![](figs/fig3_response_edit.png)

However, selection increased the frequency of parasite families with reduced infectivity to copepods, developmental stability, and fecundity. This release of cryptic, deleterious genetic variation for development (decanalization), and the limited genetic covariation with fish infectivity, both constrain adaptive change. 

Canalized development, as well as evolutionary stasis over long time spans, are both consistent with stabilizing selection. Then again, rapid development was not costly; fast-developing genotypes did not decrease copepod survival, even under host starvation, nor did they underperform in the next hosts. This can be seen in the pattern of genetic covariance (the G-matrix below; analysis [here](analyses/05quant_gen_multivariate.md)); most correlations with larval development (cerc) are positive, not negative. 

![](figs/fig6_Gmat_fsx.png)

I speculate that, on longer time scales, reduced size-dependent infectivity is the main cost of abbreviated development in small first hosts.

# Reference

To come...
