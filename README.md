# soalZard.sln

- **Link:** [Quera Problem #3537](https://quera.org/problemset/3537)
- **Description:** Given an integer *n*, print the word “Woow!” with the number of 'o' letters equal to *n + 1* (“Wow!” for n=1, “Woow!” for n=2, etc.).
- **Solution:** Implemented in C#.
  
namespace soalZard
{
    internal class Program
    {
        static void Main(string[] args)
        {
            //Console.WriteLine("Enter a number between 1 to 10:");
            int n = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("W" + new string('o', n) + "w!");
        }
    }
}
