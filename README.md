# Handwritten Text Detection using Deep Learning

## Downloading dataset

To download the dataset, you need to visit [here](https://fki.tic.heia-fr.ch/databases/download-the-iam-handwriting-database). You need to download **data/words.tgz** zip file.

After downloading, create a folder name `Dataset` on the project directory. Then copy the downloaded zip file to the `Dataset` folder.

## Run the code

1. Run `git clone https://github.com/JanayAlam/handwritten-text-detection` on the terminal.
2. Run `virtualenv venv` on the terminal. If you do not have **virtualenv** installed then you have to run `pip install virtualenv` first before running `virtualenv venv`. 
3. You have to activate the virtual environment by running `source ./venv/Scripts/activate` on the linux/mac/git bash or `.\venv\Scripts\activate` on the windows (powershell/cmd).
4. To install the required packages you need to run `pip install -r requirements.txt`.

Now you can run `jupyter notebook` command on your terminal and access and run the **handwritten-text-detector.ipynb** notebook.
