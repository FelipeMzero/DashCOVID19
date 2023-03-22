#https://linuxize.com/post/how-to-install-python-3-8-on-ubuntu-18-04/
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt install python3.8 python3.8-venv
#ttps://docs.python.org/pt-br/3.8/library/venv.html
python3.8 -m venv venv 
source ./venv/bin/activate
pip install -r requirements.txt
ython dashboard.py 