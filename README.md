The UKCA chemistry climate model uses lower-boundary conditions for its treatment of H2.  This repo consists of a notebook that converts various emissions scenarios into a lower-boundary condition for use in UKCA, in effect treating the troposphere as a well-mixed volume (reasonable as the H2 lifetime of 2.5 years is greater than the interhemispheric transport time of 1 year approx.).  A second script will look at N:S hemispheric gradient, examining this assumption further.

The script can be run on mybinder.org freely.  Each stage (cell) of the calculation (notebook) is execute by pressing Shift-Enter to evaluate it.  These cells are evaluated sequentially, with the state of variables persisting until updated.

Click on the MyBinder link below to start an interactive enviroment to evaluate the notebook.  Then click on the notebook when the Jupyter notebook viewer is launched by Binder.  [This https://www.youtube.com/watch?v=lzf5DU-sJig] video (at 1.25x speed, ideally) gives a good intro on running a notebook on mybinder.org

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/paultgriffiths/H2_economy_box_model_scenarios/master)
