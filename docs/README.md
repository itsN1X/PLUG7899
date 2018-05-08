#### (C) 2018 its[N1X](https://n1x.site) #et7899

# itsN1X / PLUG7899

## Structure
### Basics
To plot against time, the appreciation in assets.

### Endpoints
 - [ ] Get the ***:1***`quote-RT.$ASSET` from a live API, v2+ only.
 - [ ] Then, fetch from an internal `Db`, ***:2***`qty-UTC.$ASSET`.
 - [ ] Finally, plot `X,Y` as structed:
    - `X`==`RT`
    - `Y`==F(`X`), such that:
      ```
      for each $ette in RT
      {
        ASSval[$ette] = RTZ.qty[$ette] * RTZ.price[$ette];
         
### Eased One:
 - et1440 or Simply put the `Z` of `UTC`, as in `$date --date +%s` >> `1525806148` as on `ET7899`, IS THE ***:X*** `-axis`.
 - `qty[$date +%s]` is the QTY at any `$date +%s`.
 - `quo[$date +%s]` is the QUOTE at a `$date +%s`.
 - `ASVA[$date +%s]` = `qty[$date +%s]` `*` `quo[$date +%s]`
 NOTE: That the NoSQL ought to conatin an extensive `$ITEM.[$date +%s]` mapping.
