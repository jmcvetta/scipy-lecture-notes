# Installation

## Ubuntu

### 12.04 Precise Pangolin

```bash
$ sudo apt-get install python-pip virtualenvwrapper libfreetype6-dev libblas-dev liblapack-dev gfortran
$ cd ~/workspace # Path to your preferred workspace
$ git clone https://github.com/scipy-lectures/scipy-lecture-notes
$ cd scipy-lecture-notes
$ mkvirtualenv scipy
(scipy)$ pip install sphinx numpy
(scipy)$ pip install matplotlib # Must be done AFTER numpy is installed
(scipy)$ make html
```
