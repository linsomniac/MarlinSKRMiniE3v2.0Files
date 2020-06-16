SKR Mini E3 v2.0 Patch Files
============================

This repo contains patch files that implement the changes to build firmware
for the BigTreeTech SKR Mini E3 v2.0 board as documented by u/qwewer1 in
the guide at:

https://www.reddit.com/r/ender3/comments/h8y1ia/marlin_20x_guide_skr_mini_e3_v20_ender_3/

Usage
-----

- Clone the MarlinFirmware
- Check out the bugfix-2.0.x branch
- `patch -p1 <essential_changes.patch`
- If you have a bltouch, also run: `patch -p1 <bltouch.patch`

You can then build as normal, further customize, etc...
