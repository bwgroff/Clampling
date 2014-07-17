Clampling
=========

Clamp-sampling, ie clampling (my own term but probably someone else has thought about this) is
using a procedure that relies on a sampling step and keeping some of the values fixed during that step.
The first application is using RBMs for purposes like collaborative filtering and image reconstruction.

Data Coercion
-------------

Data coercion is intentionally biasing training data for a specific purpose. For instance, if you want 
to know what your cat would look like as a person, you could train any learning algorithm which supports
sampling on faces and then seed it with a cat image and apply clampling. The algorithm will attempt
to build an internal model of the cat image as a face. Not sure whether this will actually work
but it would be pretty rad if it did. 
