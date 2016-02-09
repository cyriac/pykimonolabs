## pykimonolabs

This package can be used to access the API's build on top of kimonolabs

## Installation
```
pip install pykimonolabs
```

## Usage

### Fetch data from an API
```
from kimonolabs import Kimono
k = Kimono(api_id="api_id", kimmodify=True|False, api_key="api_key")
data = k.data
```

### Update urls to crawl in an API
```
from kimonolabs import Kimono
k = Kimono(api_id="api_id", kimmodify=True|False, api_key="api_key")
k.update(urls=['https://github.com', 'https://google.com'])
k.start_crawl()
```
