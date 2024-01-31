# K_task_codes
first-level (and eventually group-wise linear mixed models) glm estimation for pre/post patients/controls self-other task

Tutorials I used (and how I found them helpful): 

1. https://carpentries-incubator.github.io/SDC-BIDS-fMRI/aio/index.html

Discusses how to import fMRIprep derivatives (outputs) for a single subject + a nice introduction to Nilearn; very helpful first tutorial but definitely has some bugs (in Alpha version) 

2. https://nilearn.github.io/dev/auto_examples/07_advanced/plot_bids_analysis.html#sphx-glr-auto-examples-07-advanced-plot-bids-analysis-py

good tutorial on multiple subject scripting for bids datasets + second level set-up (to run basic glm contrasts at the group-level, nothin fancy) -- need to adjust for running first level instead of just loading in first-level already done but great figure to quickly visualize all subjects first-level outputs 

3. https://dartbrains.org/content/GLM_Single_Subject_Model.html

such a good tutorial on building / convolving a design-matrix and mathematically what each operation is doing 

4. https://lukas-snoek.com/NI-edu/fMRI-introduction/week_5/run_level_analyses.html

this tutorial was helpful in visualizing what to do with multiple runs of the same task (informed me to add in separate intercepts for each run into the first-level glm) 

5. https://nilearn.github.io/dev/auto_examples/index.html

nilearn user page as a whole is a godsend 

