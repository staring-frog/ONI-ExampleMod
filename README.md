# ONI-ExampleMod
Sample Visual Studio solution to help you started with a new mod for Oxygen not Included.

Requirements
------------
* .NET Framework 3.5
* Visual Studio 2017

Getting started
---------------
* Do the "Installation" part of https://github.com/javisar/ONI-Modloader
* Copy the following files from ONI's `OxygenNotIncluded_Data\Managed` folder to this project's `\lib\`:
   * `Assembly-CSharp.dll`
   * `Assembly-CSharp-firstpass.dll`
   * `Assembly-UnityScript-firstpass.dll`
   * `UnityEngine.dll`
   * `UnityEngine.UI.dll`
* Build (.dll will get copied to ONI `Mods` dir);
* Run the game.