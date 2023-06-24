# [_CAL-BASH-UTILS CHANGELOG_](git@gitlab.com:osiux/cal-bash-utils.git)

 - this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html)

## [`Unreleased - 2023-06-24`](git@gitlab.com:osiux/cal-bash-utils/-/compare/v0.2.0...develop)


## [`v0.2.0 - 2023-06-24`](git@gitlab.com:osiux/cal-bash-utils/-/compare/v0.1.0...v0.2.0) _add scripts for convert calendar events into plain text journaling_

### `ascii2bullet`

- replace todo, done, note, event and from ASCII to UTF8

### `bullet2ascii`

- replace todo, done, note, event and moved from UTF8 to ASCII

### `cal2ascii`

- replace UTF8 bullets with ASCII using bullet2ascii
- remove nonexistent calcommon

### `cal2html`

- replace UTF8 bullets with ASCII using bullet2ascii

### `cal2pdf`

- replace UTF8 bullets with ASCII using bullet2ascii

### `calalias`

- refactor alias for all scripts

### `caldaily`

- add script to repeat an event daily

### `caljmonth`

- general refactor, add help with example, prevent octal error, use CAL_EXCLUDE variable to exclude events
- add script to generate bullet journal output from calmonth

### `caljyear`

- return filenames of each month and consolidate in one file for printing
- general refactor, add help with example, prevent octal error and invalid month
- add script to generate bullet journal output from caljmonth for the current month and the following months until the end of the year

### `calvmonth`

- general refactor, add help with example and prevent octal error
- add script to visualize bullet journal output from caljmonth

### `calvmonths`

- add script to visualize bullet journal output from caljmonth for current month and 3 next months

### `calvyear`

- add help with example and replace caljmonth with caljyear
- add script to visualize bullet journal output from caljmonth for the current month and the following months until the end of the year

### `calweek`

- use dynamic DATE joining YEAR, MONTH and DAY

### `calweekly`

- add script to repeat an event weekly

### `CHANGELOG`

- add v0.1.0 and Unreleased - 2023-06-22

## [`v0.1.0 - 2023-06-22`](git@gitlab.com:osiux/cal-bash-utils/-/compare/1ea5f57...v0.1.0) _first public release_

### `cal2ascii`

- convert .calendar events into ASCII

### `cal2html`

- convert .calendar events into HTML

### `cal2notify`

- send upcoming events of the day to notify-send and ntfy.sh

### `cal2pdf`

- convert .calendar events into PDF

### `calalias`

- add vcal and calv to edit .calendar usign vim

### `calday`

- show entries for today

### `caledit`

- edit .calendar using $EDITOR environment variable

### `calendar`

- add FLISoL as calendar entry example

### `calmonth`

- show entries for the current month

### `calsort`

- replace undefined variable CAL with CALENDAR
- sort by moth all entries in .calendar

### `calweek`

- show entries for the current week

### `description`

- add calendar utilities for command line written in BASH

### `general`

- add GPLv3 GNU GENERAL PUBLIC LICENSE

### `gitlab-ci`

- execute shellcheck using koalaman/shellcheck-alpine:stable

### `Makefile`

- add rules for syntax-check and install

### `pre-commit`

- add check-executables-have-shebangs, end-of-file-fixer, trailing-whitespace and shell-lint hooks

### `README`

- add cal-bash-utils GitLab URL
- add minimal README with manual install, configure and GPLv3 License
