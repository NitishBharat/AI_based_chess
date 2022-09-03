# AI_based_chess
Presented game provide a real experience to user playing chess remotely with computer mode by enhancing with algorithm used as Min max algorithm and Alpha-beta Pruning further it is trained to make it learnable so in order to improve user experience.

## Download

Press the green "Code" button and click "Download ZIP".

Save the folder to your computer, and extract the contents.

Open a Terminal (OSX/LINUX) or CMD (WINDOWS) and follow the below instructions.

## Prerequisites

We have provided a requirements.txt for you to setup your python environment.

Python Latest Version Download:
https://www.python.org/downloads/


Change directories to chess folder.
```
cd /path/to/chess/folder/
```

First off, create your virtual environment by entering the commands below...

### Mac OSX / Linux

Install virtual environment tool:
```
pip3 install virtualenv
```

Create and activate virtual environment:
```
python3 -m venv chessenv

source chessenv/bin/activate

pip3 install -r requirements.txt
```

### Windows

Install virtual environment tool:
```
pip3 install --user virtualenv
```

Create and activate virtual environment:
```
py -m venv chessenv

chessenv\Scripts\activate.bat

pip3 install -r requirements.txt
```
### RUN

Once you have got your venv activated, run the following command:

#### Mac OSX / Linux
```
python3 chess.py
```

#### Windows
```
chess.py
```
