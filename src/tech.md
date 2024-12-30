# Project Cosmos - Technical Summary

*Project Cosmos* is a 2D space exploration game developed in C++ that focuses on a high-performance, interactive experience. The game uses a combination of modern libraries and technologies to provide a smooth and engaging gameplay experience.

### Core Technologies:

1. **C++**  
   The game is developed using C++, from engine to scripting the player interaction.

2. **Entt**  
   For handling the game's entities, components, and systems, *Project Cosmos* uses **Entt**, a fast and lightweight Entity-Component-System (ECS) framework. 

3. **ImGui**  
   For creating the game's user interface, **ImGui** is used. It’s great for building in-game overlays, debug tools, and UI elements quickly. Since it integrates easily with OpenGL, it’s perfect for handling real-time interactions with the player.

4. **OpenGL**  
   The game uses **OpenGL** for rendering. Since the game is 2D, OpenGL helps create smooth, high-quality visuals for planets, moons, and other space-related objects. The rendering system is lightweight, ensuring the game performs well across different devices.

5. **Networking**  
   *Project Cosmos* supports multiplayer gameplay. This allows players to explore the universe together, collaborate on tasks, and share discoveries. I'm currently working on the architecture of the server infrastructure, with the final goal to let players host their own servers and lobbies to play with friends.

### Features:

- **2D Engine**  
  The game is designed around a 2D engine, focusing on a top-down view of space exploration. OpenGL handles the rendering, allowing for crisp visuals and smooth performance even as the game world grows more complex.

- **Multiplayer**  
  *Project Cosmos* includes networking features that allow players to interact, share blueprints, and explore space together. The multiplayer system ensures that the game remains fun and engaging, even when playing with friends.

- **Modular Tools**  
  Players can create and upgrade blueprints for essential tools like scanners and miners. These tools play a key role in exploration and resource management, allowing players to customize their experience as they progress through the game.
