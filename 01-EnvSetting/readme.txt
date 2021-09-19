In terminal, goto a particular folder. Then run:
> conda env create -f <xxx.yaml>
> conda env create -f cvcourse_macos.yml

After creating the environment, you can goto any folder and activate the it:
> conda activate <env name specify in the yaml file>
> conda activate python-cvcourse
> conda deactivate

After activate the environment, run
> jupyter-lab
then it will pop up with a browser