**v2021.12.20 (202112200)**
- [accd, misc-functions]: prevent unwanted crashes related to `eval` and `set -eu`;
- [batt-info]: filter out the unreliable `POWER_SUPPLY_CHARGE_TYPE` property (note: this change makes AccA always display "unknown" charge type);
- [batt-info]: fixed current reading issue;
- [batt-info]: round current and voltage values to two decimal places;
- [ctrl-files]: added `battery/op_disable_charge 0 1` switch;
- [README]: updated troubleshooting section;
- General optimizations.

**v2022.1.8 (202201080)**
- `acc -p` finds even more potential switches;
- Enhanced charging status detection;
- General fixes & optimizations;
- Improved idle mode support;
- New charging switches;
- Optimize system performance and battery utilization, by forcing `bg-dexopt-job` on daemon [re]start, if charging;
- Support for Qualcomm SnapDragon 8 Gen 1 devices, Nokia 2.2 and more;
- Updated documentation.

**v2022.1.28 (202201280)**
- Additional charging switches;
- Fixed bg-dexopt-job wrapper causing long accd stop delay;
- Fixed typos in README;
- Fixed voltage "millivolts --exit" error;
- General optimizations;
- Improved charging status logic;
- Moved changelog from README.md to changelog.md;
- Removed README.html;
- Support for Magisk v24 (`updateJson`);
- Updated unexpected reboot troubleshooting guide.
