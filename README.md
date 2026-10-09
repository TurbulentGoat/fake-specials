# Fake multibuy specials

This spreadsheet lists every "2 for $X" style multibuy special at Coles, Woolworths and Liquorland, and checks each one against the product's price history. A special is marked **fake** when each item on the deal costs more than the product's normal shelf price did before the special started.

A typical fake goes like this:

1. A product sells for $5.
2. The shelf price goes up to $7.
3. A "2 for $12" special appears. That works out to $6 each.
4. The tag shows a $1 saving on the new $7 price, but you pay $1 more per item than before the rise.

The file name gives the scan date: `multibuy-YYYY-MM-DD.xlsx`.

## Sheets

- **Top 10 fakes**: the worst ten fakes per store, ranked by how much dearer each item is, as a percentage. Each multibuy deal appears once. "Any 2 for $X" across nine flavours counts as one fake, shown as "(+8 more in this offer)". This sheet only includes fakes whose previous price was recorded in the last 12 weeks.
- **Coles**, **Woolworths**, **Liquorland**: every multibuy special at that store, fakes first. Fakes are highlighted in red. Each column header has a filter.

Liquorland's online shop runs on coles.com.au, so every Liquorland product also appears on the Coles sheet at the same price. The Liquorland sheet is just the liquor products.

## The table at the top of each store sheet

This table only counts that store's fake specials. It shows when each fake's previous price was recorded, which tells you how fresh the comparison is.

A fake compared against last fortnight's price is strong evidence. A fake compared against a price from two years ago is weaker, because prices change over time.

"Past 2 weeks" is also part of the current year. Because of that overlap, each row adds up to more than 100%.

## Columns on the store sheets

| Column | Meaning |
|---|---|
| link | The product page on the store's website. |
| product, size | The product name and pack size. |
| Offer | The deal as the store describes it, for example "2 for $12". |
| current $ | Today's shelf price for one item. |
| saving each $ | How much less each item costs on the deal than at today's shelf price. This is the saving the store advertises. |
| each on offer $ | The deal price divided by the number of items. |
| previous price $ | The most recent recorded shelf price that differs from today's. This is usually the price before the latest change. |
| previous date | When that previous price was recorded. |
| dearer each $ | How much more each item costs on the deal than at the previous price. A negative number means the deal really is cheaper. |
| dearer % | The same figure as a percentage of the previous price. |
| 12-wk low $ | The lowest shelf price recorded in the last 12 weeks. |
| verdict | See below. |

The Top 10 sheet shows a selection of these columns, plus the store and its rank.

## Verdicts

| Verdict | Meaning |
|---|---|
| FAKE: dearer than previous price | Each item on the deal costs more than the previous shelf price. |
| worse than 12-week low | The deal beats the previous price, but the product was cheaper at some point in the last 12 weeks. |
| genuine | The deal is at or below both the previous price and the 12-week low. |
| no history | No price history was found, so the deal can't be checked. |

## Limitations

- All prices are online prices on the scan date. Prices in your local store may differ.
- Price history is recorded roughly once a week. A short price change between recordings can be missed.
- "Genuine" only means the deal is not dearer than recent prices. It does not mean the saving is large.

## Sources

The specials come from each store's website on the scan date:

- **Coles**: specials filtered to multi-buy.
- **Woolworths**: the "Buy More Save More" specials.
- **Liquorland**: the multi-buy filter on coles.com.au/browse/liquorland.

Price history comes from a third-party database that records each product's shelf price over time.
