# Haunted house

## Description
A haunted house scene with geometries, lights, shadows and textures.

### Elements
1. Geometries:
  - Floor:
    - a plane geometry with a grass texture
  - House:
    - a box geometry for the walls with bricks texture
    - a cone geometry for the roof
    - a plane geometry for the door with a door texture
  - Bushes:
    - sphere geometries
  - Graves:
    - box geometries generated and placed randomly around the house on the floor with a for cycle and a range between 3 and 6 to not place them inside the house or outside the floor

2. Lights:
  - Ambient light:
    - an ambient light to illuminate all the elements
  - Moon light:
    - a directional light to simulate the moon light
  - Door light:
    - a point light over the door
  - Ghosts:
    - point lights moving randomly around the scene

3. Shadows:
  - Lights casting:
    * Moon light
    * Door light
    * Ghosts
  - Objects casting:
    * Walls
    * Roof
    * Bushes
    * Graves
  - Objects receiving:
    * Floor
    * Walls
    * Doors
    * Bushes
    * Graves
