# MG4
## Devlog
The FloatAnimation script creates a floating effect by moving the fish food up and down continuously.
In the Start() method, the _timer variable is initialized to the _switchSpeed value. This sets up a countdown timer that determines how long the food will move in its current direction before switching direction.
In the Update() method, which runs every frame, 
First, the script uses the _up boolean variable to decide the direction. If _up is true, the food moves upwards using transform.Translate. If it is false, the food moves downwards.
Second, the _timer decreases by Time.deltaTime. When the _timer reaches zero, it resets back to the _switchSpeed and flips the _up variable (true to false/false to true). This reverses the direction, creating the up-and-down looping animation.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)
