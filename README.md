<?xml encoding="UTF-8" ?>

# Me

Hi! I'm a programmer for DuckDev helping create A Link Between Ages.

![photo](https://avatars1.githubusercontent.com/u/9050447?v=3&s=460)


# Programming

I've participated in this project in these areas primarily:
- UML
- Animation Loading
- Scene Loading
- Scene Changing



### UML

When starting a project we must analyze wich resources we have and wich are we going to need. From a base of several modules we had to decide the optimal way of organizing our game's code. 

![uml](http://i.imgur.com/XOnmjrg.png)
Click [HERE](http://i.imgur.com/XOnmjrg.png) to see the UML bigger.


### Animation Loading

Once we had how our base we had to add a way to load sprites, manage the individual images and tell the rendered how manage them to create animations.


![Anim](https://i.gyazo.com/338e313f6883500257d21d3e45ae382a.gif)
The previous is a test run with a Diablo sprite.

### Scene Loading

Once we had our resources running, we had to filter which information was needed for each scene and handle how we store and access this data. Instead of creating a different class for each scene we created a method to load data from XML files for designers to use at their will.

![Scene Load](https://i.gyazo.com/33631512007bd89f1434f2e26b02ad52.png)



### Scene Changing

Now that we had scenes loading we had to handle how we changed between scenes. Exits are loaded from the XML and specify where they are and to where they lead. One the exit triggers, the game's control changes to our hands and we handle all data to be removed and preserved until the next scene is completly loaded for the player to continue.


