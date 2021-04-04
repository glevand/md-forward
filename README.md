# md-forward

Forward Maildir entries to an alternate location.

## Usage md-forward.sh

```
md-forward.sh - Forward Maildir entries to an alternate location.
Usage: md-forward.sh [flags]
Option flags:
  -u --mail-user    - Mail user name. Default: 'luther'.
  -s --mail-src     - Host for source Maildir. Default: 'never-too-much.vandross.net'.
  -d --mail-dest    - Host for destination Maildir. Default: 'busy-body.vandross.net'.
  -S --sync-src     - Sync to mail-src. Default: 'y'.
  -D --sync-dest    - Sync to mail-dest. Default: 'y'.
  -y --dry-run      - Do not modify files at source or dest. Default: '1'.
  -w --work-dir     - Work directory. Default: '/home/luther/md-forward/work'.
  -c --config-file  - Config file. Default: '/home/luther/md-forward.conf'.
  -h --help         - Show this help and exit.
  -q --quiet        - Less verbose execution.
  -g --debug        - Extra verbose execution.
Info:
  md-forward.sh (md-forward) version 1
  https://github.com/glevand/md-forward
  Send bug reports to: Geoff Levand <geoff@infradead.org>.
```

## License

All files in the [md-forward project](https://github.com/glevand/md-forward), unless otherwise noted, are covered by an [MIT Plus License](https://github.com/glevand/md-forward/blob/master/mit-plus-license.txt).  The text of the license describes what usage is allowed.
