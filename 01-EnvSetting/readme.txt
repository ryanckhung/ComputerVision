Install the conda by going to the URL
https://www.anaconda.com/
and search for MAC installer


In terminal, goto a particular folder. Then run:
> conda env create -f <xxx.yaml>                // the xxx.yaml file store the package information
> conda env create -f cvcourse_macos.yml
then it will create a folder in "/Users/ryan/opt/anaconda3/envs/python-cvcourse"
python-cvcourse is the name specified in the yaml file

After creating the environment, you can goto any folder and activate the it:
> conda activate <env name specify in the yaml file>
> conda activate python-cvcourse
> conda deactivate

After activate the environment, run
> jupyter-lab
then it will pop up with a browser

Check environment
> conda info --envs

Install package in Jupyter Notebook by
goto Browser -> Jupyter Notebook -> add the following and run (note, there is an "!" at the beginning)
!pip3 install opencv-python
