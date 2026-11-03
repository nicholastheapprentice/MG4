# MG4
## Devlog
The FloatAnimation script uses transform.Translate in the Update() method to move the food object according to a given _moveSpeed, which we can access in the Inspector, and Time.deltaTime, which is the time lap between each frame. 


_switchSpeed defines how long it would take before the food changes its move direction. It is passed to _timer which decreases every frame with Time.deltaTime. When the timer runs out, it would be reset and the value in _up would be reversed to change the move direction.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)