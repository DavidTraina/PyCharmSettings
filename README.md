# PyCharmSettings

My PyCharm configuration and some helpful tools I made

## Setup
### Black Format External Tool
This tool lets you format your projects with [Black](https://black.readthedocs.io/en/stable/) by pressing `Ctrl + \`
- Install Black to your base [conda](https://docs.conda.io/en/latest/index.html) environment (or anywhere else you choose)
  ```bash
  conda activate base 
  pip install black
  whereis black | xclip -sel clip 
  ```
- Open the Black Format external tool and paste the path to the `black` executable into the `Program`
- Optionally remove the `-S` flag based and/or add other options to the command based on you needs
