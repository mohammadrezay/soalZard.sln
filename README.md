# soalZard.sln
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
