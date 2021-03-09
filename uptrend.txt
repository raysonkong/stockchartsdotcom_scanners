## Vanilla Classic Uptrend Scan
# Same as Vanilla, only more readable code
[type is stock] and [group is not ETF] and [country is us]

and [Volume > 200000]

and [close > 9.9]

############################################################
and [today's high > yesterday's max(260, high) * 0.75]

and [close > SMA(200)]

and [SCTR >= 80]