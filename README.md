
# Port Arrival History Processor

## Introduction
This project is designed to handle the historical records of ships about to enter a port. It operates without the need for an API, focusing on processing data related to maritime activities efficiently.

## Installation Guide
The project is set up in a Jupyter Notebook environment, which simplifies the installation process. There are no specific requirements aside from having Jupyter Notebook installed on your machine. Follow the standard installation process for Jupyter Notebook to get started.

## Usage
To use this project, you need to ensure the following libraries are installed in your environment:

```python
import pandas as pd
import warnings
import re
from bs4 import BeautifulSoup
import asyncio
import nest_asyncio
from pyppeteer import launch
from googleapiclient.discovery import build
from pandas.errors import SettingWithCopyWarning

warnings.simplefilter(action='ignore', category=(SettingWithCopyWarning))
```

Ensure these libraries are installed and available in your Jupyter Notebook environment to successfully run the project.

## Features and Advantages
This project is unique because it does not require a shipping API. Instead, it utilizes the Google Search API, which allows for 100 free searches per day. This feature is particularly advantageous for users who need to process ship data without the high costs associated with maritime APIs.

## License
Please include your preferred license here or state that users should refer to the LICENSE file included in the repository for licensing information.
