# Creating an LLM from scratch
Creating an LLM from scratch. Original work from freecodecamp.org (https://www.youtube.com/watch?v=UU1WVnMk4E8)

## Requirements

1. Install [VisualStudio build tools](https://visualstudio.microsoft.com/pt-br/downloads/?q=build+tools)

After installing the Build Tools manager, install `Desktop development with C++` and `.NET desktop build tools`

2. Install [Conda](https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html) to manage the python packages.

3. To create the environment use `conda env create -n <your env name> -f environment.yml`. This will install all needed packages.

4. Install the Jupyter kernel using your python environment

    `python -m ipykernel install --user --name=<your env name> --display-name "cuda-gpt"`

4. Start jupyter notebook server with `jupyter notebook`

5. Open the `.ipynb` file and change the kernel: Menu Kernel -> Change Kernel -> select `cuda-gpt` kernel

TODO: Install OpenCL WSL drivers