<h1>Making a C++/CLR Windows Form Application in Visual Studio</h1>

To install CLR, It can be found by configuring the Visual Studio Installer.
You will also need .NET framework 4.7.2 what can be found below or you can retarget the solution via the project settings.

.NET Framework 4.7.2: https://dotnet.microsoft.com/en-us/download/dotnet-framework/thank-you/net472-developer-pack-offline-installer
#

C++ Windows forms. It focuses standard C++, not C++/CLI. The main difference between the example from this git and a C++ application is, that instead of using the console for user interaction - 

```cout << "Hello world" << endl;```

you can use a Windows control, e.g. a TextBox

```textBox1->AppendText("Hello World");```
