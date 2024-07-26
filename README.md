BaseFixer Plugin by Pitu

--> Key Features

- Customizable Command Activation

Set the command to activate the plugin via the configuration file.
Configurable Messages and Colors

- Customize all in-game messages and their colors

- Flexible Repair Material Configuration

Choose which materials (Wood, Stone, Metal Fragments, High-Quality Metal) are required for repairs. Defaults to Metal Fragments and High-Quality Metal.

- Permission System

Permissions: basefixer.use for using the command and basefixer.noplayertax to bypass material requirements.

--> Performance Optimizations:

- Dynamic Batching

Adjusts entities processed per second based on server load.
Rate Limiting

Controls the number of simultaneous repair commands to reduce server strain.

- Asynchronous Processing

Offloads intensive tasks from the main server thread to enhance performance.

- Configuration Options

1. Entities Per Second: Number of entities processed per second.
2. Damage Repair Cooldown: Cooldown time between repair commands.
3. Repair Cost Multiplier: Multiplier for repair material costs.
4. Global Repair Limit: Maximum number of entities repaired at once.
5. Command: Command to activate the plugin. (default /br)
6. Messages: Customizable messages for various plugin states.
7. Repair Materials: Choose required repair materials (Wood, Stone, Metal Fragments, High-Quality Metal).
