## The following tablee summarises various design changes made to the TEC-1 family of PCBs throughout the years.


| Designer     | Major Revision  | ROM RD bus clash | I/O port wraparound | Memory wraparound        | SHIFT Key | JMON Keyboard MOD  | Output Latches  |
|--------------|-----------------|------------------|---------------------|--------------------------|-----------|--------------------|-----------------|
| TE  (Ken)    | TEC-1           | YES              | 8 ports             | 16k                      | NO        | NO                 | 8212            |
| TE  (Ken)    | TEC-1A          | YES              | 8 ports             | 16k                      | NO        | NO                 | 74LS273/374/377 |
| TE  (Ken)    | TEC-1B          | YES              | 8 ports             | 16k                      | YES       | NO                 | 74LS273/374/377 |
| TE  (Craig)  | TEC-1B CH Rev.1 | YES              | 16 ports            | 64k (2x1n4148 diode mod) | YES       | YES (Resistor mod) | 74LS273/374/377 |
| TE  (Craig)  | TEC-1C          | YES              | 16 ports            | 64k (2x1n4148 diode mod) | YES       | YES (Resistor mod) | 74LS273/374/377 |
| Ben Grimmett | TEC-1D          | YES              | 16 ports            | 64k (2x1n4148 diode mod) | YES       | YES (Resistor mod) | 74LS273 only    |
| Ken Stone    | TEC-1E          | NO               | 0-7, 80-87h         | 64k (New design)         | YES       | Yes (Buffer chip)  | 74HC273         |
| Craig Jones  | TEC-1F          | NO               | 16 ports            | 64k (2x1n4148 diode mod) | YES       | YES (Buffer chip)  | 74HC374/377     |


A TEC-1 B that is a CH Rev.1 edition will have "CH rev.1" written on the solder side near the 1000u filter electrolytic.

