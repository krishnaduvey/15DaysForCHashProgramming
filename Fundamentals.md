
Versions :

VS     : 2019 version 16.3
C#     : 8.0
WCF    :  
.Net Framework : 4.8 
.Net Core : 3.0.2 { Next will be 3.1.1 }


The most recent version is 8.0, which was released in 2019 alongside Visual Studio 2019 version 16.3.








#### C# Basics :

    The Main method is the entry point of an executable program; it is where the program control starts and ends.
    Main is declared inside a class or struct. Main must be static and it need not be public. 
    (In the earlier example, it receives the default access of private.) 
    The enclosing class or struct is not required to be static.
    Main can either have a void, int, or, starting with C# 7.1, Task, or Task<int> return type.
    If and only if Main returns a Task or Task<int>, the declaration of Main may include the async modifier. 
    Note that this specifically excludes an async void Main method.
    The Main method can be declared with or without a string[] parameter that contains command-line arguments. 
      When using Visual Studio to create Windows applications, you can add the parameter manually or else 
      use the GetCommandLineArgs() method to obtain the command-line arguments. 
      Parameters are read as zero-indexed command-line arguments. Unlike C and C++, 
      the name of the program is not treated as the first command-line argument in the args array, 
      but it is the first element of the GetCommandLineArgs() method.


The following is a list of valid Main signatures:

    public static void Main() { }
    public static int Main() { }
    public static void Main(string[] args) { }
    public static int Main(string[] args) { }
    public static async Task Main() { }
    public static async Task<int> Main() { }
    public static async Task Main(string[] args) { }
    public static async Task<int> Main(string[] args) { }
    
    
