# How to use this tutorial

Natural Language Processing requires data.  The following tutorial will help you get your environment set up, so you can get started with some standard datasets:

[https://shirishkadam.com/2016/10/06/setting-up-natural-language-processing-environment-with-python/](https://shirishkadam.com/2016/10/06/setting-up-natural-language-processing-environment-with-python/)

Once you're all set up you're ready to check out Feature Transformation, which is found in:

Feature_Transform.ipynb




Structure of this tutorial:

The goal of this tutorial is to prepare the reader to do natural langauge processing.  This tutorial is intended both as a field reference and as a tutorial.  Therefore I have chosen to break up the tutorial semantically by task.

So things like feature transformations all appear together, even if they typically belong to seperate types of programs.  For instance, you would not use tf-idf with a neural network intended for machine translation - you'd lose all the stop words and then non of your sentences would make sense.

Like wise, you'd probably never use an encoder/decoder scheme with text classifcation because you'd never figure out the important words.

In addition to the reference material explaining things from a conceptual level, a number of examples will be included throughout, to show to handle individual workflows and tasks.



