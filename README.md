# in-class-activities
## Devlogs
### W1
excused absence

### W2
1.The r, g, and b variables are floats instead of ints, bools, or strings because they are not whole number values and can be decimals.2. The _bounce variable is an int instead of float, bool, or string because the ball bounces only in whole numbers which is represented by integers. 3. The error shows me the exact row and column that the error occurred and the issue that needs to be fixed.

### W3 
The player sanity level is the input (parameters) and return type is void, since method changes ligth itself. A metaphor could be that a class is a blueprint for a robot, a deisgn that describes what kind of robot it is, but it isn't an actual robot yet. A component is a real robot built from that blueprint, there can be many made from the same class, with each one having slightly different settings or appearances based on the variables within it. Member variables are the robot's traits and characteristics. Methods are the robot's abilities, like actions it knows how to perform. So a class defines what kind of robot can exist and what it can do, while each component is an actual instance of that robot living in the world.
The balls bounce too many times and become extremely bright because of their brightness being increased every time they collide, while not being reset each time. Each bounce can be multiplying the value, so after many bounces, it gets brighter and brighter. It's basically an accumulation bug, where the color brightness keeps increasing without a limit.

### W4
I added rigidbodies to the cat and soccerball, whereas the goal has Is Trigger on so the ball can pass through it.
It worked fine after following instructions.

### W5
Is vector ever overkill?
It's basically never overkill.
Our plan for DeerW5 is to make the class first with monoBehaviour and then make a member variable for the Transform of the object and then make the member variable for the mesh and make the serialized field so we can change it in Unity. Then, make a Start method so that we can initialize the navmesh agent with the current gameObject's mesh. Then change the start method destination of the navmesh to the transform

## Open-Source Assets
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 