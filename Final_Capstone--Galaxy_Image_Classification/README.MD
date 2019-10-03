## Galaxy Image Classification
#### *Using neural networks on galaxy images to predict features and types of galaxies*

The universe is an unimaginably large place. In our galaxy alone, there are between 100 billion and 400 billion stars (there are so many and they are packed so densely that this is the closest range astronomers can give for its size). And there are approximately 100 billion galaxies in the universe, each with about 100 billion stars. That's 10,000,000,000,000,000,000,000 stars, more than all the grains of sand on all of earth's beaches!

This project is based on a data set from an old Kaggle competition that was sponsored by the Galaxy Zoo Project, a crowd-source volunteer project that was started in 2007, to help classify hundreds of thousands of galaxy images that had been collected by multiple research telescopes around the world. The dataset I'm using contains 60,000 images of galaxies and I will be performing multiple classifications of types and features, using neural networks via TensorFlow/Keras. The data set includes a spreadsheet (User_responses.csv) of responses from people who classified the galaxy as a particular type or feature, with numerical averages of the responses in 11 high-level classes split into 37 separate type/feature variables. 

Instead of trying to compute the numbers in the spreadsheet themselves, I converted each high-level class to categorical values (more details on this in the presentation).

My project takes the data set and makes predictions on multiple categories:

- First level: is the image a galaxy that's smooth & round, or does it have features, or is it not a galaxy?
- Second level: (1) if it's smooth and round, how round is it? (2) Is the image of an edge-on galaxy?
- Third level: If the galaxy is not smooth/round and is not edge-on, does it have a spiral pattern?

Enjoy!
