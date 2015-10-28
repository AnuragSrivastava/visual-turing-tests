# visual Turing tests

The repository contains code for "visual Turing tests" that test your ability to discriminate between human and machine behavior on several simple visual concept learning tasks.

### Citing these experiments

Please cite the following paper:

Lake, Brenden M., Salakhutdinov, Ruslan, and Tenenbaum, Joshua B. (in press). Human-level concept learning through probabilistic program induction. _Science_.

### Hosted version of the experiments

If you are interested in trying the experiments, but you do not need the source code, you can access them at this link:

http://cims.nyu.edu/~brenden/supplemental/turingtests/turingtests.html


### Repository content

This repo is only necessary if you want to download the full set of human and model produced images, or if you want to rerun the results reported in the paper on Mechanical Turk or elsewhere.

The file "turingtests.html" demonstrates how to run each experiment. For instance, the "generating new exemplars" experiment is driven by the following hierarchy of javascript files : "judge_new_grids.js" > "judge_task.js" > "sequential_task.js" > "super_task.js"