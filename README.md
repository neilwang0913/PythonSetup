# PythonSetup

1. To install this environment
- conda update conda
- conda install git
- git clone https://github.com/neilwang0913/PythonSetup.git
- cd PythonSetup
- conda env create -f conda_env.yml

2. To activate this environment, use
- conda activate gprMax

3. To deactivate an active environment, use
- conda deactivate(Linux, MacOS)
- deactivate(Windows)

4. To update conda and Python packages
- conda update conda
- conda env update -f conda_env.yml

5. To remove conda and Python packages
- conda remove --name fzpython2022 --all 

--- Reference
[1] https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html
