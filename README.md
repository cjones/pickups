# pickups

IRC gateway for Google Hangouts using
[hangups](https://github.com/tdryer/hangups).

## Usage

`$ python3 run.py`

You will be given a URL to your oauth2 token.  Go to the url.  Copy the token.
You will be prompted for your oauth2 token.  Paste it in.
Connect yoru IRC client to localhost on port 6667

### Run under python3 and virtualenv

$ virtualenv -p python3 venv

$ source venv/bin/activate

$ pip install -r requirements.txt

$ mkdir -p ${HOME}/.cache/hangups/

$ python3 run.py

### Run hangups on a different port

$ python3 run.py --port=7667
