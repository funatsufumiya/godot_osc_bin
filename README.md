# godot_osc_bin

binary repository of [godot_osc](https://github.com/funatsufumiya/godot_osc)

if you need `godot_osc` [releases](https://github.com/funatsufumiya/godot_osc/releases) as `git submodule`, please use this repository.

## Simple usage example

```bash
cd PROJECT_DIR_OF_YOUR_GODOT
cd addons
git submodule add https://github.com/funatsufumiya/godot_osc_bin.git osc
# or simply: git clone https://github.com/funatsufumiya/godot_osc_bin.git osc
```

but I recommend to use `godotenv addons install`. see [GodotEnv's readme](https://github.com/chickensoft-games/GodotEnv?tab=readme-ov-file#initializing-godotenv-in-a-project). GodotEnv's `addons.jsonc` config is below (partial):

```json
    "osc": {
      "url": "https://github.com/funatsufumiya/godot_osc_bin",
      "checkout": "v0.1.3",
    },
```
