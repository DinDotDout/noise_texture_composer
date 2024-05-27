# noise_texture_composer
This Godot plugin is a practical tool designed for noise texture combination. Godot's noise textures do not take advantage of all the channels and thus are not optimized for noise texture lookups. The plugin works by taking multiple noise textures as inputs, each serving as a different channel, and allowing the combination of 2 to 4 channels. The plugin fetches these individual textures, validates their dimensions, and merges their r channles into a single output texture. This was developed with a focus on simplicity and lightweight design, and to fulfill a personal need without overcomplicating the solution.

![usage](https://github.com/DinDotDout/noise_texture_composer/blob/main/images/usage.png)
