### Hi there!

you stumble upon the portfolio of Devanaboina Sai Vamshi(Game Programmer, Game Collector, game technology enthusiast)
 
## Major Project

Currenly Working on my [Major Project](https://youtu.be/oo1xqFDnayA), Which is an Semi-Open World FPS Action RPG made in Unity, I have also worked on Other Game Engines like 
Unreal,Game Maker,RPG Maker

Worked on Libraries like LibGDX, Box2D, OpenGL, WebGL
## FunSide Projects

Made More Than 3 Unpublished Mobile Games 

here are Games That was published Till now for free on Itch.io
[Checkout](https://bustingjam.itch.io/)

I have also participated in Number of Game Jams like 
IGDC
Nasscom
Unreal Jam
Brackeys Game Jam and many more
Also worked on AR boardgame made in Unity

## Worked on TeamProjects

I have worked on Games like:-

De-light(Gameplay Programmer)
Getout(as asset modeller)
Farm In Harm(Gameply Programmer)
Brain's Life(GamePlay Programmer)
Refugee(Junior Programmer , Asset Modeller)


## Some Thing Interesting
```markdown
Code that i am Proud of written in java for the game Spectrum which was inspired from a game called "Hue"
 private Body createbody1(float x , float y , float width, float height, boolean isStatic , World world){


        //------------crate------//

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
 
# CopyRight@ 2019 [duxWonderlot](https://duxwonderlot.github.io/portfolio/). All Rights Reserved.

 
