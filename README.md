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

<img width="324" alt="Screenshot 2025-05-18 at 21 58 31" src="https://github.com/user-attachments/assets/f6e972e6-5bd9-4c3e-a52b-b09b92751ce3" />
<img width="324" alt="Screenshot 2025-05-18 at 21 58 59" src="https://github.com/user-attachments/assets/09af56d5-de55-44dc-9193-d984c9c94840" />
