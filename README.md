# Predicting-Stock-Prices
Beginning machine learning with sentdex's tutorial which you can find here: https://pythonprogramming.net/regression-introduction-machine-learning-tutorial/

Sentdexs' tutorial on predicting stock prices is quite good and I've learned quite a bit from here. At least, it's got me started with choosing algorithms, etc.

One problem I did note after completing the tutorial was that I wasn't "truly" predicting the stock prices, I mean, `regression.py` gives a forecast which is not really in the future. I'm not sure if this was intentional or got missed by sentdex (or it's just not working for me). It plots values which are two weeks in the past! So I've tweaked the code just a bit to really get values which are "in the future"

**Feel free to try out the code!**
1. Do ensure you've got all the necessary packages installed. Check `Pipfile` for the list
2. Run `python regression.py`

Here's a prediction I got:<br>
<img src=https://github.com/LawrenceVeigas/predicting-stock-prices/blob/master/prediction.png><br>

Again, not the most accurate prediction in the world, but at least I'm getting somewhere!
