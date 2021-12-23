<h1>Making a C++/CLR Windows Form Application in Visual Studio</h1>

To install CLR, It can be found by configuring the Visual Studio Installer.
#

C++ Windows forms. It focuses standard C++, not C++/CLI. The main difference between the example from this git and a C++ application is, that instead of using the console for user interaction - 

```cout << "Hello world" << endl;```

you can use a Windows control, e.g. a TextBox

```textBox1->AppendText("Hello World");```
