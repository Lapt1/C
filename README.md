using System;

namespace 
{
    class Program
    {
        static void Main(string[] args)
        {

            int[] arr = { 1,2,4,3,4,5,3,2,4,5,6,4,3,4,5,3,4,5,34,4};
            for (int i = 2; i < arr.Length; i += 3)
            {
                Console.WriteLine(arr[i]); 
            } 
                
        }
    }
}
