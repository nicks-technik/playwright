# playwright

## How to install the playwright stuff

```bash
sudo apt update
sudo apt install python3 python3-pip

pyvenv_wipe

# Install the playwright
pip install playwright
python -m playwright install

# Install the requirements for the playwright recording
sudo apt install nodejs npm
npm install -g playwright-cli

# Playwright start recording
playwright codegen https://example.com
playwright codegen https://example.com > generated_script.py

```
