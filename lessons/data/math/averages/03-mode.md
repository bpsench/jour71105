# Mode
Mode is useful when you need to find a numeric value that occurs frequently in a dataset. It's the value that occurs the most and unlike the other two types of averages, there can be more than one mode, or sometimes no mode.


The mode value is reached by counting -- and again, with no actual math formula to plug in, this would be a manual process were it not for spreadsheet tools. Thankfully, Sheets has this built-in function:

__`=MODE(A2:A11)`__

## Practice
Use all of the averaging functions to answer the following:
- What is the average gas price?
- Which gas price falls in the middle?
- What is the most frequently occurring gas price?

|City|Price|
|:--|--:|
|Anchorage|2.08|
|Austin|2.29|
|Chicago|2.51|
|Dallas|2.29|
|Denver|2.38|
|Honolulu|3.06|
|Houston|2.29|
|Los Angeles|2.73|
|Miami|2.64|
|New York City|2.98|
|San Juan|5.97|
|Washington DC|2.89|

_Hypothetical figures_

### Tip
The `=MODE()` function only works on numeric data. If, for instance, you wanted to analyze public opinion polls, you'd want to learn which text-formatted response occurred most, such as "First-time voter" or "Strongly Disagree". You would need to combine a few tricks, which are best described in this article from Exceljet:

[Most frequently occurring text](https://exceljet.net/formula/most-frequently-occurring-text).

## Next: [Percentages](../percentages/readme.md)
