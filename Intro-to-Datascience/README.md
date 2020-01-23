# Introduction to Data Science and Python for Finance

## Jupyter notebook setup
Download the `ipynb` notebook file here and run it using Jupyter in the browser by:
1. Go to https://jupyter.org/try
1. Click on `Try Classic Notebook`
1. Once your default Jupyter notebook has opened, select `File -> Open`
1. Click on the `Upload` button in the top-right corner of the `Files` tab window
1. Select your `ipynb` file for upload
1. Click `Upload` to upload your notebook to the hosted Jupyter server
1. Click on the `ipynb` notebook to open it

## Investor Exchange (IEX) setup
1. Go to https://iexcloud.io/ and select `Get Started`
1. Create an `Individual` account.
1. When logged in, you have a list of account plans to choose from. Below the panels is an option for `select free plan`
1. You will receive an account verification email at the address used for setup.
1.  Once you have verified your account, select the `API Tokens` left-hand menu item
1. Copy the public key (starts with `pk...`) and paste into the cell in your Jupyter notebook which has the line: `os.environ["IEX_API_KEY"] ="paste your API key here"`