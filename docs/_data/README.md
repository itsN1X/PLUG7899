Example.csv
```
TS, AssetIDX, AsetNAME, AssetQTYnet, AssetQTYdel
1525808983, 0x0000, BTC_bitcoin, 0.00001000, 0
1525808984, 0x0001, BNC_bracoin, 0.10000000, 0
1525808985, 0x0002, BCN_bytcoin, 1000.0000000, 0
```

### To determine the structural pots' evolution:

#### Level0:
```
---outer
```

#### Level1
```
outer
  |---pots
```

#### Level2
```
outer
  |---pots
    |---Pot0x01
    |---Pot0x02
    |---Pot0x03
```

#### Level3
```
outer
  |---pots
    |---Pot0x01
    |---Pot0x02
      |--QTYatTX0x00
      |--QTYatTX0x01
    |---Pot0x03
      |--QTYatTX0x00
      |--QTYatTX0x01
      |--QTYatTX0x02
      |--QTYatTX0x03
```

## FUNNTY:
It really doesn't matter as its' a mere speculation!
