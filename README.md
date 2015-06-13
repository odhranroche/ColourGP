# ColourGA
Toy genetic algorithm with GUI

Written in Lua for the LOVE framework. The population is made up of 8 individuals. The individuals genotype is a sequence of colours. An individuals fitness is based on how close to the sample image (image.bmp) they can get.

![sample image](http://i.imgur.com/wsuftdy.png "Sample image")

The population starts as random and will converge to something like:

![Evolved population](http://i.imgur.com/mgQSS1e.png "Evolved population")

The genetic functions are contained in colour.lua. It's interesting to see the effect of changing the type of selection, mutation and crossover. 

The evolution can be stopped and started with the "Evolve" button. Pressing 'r' will reset the simulation. 
