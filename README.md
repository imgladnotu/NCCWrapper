# NullCoreCrackWrapper ~ With love from Wolfie

## Why crack the cheat?
[I thought it would be funny](https://youtu.be/MQEEJ57Gsow?t=317), plus it hasn't been updated in like 500 days, so it's kinda deserved in my opinion.

## Why open source it?

I original released the crack with VMProtect on it to stop people from hex-editing the NCU, but to be honest I just stopped caring.

Feel free to set the NCU to your name, do whatever you'd like, just preferably don't go around telling people that it's all your work.

Also of course feel free to fork this and fix it if it ever goes outdated.

## Doesn't this need an internet connection?

Not at all actually.

The configs were passed to the cheat by the loader in a memory page, simply setting
this page to be blank just makes the cheat think something went wrong and resets all
of the configs to the factory defaults. So, thanks for making that easy!

## More infos
The 'RebuiltDLL' array is just a dump of NCC with a rebuilt PE header.

If for whatever reason any of the sigs break, feel free to update them yourself. Be on the lookout for 0x2A. (*)

They're located in the 'SignaturePage' array (how crazy is that?)

Also, **COMPILE IN RELEASE**!

Oh, and special thanks to Zer0Memory for some resolving stuff and the Zydis guys for their disassembler.
