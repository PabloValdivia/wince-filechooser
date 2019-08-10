wince-filechooser
=================

Description
-----------
FileChooser .NET CF 3.5 (Windows Mobile 5.0, 6.0, 6.5).


Features
--------
- Copyright: INGEIT <https://www.ingient.com>, Saúl Piña <sauljabin@gmail.com>
- License: LGPL 3
- Language: C#, .NET CF 3.5 (Windows Mobile 5.0, 6.0, 6.5)
- IDE: Visual Studio 2008
- Version: v1.0.0


Example
-------

```
string selectedPath = "";
FileChooser fileChooser = new FileChooser();
fileChooser.Text = "Title";
if (fileChooser.ShowDialog() == DialogResult.OK) {
	selectedPath = fileChooser.CurrentFile;
}
```


PrintScreen Example
-------------------
![](/documents/printscreen-1.png)
