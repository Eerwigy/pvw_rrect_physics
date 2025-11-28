# rrect_physics

This is a simple physics implementation with axis-aligned rounded rectangles that I'm using for my game Pancakes vs Waffles. I do not recommend using this in your own projects because it is probably filled with bugs.

## Usage

### Singleplayer

```toml
[dependancies]
bevy = "0.17"
rrect_physics = { git = "https://github.com/Eerwigy/rrect_physics.git" }

```

```rust
use bevy::prelude::*;
use rrect_physics::*;

fn main() -> AppExit {
    let mut app = App::new();
    app.add_plugins((DefaultPlugins, RRectPhysicsPlugin::default()));
    app.run()
}
```

### Multiplayer

Multiplayer is not available yet but probably will be within a few days from now.

