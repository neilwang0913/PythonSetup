# PythonSetup

---
Open https://www.anaconda.com/products/individual#download-section with your web browser.
Download the Anaconda Installer with Python 3 for Linux.
(The installation requires using the shell. If you aren't comfortable doing the installation yourself stop here and request help at the workshop.)
\ Open a terminal window and navigate to the directory where the executable is downloaded (e.g., `cd ~/Downloads`).
\ Type
bash Anaconda3-
and then press Tab to autocomplete the full file name. The name of file you just downloaded should appear.
Press Enter (or Return depending on your keyboard). You will follow the text-only prompts. To move through the text, press Spacebar. Type yes and press enter to approve the license. Press Enter (or Return) to approve the default location for the files. Type yes and press Enter (or Return) to prepend Anaconda to your PATH (this makes the Anaconda distribution the default Python).
Close the terminal window.

---
1. To install this environment
- conda update conda
- conda install git
- git clone https://github.com/neilwang0913/PythonSetup.git
- cd PythonSetup
- conda env create -f conda_env.yml

2. To activate this environment, use
- conda activate fzpython2022

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
