# Clinical trials widget

### A widget capable of displaying geographic and demographic information

---

## Usage

#### Basic usage

To use the widget, please go to [http://52.53.188.247/map.html](http://52.53.188.247/map.html)

#### Advanced usage

http://52.53.188.247/map.html?mode=<mode>&height=<height>&width=<width>&def_query=<def_query>

- mode: Optional. Can be none or "widget" to enable/disable widget mode
- height: Optional. Can be certain amount of pixels to adjust the height in widget mode
- width: Optional. Can be certain amount of pixels to adjust the width in widget mode
- def_query: Optional. Can be a HTML-escaped string for default query upon initialization

#### Searching

By typing words in the query field and wait for a while, the website will automatically start querying clinical trials information from our database. 

Then, a number of circles will appear with each labelling the number of studies inside such area. 

Hovering on a circle will display the total number of study population inside such area. 

Right-click on a circle will display more detailed information about the demographics. 