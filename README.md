### Modifications
* Added distance function to NanoFlann to for weighted euclidean distance
** Based on  [scipy implementation](https://docs.scipy.org/doc/scipy/reference/generated/scipy.spatial.distance.minkowski.html#scipy.spatial.distance.minkowski)

*Modified the KDTree to use this distance by default
*There's no checking whether the dimensionality of the weights matches the dimensionality of the source data so use at your own risk! 

## ofxKDTree

openFrameworks addon implementing multi-dimensional KD-Tree for storage and fast retrieval of high-dimensional vectors.

based on [nanoflann](https://github.com/jlblancoc/nanoflann)

now working but not thoroughly tested yet.

intended use case is for [ReverseImageSearchRealTime](https://github.com/genekogan/ReverseImageSearchRealTime)
