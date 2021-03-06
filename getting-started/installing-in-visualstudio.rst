Adding DockPanel Suite to Toolbox in Visual Studio
==================================================

By `Lex Li`_

This page shows you how to install DockPanel Suite to your project on Windows. 

.. contents:: In this article:
  :local:
  :depth: 1

Recommended Steps
-----------------
1. Follow :doc:`/getting-started/installing-on-windows` to compile DockPanel Suite binaries. 

2. Open Visual Studio, and navigate to its Toolbox panel.

3. Expand a tab such as General, or create a new tab by right clicking and choosing "Add Tab" menu item.

4. Right click in the tab area and choose "Choose Items..." menu item.

5. Under the ".NET Framework Components" "Choose Toolbox Items" dialog, click the "Browse..." button.

6. In the "Open" file dialog, navigate to ``bin\net40`` folder that contains the assemblies, and choose all related 
files (WerifenLuo.WinFormsUI.Docking.dll, ThemeVS2003.dll, ThemeVS2012Light.dll, and ThemeVS2013Blue.dll).

7. Click the "Open" button to exit the dialog.

8. In ".NET Framework Components" tab, click "Namespace" column header to reorder the list.

9. Make sure that "DockPanel", "VS2003Theme", "VS2005Theme", "VS2012LightTheme", and "VS2013BlueTheme" are checked.

10. Click the "OK" button to exit the dialog.

Related Resources
-----------------

- :doc:`/getting-started/installing-on-windows`
- :doc:`/getting-started/history`
- :doc:`/tutorials/basics`
- :doc:`/themes/existing-themes`