# nerdyqiskit-metal

This repository contains some qiskit-metal work that I have learnt in my early days of working in the field of quantum device design.

## Introduction

This repository will be helpful for beginner to start from the scratch.

## Toolchain installation for windows

### (1) Clone qiskit-metal repository

git should be installed first.

git clone https://github.com/Qiskit/qiskit-metal

### (2) Create conda environment

Now we will create conda environment specially for the projects related to qiskit-metal

conda create -p ./envqiskit-metal

Activate that conda environment

conda activate D:\pythoncode\envqiskit-metal

Update conda environment with the environment.yml file which is available inside the qiskit-metal repository. For that you should be at the path where the environment.yml file is located.

conda env update -p D:\pythoncode\envqiskit-metal --file environment.yml

### (3) Install qiskit-metal

This command will install the required things to make the qiskit-metal work. Please check that you have active conda envronment.

python -m pip install --no-deps -e .

