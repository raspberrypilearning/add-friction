In the Project window select 'Materials' and then 'PhysicsMaterials'. Right-click in the window, click 'Create' and select **Physic Material**. 

Give your physic material a sensible name. 

Adjust the properties to create the effect you want:

Physic Materials have three attributes that you can set to any value between `0` and `1` to change an object's interactions:
+ **Dynamic Friction:** How quickly an object that is already moving will slow down. `0` is like ice (not very much friction) and `1` would stop a moving object very quickly.
+ **Static Friction:** The amount of force needed to move an object from standing still. `0` means a small amount of force would move the object and `1` would require a huge amount of force to move an object.
+ **Bounciness:** How bouncy an object is. `0` is no bounce at all and `1` means an object will bounce and not lose any velocity.

Drag the material onto one or more GameObjects. 
