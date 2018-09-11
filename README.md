# Disclaimer

This lib will provide some VL/vvvv nodes to perform image perceptual hashing using [DupImageLib](https://github.com/Quickshot/DupImageLib).

# What is perceptual hashing ?

>_A perceptual hash is a fingerprint of a multimedia file derived from various features from its content. Unlike cryptographic hash functions which rely on the avalanche effect of small changes in input leading to drastic changes in the output, perceptual hashes are "close" to one another if the features are similar._ (from [phash.org](https://www.phash.org/))

Here are a few interesting articles on image perceptual hash in case you're interested :

- On [bertolami.com](http://bertolami.com/index.php?engine=blog&content=posts&detail=perceptual-hashing)
- On [jenssengers.com](https://jenssegers.com/61/perceptual-image-hashes)

# What's inside

You can use AverageHash, MedianHash and DifferenceHash algorithms. Some are quicker but give less pertient results, while others are slower but more accurate. They all take a _Path_ to an image as an input.

# Usage

TODO : write native lib stuff

# Next step

- Summary of the nodes/inputs, taken from DupImageLib
- More relevant demo patch (with Skia?)
- Try to understand the stream thingy