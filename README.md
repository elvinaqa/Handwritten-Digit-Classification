# Handwritten-Digit-Classification
Handwritten Digit Classification on the MNIST dataset with Convolutional Neural Networks with the accuracy of 99%
# Kaggle Digit Recognizer with CNN Tensorflow Keras

## Used Python Libraries
Include:
  Numpy
  Pandas
  Keras
  Tensorflow
  
## For

MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

In this competition, your goal is to correctly identify digits from a dataset of tens of thousands of handwritten images. We’ve curated a set of tutorial-style kernels which cover everything from regression to neural networks. We encourage you to experiment with different algorithms to learn first-hand what works well and how techniques compare.

Practice Skills
Computer vision fundamentals including simple neural networks

Classification methods such as SVM and K-nearest neighbors

## Getting Started

The data files train.csv and test.csv contain gray-scale images of hand-drawn digits, from zero through nine.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.

Each pixel column in the training set has a name like pixelx, where x is an integer between 0 and 783, inclusive. To locate this pixel on the image, suppose that we have decomposed x as x = i * 28 + j, where i and j are integers between 0 and 27, inclusive. Then pixelx is located on row i and column j of a 28 x 28 matrix, (indexing by zero).

For example, pixel31 indicates the pixel that is in the fourth column from the left, and the second row from the top, as in the ascii-diagram below.

Visually, if we omit the "pixel" prefix, the pixels make up the image like this:

000 001 002 003 ... 026 027
028 029 030 031 ... 054 055
056 057 058 059 ... 082 083
 |   |   |   |  ...  |   |
728 729 730 731 ... 754 755
756 757 758 759 ... 782 783 
The test data set, (test.csv), is the same as the training set, except that it does not contain the "label" column.

Your submission file should be in the following format: For each of the 28000 images in the test set, output a single line containing the ImageId and the digit you predict. For example, if you predict that the first image is of a 3, the second image is of a 7, and the third image is of a 8, then your submission file would look like:

ImageId,Label
1,3
2,7
3,8 
(27997 more lines)
The evaluation metric for this contest is the categorization accuracy, or the proportion of test images that are correctly classified. For example, a categorization accuracy of 0.97 indicates that you have correctly classified all but 3% of the images.

## Getting Help

If you have questions or need further guidance on using this template, please [file an issue](https://github.com/elvinaqa/vitual-assistant-python/issues). I will do my best to respond to all issues in a timely manner.

## Contributing Guidelines

All contributions and suggestions are welcome!

For suggested improvements, please [file an issue](https://github.com/elvinaqa/vitual-assistant-python/issues).

For direct contributions, please fork the repository and file a pull request. If you never created a pull request before, welcome 🎉 😄 [Here is a great tutorial](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github) on how to send one.

## Code of Conduct

In the interest of fostering an open and welcoming environment, we as contributors and maintainers pledge to making participation in our project and our community a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, gender identity and expression, level of experience, nationality, personal appearance, race, religion, or sexual identity and orientation.

This project pledges to follow the [Contributor's Covenant](http://contributor-covenant.org/version/1/4/).

## Credits


- [18F's Open Source Maintainer Guidelines](https://pages.18f.gov/open-source-program/pages/maintainer_guidelines/)

## License

This project is licensed under [The Unlicense](https://unlicense.org/) and released to the Public Domain. For more information see our [LICENSE](https://github.com/ascott1/readme-template/blob/master/LICENSE) file.
