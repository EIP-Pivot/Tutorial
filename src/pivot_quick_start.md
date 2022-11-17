## Quick start

![pvtengine](https://cdn.discordapp.com/attachments/734780616918302827/1042715236995694664/image.png)

The pivot engine offers a view port and 5 control windows. These windows can be moved and resized.


### Key mapping
foreward : [z]

backward : [s]

left : [q]

right : [d]

toogle view port : [alt]

toogle ImGUI translate : [e]

toogle ImGUI rotate : [r]

toogle ImGUI scale : [t]

save : [ctrl + s]

## Menu "File" 

![Menu LoadSave](https://cdn.discordapp.com/attachments/734780616918302827/1042729447830339595/image.png)

Contains the functionality to save and load scenes. The window also allows to load scripts or graphic assets.

## Editor Menu

![Menu editor](https://cdn.discordapp.com/attachments/734780616918302827/1042715526650134548/image.png)

The editor menu contains engine functionality
#### Scene selector
Allows you to navigate between your different scenes.

![Selecteur de scene](https://cdn.discordapp.com/attachments/823213380084695081/1042723967456251904/image.png)

#### Transformation tools

The editor allows to modify the value of the component transform of an entity, without going through the component menu, directly by interacting with the axes. 

Translate allows to modify the position of an entity.

![Translate ](https://cdn.discordapp.com/attachments/823213380084695081/1042725336812630077/image.png)

Rotate allows you to change the orientation of the entity.

![Rotate](https://cdn.discordapp.com/attachments/823213380084695081/1042725385789509642/image.png)

Finally, Scale allows you to modify the size of the entity.

![Scale ](https://cdn.discordapp.com/attachments/823213380084695081/1042725481193160734/image.png)

## Entity Menu

An entity is a structure composed of typical properties.

To create an entity, use the "Add Entity" button in the entity menu and give it a name. Validate with the key [enter].

You can create many entities.

![enter image description here](https://cdn.discordapp.com/attachments/734780616918302827/1042715365681152050/image.png)

The components of your entity are accessible via the component menu.

![enter image description here](https://cdn.discordapp.com/attachments/823213380084695081/1042727279463256126/image.png)

##  Component Menu

It's an object who is attached to an entity an define his values and states.
The component menu allows you to access the different objects attached to an entity, to modify their values and to add objects to your entity.

![Compoent menu](https://cdn.discordapp.com/attachments/734780616918302827/1042715526650134548/image.png)

After changing a value, confirm with [enter].

## System Menu

It's a function used to modify a defined entity by modifying its components.

![enter image description here](https://cdn.discordapp.com/attachments/734780616918302827/1042715636419285033/image.png)

To activate the systems, simply click on the play button on the top center for the screen.

![enter image description here](https://cdn.discordapp.com/attachments/734780616918302827/1042715781374423110/image.png)

## Physics System

![enter image description here](https://cdn.discordapp.com/attachments/823213380084695081/1042782767387263107/image.png)

The system physics allows to generate and modify the gravity applied to an entity.
It **requires** an entity with the components **[Gravity, Transform, RigidBody]**.

**You are now ready to create your First Cube with Pivot !**

