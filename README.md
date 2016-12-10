# weighted-deepwalk
weighted random walk implementation for deepwalk (in python)

As deepwalk [1] can only generate sequence in a uniform distribution, weighted edge is not accepted. 

In order to faciliate the usage, I implemented one alternative version with weighted edge. (just add one more function)

1. For most users, you can install original deepwalk package in your computer frist by:

      pip install deepwalk 

2. Then, download this package, and put the 'main.py' and 'weighted_random_walk.py' into your python lib depository directory for original deepwalk. 

3. Now, you can run your deepwalk with: 
  
      deepwalk --input input.file --format weighted_edgelist --output output.file

ref: 

[1] deepwalk: https://github.com/phanein/deepwalk
