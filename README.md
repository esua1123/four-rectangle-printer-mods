# four-rectangle-printer-mods
Modifications to FourRectanglePrinter programming assignment: pg.74 #1

import java.awt.*;

public class PrintRectanglesMod
{
	public static void main(String[] args)
	{
		Rectangle fibBonnaXxi = new Rectangle(0,0,8,13);
		
		System.out.println(fibBonnaXxi);
		
		fibMoreNaxis(fibBonnaXxi);
	}
	
	public static void fibMoreNaxis(Rectangle fibBonnaXxi)
	{
		fibBonnaXxi.translate(8,0);
		System.out.println(fibBonnaXxi);
		
		fibBonnaXxi.translate(0,13);
		System.out.println(fibBonnaXxi);
		
		fibBonnaXxi.translate(-8,0);
		System.out.println(fibBonnaXxi);
	}
}
