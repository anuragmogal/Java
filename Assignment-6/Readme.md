This is the directory for the Assignment 6: Duck

This folder contains 16 java files out of which 13 are classes and 3 are interfaces:

Main
Duck (Abstract Class)
MallardDuck
RubberDuck
DecoyDuck
FlyBehavior (interface)
FlyWithWings
FlyNoWay
QuackBehavior (interface)
Quack
MuteQuack
Squeak
SwimBehavior (interface)
SwimChhapChhap
Float
Drown
Main.java does the following functions: It executes the display, performSwim, performFly and performQuack methods for all the Duck subclasses MallardDuck, RubberDuck and DecoyDuck.

Duck.java contains:

Variables of all the interfaces for behavior: FlyBehavior, QuackBehavior, SwimBehavior
display(): Abstract method which print out which is Duck it is.
setFlyBehavior(): Set the variable of FlyBehavior to appropriate class
setQuackBehavior(): Set the variable of QuackBehavior to appropriate class
setSwimBehavior(): Set the variable of SwimBehavior to appropriate class
MallardDuck.java contains:

display(): Implementation of abstract method of Duck class which tells which duck it is.
MallardDuck(): Constructor of MallardDuck class setting up different behaviors
RubberDuck.java contains:

display(): Implementation of abstract method of Duck class which tells which duck it is.
RubberDuck(): Constructor of RubberDuck class setting up different behaviors.
DecoyDuck.java contains:

display(): Implementation of abstract method of Duck class which tells which duck it is.
DecoyDuck(): Constructor of DecoyDuck class setting up different behaviors.
FlyBehavior.java contains: It's an interface with

fly(): Abstract method to be implemented in each class defining the particular fly behavior for ducks
FlyWithWings.java contains:

fly(): Implementation of method fly from FlyBehavior saying this duck can fly.
FlyNoWay.java contains:

fly(): Implementation of method fly from FlyBehavior saying this duck can't fly.
QuackBehavior.java contains: It's an interface with

quack(): Abstract method to be implemented in each class defining the particular quack behavior for ducks
Quack.java contains:

quack(): Implementation of method quack from QuackBehavior saying that this duck makes quack sound
MuteQuack.java contains:

quack(): Implementation of method quack from QuackBehavior saying that this duck can't make quack sound.
Squeak.java contains:

quack(): Implementation of method quack from QuackBehavior saying that this duck makes squeak sound
SwimBehavior.java contains: It's an interface with

swim(): Abstract method to be implemented in each class defining the particular swim behavior for ducks
SwimChhapChhap.java contains:

swim(): Implementation of method swim from SwimBehavior saying that this duck can swim.
Float.java contains:

swim(): Implementation of method swim from SwimBehavior saying that this duck can float.
Drown.java contains:

swim(): Implementation of method swim from SwimBehavior saying that this duck can't swim.
