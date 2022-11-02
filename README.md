# snippets
# python virtualenv

sudo apt install python3-virtualenv
python3 -m virtualenv venv-1

git clone git@github.com:hft-lab/dydx-v3-python.git
./venv-1/local/bin/pip install -e dydx-v3-python
./venv-1/local/bin/python your_script.py
