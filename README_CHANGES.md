# Changes in MQTT2CAN

Every change that goes into a release is listed here, newest release first.
Add each change under **Unreleased** when it is made. When a release is
tagged, rename **Unreleased** to the version and date, and start a new
**Unreleased** section above it.

## Unreleased

- Removed the note file (b0e8df4)
- Fixed SIOCGSTAMP warning - https://wiki.gentoo.org/wiki/Linux_headers_5.2_porting_notes/SIOCGSTAMP Fixed strncpy warning for gcc 9 - https://github.com/intel/openlldp/pull/27 (9e07ca4)
- implemented publishing error frames (dc4fc01)
- fixed clientid clashes, as libmosquitto is not random enough (d1297df)
- add install target to Makefile (82f9b1a)
- parse only remaining part of RTR frames (83d42b2)
- updated LICENSE (ae9d2d4)
- support for shorter message without timestamp (a362e96)
- fixed RTR frames (860cc4f)
- fixed extended frames (e8fd141)
- reworked doublet detection (f967823)
- add help message for -r and -w (1972162)
- refactored help message (b78efd1)
- added read and write permissions for CAN interface (8d55dbb)
- fixed wrong ip link command line (d19a660)
- update README (54fbd62)
- make hostname lowercase by default (d98b640)
- use C11 standard (231e060)
- mosquitto_connect_async seems to be broken in mosquitto 1.4 (401b2c4)
- fixed parameter for hostname (af9ffef)
- implemented timestamp in CAN frames (f0d4765)
- relicensed under GPLv3 (8ee76de)
- added authentication with broker using username and password (288b41b)
- added doublet filter for detecting self published messages (b917bef)
- Big change in message topic format. (2b9de31)
- code cleanup (9cbb324)
- implemented bridge mode (49fe200)
- corrected handling of special CAN frames (ebb8a6d)
- refactored CAN frame debug messages (282e8d9)
- ignore target executable (666ed64)
- transmit of CAN frames works (55024f9)
- first version, publishing received CAN frames works (ce189a4)
- Initial commit (6de9df8)

No release has been tagged yet.
