Hello DNX Sample (Debug with Visual Studio code)

if getting error below
​
Building ConsoleApp for DNX,Version=v4.5.1
Error: Exception has been thrown by the target of an invocation.

Fix it by installing mono-devel as well as mono-complete.


To be able to debug project , we need to generate .exe file

To do this;

Build task (xbuild) 
builds project using hellodnx.csproj and generate exe file

launch starts process with debug enabled


--------------------------------------------
dnu build assemblies cannot be debugged yet with vs code