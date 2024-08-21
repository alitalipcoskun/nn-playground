It is a playground repository for my studies at Neural Networks via Andrej Karpathy YouTube videos.

# Quick tips to export and import the environment.yml file

# Activate the environment to export: 
conda activate `env_name`

# Export your active environment to a new file
conda env export > environment.yml
Note that it creates the file in the path that you are currently working on.

# Export your active environment to a new file to make sure it works across platform
conda env export --from-history > environment.yml
Note that it creates the file in the path that you are currently working on.

# Create the environment from the environment.yml file:
conda env create -f environment.yml
Note that `environment.yml` the file must be in the path that you are currently working on.