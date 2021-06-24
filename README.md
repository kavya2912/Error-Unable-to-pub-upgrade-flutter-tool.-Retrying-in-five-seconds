# Error-Unable-to-pub-upgrade-flutter-tool.-Retrying-in-five-seconds in mac and window
Flutter error solution

If you get error :
Building flutter tool...
Failed to start the Dart CLI isolate
(null).
Error: Unable to 'pub upgrade' flutter tool. Retrying in five seconds... (9 tries left)
Failed to start the Dart CLI isolate
(null).
Error: Unable to 'pub upgrade' flutter tool. Retrying in five seconds... (8 tries left)
Failed to start the Dart CLI isolate
(null).
Error: Unable to 'pub upgrade' flutter tool. Retrying in five seconds... (7 tries left)
Failed to start the Dart CLI isolate
(null).
Error: Unable to 'pub upgrade' flutter tool. Retrying in five seconds... (6 tries left)
Failed to start the Dart CLI isolate
(null).

Then for this first delete cache file from flutter/bin directory .
Cntr+C to stop infinite error loop.
Run in command line flutter pub cache repair.
After successfuly repair it.
check by typing flutter doctor
