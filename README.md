# Project: Language Translation with Sequence to Sequence


### Project Overview

In this project we are training a sequence to sequence model on a dataset of English and French sentences that can translate new sentences from English to French.

### Analysis
You can find the final Notebook [here](https://github.com/yanndupis/language-translation/blob/master/dlnd_language_translation.ipynb).

### Install

This project requires **Python 3.5** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [tensorflow](https://www.tensorflow.org/)
- [warning](https://docs.python.org/2/library/warnings.html)
- [distutils](https://docs.python.org/2/distutils/introduction.html)
- [time](https://docs.python.org/2/library/time.html)


You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend to install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

### Code

The code is provided in the `dlnd_language_translation.ipynb` notebook file. You also need the `small_vocab_en` and `small_vocab_fr` dataset files to run the Notebook.

### Run

To quickly train the model, we highly recommend to run the Notebook with GPUs using FloydHub](https://www.floydhub.com) or AWS or another platform.

If you don't have access to GPUs, you can always run this Notebook on your local machine but it might take 6/8 hours to train the model.

In a terminal or command window, navigate to the top-level project directory `language-translation/` (that contains this README) and run one of the following commands:

```bash
ipython notebook dlnd_language_translation.ipynb
```  
or
```bash
jupyter notebook Adlnd_language_translation.ipynb
```

This will open the iPython Notebook software and project file in your browser.
