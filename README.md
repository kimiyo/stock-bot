Author:  Ryan Cullen
# StockBot

StockBot is a Python application for designing and testing your own daily stock trading algorithms.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install matplotlib and yfinance from your command line.

```bash
pip install matplotlib
pip install yfinance
```

## Usage
You will be asked to enter a ticker for the stock that you want to test the algorithm on.

If you want to modify the algorithm and design your own, you only need to change the Decide() method. That method takes three functions, and you can decide what those are or design your own inputs. My implementation uses moving averages and their derivatives/concavity (the class for which is set up for you to use in your own algorithm).

## Example Output
Here are a couple images depicting the output from an algorithm I developed. 

![PEN](https://github.com/ryantcullen/stock-bot/blob/master/Example%20Pictures/B4myQ0t.png?raw=true)

![BABA](https://github.com/ryantcullen/stock-bot/blob/master/Example%20Pictures/TwOShiK.png?raw=true)

![IBM](https://github.com/ryantcullen/stock-bot/blob/master/Example%20Pictures/lhWY5yX.png?raw=true)


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

The goal for this script is of course for it to be as robust and generalized as possible in terms of the data available for the user to use to design an algorithm. Add features according to whatever that means to you and submit a pull request to the feature-test branch. If if adds value to the project it will be accepted and merged. 

Please make sure to update tests as appropriate.

Thanks!  :)


