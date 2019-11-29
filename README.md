# Quantum coding workshop

## Prerequisites

Before attending the workshop, please ensure you have the following installed. If you are unable to do so, the 30 minutes prior to the workshop starting are reserved for helping with any installation problems.

What you'll need:
- A working internet connection.
- Knowledge of how to open the terminal (OSX / Linux), or command prompt (Windows).

## Installation guide
By the end of this you should have:
- Python 3
- Jupyter notebook (https://jupyter.org/)
- Qiskit (https://qiskit.org/)
- A downloaded copy of this repository

### Python 3
Here are three options to install Python - please pick one.
- **Recommended for all, essential for Windows**: Install Anaconda (https://docs.conda.io/projects/conda/en/latest/user-guide/install/). 
- Install Miniconda using the same link as above. This is a smaller download size but requires an extra step later.
- Install Python directly (https://wiki.python.org/moin/BeginnersGuide/Download).

### Jupyter
- If you installed Anaconda, you will already have Jupyter.
- Otherwise **Mac/Linux:** Open up the terminal and type
`pip3 install jupyter`

### Qiskit

- **Mac/Linux:** Open up the terminal and type
`pip3 install qiskit`
- **Windows:** Open Anaconda Prompt from the start menu. Once it's open, type
`pip install qiskit`

### Download the workshop material
- **Mac/Linux:** Open up the terminal and navigate to the folder where you would like to store the workshop by typing`cd path/to/folder`. For example, type `cd Downloads` if you want to save it in your Downloads.
- **Windows:** Open up Anaconda Prompt and navigate to the folder where you would like to store the workshop by typing`cd path\to\folder`. For example, type `cd Downloads` if you want to save it in your Downloads.
- **All operating systems** type:
`git clone https://github.com/bjader/quantum-coding-tutorial.git`

Alternatively:
- Scroll up to the top of this page.
- Click on the "Clone or download button" and click on "Download ZIP".
![image](https://user-images.githubusercontent.com/14994219/69331466-bca1f580-0c4c-11ea-90fb-88509f2cf485.png)

## Check everything is working

- **Mac/Linux:** Open up the terminal and navigate to where you saved the workshop
`cd path/to/folder/quantum-coding-tutorial`
- **Windows:** Open Anaconda Prompt and navigate to where you saved the workshop
`cd path\to\folder\quantum-coding-tutorial`
- **All operating systems** type
`jupyter notebook index.ipynb`
- If all has been successful, your browser will open and display the workshop!
