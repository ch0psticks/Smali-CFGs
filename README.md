Smali-CFGs
==========

Smali Control Flow Graph's

Smali Class Method CFG.

	$ flow.py -c smali/android/system/CoreService.smali -m run Method CFG

Smali Class File CFG.

	$ flow.py -c smali/android/system/CoreService.smali Class CFG

Smali Calls XRefs CFG.

	$ xref.py -d smali/ -m XRefBoth -f "android/system/a/g->a" XRefs CFG
