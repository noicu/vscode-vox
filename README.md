# VOX Viewer for VSCode

## Description

Preview MagicaVoxel models in VSCode

## Main Features

### Model Viewer
Support formats:
* `vox` MagicaVoxel's vox format.

  ---


## Configuration

|Name                             |Type      |Description
|---------------------------------|----------|------------
|`vox.wireframe`             |`boolean` |Display mesh in wireframe mode
|`vox.background`            |`string`  |Set the default background color (e.g. '#8f8f8f')
|`vox.boundingBox`           |`boolean` |Display a bounding box around the model
|`vox.grid`                  |`boolean` |Display a grid at the origin
|`vox.gridSize`              |`number`  |Set the size of the grid
|`vox.near`                  |`number`  |Set the near plane distance
|`vox.far`                   |`number`  |Set the far plane distance
|`vox.limitFps`              |`number`  |Set the max fps (use 0 for no limit)
|`vox.hotReload`             |`boolean` |Enable hot reload mode for viewer
|`vox.hotReloadAutomatically`|`boolean` |Enable this to reload models without the question popup

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Requirements

Visual Studio Code v1.49.0

## Credits

* [Visual Studio Code](https://code.visualstudio.com/)
* [THREE.js](https://threejs.org)
* [dat.GUI](http://workshop.chromeexperiments.com/examples/gui/#1--Basic-Usage)

## License

[MIT](LICENSE.md)
