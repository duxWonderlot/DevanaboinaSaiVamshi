### Hi there!

you stumble upon the portfolio of Devanaboina Sai Vamshi(Game Programmer, Game Collector, game technology enthusiast)

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

## Major Project

Currenly Working on my https://youtu.be/oo1xqFDnayA[Major Project], Which is an Semi-Open World FPS Action RPG made in Unity, I have also worked on Other Game Engines like Unreal,Game Maker,RPG Maker

Worked on Libraries like LibGDX, Box2D, OpenGL, WebGL
## FunSide Projects

Made More Than 3 Unpublished Mobile Games 

here are Games That was published Till now for free on Itch.io
[Checkout](https://bustingjam.itch.io/)

I have also participated in Number of Game Jams like IGDC , Nasscom , Unreal Jam , Brackeys Game Jam and many more
Also worked on AR boardgame made in Unity
## Worked on TeamProjects

I have worked on Games like De-light(Gameplay Programmer) , Getout(as asset modeller), Farm In Harm(Gameply Programmer) , Brain's Life(GamePlay Programmer) , Refugee(Junior Programmer , Asset Modeller)


Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Code that i am Proud of written in java
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

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

###  

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/duxWonderlot/portfolio/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
