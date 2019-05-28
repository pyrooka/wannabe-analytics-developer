# Wannabe analytics developer
Just a challenge solution.

## Setup
1. Install Python 3
2. Install pip
3. Install the necessary packages:
   - with pip: `pip install -r requirements.txt`
   - with pipenv: `pipenv install`

## Usage
1. Set the `SOURCE_DB_URL` and `TARGET_DB_URL` environment variables if your system isn't running with the default config.
2. Run the `transfer.py` script to fill the new DB from the old one. Use with flag `-d/--debug` to display SQL logs.
3. Wait until the script is finished.
4. Run the `plot.py` to create a HTML report from the new data.