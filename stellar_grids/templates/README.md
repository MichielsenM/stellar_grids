# Templates
A number of template files; GYRE inlists, bash scripts, VSC submit files.
Check the [VSC documentation](https://docs.vscentrum.be/en/latest/index.html) for more info on the submission scripts.

## Contents
1. `gyre_template.in`: template for a GYRE inlist.
2. `run_GYRE.sh`: bash script to run GYRE and make error and log files.
3. `run_MESA.sh`: bash script to run MESA and make error and log files.
4. `SLURM_submit_list_template`: Template to submit a jobarray to the pleiades' SLURM (local cluster at IvS).
5. `VSC_submit_GYRE.pbs`: file to submit a jobarray on the VSC, running `run_GYRE.sh` with a range of parameters.
6. `VSC_submit_MESA.pbs`: file to submit a jobarray on the VSC, running `run_MESA.sh` with a range of parameters.
