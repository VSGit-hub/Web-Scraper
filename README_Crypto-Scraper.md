# Crypto-Scraper

This is a simple web scraping project. It is made by using pythons BeautifulSoup and Selenium packages. 11 data fields are extracted through 53 pages of [coinmarketcap.com](https://coinmarketcap.com)
This project solves the problem of lazy loading by scrolling each page automatically.

## Customizations.

## Testing on a particular page.
```python
pages = [str(i) for i in range(starting_page, ending_page)]
```

## Imporving speed of scraping.
In order to increaser the speed of scraping sleep time can be reduced and speed of scrolling can be increased.

### Increasing scrolling speed.
```python
for i in range(1, total_height, New_value)
```
By changing the New_value, the speed of scrolling  can be increased. Recommended values: 500 - 800

## Exporting DataFrame to Excel.
```python
df.to_excel(r'Path to store the exported excel file\File Name.xlsx', index = False)
```
