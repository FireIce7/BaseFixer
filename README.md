
# BaseFixer Plugin by Pitu

The **BaseFixer** plugin is a customizable solution for Rust servers, designed to streamline the repair process for structures while optimizing server performance.

---

## Key Features

### Customizable Command Activation
- Set the command to activate the plugin through the configuration file.

### Configurable Messages and Colors
- Fully customize in-game messages and their colors.

### Flexible Repair Material Configuration
- Choose which materials are required for repairs:
  - **Wood**
  - **Stone**
  - **Metal Fragments** (default)
  - **High-Quality Metal** (default)

### Permission System
- **Available Permissions**:
  - `basefixer.use`: Required to use the command.
  - `basefixer.noplayertax`: Allows players to bypass material requirements.

---

## Performance Optimizations

### Dynamic Batching
- Dynamically adjusts the number of entities processed per second based on server load.

### Rate Limiting
- Limits the number of simultaneous repair commands to reduce server strain.

### Asynchronous Processing
- Offloads intensive tasks to asynchronous threads, enhancing server performance.

---

## Configuration Options

The plugin provides various configuration options to suit your server's needs:

1. **Entities Per Second**:
   - Sets the number of entities processed per second.
2. **Damage Repair Cooldown**:
   - Cooldown time between repair commands.
3. **Repair Cost Multiplier**:
   - Multiplier for repair material costs.
4. **Global Repair Limit**:
   - Maximum number of entities repaired at once.
5. **Command**:
   - Command to activate the plugin (default: `/br`).
6. **Messages**:
   - Customizable messages for different plugin states.
7. **Repair Materials**:
   - Select required repair materials:
     - Wood
     - Stone
     - Metal Fragments
     - High-Quality Metal

---

This plugin is highly configurable and perfect for servers seeking a balance between functionality and performance. Adjust the configuration file to get the most out of BaseFixer!
