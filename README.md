# About optimize-mysql for Movable Type

## Synopsis

The optimize-mysql script can be optimize mysql database from the command line.

## Example

Execute from the command line.

    cd /path/to/mt; perl ./tools/optimize-mysql

## Example - Executing from Cron

Execute rebuild all archives once a day(at 2:00 am).

    0 2 * * * cd /path/to/mt; perl ./tools/optimize-mysql
