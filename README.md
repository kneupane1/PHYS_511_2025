## PHYS 511 Nuclear Physics Data AnaLysis Lab

Our lab's documentation will be available on here https://github.com/kneupane1/PHYS_511_2025/tree/master. You can download or clone files from this page. However I will also send you emails before every labs with the required files and tasks to do. Below is a guide on how to properly prepare yourself and your computer for our labs.

### Purpose Behind Coding Lab

This lab is aimed to teach you both basic programming in python as well as see how it can be applied in a nuclear physics setting. Given the vast amounts of data that we deal with in this field, effective analysis often requires programming skills. Although languages such as C++, Java, and Fortran are commonly used, Python is increasingly being recognized as a powerful tool for data analysis. Moreover, the use of Jupyter Notebooks provides an efficient platform for obtaining quick results and feedback on your code.

## Getting Working Python and Jupyter Notebooks

#Step1:

- If you do not have python3 or anaconda in your computer, you need to install python3 or anaconda. If you already have either python3 or anaconda with Jupyter Notebook you can jump to #Step 2.

### Anaconda install

Documentation on installing conda for your operating system is located [here](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) or directly [here](https://www.anaconda.com/products/distribution)
Anaconda should comes with all of the required packages.

### Python install

1.Install python latest version [here](https://www.python.org/downloads/)
2.Install Jupyter Notebooks is located [here](https://jupyter.org/install)

#Step2:

### Required modules installation

To complete our lab, you will need Jupyter Notebooks, NumPi, SciPy, Matplotolib, and Pandas. You can verify whether these packages are installed in your computer by running the following command in your terminal or command prompt (first one for anaconda, second one for python):

conda list
pip list

If any of these packages are not installed on your system, please install them. You can find instructions to install them online based on your operating system (Windows, macOS, or Linux).
In general this code should install all the packages you needed in python3:
pip3 install jupyter matplotlib numpy scipy pandas

or you can use them one by one:
pip3 install jupyter
pip3 install matplotlib
and so on ..

#Step 3:

### Success Check

Once you have successfully gotten Jupyter Notebooks installed, open it using anaconda graphical user interface (GUI) or from terminal/command prompt by typing:

jupyter notebook

It will open the Jupyter Notebook and then you need to click on the folder where you saved the files you downlaoded from email.

Now, try running the test file named 'Test Functionality'. If it runs without error, you are all set for our next lab.
If you run into issues please feel free to contact me: kneupane@email.sc.edu
