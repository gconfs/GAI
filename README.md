# Welcome to GAI, GConfs Artificial Intelligence

This program let you automates the split of streams into multiple videos

## Installation

```bash
git clone
cd gstream
xargs -a bash-requirements.txt sudo apt-get install
python3 -m venv env
source env/bin/activate
pip install -r python-requirements.txt
```

For this part you will need 2 zip files containing your training set
gconfs.zip which contains the break images and gconf.zip the rest
You can find this zip files on my google drive: <br />
gconfs.zip: https://drive.google.com/open?id=1QYZtNmNUdS67xbhmIsmWQDFCfaXe6q6u <br />
gconf.zip: https://drive.google.com/open?id=17kNrihLoJpcXSlRDc1RcPyHvm3WKXiNt

```bash
cd ressources/train_set
unzip gconfs.zip
unzip gconf.zip
```
