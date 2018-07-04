# rafem_cem_coupling

Coupling experiment using RAFEM and CEM

# Get started

Create an empty conda environment to install the software and run
the experiments in.

    $ conda create -n rafem_cem python=2.7
    $ source activate rafem_cem

Install the software needed to run the experiments.

    $ conda install pymt -c csdms-stack -c conda-forge
    $ conda install pymt_cem pymt_waves rafem -c csdms-stack -c conda-forge
    $ conda install ipython matplotlib

# Run the model

Run the model from the command line. The arguments are:
* asymmetry of incoming waves angle
* highness factor on incoming waves angle
* wave height

    $ python run_model.py .5 .5 2.
