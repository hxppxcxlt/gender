# gender
> enjoy the full spectrum of body shaping possibilities

did you know that gender is actually a spectrum in second life instead of a
binary choice? did you know that you can still use 'gendered' sliders such
as breast settings even if you are still 'male'?

this repository helps you fully unlock how you can shape your body by doing
the following:

* all 'gendered' sliders are now ungendered and always available for you to use

* the 'male' and 'female' buttons have been replaced with a new 'gender' slider
  in the 'body' section of the shape editor

this is useful for everyone, as these slider settings can help you do things
like fine-tune the shape of your shoulders and chest in ways not usually
possible

**YES:** everyone else can see your new shape using this, this is not local only

# requirements
these patches were made for use with the [firestorm viewer][0]

# setup
* **CLICK GREEN THE CODE BUTTON ON THIS PAGE** and select 'Download ZIP'

* copy `character/avatar_lad.xml` over the `character/avatar_lad.xml` in your
  firestorm directory

* copy `skins/default/xui/en/panel_edit_wearable.xml` over the same
  `skins/default/xui/en/panel_edit_wearable.xml` in your firestorm directory

* copy `skins/default/xui/en/strings.xml` over the same 
  `skins/default/xui/en/strings.xml` in your firestorm directory, do not 
  skip this step even if you will not use english!

* (if not using english) copy the `strings.xml` for your language into place, 
  there are translation files available for all supported languages

# advanced setup
if you are able to use the `patch` utility, you may instead apply the
`gender.patch` to the firestorm directory by doing:

``` shell
cd /path/to/firestorm
patch -p1 < /path/to/gender.patch
```

# caveats
many scripts that try to detect your gender expect your new gender slider to
be either set to 0 for female or 100 for male, if you set this somewhere
in-between it is possible you will be misgendered by furniture

[0]: https://www.firestormviewer.org/

