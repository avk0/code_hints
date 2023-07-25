Configs can be set as:
- environment variables using python-dotenv
- - for developement set variables in `.env` file
- - for production same or through `os.getenv()` if variables are set outside the code
- `.yaml` file using `import yaml` in python file. Convenient formatting and can be used as dict. Linux-style configs.
- `.ini` file using `import configparser`. Good when you have no more than two levels of config dict. Win-style config.
- python file `settings.py`
- JSON file. Not easy formatting. 
