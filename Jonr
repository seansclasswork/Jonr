import java.applet.Applet;
import java.awt.*;

import java.applet.Applet;
import java.awt.*;
import java.awt.Font.*;


public class Jonr extends Applet
{

   public void paint(Graphics page)
   {
      Font myFont = new Font("ComicSans",Font.BOLD, 40);
      page.setFont(myFont);
      for(int x = 0; x<1000; x++)
      {
         page.setColor(Color.GREEN);
         page.fillRect(0, 0, 400, 400);
         page.setColor(Color.PINK);
         page.drawString("JONR", 200, 200);
         
         try
         {
            Thread.sleep(10);
         }
         catch(InterruptedException ex)
         {
            Thread.currentThread().interrupt();
         }
         
         page.setColor(Color.PINK);
         page.fillRect(0, 0, 400, 400);
         page.setColor(Color.GREEN);
         page.drawString("JONR", 200, 200);
         
         try
         {
            Thread.sleep(10);
         }
         catch(InterruptedException ex)
         {
            Thread.currentThread().interrupt();
         }
      }
   }
}
