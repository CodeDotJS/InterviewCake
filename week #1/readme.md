## Apple Stocks

__Writing programming interview questions hasn't made me rich yet ... so I might give up and start trading Apple stocks all day instead.__

First, I wanna know how much money I could have made yesterday if I'd been trading
Apple stocks all day.

So I grabbed Apple's stock prices from yesterday and put them in an array called
`stockPrices`, where:

- The __indices__ are the time (in minutes) past trade opening time, which was
9:30am local time.

- The __values__ are the price (in US dollars) of one share of Apple stock at that
time.

So if the stock cost $500 at 10:30am, that means `stockPrices[60] = 500`.

Write an effcient function that takes stockPrices and returns __the best proft I could
have made from one purchase and one sale of one share of Apple stock
yesterday__.

For example -

```js
const stockPrices = [10, 7, 5, 8, 11, 9];

getMaxProfit(stockPrices);
// Returns 6 (buying for $5 and selling for $11)
```

No "shorting"—you need to buy before you can sell. Also, you can't buy and sell in the
same time step—at least 1 minute has to pass.
