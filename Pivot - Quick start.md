## Quick start

![pvtengine](https://cdn.discordapp.com/attachments/677099357173973014/995950401637589053/unknown.png)
The pivot engine offers a view port and 5 control windows. These windows can be moved and resized.


### Key mapping
foreward : [z]
backward : [s]
left : [q]
right : [d]
toogle view port : [alt]

## Menu "Load/Save" 

![Menu LoadSave](https://cdn.discordapp.com/attachments/677099357173973014/995987255107792987/unknown.png)

Contains the functionality to save and load scenes. The window also allows to load scripts or graphic assets.

## Editor Menu

![Menu editor](https://cdn.discordapp.com/attachments/677099357173973014/995986851657678848/unknown.png)

The editor menu contains engine functionality
#### Scene selector
Allows you to navigate between your different scenes.

![Selecteur de scene](https://cdn.discordapp.com/attachments/677099357173973014/995979906833985637/unknown.png)

#### Transformation tools

The editor allows to modify the value of the component transform of an entity, without going through the component menu, directly by interacting with the axes. 

Translate allows to modify the position of an entity.

![Translate ](https://cdn.discordapp.com/attachments/677099357173973014/995978500752285766/unknown.png)

Rotate allows you to change the orientation of the entity.

![Rotate](https://cdn.discordapp.com/attachments/677099357173973014/995978555047546960/unknown.png)

Finally, Scale allows you to modify the size of the entity.

![Scale ](https://cdn.discordapp.com/attachments/677099357173973014/995978636203143168/unknown.png)

## Entity Menu

An entity is a structure composed of typical properties.

To create an entity, use the "Add Entity" button in the entity menu and give it a name. Validate with the key [enter].

![enter image description here](https://cdn.discordapp.com/attachments/677099357173973014/995694293203292220/unknown.png)

You can create many entities.

![enter image description here](https://cdn.discordapp.com/attachments/677099357173973014/995695102674620426/unknown.png)

The components of your entity are accessible via the component menu.

![enter image description here](https://cdn.discordapp.com/attachments/677099357173973014/995695765265588255/unknown.png)

##  Component Menu

It's an object who is attached to an entity an define his values and states.
The component menu allows you to access the different objects attached to an entity, to modify their values and to add objects to your entity.

![Compoent menu](https://cdn.discordapp.com/attachments/677099357173973014/995702999546593280/unknown.png)

After changing a value, confirm with [enter].

![enter image description here](https://cdn.discordapp.com/attachments/677099357173973014/995958217597259827/unknown.png)

## System Menu

It's a function used to modify a defined entity by modifying its components.

![enter image description here](https://cdn.discordapp.com/attachments/677099357173973014/995692501392433232/System-imgui.PNG)

To activate the systems, simply click on the system box in the editor menu.

![enter image description here](https://cdn.discordapp.com/attachments/677099357173973014/996008376968429608/unknown.png)

## Physics System

![enter image description here](https://cdn.discordapp.com/attachments/677099357173973014/995984389643178014/unknown.png)

The system physics allows to generate and modify the gravity applied to an entity.
It **requires** an entity with the components **[Gravity, Transform, RigidBody]**.

**You are now ready to create your First Cube with Pivot !**

