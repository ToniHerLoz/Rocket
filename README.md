# Rocket
 
## :floppy_disk: How to install?

![imagen](https://user-images.githubusercontent.com/59538289/134321423-5e24671e-7e72-4fbc-b26b-4047ccd7a165.png)

1. Copy Rocket folder to /Mordhau/Plugins/
2. Copy Rocket.uasset to /Mordhau/Content/

## How to use?

1. Open your project.
2. Copy Rocket.uasset to your map foler.

![copy](https://user-images.githubusercontent.com/59538289/134322419-9eb1503f-c719-4edc-b618-2e370d1b2505.gif)

4. Open Rocket Actor and edit the following variables:
  - UnMount File: -> Path of the file that the map detects to unmount PAK FILE 
  - Mount File: -> Path of the file that the map detects to Mount new PAK FILE 
  - Pak Path: -> Pak file mounting / unmounting
  - Level Name: -> Level Name to load when mount new pak
5. Save and Compile blueprint.
6. Drag Rocket to map and verify that the routes are correct. 
7. Cook and pack manually 
8. Launch game and write in console:
   - MountPak PakPath -> MountPak D:\Survival.pak -> Console return success
   - Open LevelName -> Open testmapa
9. Now edit your map and click in Rocket buttom the game will automatically reload the map with the changes. 
10. Remove "Rocket" from your map when you share it.
