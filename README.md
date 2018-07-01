# bag-of-visual-words

![alt text][results]

Using the bag-of-words algorithm mainly used in text-retrieval applications for visual recognition using a linear support vector machine classifier.

All the progress has been recorded in jupyter notebooks: 

- A `training` jupyter notebook where all the implementation details are explained interactively with text along `Python` 3 code.
- A `classify` jupyter notebook where the steps to be followed when a test set is given to classify it using the dumped information from the training jupyter notebook, which contains essential information for the classification process, such as the classifier itself or the visual vocabulary calculated using an unsupervised learning algorithm.

Links for the notebooks in their respective order are provided below:

+ [`training`](http://nbviewer.jupyter.org/github/diegovincent/bag-of-visual-words/blob/master/src/training.ipynb)
+ [`classify`](http://nbviewer.jupyter.org/github/diegovincent/bag-of-visual-words/blob/master/src/classify.ipynb)

Project dependencies as well as other useful information will be posted in the future.

[results]: https://github.com/diegovincent/bag-of-visual-words/blob/master/src/output/Montage_screenshot_01.07.2018.png "Classifier results"

**References**:

[Towards Optimal Bag-of-Features for Object
Categorization and Semantic Video Retrieval](http://yugangjiang.info/publication/civr07_yjiang.pdf)
[Evaluating Bag-of-Visual-Words Representations in Scene
Classification](http://lastchance.inf.cs.cmu.edu/alex/BagOfVisWords.MIR07.pdf)
[Inverse Document Frequency Weighting](https://nlp.stanford.edu/IR-book/html/htmledition/inverse-document-frequency-1.html)
[Bag of Visual Words in OpenCV for C++](http://vgg.fiit.stuba.sk/2015-02/bag-of-visual-words-in-opencv/)
