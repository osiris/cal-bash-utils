# `cal-bash-utils`

calendar utilities for command line written in BASH

## Install

### Manual

Clone the repository:

```bash

  cd /opt
  git clone https://gitlab.com/osiux/cal-bash-utils.git

```

Add to `$HOME/.bashrc`:

```bash

if [[ -d "/opt/cal-bash-utils" ]]
then
  PATH="/opt/cal-bash-utils:$PATH"
  source /opt/cal-bash-utils/calalias
fi

```

## License

_GNU General Public License, GPLv3._

## Author Information

This repo was created in 2023 by
 [Osiris Alejandro Gomez](https://osiux.com/), worker cooperative of
 [gcoop Cooperativa de Software Libre](https://www.gcoop.coop/).
