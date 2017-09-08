If I'm missing roslyn/cs.exe when i run it (CTRL + F5), Then
- Open Tools > NuGet Package Manager> Package Manager Console...
- Type update-package Microsoft.CodeDom.Providers.DotNetCompilerPlatform -r 
- If you are still having problems, also type the following in the Package Manager Console:
	- update-package -reinstall