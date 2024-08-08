# A Differential Testing Framework to Identify Critical AV Failures Leveraging Arbitrary Inputs
This repository contains the code for the ICSE'25 submission "A Differential Testing Framework to Identify Critical AV Failures Leveraging Arbitrary Inputs"

Due to liscensing limitations, the videos utilized in the experiment cannot be bundled with the anonymized repository. However, the AV and SUT outputs produced from the videos have been included.

# Reproducing the results in the paper
The following was tested on a fresh install of Ubuntu 22.04 using [miniconda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html)

With `conda` installed, run the following:

```bash
source create_env.sh
source generate_figures.sh
```

This will launch all of the scripts in succession to compute all of the figures and tables used in the paper. The scripts are heavily parallelized and will run for ~20 minutes on a machine with 32 cores; runtimes will vary based on available hardware.

All figures will be saved in [3_Process/gen_figures/](3_Process/gen_figures). A version of these figures has been bundled with this repository; running the script will overwrite the included files.

The following table describes how to find the figures used in the paper.
NOTE: all referenced frames from the paper, e.g. Figures 1, 3, 4, 5, 6, and 9 will appear as a blank image with steering angles only since the videos are not included.
