
# Creation of a cube with pivot

Create a new entity in the entity menu and give it a name, here "myCube".
In the component menu add a "**RenderObject**", a "**Transform**" and a "**RigidBody**" to your entity.

![enter image description here](https://cdn.discordapp.com/attachments/823213380084695081/1042777723141107742/image.png)

To display the cube you now need to load its graphic asset.
Use the "Save/Load" menu and select "Load asset".

A cube asset can be found by default under **editor/asset/cube.obj**.

If you want to use your own assets, Pivot is able to load **.obj** and **.gltf**.

![enter image description here](https://cdn.discordapp.com/attachments/823213380084695081/1042780835398557796/image.png)

A window confirms the successful loading of your asset.
You have made your first cube in the pivot engine.

## Modify the cube 

We are now going to use the component menu to modify the variables of our cube.
The "transform" component has built-in tools to modify its value without using the component menu.

![enter image description here](https://cdn.discordapp.com/attachments/823213380084695081/1042781573919035443/image.png)

### Moving
Moving an entity can be done by interacting with the axis present in our entity or by directly modifying its position values in the component menu.

### Rotation 

The rotation of an entity is done by interacting with the present axis in our entity or by directly modifying its position values in the component menu.

### scaling
The scaling of an entity is done by interacting with the present axis in our entity or by directly modifying its position values in the component menu.

## Gravity

To add gravity to the previously created cube, simply add the system physics.
You can then modify the velocity and acceleration of your cube, or apply the gravity component.

![enter image description here](https://cdn.discordapp.com/attachments/823213380084695081/1042782612495814716/image.png)

After adding the physic system, activate the system using the editor menu.
You can observe the evolution of your cube under the physic system.

![enter image description here](https://cdn.discordapp.com/attachments/823213380084695081/1042782676836417656/image.png)

After activation of the systems our cube has moved well.

![enter image description here](https://cdn.discordapp.com/attachments/823213380084695081/1042782767387263107/image.png)

**Jump now to the save and load guide to save your Pivot scenes!**
