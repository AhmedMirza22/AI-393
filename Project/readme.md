**PROJECT FINAL REPORT**



**NAME : IBADULLAH**
**STUDENT-ID : 63052**

**NAME : AHMED MIRZA**
**STUDENT-ID : 63254** (Group Leader)


Cross-verification is a mathematical method used to measure the ability of machine learning models.

It is widely used in machine learning comparisons to compare and select the problem model to make a given predictive model because it is easy to understand, easy to use, and results in skill measurements often with lower options than other methods.
1) That is the validation of the k-fold cross process used to measure model ability on new data.
2) There are some common tricks you can use to select the k value of your data.
3) There are variations commonly used in cross-verification such as string splits and repetitions found in scikit-learn.

k-Fold Cross-Validation:
Cross-verification the retrieval process is used to test machine learning models in a sample of limited data.

The process has one parameter called k referring to the number of groups a sample of the given data should be divided. As such, the process is often called k-fold cross-validation. When selecting a specific value of k, it can be used instead of k in reference to the model, as k = 10 becomes tenfold.

Cross-verification is mainly used in machine learning that is used to measure the ability of a machine learning model in invisible data. That is, using a limited sample to estimate how the model is expected to operate normally when used to make unpredictable data predictions during model training.

Configuration of k:
The value k should be carefully selected from the sample of your data.

A poorly chosen value of k can lead to a misinterpretation of the model's capabilities, such as points with high variability (which can vary greatly based on data used to match the model), or large selections, (such as over-indicating model ability).

Three common tricks for selecting the value of k are as follows:

Representative: The value of k is chosen in such a way that each train / test group of data samples is large enough to statistically represent a broad database.
k = 10: The value of k is limited to 10, the value obtained by testing so that it usually results in a measure of modeling skills with a low bias difference.
k = n: The value of k is directed to n, where n the size of the database gives each test sample the opportunity to be used in the capture database. This method is called leave-one-out cross-validation.

Cross-Validation API :
We do not need to use k-fold cross-validation manually. The scikit-learn library provides a startup that will separate a sample of the data provided.

The KFold () scikit-learn section can be used. It takes as an argument the amount of separation, whether sampling or not, and the pseudorandom number generator used before mixing.

For example, we can create an example that divides the database into 3 folders, extracts it before splitting, and uses the 1 value in the pseudorandom number producer.

Variations on Cross-Validation :
There are several variations in the k-fold cross verification process.

The three most commonly used variants are as follows:

Train / Test Separation: A single overdose taken, k can be set to 2 (not 1) in such a way that a single train / test split is created to test the model.
LOOCV: 
Taken from other extremes, k can be set to the total number of views in the database as each view is given the opportunity to be extracted from the database. This is called leave-one-out cross-validation, or LOOCV for short.
Stratified:
 The division of data into folders can be controlled by processes such as ensuring that each fold has the same amount of views as a given category value, such as the phase output value. This is called separate authentication.
Repetition:
 When the process of verifying k-fold fold is repeated n, where necessary, the sample data is changed before each duplication, resulting in a separate sample separation.
Nested:
 When k-fold cross-validation is performed within each cross-validation pen, it is usually possible to perform hyperparameter tuning during model testing. This is called a combination of affirmative affirmations or double affirmation of cross-verification.
 
Python text is basically a file containing code written in Python. A file containing python text can be extended '. py 'or you can have an extension'. pyw 'if it works on a windows machine. To run the python script, we need a python interpreter that needs to be downloaded and installed.



Structure of Code is Key:
Due to the way in which implants and modules are handled in Python, it is very easy to plan a Python project. It's simple, here, it means you don't have a lot of issues and that the module import model is easy to understand. Therefore, you are left with the clean task of building the various components of your project and their interactions.

Simple project planning means it’s easy and awkward. Other features of an informal project include:

Several round lean and dirty The carpenter in question.whatdo (), then you have a circular lean. In this case you will need to use weak methods such as using import statements within your methods or functions.
Hidden Encryption: Each change in Table application breaks 20 tests in unrelated test cases because it violates the Carpenter's code, requiring very careful surgery to adapt to the change. This means you have too many ideas about Table in Carpenter's code or repeating.
Difficult use of the global environment or context: Instead of overtaking (obvious height, width, type, wood) with each other, Table and Carpenter rely on global variables that can be converted and converted into aircraft by different agents. You need to scrutinize all access to these global variables to understand why a rectangular table becomes a square, and then find that the remote template code also changes this context, aligning with the size of the table.
Spaghetti Code: Multiple pages nested if clauses and loops with process code with multiple copies and no relevant segment known as spaghetti code. The logical introduction of Python (one of its most controversial features) makes it very difficult to maintain this type of code. The good news is that you may not see much.
Ravioli code is most likely in Python: it contains hundreds of similar pieces that make sense, usually classes or objects, without the proper structure. If you never remember, if you have to use FurnitureTable, AssetTable or Table, or TableNew for your intimate work, you may be swimming with a ravioli code.

Modules: 
Python modules are one of the largest extraction layers available and perhaps the most natural. The extraction layers allow you to split the code into sections that store performance-related data.

For example, a project layer may manage to meet user actions, while another will handle low data fraud. The natural way to separate the two layers is to reassemble all interfacing functionality into one file, and all sub-standard functionality in another file. In this case, the display file needs to import a lower level file. This is done by importing and departing from import statements.

As soon as you use import statements, you use modules. These could be built-in modules such as os and sys, third-party modules that you have installed in your area, or internal modules for your project.

To comply with the style guide, keep short module names, short characters, and make sure you avoid using special symbols such as a dot (.) Or a question mark (?) A file name like my.spam.py is the one you should avoid! Naming it this way will affect Python's view of modules.

In the case of my.spam.py Python is waiting to find the spam.py file in the folder with my wrong name. There is an example of how a dot should be used in Python documents.

If you like, you can name your module my_spam.py, but even our trusted friend below, should not appear that often in module names. However, using other characters (spaces or links) in module names will prevent import (- delete operator). Try to keep short module names so there is no need to separate words. And, above all, don’t keep the name of the space with underscore; use submodules instead.

Object-oriented programming:
Python is sometimes defined as the programming language of an object. This can be misleading in some way and requires further clarification.

In Python, everything is a thing, and can be treated that way. This means that when we say, for example, that jobs are first-class things. Tasks, classes, cables, and even genres are Python's objects: like anything, they have a genre, they can be transmitted as work arguments, and they can have methods and structures. In this understanding, Python can be considered as a target language.

However, unlike Java, Python does not set a targeted program as the main program pradigm. It is best for the Python project not to focus on an object, eg no use or very few class definitions, class legacy, or other methods related to programming languages targeted at an object.

In addition, as seen in the module section, Python's approach to managing modules and word spaces provides the developer with a natural way of ensuring the installation and separation of extraction layers, both of which are the most common reasons for using object orientation. Therefore, Python programmers have an extra dimension of not using object orientation, when not required by the business model.
Dynamic typing :

Python type is dynamic, which means that the variable has no fixed type. In fact, in Python, the variables are quite different from those of many other languages, especially mathematical languages. Variable is not part of a computer memory where a certain number is written, it is 'tags' or 'words' that point to objects. It is therefore possible that the variable 'a' is set to the number 1, and the value 'string', is applied.

Powerful Python typing is often viewed as weak, and it can actually lead to problems with the error code. Something called 'a' can be set to many different things, and the engineer or maintainer needs to trace the word to the code to make sure it is not set to something completely unrelated.



