kobs-ng-patches
===============

Patches for kobs-ng

1. kobs-ng-3.0.35-4.0.0_explicit_rom.patch

Allows you to specify the ROM version explicitly using a
command line parameter. For example "kobs-ng -r mx28 init ..."
rather than use the broken heuristic that results in

"Couldn't find Boot ROM version
We can not find the right ROM version!"

