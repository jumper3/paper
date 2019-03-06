## ubuntu 18.04 运行BCASE2018基线系统

```bash
cd ~
git clone https://github.com/DCASE-REPO/dcase2018_baseline.git
cd dcase2018_baseline/task1
sudo apt-get install python-pip
pip install --upgrade setuptools
python -m pip install --upgrade pip
sudo apt-get install wheel
sudo apt-get install python-subprocess32
sudo apt-get install libsndfile1
pip install -r requirements.txt
```

