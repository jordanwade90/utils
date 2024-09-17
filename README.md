# Miscellaneous utilities

[i3][] helpers

- `dmenu_power`: Use dmenu to power off, reboot, or suspend the system.
  Assumes systemd.

- `rotateme`: Rotate the current screen.
  Requires python3, the i3ipc module, and xrandr(1).

Random number generators

- `diceme [N ...]`: rolls Nd6 (defaults to 5d6).
- `digitme [N ...]`: rolls Nd10 (defaults to {3,3,4}d10)
- `dicewareme [N ...]`: generate N-word [Diceware][] passphrases
  using the wordlist at `diceware.wordlist.asc`.

RNGs pull randomness from /dev/random.
All scripts require bash, od, and printf.
`dicewareme` also requires grep and cut.

[Diceware]: https://theworld.com/~reinhold/diceware.html
[i3]: https://i3wm.org/
