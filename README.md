# NPulley.github.io
## Programming Portfolio : Projects

### Journey Home
![JourneyHome](https://github.com/NPulley33/NPulley.github.io/assets/149650114/b5f6e416-5f54-4508-b2ce-c4d5ae232967)

Programming 101 Midterm Project: Coded in C# <br>
You are a lonely traveler in Ancient Greece who is trying to find their way back to their family. You must make 10 moves forward to reach home. Along the way, you can make different pathing options, like exploring sites along the road or reaching forks in the road. At these intersections, you have a chance to encounter a NPC from the mythos. The NPC will offer you a boon for your journey, however, the boon has the potential to be good, which will move you forward faster, or to be bad, which will set you back on your journey. Each NPC has a different list of boons, with different odds to get a good or bad outcome.  
<br>

### Ghostman
![Ghostman SSH 1](https://github.com/NPulley33/NPulley.github.io/assets/149650114/d2856d04-c603-46e2-a904-e1016c06ebcc)

Personal Project: Coded in Java <br>
After taking AP Computer Science, this was a personal project made to see what I could do with what I had learned in the class. I worked with building out a minigame in a 2D environment while building new features. Features included an inventory, main menu and pause screens, an animated walk cycle, and more. <br>
Sample Code: <br>
```
import java.awt.Graphics;
import java.awt.image.BufferedImage;
import java.io.File;
import java.io.IOException;
import javax.imageio.ImageIO;
//import java.awt.Color;

public class Key extends GameObject {

    private BufferedImage display;
    
    public Key(int x, int y, String s) {
        super (x, y);
        this.width = 50;
        this.height = 50;
        try {
            display = ImageIO.read(new File("Key" + s + ".png"));
        } catch (IOException e) {
            display = null;
            System.err.println(e + " file: Key.png");
        }
    }

    @Override
    public void paint(Graphics g) {
        g.drawImage(display, (int)this.xPos, (int)this.yPos, null);
        //g.setColor(Color.WHITE); //shows hitboxes
        //g.drawRect((int) this.xPos, (int) this.yPos, this.width, this.height);
    }
    //@Override
    public void update() {

    }
    

    public void setLocation(double x, double y){
        this.xPos = x;
        this.yPos = y;
    }

}
```

### Tip Calculator 
Programming 101 in class demo: Coded in C# <br>
An in class demo that created a [Tip Calculator](https://gist.github.com/NPulley33/797af3cb004f54763b08b259bef83bec) to calculate an amount to tip based on the bill total and tip amount given. Also served as an introduction to exception handling and input validation. 

### Trivia Game
Programming 101 in class demo: Coded in C# <br>
An in class demo that created a quick Trivia Game. Topics covered/used: state machine using a switch/case, properties, overloaded consturctors, custom classes, & reading in external data.

### Introduction to using WPF
![image](https://github.com/NPulley33/NPulley33.github.io/assets/149650114/54d19ada-f709-453e-9912-58ea1aa9676b)
![image](https://github.com/NPulley33/NPulley33.github.io/assets/149650114/bf6fa8d7-73fb-48d9-882e-b4d525f970ed) <br>

Programming 101 in class demo: Coded in C# <br>
An in calss demo that served as an introduction to using WPF Applications. Topic covered/used: buttons & radio buttons, shapes, text block & boxes, colors, linking C# scripts to XMAL. 





