**v0.6**

- added two more units ("1737e" and "1737f") counting a total of 5 units (35 possible channels)

**v0.5**

- save incremental numbers (per unit) into sqlite3 db
- support for up to 3 units (allowing to manage ~21 channels)
- corrected the channels being used (1-7 and 15)
- slightly amended `--channel <[unit:]channel>` parameter to take units into account
- added `-s` argument to output sqllite3 db content (containing last run for instance)
- removed `-i` to manually increment counter
- added `--mod` (for very advanced users) to modify database entry
- replaced `PAIR` command with `TRAIN` needed to train the shutter
- added `REMOVE` command to remove the sender from shutter

**v0.4**

- added ser2net support for device

**v0.3**

- added commands "DOWN2" and "UP2" for intermediate positions

**v0.2**

- always use "centronic.num" from its local directory

**v0.1**

- Initial version