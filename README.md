# Textract

Python script to extract text from images

## Getting Started

## Prerequisites

### Git

Install git if you don't have it by going to https://git-scm.com/downloads

### Python

Install Python on your local machine by going to [Python's download section](https://www.python.org/downloads/)

#### Alternative methods for installing Python:

[scoop](https://scoop.sh/)

```
scoop install python
```

[chocolatey](https://chocolatey.org/install)

```
choco install python
```

#### Tesseract

Get the pytesseract installer from https://github.com/UB-Mannheim/tesseract/wiki

## Installing

#### Step-1

Install tesseract from the installer that you downloaded earlier. Note the path where the installer will install tesseract.<br />
If you use the default install directory, it should be:

```
C:\Program Files\Tesseract-OCR\tesseract.exe
```

Once the installer is finished, add the above the directory (or the directory that you installed to) to the path.

#### If you changed the install directory of tesseract make sure to edit `pytesseract.pytesseract.tesseract_cmd` in the python file to your directory

#### Step-2

Install the required files for the script to run by pip installing the libraries in the requirement.txt Or install them by using these commands one by one.

```
pip install pyperclip
pip install PyQt5
pip install pytesseract
pip install py-notifier
pip install Pillow
```

#### Step-3

Git clone the repository by

```
git clone https://github.com/meetmistry0/Textract.git
```

#### Step-4

cd to the directory where you cloned the repository and use the following command to start the script

```
python textract.py
```

## Authors

- **Meet Mistry** - [Github](https://github.com/meetmistry0)
