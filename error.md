## Our Errors

### Error: Unable to create process : https://github.com/jupyter/notebook/issues/4656 
My advice for you is to rebuild your environment by following the steps below:
1. Activate your environment

Open your terminal, and activate your environment with conda activate...
2. Remove the existing environment
After the environment is activated, do conda uninstall scikit-learn python and type y where necessary. The command will remove sk-learn, jupyter, pandas etc.
3. Rebuild your environment
Once those packages have been successfully removed, rebuild your environment by typing conda install python=3.6.9 jupyter pandas matplotlib scikit-learn=0.22 numpy. Enter y where necessary. Wait for couple of minutes and your environment should be ready.
After that enter Jupyter notebook and jupyter notebook should be up and running.

If you have any question, I will be glad to answer them. Good luck.👍🏾

My journey in machine learning engineer 
