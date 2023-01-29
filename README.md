# Economic Inequality Simulator Investigation
Cambridge Computer Science Part IA; Scientific Computing Tick 4

The economist Thomas Piketty argues that we have entered an age where the return on capital is greater than the growth due to income, and that this leads to higher inequality. Your task is to investigate this idea, and report on your findings.

We can incorporate income into our simple model of the economy by assigning each individual i a per-timestep income $g_i$, where the $g_i$ are randomly chosen a priori, for example as a random number in the range [0,1]. 
We can incorporate return on capital into the model, by multiplying wealth by a growth factor every timestep. (We should also normalize wealth every timestep. If we didn't then total wealth would increase unboundedly, and we'd need to incorporate wage inflation, and worry about numerical stability.)


Investigate Piketty's idea, by modifying your simulator in whatever way you decide is appropriate, deciding what to measure, and running simulations and producing appropriate plots. Write a one-page report of your investigation.
