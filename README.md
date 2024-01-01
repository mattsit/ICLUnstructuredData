# Topic modeling on earnings calls transcripts from big tech from 2020-2023
MLDS @ ICL Unstructured Data course final project

Matthew Sit

Fall 2023

## How to run the code

I used Google Colab to run the code.

1. Download the contents of this repository and upload the notebook to your Google Drive account. Open the notebook using Google Colab (free for all users).
2. Connect to the default runtime and run all cells, paying careful attention to the top few cells which are the pre-requisite setup cells.
3. In the second cell, a "Choose Files" button will appear and execution will wait until you click the button and upload the necessary data files, which are all the files contained in the two data directories in this repository:
    - the Meta earnings call raw transcript files (15 files) (copy+pasted from investors relations site from pdf to txt)
    - the Microsoft earnings call raw transcript files (15 files) (downloaded from the investors relations site and re-saved as txt)
    - **Total: 30 files to be uploaded**
4. In the third cell, some installations are required which are not available in the default runtime. These should be completed automatically without issue.
5. The rest of the notebook should now run.

## Approximate runtime for notebook on Google Colab
8 minutes

## Hardware/software requirements
No additional hardware or software is needed besides the default Google Colab runtime. No special clusters, parallel jobs, SLURM, OpenPBS, nodes, cores, CPU/GPU, or memory per CPU requirements.

The Google Colab default runtime is called the "Python 3 Google Compute Engine backend" and has 12.7 GB system RAM and 107.7 GB disk available for free.

