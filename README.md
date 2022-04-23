# for-loop
using System;
using System.IO;
using System.Linq;
using System.Collections.Generic;

namespace CSharp_Shell
{

    public static class Program 
    {
        public static void Main() 
        {
        	int i=0;
        	Console.WriteLine("Even num:");
        	for(i=1;i<=10;i++)
        	{
        		if(i%2==0)
        		{
        			Console.Write(i+" ");
        		}
        	}
           
        }
    }
}
