# memtorch
https://github.com/coreylammie/MemTorch

# Memtorch CPU
## Instructions
1. Download [Anaconda](https://www.anaconda.com/download)
2. Unzip MemTorch-CPU.zip
3. `cd MemTorch`
4. Import the `windows11_memtorch_cpu.yml` using the Import button under "Environments" in Anaconda. (Currently only tested with windows 11)
    - if different OS try `no_OS_memtorch_cpu.yml`
    - Error might happen when importing. Ignore for now. Will be resolved later.
5. pip3 or `pip install -r requirements.txt`
6. `pip install .`
7. Verify in Anaconda using UI -> Environments -> Installed dropdown -> Update index -> search memtorch-cpu
Note: make sure to click play button in Environments -> open in terminal
    - or `python` -> `import memtorch`
    - or `pip show memtorch-cpu`