# Hi there!

You stumble upon the portfolio of Devanaboina Sai Vamshi(GamePlay Programmer, Game Collector, game technology enthusiast)

## Major Project

Currenly Working on my [Major Project](https://youtu.be/oo1xqFDnayA), Which is an Semi-Open World FPS Action RPG made in Unity, I have also worked on Other Game Engines like 
Unreal,Game Maker,RPG Maker
Worked on Libraries like LibGDX, Box2D, OpenGL, WebGL

## FunSide Projects

Made More Than 3 Unpublished Mobile Games 

## Here are Games That was published Till now for free on Itch.io [Checkout](https://bustingjam.itch.io/)

I have also participated in Number of Game Jams like 
-**IGDC**

-**Nasscom**

-Unreal Jam

-**Brackeys Game Jam and many more**

-**Also worked on AR boardgame made in Unity**

## Worked on TeamProjects

I have worked on Games like:-

-**De-light(Gameplay Programmer)**

-Getout(as asset modeller)

-**Farm In Harm(Gameplay Programmer)**

-**Brain's Life(GamePlay Programmer)**

-**Refugee(Junior Programmer , Asset Modeller)**


## Some Thing Interesting
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
 
### Contact
You can contact me from [LinkedIn](https://in.linkedin.com/in/devanaboina-sai-vamshi-218300156)
 
### CopyRight@ 2019 [duxWonderlot](https://duxwonderlot.github.io/portfolio/). All Rights Reserved.

 
