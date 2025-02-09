--install python in VM--
sudo apt update
sudo apt install python3 python3-pip
python3 --version
pip --version
sudo apt install python3-venv
python3 -m venv venv
source venv/bin/activate
mkdir ~/my_python_project
cd ~/my_python_project
pip install Flask
nano app.py 
python app.py
