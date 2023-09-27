# Unity Folder Structure

This document outlines the folder structure that I adhere to when creating Unity projects. It reflects best practices for organizing Unity projects to enhance clarity and efficiency.

## Assets

The heart of your Unity project, where you store all project assets, is divided into several key categories:

- **Animation:**
  - *Timeline:*
  - *Animator:*

- **Art:**
  - **Models:**
  - **Materials:**
    - *ParticleSystem:*
    - *ShaderGraphs:*
  - **ParticleSystem:**
  - **Textures:**
    - *ParticleSystem:*
    - *ShaderGraphs:*

- **Audio:**
  - **Music:**
  - **Sound:**

- **Code:**
  - **Scripts:**
    - **Player:**  
      - `PlayerMovement.cs`
      - `PlayerHealth.cs`
    - **Enemy:**  
      - `EnemyAI.cs`
    - **UI:**  
      - `UIManager.cs`
    - **Classes:** (Additional scripts and classes)
    - **Utils:** (Utility scripts and classes)
  - **Shader:**

- **Docs:**
  - `DesignPatterns.txt` (Project documentation)

- **Editor:**
  (Custom editor scripts, if any)

- **Level:**
  - **Prefab:**
    - **Environment:** (Prefabs for environmental objects)
    - **Characters:** (Prefabs for characters)
    - **Items:** (Prefabs for in-game items)
  - **Scene:**
    - *Main:*
  - **UI:**
    - **Font:** (Font assets)
    - *Main:*

- **ThirdParty:**
  - **Plugins:**
    (Third-party assets and plugins)
