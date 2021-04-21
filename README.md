
# Silicon Valley Bitcoin alert
<img src="gilfoyle.jpg"  title="silicon valley bitcoin alert">

# Bitcoin is Really Volatile Today

## Api : coinmarketcap <a href="https://coinmarketcap.com/api/documentation/v1/#">coinmarketcap</a>

#### If program doesn't execute try replacing api key in headers of source code with you own api key 

#### Api key can be collected from <a href="https://coinmarketcap.com/api/documentation/v1/#">coinmarketcap</a>

<ul>

  <li>When the previous price of a bitcoin is hit by the latest price the  program alerts playing Napalm Death mp3</li>
  <li>previous price is fetched from the alerts.txt file</li>
  <li>Latest price is fetched from the coinmarketcap api </li>
  <li>Default currency is in USD But it can be changed on the source code with (USD or whatever you like)</li>
  <li>This Api changes every 5 minute..so program checks the changes every 5 minute and display results</li>

</ul>
 
## Installation and Running code

- `git clone https://github.com/Newell-Road-Strategic-Technologies/Gilfoyle-bitcoin-alert.git`
- `cd Gilfoyle-bitcoin-alert`
- `pip install -r requirements.txt` 
- `python alerts.py`

## License

Everything inside this repository is under [MIT License](https://raw.githubusercontent.com/Newell-Road-Strategic-Technologies/Gilfoyle-bitcoin-alert/master/LICENSE).
