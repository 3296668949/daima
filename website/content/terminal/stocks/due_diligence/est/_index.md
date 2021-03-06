```
usage: est [-h] [--export {csv,json,xlsx}]
```

Yearly estimates and quarter earnings/revenues. [Source: Business Insider]

```
optional arguments:
  -h, --help            show this help message
  --export {csv,json,xlsx}
                        Export raw data into csv, json, xlsx
```

Example:
```
2022 Feb 16, 04:28 (✨) /stocks/dd/ $ est
                              Annual Earnings Estimates
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━┳━━━━━━━━━┳━━━━━━━━━┳━━━━━━━━━━┳━━━━━━━━━━┓
┃                                ┃ 2022    ┃ 2023    ┃ 2024    ┃ 2025     ┃ 2026     ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━╇━━━━━━━━━╇━━━━━━━━━╇━━━━━━━━━━╇━━━━━━━━━━┩
│ Revenue                        │ 198,840 │ 227,368 │ 258,184 │ 304,349  │ 329,924  │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Dividend                       │ -       │ -       │ 2.57    │ 3.16     │ -        │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Dividend Yield (in %)          │ 0.79 %  │ 0.79 %  │ 0.86 %  │ 1.05 %   │ -        │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ EPS                            │ 9.38    │ 10.79   │ 12.56   │ 15.45    │ 18.44    │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ P/E Ratio                      │ 31.96   │ 27.79   │ 23.87   │ 19.40    │ 16.26    │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ EBIT                           │ 84,138  │ 96,475  │ 113,177 │ -        │ 147,282  │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ EBITDA                         │ 99,584  │ 115,199 │ 132,683 │ 104,977  │ -        │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Net Profit                     │ -       │ -       │ -       │ 96,935   │ -        │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Net Profit Adjusted            │ 70,912  │ 80,815  │ 93,717  │ 96,935   │ -        │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Pre-Tax Profit                 │ -       │ -       │ -       │ 113,454  │ -        │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Net Profit (Adjusted)          │ -       │ -       │ -       │ -        │ -        │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ EPS (Non-GAAP) ex. SOE         │ 9.38    │ 10.79   │ 12.56   │ 15.45    │ 18.44    │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ EPS (GAAP)                     │ -       │ -       │ -       │ 17.40    │ 18.27    │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Gross Income                   │ 136,567 │ 155,747 │ 179,297 │ 191,558  │ -        │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Cash Flow from Investing       │ -21,317 │ -29,939 │ -34,696 │ -36,887  │ -        │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Cash Flow from Operations      │ 91,127  │ 107,754 │ 122,969 │ 123,564  │ -        │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Cash Flow from Financing       │ -49,957 │ -49,910 │ -54,405 │ -57,207  │ -        │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Cash Flow per Share            │ 11.46   │ 14.30   │ 16.69   │ -        │ -        │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Free Cash Flow                 │ 64,929  │ 76,285  │ 88,074  │ 114,306  │ 136,804  │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Free Cash Flow per Share       │ 8.48    │ 10.04   │ 11.82   │ 11.77    │ -        │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Book Value per Share           │ 24.31   │ 29.34   │ 36.58   │ -        │ -        │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Net Debt                       │ -       │ -       │ -       │ -173,383 │ -228,921 │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Research & Development Exp.    │ 23,771  │ 26,576  │ 29,532  │ 32,650   │ -        │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Capital Expenditure            │ -       │ -       │ -       │ 36,887   │ -        │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Selling, General & Admin. Exp. │ 28,218  │ 31,017  │ 32,224  │ -        │ -        │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Shareholder’s Equity           │ 175,057 │ 214,492 │ 253,332 │ 243,941  │ -        │
├────────────────────────────────┼─────────┼─────────┼─────────┼──────────┼──────────┤
│ Total Assets                   │ 368,815 │ 418,601 │ 427,972 │ 400,662  │ -        │
└────────────────────────────────┴─────────┴─────────┴─────────┴──────────┴──────────┘

                                         Quarterly Earnings Estimates
┏━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━┓
┃                  ┃ Previous Quarter ┃ Current Quarter ┃ Next Quarter    ┃ Current Year    ┃ Next Year       ┃
┡━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━┩
│ Date             │ -                │ -               │ ending 06/29/22 │ ending 06/29/22 │ ending 06/29/23 │
├──────────────────┼──────────────────┼─────────────────┼─────────────────┼─────────────────┼─────────────────┤
│ No. of Analysts  │ -                │ -               │ -               │ -               │ -               │
├──────────────────┼──────────────────┼─────────────────┼─────────────────┼─────────────────┼─────────────────┤
│ Average Estimate │ -                │ -               │ -               │ -               │ -               │
├──────────────────┼──────────────────┼─────────────────┼─────────────────┼─────────────────┼─────────────────┤
│ Year Ago         │ -                │ -               │ -               │ -               │ -               │
├──────────────────┼──────────────────┼─────────────────┼─────────────────┼─────────────────┼─────────────────┤
│ Publish Date     │ -                │ -               │ -               │ -               │ -               │
└──────────────────┴──────────────────┴─────────────────┴─────────────────┴─────────────────┴─────────────────┘

                                          Quarterly Revenue Estimates
┏━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━┓
┃                  ┃ Previous Quarter ┃ Current Quarter ┃ Next Quarter    ┃ Current Year    ┃ Next Year       ┃
┡━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━┩
│ Date             │ -                │ -               │ ending 06/29/22 │ ending 06/29/22 │ ending 06/29/23 │
├──────────────────┼──────────────────┼─────────────────┼─────────────────┼─────────────────┼─────────────────┤
│ No. of Analysts  │ -                │ -               │ -               │ -               │ -               │
├──────────────────┼──────────────────┼─────────────────┼─────────────────┼─────────────────┼─────────────────┤
│ Average Estimate │ -                │ -               │ -               │ -               │ -               │
├──────────────────┼──────────────────┼─────────────────┼─────────────────┼─────────────────┼─────────────────┤
│ Year Ago         │ -                │ -               │ -               │ -               │ -               │
├──────────────────┼──────────────────┼─────────────────┼─────────────────┼─────────────────┼─────────────────┤
│ Publish Date     │ -                │ -               │ -               │ -               │ -               │
└──────────────────┴──────────────────┴─────────────────┴─────────────────┴─────────────────┴─────────────────┘
```
