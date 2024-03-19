# ThreeJs Projects

Developments that intend to explore the knowlodges about JS and threJs library.
* Plane game. 
    - Setting a threeJS scene.
    - DOM and Web interaction with threeJS functionalities. 
    - Loading and manipulating GLTF files in ThreeJS.
    - Collisions. Create a collision test for the game obstacles.
    - Check the relative positions of the plane and obs, determine the hit condition and the respawn condition using distance square.

* Shooting Game.
    - Manipulating elements of a GLTF file. materials, textures, animations, organize hierarchy nodes of the meshs, etc.
    - Navmesh concept. Using unity, Determine the areas that is possible to interact 
        - Using the a simplify geometries of the eviroment(this might involve reducing the number of vertices, merging close vertices, or simplifying complex shapes), determine the area.
        - Triangulation. Transform the geometries to triangles for mash generation. 
        - Define the params of unity. Determine the walkable, obstacles, possible connections between triangles to be used in pathfinding.
    - Pathfinding.
        - Load an initialize the navmesh with the library.
        - Convert from mouse to normalized scene coodinates using as a raycast event.
        - Using FindPath, 
            - determine the calculated path with the possible nodes, define the direction, animation, movement. 
            - With a vector from the npc and the target compare the square distance condition. Or with the the condition of overpassed the node target an update problem.
            - If there is another node the process is repeated, with the length is equal the final target is reached.
    - Bullet collision.
            - determine the number of interactions, size of object, bullet velocity, fps.
            - Create the target cylinder for intersection when hiter by the sphere(bullet)
    * Pool Game
        - Using cannon.js library and a module to use in threJs. cannon wold, rigid objects.
        - Define contact with the material properties. aply impulse using a vector as the force bar.
        - Construction of a low polygon geometry. Composition of boxes and archs(for holes) to form the pooltable.
        - Raycast for the aim.

test
                

## Using

* https://github.com/donmccurdy/three-pathfinding
* https://github.com/mrdoob/three.js
* https://github.com/bytezeroseven/AA.js 
* https://github.com/pmndrs/use-cannon


## How to

* go to directory start.
* chose the directory game.
* install live server
* open index file with live server.
