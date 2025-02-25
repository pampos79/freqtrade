**27/04/2021**
- Changed default "initial_state" to "running"
- Modified "setup complete" message
- Added BNB to blacklist to avoid "insufficient balance for requested action" on sell order
- Additional Telegram buttons

**26/04/2021**
- Modified "stop_duration_candles" to 1 to accommodate new strategy

**25/04/2021**
- Moved to MACD & SMA strategy

**16/04/2021**
- Separated configuration, strategy and service files
- Created updateFreqtrade, updateConfig and updateStrategy scripts
- Added SUSD to blacklist

**14/04/2021**
- Improved IP detection

**09/04/2021**
- Now configured to use stoploss_on_exchange
- Created freqtrade and freqUI update script

**04/04/2021**
- Removed "minimal_roi" from strategy
- Added "trailing_stop" to strategy

**29/03/2021**
- Added "PAXG" to blacklist
- Added RSI indicator
- Modified ROI
- Modified "AgeFilter" to 5

**26/03/2021**

- Added "AgeFilter"
- Removed "aiohttp_trust_env" option from config.json
- Decreased "rateLimit" to 200
- Increased "number_assets" to 350
- Updated README.md

**23/03/2021**

- Changed "enableRateLimit" to "true"

**18/03/2021**

- Tidy up installer script
- Updated README.md

**17/03/2021**

- Added binance stablecoins and Fiat currencies to blacklist

**02/03/2021**

- Added Leveraged tokens to blacklist
- Prompt for FreqUI port
- Added Protections options in config.json

**01/03/2021**

- Now using VolumePairList method
- Also using multiple filters
- Updated README.md

**01/03/2021**

- Updated coin pairs list
- Updated README.md

**28/02/2021**

- Additional prompts for installation wizard
- Minor changes in config.json
- Added FreqUI installer
- Now automatically gets host IP Address
- Can now set FreqUI user/pass
- Set dry_run to false
- Now setting "jwt_secret_key" automatically
- Echoes FreqUI URL after installation

**27/02/2021**

- Removed deprecated ticker_interval from config.json
- Set minimal_roi to "0":  0.01 only
- Added custom keyboard commands for Telegram

**24/02/2021**

- Created prompts for installation wizard
- Updated README.md

**20/02/2021**

- Merged all scripts into one
- Updated README.md
- Updated coins pair list

**19/02/2021**

- Updated README.md

**19/01/2021**

- Removed comments from strategy
- Updated coins pair list

**18/01/2021**

- Created Freqtrade install script
- Created strategy install script
- Created configuration install script
- Created service install script
- Created README.md
