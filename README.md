# Awesome Data Science & Visualization with stars

A curated list of data science, machine learning and visualization tools with
emphasis on [python][], [d3][] and web applications.

[CONTRIBUTING](https://github.com/quantmind/awesome-data-science-viz/blob/master/contributing.md) ⭐ 184 | 🐛 2 | 📅 2022-11-29

## Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

* [Machine Learning](#machine-learning)
  * [Resources](#resources)
  * [Frameworks](#frameworks)
  * [Neural networks](#neural-networks)
  * [Reinforcement Learning](#reinforcement-learning)
  * [Examples](#examples)
* [NLP](#nlp)
  * [Analysis](#analysis)
  * [Tools](#tools)
  * [Resources](#resources-1)
* [Images](#images)
  * [Resources](#resources-2)
  * [Frameworks](#frameworks-1)
* [Data](#data)
  * [Sources](#sources)
  * [Aggregators](#aggregators)
  * [Explore](#explore)
  * [Storage](#storage)
* [Visualization](#visualization)
  * [Resources](#resources-3)
  * [JavaScript Libraries](#javascript-libraries)
  * [Python Libraries](#python-libraries)
  * [D3 based libraries](#d3-based-libraries)
  * [Digital Art](#digital-art)
* [Languages](#languages)
  * [Python](#python)
  * [JavaScript](#javascript)
* [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Machine Learning

### Resources

* [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning) ⭐ 74,070 | 🐛 26 | 🌐 Python | 📅 2026-08-11 comprehensive list of machine learning resources
* [Python data-science handbook](https://github.com/jakevdp/PythonDataScienceHandbook) ⭐ 49,636 | 🐛 227 | 🌐 Jupyter Notebook | 📅 2024-06-26
* [Deep Learning Papers Reading Roadmap](https://github.com/songrotek/Deep-Learning-Papers-Reading-Roadmap) ⭐ 39,546 | 🐛 91 | 🌐 Python | 📅 2022-11-27
* [Data science ipython notebooks](https://github.com/donnemartin/data-science-ipython-notebooks) ⭐ 29,306 | 🐛 48 | 🌐 Python | 📅 2024-03-20
* [Probabilistic Programming and Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers) ⭐ 28,169 | 🐛 203 | 🌐 Jupyter Notebook | 📅 2024-06-25 An introduction to Bayesian methods + probabilistic programming with a computation/understanding-first, mathematics-second point of view. All in pure Python
* [Dive into machine learning](https://github.com/hangtwenty/dive-into-machine-learning) ⚠️ Archived collections of links and notebooks for a gentle introduction to machine learning
* [TopDeepLearning](https://github.com/aymericdamien/TopDeepLearning) ⭐ 6,269 | 🐛 20 | 🌐 Python | 📅 2026-07-15 is a list of popular github projects related to deep learning (ranked by stars)

### Frameworks

* [Scikit Learn](https://github.com/scikit-learn/scikit-learn) ⭐ 66,972 | 🐛 2,125 | 🌐 Python | 📅 2026-08-19 is a Python module for machine learning built on top of [SciPy](https://www.scipy.org/)
* [Keras](https://github.com/fchollet/keras) ⭐ 64,241 | 🐛 228 | 🌐 Python | 📅 2026-08-18 Deep Learning library for [Theano][], [TensorFlow][] and [CNTK][].
* [Caffe](https://github.com/BVLC/caffe) ⭐ 34,560 | 🐛 1,566 | 🌐 C++ | 📅 2024-07-31 deep learning framework made with expression, speed, and modularity in mind. Written in C++ and has python bindings.
* [XGboost](https://github.com/dmlc/xgboost) ⭐ 28,669 | 🐛 419 | 🌐 C++ | 📅 2026-08-19 an optimized distributed gradient boosting library designed to be highly efficient, flexible and portable. Written in C++ with python integration.
* [Tpot](https://github.com/rhiever/tpot) ⭐ 10,051 | 🐛 312 | 🌐 Jupyter Notebook | 📅 2025-09-11 is a python tool that automatically creates and optimizes machine learning pipelines using genetic programming.
* [Torch](https://github.com/torch/torch7) ⭐ 9,141 | 🐛 298 | 🌐 C | 📅 2025-03-31 provides several tools for fast tensor mathematics, storage interfaces and machine learning models. Written in C with Lua interface.
* [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit) ⭐ 8,705 | 🐛 1 | 🌐 C++ | 📅 2026-08-18 is a machine learning system which pushes the frontier of machine learning with techniques such as online, hashing, allreduce, reductions, learning2search, active, and interactive learning. Writtent in C++ with bindings for python and other languages.
* [Theano][] is a Python library that allows you to define, optimize, and evaluate mathematical expressions involving multi-dimensional arrays efficiently
* [TensorFlow][] library for numerical computation using data flow graphs. Nodes in the graph represent mathematical operations, while the graph edges represent the multidimensional data arrays (tensors) communicated between them.
* [PyTorch](https://pytorch.org/) tensors and dynamic neural networks in Python with strong GPU acceleration
* [CNTK][] computational network toolkit. A C++ library by Microsoft Research.

### Neural networks

* [OpenNN](https://github.com/Artelnics/OpenNN) ⭐ 1,198 | 🐛 0 | 🌐 C++ | 📅 2026-08-19 a neural network C++ library
* [Brainforge](https://github.com/csxeba/brainforge) ⭐ 113 | 🐛 3 | 🌐 Python | 📅 2023-07-30 A Neural Networking library based on NumPy only
* [deeplearn.js](https://pair-code.github.io/deeplearnjs/) a neural network library for the web

### Reinforcement Learning

* [Gym](https://github.com/openai/gym) ⚠️ Archived A toolkit for developing and comparing reinforcement learning algorithms. Written in Python.
* [TFLearn](https://github.com/tflearn/tflearn) ⭐ 9,575 | 🐛 579 | 🌐 Python | 📅 2024-05-06 is a deep learning library featuring a higher-level API for [TensorFlow][].
* [Tensorforce](https://github.com/reinforceio/tensorforce) ⭐ 3,306 | 🐛 44 | 🌐 Python | 📅 2026-07-14 a TensorFlow library for applied reinforcement learning
* [Keras-rl](https://github.com/matthiasplappert/keras-rl) ⭐ 12 | 🐛 0 | 📅 2022-05-23 Deep Reinforcement Learning for Keras.

### Examples

* [TensorFlow Examples](https://github.com/aymericdamien/TensorFlow-Examples) ⭐ 43,733 | 🐛 228 | 🌐 Jupyter Notebook | 📅 2024-07-26 a [TensorFlow][] tutorial with popular machine learning algorithms implementation
* [AIMA python](https://github.com/aimacode/aima-python) ⭐ 8,795 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2026-06-30 Python code for the book [Artificial Intelligence: A Modern Approach](https://www.amazon.co.uk/Artificial-Intelligence-Approach-Stuart-Russell/dp/1292153962)

## NLP

Natural Language processing benefits from [Recurrent Neural Network](https://en.wikipedia.org/wiki/Recurrent_neural_network)
algorithms.

### Analysis

* [huggingface/transformers](https://github.com/huggingface/transformers) ⭐ 164,253 | 🐛 2,380 | 🌐 Python | 📅 2026-08-19 State-of-the-art Natural Language Processing for Pytorch and TensorFlow 2.0
* [SpaCy](https://github.com/spacy-io/spaCy) ⭐ 33,830 | 🐛 236 | 🌐 Python | 📅 2026-08-07 is a powerful, production ready, NLP library for python
* [fastText](https://github.com/facebookresearch/fastText) ⚠️ Archived a C++ library for sentence classification
* [Natural Language Toolkit](https://github.com/nltk/nltk) ⭐ 14,698 | 🐛 229 | 🌐 Python | 📅 2026-08-19 (NLTK) is a suite of python modules, data sets and tutorials supporting research and development in [NLP][]. Some of its modules are out of date but still a useful resource nonetheless.
* [TextBlob](https://github.com/sloria/TextBlob) ⭐ 9,544 | 🐛 71 | 🌐 Python | 📅 2026-08-18 is a python library for processing textual data. It provides a simple API for diving into common [NLP][] tasks such as part-of-speech tagging, noun phrase extraction, sentiment analysis, classification, translation, and more.
* [langdetect](https://github.com/Mimino666/langdetect) ⭐ 1,900 | 🐛 71 | 🌐 Python | 📅 2025-03-03 is a port of Google's language-detection library to Python.
* [simhash](https://github.com/leonsim/simhash) ⭐ 1,038 | 🐛 7 | 🌐 Python | 📅 2022-03-24 a python implementation of [Simhash Algorithm](http://www.wwwconference.org/www2007/papers/paper215.pdf) for detecting near-duplicate web documents

### Tools

* [dataprofiler](https://github.com/capitalone/DataProfiler) ⭐ 1,574 | 🐛 78 | 🌐 Python | 📅 2026-07-20 The DataProfiler is a Python library designed to make data analysis, monitoring and sensitive data detection easy. NLP processing is accomplished using a character-level CNN.
* [inflect.py](https://github.com/pwdyson/inflect.py) ⭐ 1,082 | 🐛 65 | 🌐 Python | 📅 2026-04-13 Correctly generate plurals, ordinals, indefinite articles; convert numbers to words

### Resources

* [Oxford Deep NLP 2017 course](https://github.com/oxford-cs-deepnlp-2017/lectures) ⭐ 15,856 | 🐛 12 | 📅 2023-07-02 lecture slides and course description for the Deep Natural Language Processing course

## Images

### Resources

* [Convolutional neural network](https://en.wikipedia.org/wiki/Convolutional_neural_network) In machine learning, a convolutional neural network (CNN, or ConvNet) is a class of deep, feed-forward artificial neural network that have successfully been applied to analyzing visual imagery.

### Frameworks

* [CovNetJS](https://github.com/karpathy/convnetjs) ⭐ 11,195 | 🐛 76 | 🌐 JavaScript | 📅 2023-01-07 train Convolutional Neural Networks (or ordinary ones) in the browser
* [srez](https://github.com/david-gpu/srez) ⚠️ Archived Image super-resolution through deep learning
* [Noteshrink](https://github.com/mzucker/noteshrink) ⭐ 4,841 | 🐛 21 | 🌐 Python | 📅 2024-03-20 Convert scans of handwritten notes to beautiful, compact PDFs
* [SimpleCV](https://github.com/sightmachine/SimpleCV) ⭐ 2,731 | 🐛 121 | 🌐 Python | 📅 2024-12-20 is a framework for machine vision, using [OpenCV][] and Python. It provides a concise, readable interface for cameras, image manipulation, feature extraction, and format conversion.
* [match](https://github.com/usepavlov/match) ⭐ 1,265 | 🐛 17 | 🌐 Python | 📅 2020-07-25 makes it easy to search for images that look similar to each other
* [tesseract-ocr][] well tested [OCR][] engine written in C++
* [OpenCV][] computer vision and machine learning software library. The library has more than 2500 optimized algorithms, which includes a comprehensive set of both classic and state-of-the-art computer vision and machine learning algorithms. These algorithms can be used to detect and recognize faces, identify objects, classify human actions in videos, track camera movements, track moving objects, extract 3D models of objects, produce 3D point clouds from stereo cameras, stitch images together to produce a high resolution image of an entire scene, find similar images from an image database, remove red eyes from images taken using flash, follow eye movements, recognize scenery and establish markers to overlay it with augmented reality, etc. Written in C++ with bindins for most languages including python.

## Data

### Sources

* [7 and a quarter hours of largely highway driving](https://github.com/commaai/research) ⭐ 4,122 | 🐛 39 | 🌐 Python | 📅 2022-08-16 from [comma.ai research](http://comma.ai/)
* [Public APIs](https://github.com/toddmotto/public-apis) ⭐ 2,738 | 🐛 11 | 📅 2024-06-23 a collective list of public JSON APIs for use in web development
* [Quandl](https://www.quandl.com/) delivers free and premium financial, economic, and alternative data from hundreds of sources
  via their website, API, or directly into dozens of tools

### Aggregators

* [pyspider](https://github.com/binux/pyspider) ⚠️ Archived a web crawler system in python.
* [Newspaper](https://github.com/codelucas/newspaper) ⭐ 15,138 | 🐛 514 | 🌐 Python | 📅 2026-08-09 News, full-text, and article metadata extraction in Python 3.

### Explore

* [Crossfilter](https://github.com/square/crossfilter) ⭐ 6,189 | 🐛 4 | 🌐 JavaScript | 📅 2026-03-04 is a JavaScript library for exploring large multivariate datasets in the browser.

### Storage

* [pytables](https://github.com/PyTables/PyTables) ⭐ 1,372 | 🐛 153 | 🌐 Python | 📅 2026-08-17 a package for managing hierarchical datasets and designed to efficiently cope with extremely large amounts of data. It is built on top of the [HDF5][] library and the NumPy package.

## Visualization

### Resources

* [Visualization Universe](http://visualizationuniverse.com/)
* [Awesome D3](https://github.com/wbkd/awesome-d3) ⭐ 5,314 | 🐛 5 | 📅 2023-01-13
* [Comparison of JavaScript charting libraries](https://en.wikipedia.org/wiki/Comparison_of_JavaScript_charting_libraries)

### JavaScript Libraries

* [Chart.js](https://github.com/chartjs/Chart.js) ⭐ 67,642 | 🐛 579 | 🌐 JavaScript | 📅 2026-05-27 HTML5 Charts using the canvas tag
* [plotly.js](https://github.com/plotly/plotly.js) ⭐ 18,295 | 🐛 849 | 🌐 JavaScript | 📅 2026-08-19 charting library built on top of [d3][] and [stack.gl](http://stack.gl/)
* [frappe/charts](https://github.com/frappe/charts) ⭐ 15,083 | 🐛 145 | 🌐 JavaScript | 📅 2025-07-02 Simple, responsive, modern SVG Charts with zero dependencies
* [G2](https://github.com/antvis/g2) ⭐ 12,591 | 🐛 182 | 🌐 TypeScript | 📅 2026-07-15 is a visualization grammar, a data-driven visual language with a high level of usability and scalability
* [GraphicsJS](https://github.com/AnyChart/GraphicsJS) ⭐ 995 | 🐛 8 | 🌐 JavaScript | 📅 2026-06-19 A lightweight JavaScript graphics library with the intuitive API, based on SVG/VML technology.

### Python Libraries

* [dash](https://github.com/plotly/dash/) ⭐ 24,376 | 🐛 539 | 🌐 Python | 📅 2026-08-18 Dash is a Python framework for building analytical web applications
* [bqplot](https://github.com/bloomberg/bqplot) ⭐ 3,694 | 🐛 278 | 🌐 TypeScript | 📅 2026-05-07 plotting library for IPython/Jupyter notebooks - front-end in [d3][]
* [bokeh](https://bokeh.pydata.org/en/latest/) an interactive visualization library that targets modern web browsers for presentation
* [Altair](https://altair-viz.github.io/) declarative statistical visualization library for Python, based on Vega and Vega-Lite

### D3 based libraries

* [C3.js](https://github.com/c3js/c3) ⭐ 9,347 | 🐛 771 | 🌐 JavaScript | 📅 2026-08-05 D3-based reusable chart library
* [dc.js](https://github.com/dc-js/dc.js) ⭐ 7,430 | 🐛 412 | 🌐 JavaScript | 📅 2024-07-31 Multi-Dimensional charting built to work natively with crossfilter rendered with d3.js
* [tau Charts](https://github.com/TargetProcess/tauCharts) ⭐ 1,900 | 🐛 100 | 🌐 JavaScript | 📅 2023-10-04
* [semiotic](https://github.com/emeeks/semiotic) ⭐ 5 | 🐛 0 | 📅 2019-03-04 a data visualization framework combining React & D3
* [brite Charts](https://github.com/eventbrite/britecharts) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2023-05-17 reusable Charting Library based on D3.js v4 by <https://www.eventbrite.co.uk/>
* [d3-visualize](https://github.com/quantmind/d3-visualize) ⚠️ Archived is a [d3-view](https://github.com/quantmind/d3-view) ⚠️ Archived based reactive data-visualization library - alpha
* [d3-waffle](http://jbkunst.github.io/d3-waffle/) waffle plots with d3
* [Vega](https://vega.github.io/vega/) visualization grammar
* [Vega-lite](https://vega.github.io/vega-lite/) high-level grammar of interactive graphics

### Digital Art

* [Generating Abstract Patterns with TensorFlow](http://blog.otoro.net/2016/03/25/generating-abstract-patterns-with-tensorflow/) Compositional Pattern Producing Network (CPPN)

## Languages

### Python

* [Awesome Python](https://github.com/vinta/awesome-python) ⭐ 314,851 | 🐛 18 | 🌐 Python | 📅 2026-08-16 A curated list of awesome Python frameworks, libraries, software and resources.
* [Interactive coding challenges](https://github.com/donnemartin/interactive-coding-challenges) ⭐ 31,737 | 🐛 75 | 🌐 Python | 📅 2024-05-08 which focus on algorithms and data structures that are typically found in coding interviews

### JavaScript

* [Simple Statistics](http://simplestatistics.org/) statistical methods in readable JavaScript for browsers, servers.
* [Computer science in JavaScript](https://github.com/nzakas/computer-science-in-javascript) ⭐ 9,111 | 🐛 12 | 🌐 JavaScript | 📅 2026-01-08 Collection of classic computer science paradigms, algorithms, and approaches written in JavaScript

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Quantmind](http://quantmind.com) has waived all copyright and related or neighboring rights to this work.

[d3]: https://github.com/d3

[HDF5]: https://www.hdfgroup.org/HDF5/

[NLP]: https://en.wikipedia.org/wiki/Natural_language_processing

[OCR]: https://en.wikipedia.org/wiki/Optical_character_recognition

[OpenCV]: https://github.com/opencv/opencv

[python]: https://www.python.org/

[TensorFlow]: https://github.com/tensorflow/tensorflow

[Theano]: https://github.com/Theano/Theano

[tesseract-ocr]: https://github.com/tesseract-ocr/tesseract

[CNTK]: https://github.com/Microsoft/CNTK

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
