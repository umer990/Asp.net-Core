# Asp.net-Core



Install the .NET SDK
To start building .NET apps you just need to download and install the .NET SDK (Software Development Kit).


Create your app
Open a new command prompt and run the following commands:

dotnet new console -o myApp
cd myApp
The dotnet command creates a new application of type console for you. The -o parameter creates a directory named myApp where your app is stored, and populates it with the required files. The cd myApp command puts you into the newly created app directory.

The main file in the myApp folder is Program.cs. By default, it already contains the necessary code to write "Hello World!" to the Console.

using System;

namespace myApp
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World!");
        }
    }
}
Run your app
In your command prompt, run the following command:

dotnet run
Congratulations, you've built and run your first .NET app!

Get an editor
Visual Studio is a fully-featured integrated development environment (IDE) for developing .NET apps on Windows
