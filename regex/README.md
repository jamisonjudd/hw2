# BIDS-style file names

- sub-*1000*\_task-*nback*\_acq-*singleband*\_run-*03*\_*bold*
- sub-*EXP23*\_task-*rest*\_acq-*multiband*\_run-*01*\_*bold*

```
sub(\-(\w+)\_)task(\-(\w+)\_)acq\-(\w+)\_run\-(\d+)_(.*)
```
Italicized sections captured with:
- Group 2
- Group 4
- Group 5
- Group 6
- Group 7

# Phone numbers

- +1 *123*\-*456*\-*7891*
- (*123*) *555*-*5555*
- *860*.*865*.*9805*
- 1-*800*-*865*-*9805*

```
(\d{3}).+(\d{3}).+(\d{4})
```

Area code, exchange, and number captured respectively with:
- Group 1
- Group 2
- Group 3
