# Resize animations for waywall

don't use this but if you want to, example here
```lua
require("ww_resize_animations.init").setup(config, {
    speed = 4,
    fps = 20,
    normal_res = { w = 1920, h = 1080 },
    resolutions = {
        { key = "*-L", w = 340, h = 1080 }
    }
})
```
