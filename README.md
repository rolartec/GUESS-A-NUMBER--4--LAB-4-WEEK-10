GUESS-A-NUMBER--4--LAB-4-WEEK-10
================================

Guess a number-4 ,  Lab#4 week 10 BY REINA OLARTE


//  BY  REINA OLARTE
//  RANDOM NUMBER LAB #4  WEEK 10

public class RandomNumber 
{
	int computerNumber;
	int LowNumber;
	int HighNumber;
	public RandomNumber(int high)
	{
		HighNumber = high;
	}
	public RandomNumber(int low, int high)
	{
		HighNumber = high;
		LowNumber = low;
	}
	public int getHighNumber()
	{
		return HighNumber;
	}
	public int getLowNumber()
	{
		return LowNumber;
	}
	public int GetANumber()
	{
		computerNumber = (LowNumber + (int)(Math.random() * (HighNumber-LowNumber)));
		return computerNumber;
	}
	public int GetANumber(int low, int High)
	{
		computerNumber = (low + (int)(Math.random() *(High-low)));
		return computerNumber;
	}
	public int GetANumber(int High)
	{		
		computerNumber = 0 + (int)(Math.random() *High);
		return computerNumber;
	}
	public int setLowNumber(int low)
	{
		LowNumber = low;
		return LowNumber;
	}
	public int setHighNumber(int high)
	{
		HighNumber = high;
		return HighNumber;
	}
}
