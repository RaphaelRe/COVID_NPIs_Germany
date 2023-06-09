Association between non-pharmaceutical interventions and the spread of infectious disease during the Covid-19 outbreak in Germany: Application of a hierarchical Bayesian Approach
-------------------------------------------------------------------------------

## Online material

Here you can find the 2 directories and one file:
* `data`: all data files to run the model.
* `model`: The used model in python. 
* `fit_model_Germany.py` runs the model.

Please note that the calculation time and resources vary depending on the length of the chains, number of sampled chains and used cores. The code is written to parallelize over the number of chains, i.e. the number of chains defines the number of used cores.

Also note, that the code was tested and run on Debian GNU/Linux 11 (bullseye).


To run the model, adapt the number of iterations, path for results etc. in the script `fit_model_Germany.py` and run it.
