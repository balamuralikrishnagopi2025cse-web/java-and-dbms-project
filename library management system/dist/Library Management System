
Set shell = CreateObject("WScript.Shell")
Set fso = CreateObject("Scripting.FileSystemObject")

folder = fso.GetParentFolderName(WScript.ScriptFullName)
shell.CurrentDirectory = folder

shell.Run "javaw -cp ""library_management_system.jar;lib\*"" loginpage", 0, False
