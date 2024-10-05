# memtorch
https://github.com/coreylammie/MemTorch

# Memtorch CPU
## Pre-reqs
- git clone --recursive https://github.com/coreylammie/MemTorch
- cd MemTorch
- delete the two files
    - setup.py
    - requirements.txt
- unzip memtorch-cpu.zip
- add the two files
    - setup.py
    - requirements.txt


## Instructions
1. Download [Anaconda](https://www.anaconda.com/download)
2. unzip memtorch-cpu.zip
3. `cd memtorch-cpu`
4. Import the `windows11_memtorch_cpu.yml` using the Import button under "Environments" in Anaconda. (Currently only tested with windows 11) and only on python 3.10
    - if different OS try `no_OS_memtorch_cpu.yml`
    - Error might happen when importing. Ignore for now. Will be resolved later.
5. pip3 or `pip install -r requirements.txt`
6. `pip install .`
7. Verify in Anaconda using UI -> Environments -> Installed dropdown -> Update index -> search memtorch-cpu
Note: make sure to click play button in Environments -> open in terminal
    - or `python` -> `import memtorch`
    - or `pip show memtorch-cpu`