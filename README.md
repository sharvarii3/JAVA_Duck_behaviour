# Duck Simulation Program

## Overview
This Java project is a **Duck Simulation** program that demonstrates the **Strategy Design Pattern** to manage different duck behaviors dynamically.

## Features
- Different types of ducks with unique behaviors.
- Uses interfaces for **FlyBehavior** and **SwimBehavior**.
- Implements the **Strategy Pattern** to allow changing behavior dynamically.

## Classes & Interfaces

### Interfaces:
- **`FlyBehaviour`** - Defines the `fly()` method.
- **`SwimBehavior`** - Defines the `swim()` method.

### Duck Base Class:
- **`Duck`** (Abstract Class) - Contains shared methods like `performFly()`, `performSwim()`, and `display()`.

### Concrete Duck Implementations:
- **`MallardDuck`** - Can fly and swim.
- **`RedHeadDuck`** - Can fly and swim.
- **`RubberDuck`** - Cannot fly but floats on water.
- **`DecoyDuck`** - Cannot fly but floats on water.
- **`ModelDuck`** - Cannot fly initially but can be changed dynamically.

### Behavior Implementations:
- **`Fly`** - Implements `FlyBehaviour`, allowing ducks to fly.
- **`NotFly`** - Implements `FlyBehaviour`, making ducks unable to fly.
- **`Swim`** - Implements `SwimBehavior`, allowing ducks to swim.
- **`Float`** - Implements `SwimBehavior`, making ducks float instead of swimming.

### Main Program:
- **`Main`** class provides a menu-driven system to allow users to select a duck and observe its behaviors.


