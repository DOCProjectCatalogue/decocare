## START analysis/sarak/raw//ReadHistoryData-page-4.data
#### STOPPING DOUBLE NULLS @ 1015, found 7 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x19 0x78                                  .x
##### DEBUG DECIMAL
             25  120
#### RECORD 0 BolusWizard 2013-08-27T12:33:02 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 122,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 0.0,
 'carb_input': 15,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 0.0,
 'sensitivity': 120,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 48}
```
    op hex (2)
    0000   0x5b 0x7a                                  [z
    decimal
             91  122
    datetime (2013-08-27T12:33:02)
    0000   0x82 0x21 0x0c 0x1b 0x0d                   .!...
    body (15)
    hex
    0000   0x0f 0x50 0x00 0x78 0x3c 0x64 0x00 0x00    .P.x<d..
    0008   0x30 0x00 0x00 0x00 0x00 0x30 0x78         0....0x
    decimal
             15   80    0  120   60  100    0    0
             48    0    0    0    0   48  120
    HOUR BITS: [0, 0, 1]
#### RECORD 1 Bolus 2013-08-27T12:33:02 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 4.8, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x30 0x00 0x30 0x00 0x00 0x00    ..0.0...
    decimal
              1    0   48    0   48    0    0    0
    datetime (2013-08-27T12:33:02)
    0000   0x82 0x21 0x4c 0x1b 0x0d                   .!L..
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 2 CalBGForPH 2013-08-27T13:18:56 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 127}
```
    op hex (2)
    0000   0x0a 0x7f                                  ..
    decimal
             10  127
    datetime (2013-08-27T13:18:56)
    0000   0xb8 0x12 0x2d 0x1b 0x0d                   ..-..
    body (0)

#### RECORD 3 BolusWizard 2013-08-27T13:19:01 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 127,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 4.0,
 'carb_input': 13,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 0.4,
 'sensitivity': 120,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 40}
```
    op hex (2)
    0000   0x5b 0x7f                                  [.
    decimal
             91  127
    datetime (2013-08-27T13:19:01)
    0000   0x81 0x13 0x0d 0x1b 0x0d                   .....
    body (15)
    hex
    0000   0x0d 0x50 0x00 0x78 0x3c 0x64 0x04 0x00    .P.x<d..
    0008   0x28 0x00 0x00 0x28 0x00 0x28 0x78         (..(.(x
    decimal
             13   80    0  120   60  100    4    0
             40    0    0   40    0   40  120

#### RECORD 4 UnabsorbedInsulinBolus unknown head[5], body[0] op[0x5c]
###### DECODED
```python
[{'age': 46, 'amount': 1.2, 'curve': 192}]
```
    op hex (5)
    0000   0x5c 0x05 0x30 0x2e 0xc0                   \.0..
    decimal
             92    5   48   46  192
    datetime (unknown)

    body (0)

#### RECORD 5 Bolus 2013-08-27T13:19:01 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 4.0, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x28 0x00 0x28 0x00 0x28 0x00    ..(.(.(.
    decimal
              1    0   40    0   40    0   40    0
    datetime (2013-08-27T13:19:01)
    0000   0x81 0x13 0x4d 0x1b 0x0d                   ..M..
    body (0)

#### RECORD 6 CalBGForPH 2013-08-27T14:29:57 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 294}
```
    op hex (2)
    0000   0x0a 0x26                                  .&
    decimal
             10   38
    datetime (2013-08-27T14:29:57)
    0000   0xb9 0x1d 0x2e 0x1b 0x8d                   .....
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 7 BolusWizard 2013-08-27T14:29:59 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 294,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 3.6,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 11.6,
 'sensitivity': 120,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0x26                                  [&
    decimal
             91   38
    datetime (2013-08-27T14:29:59)
    0000   0xbb 0x1d 0x0e 0x1b 0x0d                   .....
    body (15)
    hex
    0000   0x00 0x51 0x00 0x78 0x3c 0x64 0x74 0x00    .Q.x<dt.
    0008   0x00 0x00 0x00 0x24 0x00 0x50 0x78         ...$.Px
    decimal
              0   81    0  120   60  100  116    0
              0    0    0   36    0   80  120

#### RECORD 8 UnabsorbedInsulinBolus unknown head[8], body[0] op[0x5c]
###### DECODED
```python
[{'age': 76, 'amount': 1.0, 'curve': 192},
 {'age': 116, 'amount': 1.2, 'curve': 192}]
```
    op hex (8)
    0000   0x5c 0x08 0x28 0x4c 0xc0 0x30 0x74 0xc0    \.(L.0t.
    decimal
             92    8   40   76  192   48  116  192
    datetime (unknown)

    body (0)

#### RECORD 9 Bolus 2013-08-27T14:29:59 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 8.0, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x50 0x00 0x50 0x00 0x24 0x00    ..P.P.$.
    decimal
              1    0   80    0   80    0   36    0
    datetime (2013-08-27T14:29:59)
    0000   0xbb 0x1d 0x4e 0x1b 0x0d                   ..N..
    body (0)

#### RECORD 10 CalBGForPH 2013-08-27T23:24:46 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 256}
```
    op hex (2)
    0000   0x0a 0x00                                  ..
    decimal
             10    0
    datetime (2013-08-27T23:24:46)
    0000   0xae 0x18 0x37 0x1b 0x8d                   ..7..
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 11 BolusWizard 2013-08-27T23:24:50 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 256,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 0.0,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 8.8,
 'sensitivity': 100,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2013-08-27T23:24:50)
    0000   0xb2 0x18 0x17 0x1b 0x0d                   .....
    body (15)
    hex
    0000   0x00 0x51 0x00 0x64 0x3c 0x64 0x58 0x00    .Q.d<dX.
    0008   0x00 0x00 0x00 0x00 0x00 0x58 0x78         .....Xx
    decimal
              0   81    0  100   60  100   88    0
              0    0    0    0    0   88  120

#### RECORD 12 Bolus 2013-08-27T23:24:50 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 8.8, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x58 0x00 0x58 0x00 0x00 0x00    ..X.X...
    decimal
              1    0   88    0   88    0    0    0
    datetime (2013-08-27T23:24:50)
    0000   0xb2 0x18 0x57 0x1b 0x0d                   ..W..
    body (0)

#### RECORD 13 BasalProfileStart 2013-08-28T00:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x00                                  {.
    decimal
            123    0
    datetime (2013-08-28T00:00:00)
    0000   0x80 0x00 0x00 0x1c 0x0d                   .....
    body (3)
    hex
    0000   0x00 0x1d 0x00                             ...
    decimal
              0   29    0

#### RECORD 14 MResultTotals 2013-08-28T00:00:00 head[5], body[3] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x03 0xdc                   .....
    decimal
              7    0    0    3  220
    datetime (2013-08-28T00:00:00)
    0000   0x9b 0x0d                                  ..
    body (3)
    hex
    0000   0x00 0x00 0x00                             ...
    decimal
              0    0    0

#### RECORD 15 Sara6E 2013-08-28T00:00:00 head[1], body[49] op[0x6e]

    op hex (1)
    0000   0x6e                                       n
    decimal
            110
    datetime (2013-08-28T00:00:00)
    0000   0x9b 0x0d                                  ..
    body (49)
    hex
    0000   0x05 0x00 0xc8 0x00 0x00 0x04 0x00 0x00    ........
    0008   0x03 0xdc 0x02 0xdc 0x4a 0x01 0x00 0x1a    ....J...
    0010   0x00 0x1c 0x00 0x58 0x00 0xa8 0x00 0x00    ...X....
    0018   0x00 0x00 0x02 0x02 0x00 0x00 0x04 0x00    ........
    0020   0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x7a    .......z
    0028   0x26 0x00 0x00 0x00 0x00 0x00 0x00 0x00    &.......
    0030   0x00                                       .
    decimal
              5    0  200    0    0    4    0    0
              3  220    2  220   74    1    0   26
              0   28    0   88    0  168    0    0
              0    0    2    2    0    0    4    0
              0    0    0    0    0    0    0  122
             38    0    0    0    0    0    0    0
              0

#### RECORD 16 BasalProfileStart 2013-08-28T04:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x01                                  {.
    decimal
            123    1
    datetime (2013-08-28T04:00:00)
    0000   0x80 0x00 0x04 0x1c 0x0d                   .....
    body (3)
    hex
    0000   0x08 0x21 0x00                             .!.
    decimal
              8   33    0

#### RECORD 17 BasalProfileStart 2013-08-28T08:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x02                                  {.
    decimal
            123    2
    datetime (2013-08-28T08:00:00)
    0000   0x80 0x00 0x08 0x1c 0x0d                   .....
    body (3)
    hex
    0000   0x10 0x22 0x00                             .".
    decimal
             16   34    0

#### RECORD 18 CalBGForPH 2013-08-28T08:59:44 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 107}
```
    op hex (2)
    0000   0x0a 0x6b                                  .k
    decimal
             10  107
    datetime (2013-08-28T08:59:44)
    0000   0xac 0x3b 0x28 0x1c 0x0d                   .;(..
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 19 BolusWizard 2013-08-28T08:59:58 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 107,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 0.0,
 'carb_input': 26,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 0.0,
 'sensitivity': 120,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 84}
```
    op hex (2)
    0000   0x5b 0x6b                                  [k
    decimal
             91  107
    datetime (2013-08-28T08:59:58)
    0000   0xba 0x3b 0x08 0x1c 0x0d                   .;...
    body (15)
    hex
    0000   0x1a 0x50 0x00 0x78 0x3c 0x64 0x00 0x00    .P.x<d..
    0008   0x54 0x00 0x00 0x00 0x00 0x54 0x78         T....Tx
    decimal
             26   80    0  120   60  100    0    0
             84    0    0    0    0   84  120
    HOUR BITS: [0, 0, 1]
#### RECORD 20 Bolus 2013-08-28T08:59:58 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 8.4, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x54 0x00 0x54 0x00 0x00 0x00    ..T.T...
    decimal
              1    0   84    0   84    0    0    0
    datetime (2013-08-28T08:59:58)
    0000   0xba 0x3b 0x48 0x1c 0x0d                   .;H..
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 21 CalBGForPH 2013-08-28T11:09:05 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 264}
```
    op hex (2)
    0000   0x0a 0x08                                  ..
    decimal
             10    8
    datetime (2013-08-28T11:09:05)
    0000   0x85 0x09 0x2b 0x1c 0x8d                   ..+..
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 22 BolusWizard 2013-08-28T11:09:06 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 264,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 1.6,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 9.6,
 'sensitivity': 120,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0x08                                  [.
    decimal
             91    8
    datetime (2013-08-28T11:09:06)
    0000   0x86 0x09 0x0b 0x1c 0x0d                   .....
    body (15)
    hex
    0000   0x00 0x51 0x00 0x78 0x3c 0x64 0x60 0x00    .Q.x<d`.
    0008   0x00 0x00 0x00 0x10 0x00 0x50 0x78         .....Px
    decimal
              0   81    0  120   60  100   96    0
              0    0    0   16    0   80  120

#### RECORD 23 UnabsorbedInsulinBolus unknown head[5], body[0] op[0x5c]
###### DECODED
```python
[{'age': 136, 'amount': 2.1, 'curve': 192}]
```
    op hex (5)
    0000   0x5c 0x05 0x54 0x88 0xc0                   \.T..
    decimal
             92    5   84  136  192
    datetime (unknown)

    body (0)

#### RECORD 24 Bolus 2013-08-28T11:09:07 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 8.0, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x50 0x00 0x50 0x00 0x10 0x00    ..P.P...
    decimal
              1    0   80    0   80    0   16    0
    datetime (2013-08-28T11:09:07)
    0000   0x87 0x09 0x4b 0x1c 0x0d                   ..K..
    body (0)

#### RECORD 25 BasalProfileStart 2013-08-28T12:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x03                                  {.
    decimal
            123    3
    datetime (2013-08-28T12:00:00)
    0000   0x80 0x00 0x0c 0x1c 0x0d                   .....
    body (3)
    hex
    0000   0x18 0x1d 0x00                             ...
    decimal
             24   29    0

#### RECORD 26 CalBGForPH 2013-08-28T12:47:24 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 146}
```
    op hex (2)
    0000   0x0a 0x92                                  ..
    decimal
             10  146
    datetime (2013-08-28T12:47:24)
    0000   0x98 0x2f 0x2c 0x1c 0x0d                   ./,..
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 27 BolusWizard 2013-08-28T12:47:53 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 146,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 2.8,
 'carb_input': 39,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 1.6,
 'sensitivity': 120,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 128}
```
    op hex (2)
    0000   0x5b 0x92                                  [.
    decimal
             91  146
    datetime (2013-08-28T12:47:53)
    0000   0xb5 0x2f 0x0c 0x1c 0x0d                   ./...
    body (15)
    hex
    0000   0x27 0x50 0x00 0x78 0x3c 0x64 0x10 0x00    'P.x<d..
    0008   0x80 0x00 0x00 0x1c 0x00 0x80 0x78         ......x
    decimal
             39   80    0  120   60  100   16    0
            128    0    0   28    0  128  120
    HOUR BITS: [0, 0, 1]
#### RECORD 28 UnabsorbedInsulinBolus unknown head[8], body[0] op[0x5c]
###### DECODED
```python
[{'age': 104, 'amount': 2.0, 'curve': 192},
 {'age': 234, 'amount': 2.1, 'curve': 192}]
```
    op hex (8)
    0000   0x5c 0x08 0x50 0x68 0xc0 0x54 0xea 0xc0    \.Ph.T..
    decimal
             92    8   80  104  192   84  234  192
    datetime (unknown)

    body (0)

#### RECORD 29 Bolus 2013-08-28T12:47:53 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 12.8, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x80 0x00 0x80 0x00 0x1c 0x00    ........
    decimal
              1    0  128    0  128    0   28    0
    datetime (2013-08-28T12:47:53)
    0000   0xb5 0x2f 0x4c 0x1c 0x0d                   ./L..
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 30 CalBGForPH 2013-08-28T16:30:14 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 216}
```
    op hex (2)
    0000   0x0a 0xd8                                  ..
    decimal
             10  216
    datetime (2013-08-28T16:30:14)
    0000   0x8e 0x1e 0x30 0x1c 0x0d                   ..0..
    body (0)

#### RECORD 31 BolusWizard 2013-08-28T16:30:17 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 216,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 0.0,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 6.4,
 'sensitivity': 120,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0xd8                                  [.
    decimal
             91  216
    datetime (2013-08-28T16:30:17)
    0000   0x91 0x1e 0x10 0x1c 0x0d                   .....
    body (15)
    hex
    0000   0x00 0x50 0x00 0x78 0x3c 0x64 0x40 0x00    .P.x<d@.
    0008   0x00 0x00 0x00 0x00 0x00 0x40 0x78         .....@x
    decimal
              0   80    0  120   60  100   64    0
              0    0    0    0    0   64  120

#### RECORD 32 UnabsorbedInsulinBolus unknown head[11], body[0] op[0x5c]
###### DECODED
```python
[{'age': 227, 'amount': 3.2, 'curve': 192},
 {'age': 71, 'amount': 2.0, 'curve': 208},
 {'age': 201, 'amount': 2.1, 'curve': 208}]
```
    op hex (11)
    0000   0x5c 0x0b 0x80 0xe3 0xc0 0x50 0x47 0xd0    \....PG.
    0008   0x54 0xc9 0xd0                             T..
    decimal
             92   11  128  227  192   80   71  208
             84  201  208
    datetime (unknown)

    body (0)

#### RECORD 33 Bolus 2013-08-28T16:30:17 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 6.4, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x40 0x00 0x40 0x00 0x00 0x00    ..@.@...
    decimal
              1    0   64    0   64    0    0    0
    datetime (2013-08-28T16:30:17)
    0000   0x91 0x1e 0x50 0x1c 0x0d                   ..P..
    body (0)

#### RECORD 34 CalBGForPH 2013-08-28T19:18:27 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 106}
```
    op hex (2)
    0000   0x0a 0x6a                                  .j
    decimal
             10  106
    datetime (2013-08-28T19:18:27)
    0000   0x9b 0x12 0x33 0x1c 0x0d                   ..3..
    body (0)

#### RECORD 35 BolusWizard 2013-08-28T19:18:44 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 106,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 0.4,
 'carb_input': 17,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 0.0,
 'sensitivity': 100,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 68}
```
    op hex (2)
    0000   0x5b 0x6a                                  [j
    decimal
             91  106
    datetime (2013-08-28T19:18:44)
    0000   0xac 0x12 0x13 0x1c 0x0d                   .....
    body (15)
    hex
    0000   0x11 0x50 0x00 0x64 0x3c 0x64 0x00 0x00    .P.d<d..
    0008   0x44 0x00 0x00 0x04 0x00 0x44 0x78         D....Dx
    decimal
             17   80    0  100   60  100    0    0
             68    0    0    4    0   68  120

#### RECORD 36 UnabsorbedInsulinBolus unknown head[8], body[0] op[0x5c]
###### DECODED
```python
[{'age': 175, 'amount': 1.6, 'curve': 192},
 {'age': 139, 'amount': 3.2, 'curve': 208}]
```
    op hex (8)
    0000   0x5c 0x08 0x40 0xaf 0xc0 0x80 0x8b 0xd0    \.@.....
    decimal
             92    8   64  175  192  128  139  208
    datetime (unknown)

    body (0)

#### RECORD 37 Bolus 2013-08-28T19:18:44 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 6.8, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x44 0x00 0x44 0x00 0x04 0x00    ..D.D...
    decimal
              1    0   68    0   68    0    4    0
    datetime (2013-08-28T19:18:44)
    0000   0xac 0x12 0x53 0x1c 0x0d                   ..S..
    body (0)

#### RECORD 38 CalBGForPH 2013-08-28T22:42:58 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 102}
```
    op hex (2)
    0000   0x0a 0x66                                  .f
    decimal
             10  102
    datetime (2013-08-28T22:42:58)
    0000   0xba 0x2a 0x36 0x1c 0x0d                   .*6..
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 39 BolusWizard 2013-08-28T22:43:04 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 102,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 0.0,
 'carb_input': 22,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 0.0,
 'sensitivity': 100,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 88}
```
    op hex (2)
    0000   0x5b 0x66                                  [f
    decimal
             91  102
    datetime (2013-08-28T22:43:04)
    0000   0x84 0x2b 0x16 0x1c 0x0d                   .+...
    body (15)
    hex
    0000   0x16 0x50 0x00 0x64 0x3c 0x64 0x00 0x00    .P.d<d..
    0008   0x58 0x00 0x00 0x00 0x00 0x58 0x78         X....Xx
    decimal
             22   80    0  100   60  100    0    0
             88    0    0    0    0   88  120
    HOUR BITS: [0, 0, 1]
#### RECORD 40 UnabsorbedInsulinBolus unknown head[8], body[0] op[0x5c]
###### DECODED
```python
[{'age': 210, 'amount': 1.7, 'curve': 192},
 {'age': 124, 'amount': 1.6, 'curve': 208}]
```
    op hex (8)
    0000   0x5c 0x08 0x44 0xd2 0xc0 0x40 0x7c 0xd0    \.D..@|.
    decimal
             92    8   68  210  192   64  124  208
    datetime (unknown)

    body (0)

#### RECORD 41 Bolus 2013-08-28T22:43:04 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 8.8, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x58 0x00 0x58 0x00 0x00 0x00    ..X.X...
    decimal
              1    0   88    0   88    0    0    0
    datetime (2013-08-28T22:43:04)
    0000   0x84 0x2b 0x56 0x1c 0x0d                   .+V..
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 42 BasalProfileStart 2013-08-29T00:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x00                                  {.
    decimal
            123    0
    datetime (2013-08-29T00:00:00)
    0000   0x80 0x00 0x00 0x1d 0x0d                   .....
    body (3)
    hex
    0000   0x00 0x1d 0x00                             ...
    decimal
              0   29    0

#### RECORD 43 MResultTotals 2013-08-29T00:00:00 head[5], body[3] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x04 0xdc                   .....
    decimal
              7    0    0    4  220
    datetime (2013-08-29T00:00:00)
    0000   0x9c 0x0d                                  ..
    body (3)
    hex
    0000   0x00 0x00 0x00                             ...
    decimal
              0    0    0

#### RECORD 44 Sara6E 2013-08-29T00:00:00 head[1], body[49] op[0x6e]

    op hex (1)
    0000   0x6e                                       n
    decimal
            110
    datetime (2013-08-29T00:00:00)
    0000   0x9c 0x0d                                  ..
    body (49)
    hex
    0000   0x05 0x00 0x9d 0x00 0x00 0x06 0x00 0x00    ........
    0008   0x04 0xdc 0x02 0xdc 0x3b 0x02 0x00 0x29    ....;..)
    0010   0x00 0x68 0x01 0x70 0x00 0x90 0x00 0x00    .h.p....
    0018   0x00 0x00 0x04 0x02 0x00 0x00 0x04 0x00    ........
    0020   0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x66    .......f
    0028   0x08 0x00 0x00 0x00 0x00 0x00 0x00 0x00    ........
    0030   0x00                                       .
    decimal
              5    0  157    0    0    6    0    0
              4  220    2  220   59    2    0   41
              0  104    1  112    0  144    0    0
              0    0    4    2    0    0    4    0
              0    0    0    0    0    0    0  102
              8    0    0    0    0    0    0    0
              0

#### RECORD 45 BasalProfileStart 2013-08-29T04:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x01                                  {.
    decimal
            123    1
    datetime (2013-08-29T04:00:00)
    0000   0x80 0x00 0x04 0x1d 0x0d                   .....
    body (3)
    hex
    0000   0x08 0x21 0x00                             .!.
    decimal
              8   33    0

#### RECORD 46 CalBGForPH 2013-08-29T04:54:09 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 265}
```
    op hex (2)
    0000   0x0a 0x09                                  ..
    decimal
             10    9
    datetime (2013-08-29T04:54:09)
    0000   0x89 0x36 0x24 0x1d 0x8d                   .6$..
    body (0)
    HOUR BITS: [0, 0, 1] YEAR BITS: [1, 0, 0, 0]
#### RECORD 47 BolusWizard 2013-08-29T04:54:12 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 110,
 '_byte[7]': 0,
 'bg': 265,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 0.0,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 1.4,
 'food_estimate': 8.8,
 'sensitivity': 120,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0x09                                  [.
    decimal
             91    9
    datetime (2013-08-29T04:54:12)
    0000   0x8c 0x36 0x04 0x1d 0x0d                   .6...
    body (15)
    hex
    0000   0x00 0x51 0x00 0x78 0x3c 0x6e 0x58 0x00    .Q.x<nX.
    0008   0x00 0x00 0x00 0x00 0x00 0x58 0x82         .....X.
    decimal
              0   81    0  120   60  110   88    0
              0    0    0    0    0   88  130
    HOUR BITS: [0, 0, 1]
#### RECORD 48 UnabsorbedInsulinBolus unknown head[5], body[0] op[0x5c]
###### DECODED
```python
[{'age': 115, 'amount': 2.2, 'curve': 208}]
```
    op hex (5)
    0000   0x5c 0x05 0x58 0x73 0xd0                   \.Xs.
    decimal
             92    5   88  115  208
    datetime (unknown)

    body (0)

#### RECORD 49 Bolus 2013-08-29T04:54:12 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 8.8, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x58 0x00 0x58 0x00 0x00 0x00    ..X.X...
    decimal
              1    0   88    0   88    0    0    0
    datetime (2013-08-29T04:54:12)
    0000   0x8c 0x36 0x44 0x1d 0x0d                   .6D..
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 50 BasalProfileStart 2013-08-29T08:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x02                                  {.
    decimal
            123    2
    datetime (2013-08-29T08:00:00)
    0000   0x80 0x00 0x08 0x1d 0x0d                   .....
    body (3)
    hex
    0000   0x10 0x22 0x00                             .".
    decimal
             16   34    0

#### RECORD 51 CalBGForPH 2013-08-29T10:53:43 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 101}
```
    op hex (2)
    0000   0x0a 0x65                                  .e
    decimal
             10  101
    datetime (2013-08-29T10:53:43)
    0000   0xab 0x35 0x2a 0x1d 0x0d                   .5*..
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 52 BolusWizard 2013-08-29T10:53:50 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 101,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 0.0,
 'carb_input': 17,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 0.0,
 'sensitivity': 120,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 56}
```
    op hex (2)
    0000   0x5b 0x65                                  [e
    decimal
             91  101
    datetime (2013-08-29T10:53:50)
    0000   0xb2 0x35 0x0a 0x1d 0x0d                   .5...
    body (15)
    hex
    0000   0x11 0x50 0x00 0x78 0x3c 0x64 0x00 0x00    .P.x<d..
    0008   0x38 0x00 0x00 0x00 0x00 0x38 0x78         8....8x
    decimal
             17   80    0  120   60  100    0    0
             56    0    0    0    0   56  120
    HOUR BITS: [0, 0, 1]
#### RECORD 53 UnabsorbedInsulinBolus unknown head[5], body[0] op[0x5c]
###### DECODED
```python
[{'age': 104, 'amount': 2.2, 'curve': 208}]
```
    op hex (5)
    0000   0x5c 0x05 0x58 0x68 0xd0                   \.Xh.
    decimal
             92    5   88  104  208
    datetime (unknown)

    body (0)

#### RECORD 54 Bolus 2013-08-29T10:53:50 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 5.6, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x38 0x00 0x38 0x00 0x00 0x00    ..8.8...
    decimal
              1    0   56    0   56    0    0    0
    datetime (2013-08-29T10:53:50)
    0000   0xb2 0x35 0x4a 0x1d 0x0d                   .5J..
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 55 BasalProfileStart 2013-08-29T12:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x03                                  {.
    decimal
            123    3
    datetime (2013-08-29T12:00:00)
    0000   0x80 0x00 0x0c 0x1d 0x0d                   .....
    body (3)
    hex
    0000   0x18 0x1d 0x00                             ...
    decimal
             24   29    0

#### RECORD 56 CalBGForPH 2013-08-29T12:09:18 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 220}
```
    op hex (2)
    0000   0x0a 0xdc                                  ..
    decimal
             10  220
    datetime (2013-08-29T12:09:18)
    0000   0x92 0x09 0x2c 0x1d 0x0d                   ..,..
    body (0)

#### RECORD 57 BolusWizard 2013-08-29T12:09:23 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 220,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 3.2,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 6.4,
 'sensitivity': 120,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0xdc                                  [.
    decimal
             91  220
    datetime (2013-08-29T12:09:23)
    0000   0x97 0x09 0x0c 0x1d 0x0d                   .....
    body (15)
    hex
    0000   0x00 0x50 0x00 0x78 0x3c 0x64 0x40 0x00    .P.x<d@.
    0008   0x00 0x00 0x00 0x20 0x00 0x20 0x78         ... . x
    decimal
              0   80    0  120   60  100   64    0
              0    0    0   32    0   32  120

#### RECORD 58 UnabsorbedInsulinBolus unknown head[8], body[0] op[0x5c]
###### DECODED
```python
[{'age': 76, 'amount': 1.4, 'curve': 192},
 {'age': 180, 'amount': 2.2, 'curve': 208}]
```
    op hex (8)
    0000   0x5c 0x08 0x38 0x4c 0xc0 0x58 0xb4 0xd0    \.8L.X..
    decimal
             92    8   56   76  192   88  180  208
    datetime (unknown)

    body (0)

#### RECORD 59 Bolus 2013-08-29T12:09:23 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 3.2, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x20 0x00 0x20 0x00 0x20 0x00    .. . . .
    decimal
              1    0   32    0   32    0   32    0
    datetime (2013-08-29T12:09:23)
    0000   0x97 0x09 0x4c 0x1d 0x0d                   ..L..
    body (0)

#### RECORD 60 CalBGForPH 2013-08-29T15:06:03 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 106}
```
    op hex (2)
    0000   0x0a 0x6a                                  .j
    decimal
             10  106
    datetime (2013-08-29T15:06:03)
    0000   0x83 0x06 0x2f 0x1d 0x0d                   ../..
    body (0)

#### RECORD 61 BolusWizard 2013-08-29T15:06:15 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 106,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 0.0,
 'carb_input': 15,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 0.0,
 'sensitivity': 120,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 48}
```
    op hex (2)
    0000   0x5b 0x6a                                  [j
    decimal
             91  106
    datetime (2013-08-29T15:06:15)
    0000   0x8f 0x06 0x0f 0x1d 0x0d                   .....
    body (15)
    hex
    0000   0x0f 0x50 0x00 0x78 0x3c 0x64 0x00 0x00    .P.x<d..
    0008   0x30 0x00 0x00 0x00 0x00 0x30 0x78         0....0x
    decimal
             15   80    0  120   60  100    0    0
             48    0    0    0    0   48  120

#### RECORD 62 UnabsorbedInsulinBolus unknown head[8], body[0] op[0x5c]
###### DECODED
```python
[{'age': 183, 'amount': 0.8, 'curve': 192},
 {'age': 253, 'amount': 1.4, 'curve': 192}]
```
    op hex (8)
    0000   0x5c 0x08 0x20 0xb7 0xc0 0x38 0xfd 0xc0    \. ..8..
    decimal
             92    8   32  183  192   56  253  192
    datetime (unknown)

    body (0)

#### RECORD 63 Bolus 2013-08-29T15:06:15 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 4.8, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x30 0x00 0x30 0x00 0x00 0x00    ..0.0...
    decimal
              1    0   48    0   48    0    0    0
    datetime (2013-08-29T15:06:15)
    0000   0x8f 0x06 0x4f 0x1d 0x0d                   ..O..
    body (0)

#### RECORD 64 CalBGForPH 2013-08-29T15:26:30 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 100}
```
    op hex (2)
    0000   0x0a 0x64                                  .d
    decimal
             10  100
    datetime (2013-08-29T15:26:30)
    0000   0x9e 0x1a 0x2f 0x1d 0x0d                   ../..
    body (0)

#### RECORD 65 BolusWizard 2013-08-29T15:26:37 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 100,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 4.8,
 'carb_input': 13,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 0.0,
 'sensitivity': 120,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 40}
```
    op hex (2)
    0000   0x5b 0x64                                  [d
    decimal
             91  100
    datetime (2013-08-29T15:26:37)
    0000   0xa5 0x1a 0x0f 0x1d 0x0d                   .....
    body (15)
    hex
    0000   0x0d 0x50 0x00 0x78 0x3c 0x64 0x00 0x00    .P.x<d..
    0008   0x28 0x00 0x00 0x30 0x00 0x28 0x78         (..0.(x
    decimal
             13   80    0  120   60  100    0    0
             40    0    0   48    0   40  120

#### RECORD 66 UnabsorbedInsulinBolus unknown head[11], body[0] op[0x5c]
###### DECODED
```python
[{'age': 23, 'amount': 1.2, 'curve': 192},
 {'age': 203, 'amount': 0.8, 'curve': 192},
 {'age': 17, 'amount': 1.4, 'curve': 208}]
```
    op hex (11)
    0000   0x5c 0x0b 0x30 0x17 0xc0 0x20 0xcb 0xc0    \.0.. ..
    0008   0x38 0x11 0xd0                             8..
    decimal
             92   11   48   23  192   32  203  192
             56   17  208
    datetime (unknown)

    body (0)

#### RECORD 67 Bolus 2013-08-29T15:26:37 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 4.0, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x28 0x00 0x28 0x00 0x30 0x00    ..(.(.0.
    decimal
              1    0   40    0   40    0   48    0
    datetime (2013-08-29T15:26:37)
    0000   0xa5 0x1a 0x4f 0x1d 0x0d                   ..O..
    body (0)

#### RECORD 68 CalBGForPH 2013-08-29T19:24:17 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 236}
```
    op hex (2)
    0000   0x0a 0xec                                  ..
    decimal
             10  236
    datetime (2013-08-29T19:24:17)
    0000   0x91 0x18 0x33 0x1d 0x0d                   ..3..
    body (0)

#### RECORD 69 BolusWizard 2013-08-29T19:24:19 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 236,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 0.0,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 7.6,
 'sensitivity': 100,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0xec                                  [.
    decimal
             91  236
    datetime (2013-08-29T19:24:19)
    0000   0x93 0x18 0x13 0x1d 0x0d                   .....
    body (15)
    hex
    0000   0x00 0x50 0x00 0x64 0x3c 0x64 0x4c 0x00    .P.d<dL.
    0008   0x00 0x00 0x00 0x00 0x00 0x4c 0x78         .....Lx
    decimal
              0   80    0  100   60  100   76    0
              0    0    0    0    0   76  120

#### RECORD 70 UnabsorbedInsulinBolus unknown head[11], body[0] op[0x5c]
###### DECODED
```python
[{'age': 241, 'amount': 1.0, 'curve': 192},
 {'age': 5, 'amount': 1.2, 'curve': 208},
 {'age': 185, 'amount': 0.8, 'curve': 208}]
```
    op hex (11)
    0000   0x5c 0x0b 0x28 0xf1 0xc0 0x30 0x05 0xd0    \.(..0..
    0008   0x20 0xb9 0xd0                              ..
    decimal
             92   11   40  241  192   48    5  208
             32  185  208
    datetime (unknown)

    body (0)

#### RECORD 71 Bolus 2013-08-29T19:24:19 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 7.6, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x4c 0x00 0x4c 0x00 0x00 0x00    ..L.L...
    decimal
              1    0   76    0   76    0    0    0
    datetime (2013-08-29T19:24:19)
    0000   0x93 0x18 0x53 0x1d 0x0d                   ..S..
    body (0)

#### RECORD 72 CalBGForPH 2013-08-29T19:49:55 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 201}
```
    op hex (2)
    0000   0x0a 0xc9                                  ..
    decimal
             10  201
    datetime (2013-08-29T19:49:55)
    0000   0xb7 0x31 0x33 0x1d 0x0d                   .13..
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 73 BolusWizard 2013-08-29T19:50:04 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 201,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 7.2,
 'carb_input': 21,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 5.2,
 'sensitivity': 100,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 84}
```
    op hex (2)
    0000   0x5b 0xc9                                  [.
    decimal
             91  201
    datetime (2013-08-29T19:50:04)
    0000   0x84 0x32 0x13 0x1d 0x0d                   .2...
    body (15)
    hex
    0000   0x15 0x50 0x00 0x64 0x3c 0x64 0x34 0x00    .P.d<d4.
    0008   0x54 0x00 0x00 0x48 0x00 0x54 0x78         T..H.Tx
    decimal
             21   80    0  100   60  100   52    0
             84    0    0   72    0   84  120
    HOUR BITS: [0, 0, 1]
#### RECORD 74 UnabsorbedInsulinBolus unknown head[14], body[0] op[0x5c]
###### DECODED
```python
[{'age': 27, 'amount': 1.9, 'curve': 192},
 {'age': 11, 'amount': 1.0, 'curve': 208},
 {'age': 31, 'amount': 1.2, 'curve': 208},
 {'age': 211, 'amount': 0.8, 'curve': 208}]
```
    op hex (14)
    0000   0x5c 0x0e 0x4c 0x1b 0xc0 0x28 0x0b 0xd0    \.L..(..
    0008   0x30 0x1f 0xd0 0x20 0xd3 0xd0              0.. ..
    decimal
             92   14   76   27  192   40   11  208
             48   31  208   32  211  208
    datetime (unknown)

    body (0)

`end analysis/sarak/raw//ReadHistoryData-page-4.data: 75 records`
