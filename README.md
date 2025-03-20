# Flipkart_Data_pipline
"This pipeline extracts data from Flipkart, loads it into the system, and then transforms it into valuable insights."
This project extracts data from Flipkart using web scraping, processes the extracted data, and converts it into useful insights.

### 📌 Features

1. Extracts product details from Flipkart
2. Parses HTML using BeautifulSoup
3. Stores extracted data in Pandas DataFrame
4. Supports structured data transformation

## 🛠️ Installation
To use this project, install the required dependencies:
```
from bs4 import BeautifulSoup
import requests
import pandas as pd
import numpy as np
```

## Main Function of This Project

### For Request To flipkart from your browser apply this 
    HEADERS = ({'User-Agent':'[Know your User-agent click_here](https://www.whatismybrowser.com/detect/what-is-my-user-agent/)' , 'Accept-Language':'en-US, en;q=0.5'})

### The webpage URL
    URL = "Your URL FROM FLIPKART"

### HTTP Request
    webpage = requests.get(URL, headers=HEADERS)

### ⚠️THE MAIN THING AT LAST IS THAT FLIPKART CHANGE IT'S CLASS/DIV AFTER SOME PERIOD REGULARLY SO YOU NEED TO KEEP MODIFY YOU CODE.
