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
- Recommended: Install Anaconda (https://docs.conda.io/projects/conda/en/latest/user-guide/install/).
- Install Miniconda using the same link as above. This is a smaller download size but requires an extra step later.
- Install Python directly (https://wiki.python.org/moin/BeginnersGuide/Download).

### Jupyter
- If you installed Anaconda, you will already have Jupyter.
- Otherwise open up the terminal / command prompt and type:
`pip3 install jupyter`

### Qiskit
- Open up the terminal / command prompt and type
`pip3 install qiskit`

### Download the workshop material
- Open up the terminal / command prompt and navigate to where you would like to store the workshop.
- Type:
`git clone https://github.com/bjader/quantum-coding-tutorial.git`

Alternatively:
- Scroll up to the top of this page.
- Click on the "Clone or download button" and click on "Download ZIP".
![image](https://user-images.githubusercontent.com/14994219/69331466-bca1f580-0c4c-11ea-90fb-88509f2cf485.png)

## Check everything is working

- Open up the terminal / command prompt and navigate to where you saved the workshop. For Mac / Linux type `cd path/to/folder`. For Windows command prompt type `cd /d c:\path\to\folder`, which assumes you are in the c: drive.
- Type
`jupyter notebook index.ipynb`
- If all has been successful, your browser will open and display the workshop!
