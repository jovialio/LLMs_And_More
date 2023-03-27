## Just documenting things on LLMs.

Create conda environment and activate it for jupyter notebook.
'''
conda create --name {env_name}
conda activate {env_name}

pip3 install --user ipykernel
python3 -m ipykernel install --user --name={env_name}
'''
