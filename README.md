# mixxx-flatpak
recipe to build Mixxx for Flatpak

To use it, you will need to install tools:
 - flatpak-builder
 - flatpak
 
Then install KDE SDK and KDE Platform via flatpak and run
````
flatpak-builder [your-work-directory] org.mixxx.mixxx.json --jobs=[how-many-you-want] --install
````

After some hours you can run Mixxx via
````
flatpak run org.mixxx.mixxx
````

# Issues
As wanted first to check out if it works there some not-done details:
- builds without opus support
- builds without JACK support
- mostly untested, but it plays
