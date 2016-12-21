# ants-bridge
Animation of ant-like robots rescuing town after eartquaqe

Buildings were generated using [BlenderGIS](https://github.com/domlysz/BlenderGIS) basing on map of Amatrice.

## Development

Reference photos: [Link](https://drive.google.com/drive/folders/0B13yZwofq0THNW53YzhWMGhPMGM)

Project is splitted into severeal blender files to make version git workflow easier. Objects imported into `Main scene` should have `EX` postfix in name.

Files responsibilities:
* `Main scene.blend` - importing objects from other files and setting cameras, lightning and so on...
* `Amatrice.blend` - buildings
* `Terrain.blend` - roads, terrain

Pro tips:
* For setting up camera use Ctrl+0 with camera selected, then Shift+F, and move with WSADQE, see status bar.

