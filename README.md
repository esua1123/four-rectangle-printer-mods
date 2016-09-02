# four-rectangle-printer-MODS
Modifications to FourRectanglePrinter programming assignment: pg.74 #1

import java.awt.*;

public class PrintRectanglesMod
{
	public static void main(String[] args)
	{
		Rectangle fibBOnnaXxi = new Rectangle(0,0,8,13);
		
		System.out.println(fibBOnnaXxi);
		
		fibMoreNaxis(fibBOnnaXxi);
	}
	
	public static void fibMoreNaxis(Rectangle fibBOnnaXxi)
	{
		fibBOnnaXxi.translate(8,0);
		System.out.println(fibBOnnaXxi);
		
		fibBOnnaXxi.translate(0,13);
		System.out.println(fibBOnnaXxi);
		
		fibBOnnaXxi.translate(-8,0);
		System.out.println(fibBOnnaXxi);
	}
}
