# pyCSEP - StatSei Workshop
<img src="https://i.postimg.cc/Bb60rVQP/CSEP2-Logo-CMYK.png" width="320">


## Objective

This workshop is about testing earthquake forecasts and perform evaluations with the pyCSEP software toolkit. The objective is to familiarize the participants with the basic functionalities of the software, and to provide a hands-on experience with the software. The workshop is divided into two parts: (1) a brief introduction to the software and its functionalities, and (2) a series of tutorials to perform evaluations of earthquake forecasts.

## Setting up

> :bulb: **TL, DR** \
        ```git clone https://github.com/cseptesting/pycsep_workshop_statsei24``` \
        ```conda env create -f environment.yml``` && 
        ```conda activate pycsep_statsei```


 **Instructions**
   * Clone or download this repository to your computer.
   * Set up ``Python`` and `Conda` using the [Miniforge](https://github.com/conda-forge/miniforge) or [MiniConda](https://docs.conda.io/en/latest/miniconda.html) distributions, following the instructions in the links.
   * Open a terminal window on your computer (in windows, open ``Miniforge Prompt`` or ``Anaconda Prompt``). Confirm that your ``Conda`` software is running by a command, e.g.:
     ```bash
      conda --version
     ```
     Alternatively, you can use the `pip` python manager if desired (we recommend however using `Conda`, which handles better the required system library dependencies).
   * Install [`pyCSEP`](https://github.com/sceccode/pycsep) following the [installation instructions](https://pycsep.readthedocs.io/en/latest/installation.html). 
   * Install the `jupyter` notebook package in the same environment where you installed `pyCSEP`:
     ```bash
     conda install -c conda-forge -y jupyterlab
     ```
     
## Running the tutorials
    
   * Open a terminal window on your computer and navigate to the directory where you cloned or downloaded this repository.
   * Start the Jupyter notebook server by typing:
     ```bash
     jupyter lab
     ```
   * A new tab in your web browser should open, showing the contents of the directory where you cloned or downloaded this repository. Open one of the notebooks in the `tutorials` directory.
   * Follow the instructions in the notebook to complete the workshop.

## Troubleshooting

   * If you have any issues, please open an issue in this repository or contact the authors by emaiL:
     - Pablo Iturrieta: [pciturri@gfz-potsdam.de](mailto:)
     - Toño Bayona: [jose.bayona@bristol.ac.uk](mailto:jose.bayona@bristol.ac.uk) 
     - Max Werner: [max.werner@bristol.ac.uk](mailto:)