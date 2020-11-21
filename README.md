In order to transparently load and save presets from the git repository we can use soft links

Drum Kit and Mixer Presets

```
cd "/Users/$USER/Library/Application Support/Toontrack/Superior3/PresetsEZX/SL-SUPERIOR_DRUMMER_3"
rm -r S3Presets
ln -s $pathToGitRepo/S3Presets S3Presets
```



Midi Mapping Presets

```
cd "/Users/$USER/Library/Application Support/Toontrack/Superior3"
rm -r EdrumPresets
ln -s $pathToGitRepo/EdrumPresets EdrumPresets
```







