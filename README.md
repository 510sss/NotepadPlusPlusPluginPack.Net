# NppPlugin .NET package for VS2015 and beyond...

This is a fork of UFO's plugin package updated for VS2015

## Getting started
  1. Download a [release](https://github.com/kbilsted/NotepadPlusPlusPluginPack.Net/releases/) and unzip it
  2. Place the visual studio project template (the `Visual Studio Project Template C#\NppPlugin.zip`) in the visual studio path (typically `"My Documents\Visual Studio 2015\Templates\ProjectTemplates\Visual C#\"` but see [instructions](https://github.com/kbilsted/NotepadPlusPlusPluginPack.Net/blob/master/Visual%20Studio%20Project%20Template%20C%23/HOW-TO-INSTALL-ME.txt) inside the release)
  3. Ensure you have installed **Visual C++** from the visual studio installer otherwise your project wont build
  4. Create a new project inside Visual studio using `file -> new -> project -> visual C# -> Notepad++ project`
  5. Build (building will copy the dll to the `Notepad++/plugins` folder)
  6. Start Notepad++ and activate your plugin from the plugins menu

## Content information
This package contains two folders:

  1. Templates:
    Simple templates for very fast and even easier building of .NET plugins for Notepad++.
    Setting up a plugin for N++ has never ever been as easy as with this package.
    Please see the containing txt files for further installation information.

  2. Demo:
    An example .NET plugin for Notepad++, build upon the template above.
    It demonstrates the same functionality as the original demo plugin by Don Ho:
    http://download.tuxfamily.org/nppplugins/NppPluginDemo/NppPluginDemo.zip

    
    
## Credits

  * For the main work on the plugin package
    * A Guy called "Ufo" - merging in v0.5 http://sourceforge.net/projects/sourcecookifier/files/other%20plugins/NppPlugin.NET.v0.5.zip/download and v0.7 https://bitbucket.org/uph0/npppluginnet 
  * The DllExport technique:
    * Dark Daskin: http://www.codeproject.com/KB/dotnet/DllExporter.aspx
    * Robert Giesecke: http://sites.google.com/site/robertgiesecke/Home/uploads/csharpprojecttemplateforunmanagedexports https://www.nuget.org/packages/UnmanagedExports


## Requirements:
  * works with .NET Runtime 2.0 and above
  * UNICODE only! ANSI is doable, but not supported so far

