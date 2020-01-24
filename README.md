![](logo-800x300.png)

# Joshua Project Python Library
> This is a Python library to help one use APIv2 to fetch the data from the database JoshuaProject.net web site.

This library uses [Joshua Project's APIv2](https://joshuaproject.net/api/v2).
You'll need an **`api_key`** to use API and the library. Get it [here](https://joshuaproject.net/api/v2).
For details, see [**Documentation**](https://joshuaproject.net/api/v2/documentation).

## Install

`pip install joshuaproject`

## How to use

### URL Constricting finctions

```python
api_key='set_your_key'
```

Get all people groups in a specific country. Countries are encoded 

```python
url_pgs_cntry('RS',api_key=api_key)
```




    'https://joshuaproject.net/api/v2/people_groups?ROG3=RS&api_key=set_your_key'


