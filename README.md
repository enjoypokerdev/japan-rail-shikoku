[README.md](https://github.com/user-attachments/files/35189906/README.md)
# japan-rail-shikoku

A small pixel-art train game set on the JR Shikoku line. Drive between stations, stop at each platform, open and close the doors, and try to finish the route as fast as you can. 


## How to play 

Drive the train along the route from the first station to the last. Along the way you will pass through three stations: Matsuyama, Takamatsu and Kochi. 

### Controls 

|Action|Key|
|---|---|
|Speed up|`[`W`]`|
|Slow down|`[`S`]`|
|Open / close doors|`[`E`]`|



### Rules 

- The doors can only be opened at a station, and only when the train has come to a complete stop. 

- You can't move until the doors are closed again. 

- Opening the doors and then closing them counts as visiting that station. Each visit is written on your notepad. 

- The run ends when you close the doors at the last station, or if you drive past it. 

### Routes 

There are three routes to choose from: Short, Medium and Long. They are the same line, and the only difference is the distance. 

### Score 

- 1000 points for every station you visit. 

- Up to 2000 bonus points for finishing quickly. The bonus shrinks as your time approaches the route's par time, and it is scaled by how many stations you visited, so skipping stations costs you. 

## Download 

Get the latest version from the Releases page. 

- macOS: unzip the download, then right-click the app and choose Open. The app isn't signed, so if macOS still blocks it, go to System Settings → Privacy & Security and click Open Anyway. 

## Build from source 

The game is written in GDScript and made with <u>Godot 4.7.</u> 

1. Install Godot 4.7. 

2. Clone or download this repository. 

3. Open `project.godot` in Godot and press Play (the main scene is the start menu). 

## Credits 

Made with Godot. 

Pixel art drawn in LibreSprite. 

Font: Tiny5, licensed under the SIL Open Font License (see `Assets/Tiny5/OFL.txt` ). 

## Disclaimer 

This is an unofficial fan project. It is not affiliated with, endorsed by, or connected to JR Shikoku (Shikoku Railway Company). 

