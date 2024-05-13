# NEAT-Sim
NeuroEvolution Augmenting Topologie (NEAT) - with a SNN and ANN runner (multi-threaded)

A more detailed README will be added soon.

The algorithm is base on [NEAT paper](http://nn.cs.utexas.edu/downloads/papers/stanley.ec02.pdf) (long version) by Kenneth O. Stanley and Risto Miikkulainen. or a shortest version of the paper [here](https://nn.cs.utexas.edu/downloads/papers/stanley.cec02.pdf) (6 pages).

To test the program, execute either `python test_SL.py NEAT` or `python test_RL.py NEAT` from within the test folder. Additional options are available in the test_SL.py and test_RL.py files, as well as within the configuration files located in the config folder.

To facilitate comparisons, an ANN runner built with PyTorch is also available. To use it, uncomment the line start_config_path = "./config/config_ann/SL/" in either test_SL.py or test_RL.py, and comment out the corresponding SNN configuration line start_config_path = "./config/config_snn/SL/"

A more complete version with more algorithms and more examples is also available at: https://github.com/OlivierBelan/Evo-Sim (mainly NeuroEvolution algorithms)