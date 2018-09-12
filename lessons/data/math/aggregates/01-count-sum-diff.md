# Count vs Sum

Here's a great way to think about the difference between counting versus summing. Think about how many units of currency there are in circulation in the United States today.

![Silvrback blog image](https://silvrback.s3.amazonaws.com/uploads/ed7f5ac0-e196-4323-bb1d-c46ecfb7fc25/usd-coins_crop_large.jpg)

![Silvrback blog image](https://silvrback.s3.amazonaws.com/uploads/3d8c214c-43b6-4c2f-a035-c1da94f6be48/usd-bills_reduced_large.jpg)

If you _count the units_, they equal __14__ -- we have the penny, nickel, dime, quarter, half-dollar, and two versions of the dollar as the [current coins](https://www.usmint.gov/mint_programs/circulatingCoins/). And then the [current treasury notes](https://www.treasury.gov/resource-center/faqs/Currency/Pages/denominations.aspx) are the one, two, five, ten, twenty, fifty and hundred dollar bills.

Yet if you add together their values:
$0.01 + $0.05 + $0.10 + $0.25 + $0.50 + $1.00 + $1.00 + $1 + $2 + $5 + $10 + $20 + $50 + $100
their _sum total amount_ is __$190.91__.

In one case you count, in the other case you sum and SQL can make the same distinction when you query your data. While you can __COUNT__ both numeric and non-numeric data, you can only __SUM__ numeric data. Why is this the case?

__IMPORTANT: When you count and/or sum, the figures that SQL returns are not actual numbers within the data, rather they are virtual stats, the results of calculations that SQL performs on the fly based on the math that you imply in your query. Formally, they are called "aggregate functions." The other aggregate functions calculate the minimum, maximum and average results of given data.__

# Difference
