using System;
					
public class Program
{
	public static void Main()
	{
		 string[] fruits = { "banana", "apple", "orange", "pear", "grape", "pineapple" };
            Console.WriteLine("Enter the fruit you would like to find:");
            string searchWord = Console.ReadLine();
            bool isFound = LinearSearch(fruits, searchWord);
            Console.WriteLine(isFound);
        }
        static bool LinearSearch(string[] array, string target)
		{
            for (int index = 0; index < array.Length; index++)
            {
                if (array[index] == target)
                {
                    return true;
                }
            }
            return false;
	}
}
