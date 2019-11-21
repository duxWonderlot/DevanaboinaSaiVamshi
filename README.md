<img src="img/bg1.png">
# Hi there!
  
You stumble upon the portfolio of Devanaboina Sai Vamshi
(GamePlay Programmer, Game Collector, game technology enthusiast,Technical Artist)
 
## Major Project(Project Cybernet)

Currently Working on my (**Rapid Prototype**)**[Major Project](https://youtu.be/oo1xqFDnayA)**, Which is an Semi-Open World FPS Action RPG made in Unity, I have also

### Build tools for designers to easy create vertical cities for the game
<img src="img/Screenshot_259.png">

### Build an Quest System Tool for designers for Interactive StoryTelling 
<img src="img/Screenshot_267.png">

### Made a Sword Combat System for Cyber Samurai Class in the Game Project Cybernet 
<img src="img/Screenshot_263.png">

### Did Animation Programming with VFX Integrated
<img src="img/Screenshot_264.png">

### Elevator Mechanic For the Game
<img src="Screenshot (167).png">
 
worked on Other Game Engines like 
Unreal,Game Maker,RPG Maker
Worked on Libraries like LibGDX, Box2D, OpenGL, WebGL

### Final Output for Showcase
<img src="cn.png">
<img src="projectcn.png">
[**Game Trailer of Project Cybernet**](https://youtu.be/7CapVknboG8)
### FunSide Projects
Made More Than 6 Unpublished Mobile Games
## Worked(Out Sorcing) 
# French Company
   Task: Different Types of AI's for a Cyberpunk Game  
    Role: AI Programmer
<img src="frc.png">
<img src="frc_1.png">
# Worked for Indie Company
   Made Air Hockey AI  
    Role: Games Programmer
  
**Ai Showcase**
[-**Crowd Simulation** ](https://youtu.be/AQYjHYnetUE) 

**3D-Platformer** 
[-**Brain's Life(GamePlay Programmer)**](https://www.youtube.com/watch?v=9DbjPjFcU34&t=3s)
## Game Jams Participated 

**Farm in Harm (Nasscom Game Jam 2016) UI Programmer**

-**GetOut NGDC 2017(Asset Modeller)**

-**Refugee(Junior Programmer , Asset Modeller)**

[-**WarOfTheLastSamurai(GMTK 2019)**](https://cyberq.itch.io/warofthelastsamurai)

[-**FillTheVoidInSpace(GamesPlusJams Game Jam)**](https://cyberq.itch.io/fillthevoid-arcade)

[-**DeLight(GMTK 2018 , Level Designer, GamePlay Programmer)**](https://suryavamsikk.itch.io/de-light) **Many More Jams.......**

## Tech Demo RTX 

[**Rtx_Tech_demo**](https://youtu.be/_Np7S2dD5jQ)

## Tech Demo Ecs 

[**Ecs_Tech_demo**](https://cyberq.itch.io/ecs-experience)

## Interesting Mechanics for 2d parkour Game 
 
<img src="Screenshot (61).png">
 Automatic Parkour System using Raycasts in Unity

### this is Interesting code blocks of the Game Spectrum 
```markdown
Code that i am Proud of written in java for the game Spectrum which was inspired from a game called "Hue"
 private Body createbody1(float x , float y , float width, float height, boolean isStatic , World world){


        //--------Create------//

        if (isStatic)
            bodyDef.type = BodyDef.BodyType.StaticBody;
        else
            bodyDef.type = BodyDef.BodyType.DynamicBody;
        bodyDef.position.set(x / PPM, y / PPM);
        //.fixedRotation = true;


        PolygonShape shape = new PolygonShape();
        shape.setAsBox(width / 2 / PPM, height / 2 / PPM);          // taking bodies position
        fixtureDef.shape = shape;
        fixtureDef.friction = 0.5f;
        fixtureDef.restitution = 0.0f;
        fixtureDef.density = 0.0f;

        this.body = world.createBody(bodyDef);
        this.body.createFixture(fixtureDef).setUserData(this);



        return body;

    }
 
```
this is small chuck of code that was used in Spectrum Game
```markdown
//fasinated codeblock written in java
  public void beginContact(Contact contact) {


                                         fix  = contact.getFixtureA();
                                         fix1 = contact.getFixtureB();



    if(contact.getFixtureA().getBody() ==crate && contact.getFixtureB().getBody() == Texbody
                         ||contact.getFixtureA().getBody() ==Texbody && contact.getFixtureB().getBody() == crate){

                              System.out.print("Collision happend");
                              // player.destroyFixture(fixture1);
                            ((Game)Gdx.app.getApplicationListener()).setScreen(new level2());// this is used for screen change

                                         }

 
```
level design and color change in the game 
```markdown
//fasinated codeblock written in java

   public void Colorchange(float r , float g , float b , float a) {

      // r = 0; g = 0.0f ; b = 0.0f; a = 1.0f;

        rayH.setAmbientLight(r, g, b, a);
    }
    //this is how i level designed my game
    
    batch.draw(tex,1000,-280,200,200);
        batch.draw(tex,800,-280,200,200);
        batch.draw(tex,600,-280,200,200);
        batch.draw(tex,0,-280,200,200);
        batch.draw(tex,400,-280,200,200);
        batch.draw(tex,600,-280,200,200);
        batch.draw(tex,200,-280,200,200);
        batch.draw(tex,-200,-280,200,200);
        batch.draw(tex,-400,-280,200,200);
        batch.draw(tex,-600,-280,200,200);
        batch.draw(tex,-800,-280,200,200);
        batch.draw(tex,-1000,-280,200,200);

        //titles of the top platform
        batch.draw(tex,1000,160,200,200);
        batch.draw(tex,800,160,200,200);
        batch.draw(tex,0,  160,200,200);
        batch.draw(tex,400,160,200,200);
        batch.draw(tex,600,160,200,200);
        batch.draw(tex,200,160,200,200);
        batch.draw(tex,-200,160,200,200);
        batch.draw(tex,-400,160,200,200);
        batch.draw(tex,-600,160,200,200);
        batch.draw(tex,-800,160,200,200);
        batch.draw(tex,-1000,160,200,200);
        batch.end();
        
        
    
```
for Optimization in the Physics Library
```markdown
//this is how i have destroy objects in the game
 Obstruc.setActive(false);
 Obstruc1.setActive(false);
 Obstrcu2.setActive(false);
 ```
 
### Resume 
[CheckoutResume](https://github.com/duxWonderlot/DevanaboinaSaiVamshi/blob/master/D%20Sai%20Vamshi%20resume%20pdf.pdf) 
 
### Contact
You can contact me from [LinkedIn](https://in.linkedin.com/in/devanaboina-sai-vamshi-218300156)
 
### CopyRight© 2019 [duxWonderlot](https://duxwonderlot.github.io/portfolio/). All Rights Reserved.

 
 
