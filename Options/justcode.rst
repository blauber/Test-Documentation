Just Code
=========
Key Goals
---------

Options
-------

Scratch
~~~~~~~

KidsRuby
~~~~~~~~

Python
~~~~~~

Here is some code::

    # This program adds up integers that have been passed as arguments in the command line
    import sys
    try:
        total = sum(int(arg) for arg in sys.argv[1:])
        print ('sum =', total)
    except ValueError:
        print ('Please supply integer arguments')

And here is some C# code just in case
you wanted to see it::

    using System;
    using System.Collections.Generic;
    using System.Linq;
    using System.Text;
    using System.Threading.Tasks;

    namespace CSharpTutorials
    {
        class Program
        {
            static void Main(string[] args)
            {
                string message = "Hello World!!";

                Console.WriteLine(message);
            }
        }
    }



Hopscotch
~~~~~~~~~
