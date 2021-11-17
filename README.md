# espanso-hexcodes

Completion for HexDrone statuses.

A package to complete HexCorp status codes in areas where the HexCorp AI can't
reach.

# Install

```espanso install hexcorp-status-codes https://github.com/HexDrone7375/espanso-hexcodes --external```

# Usage

Type `::hc` after your drone ID along with the 3 digit status code.

e.g:

```7375 ::hc007```

Turns into

```7375 :: Code `007` :: Signal :: Beep```

# What are the status codes?

The package follows the status codes seen at
https://www.hexcorp.net/drone-status-codes-v2.

# I didn't have to type the drone ID in the AutoHotKey implementation. What
gives?

It's written this way to avoid as much configuration as possible. Plus, it
shouldn't be too difficult to remember 4 digits right?

# Why make this when the AutoHotKey version exists?

I use Linux, and AutoHotKey is Windows only. Espanso gave a nice solution that
people on multiple platforms can benifit from.
