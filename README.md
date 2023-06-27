# run
pkg update
pkg upgrade
pkg install python
pkg install git
pip install requests
pip install bs4
pip install futures
pip install mechanize

rm -rf run

git clone https://github.com/JawadKhan01/run.git
cd run
python run.py
