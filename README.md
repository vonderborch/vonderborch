<!--
**vonderborch/vonderborch** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# My Personal Projects

## Latest Updates
2022/08/05:
- Added FnaUpdater to Apps section - a way to keep FNA up-to-date more easily
- Added SolutionCreator to Apps section - a way to create solution templates without relying on Visual Studio directly
- Further cleaned up this readme

2022/08/04:
- Big batch of new libraries I've been working on in spare time: Velentr.Debugging, Velentr.AbstractShapes, Velentr.Scaling, Velentr.Resolution
- Reorganized List to be alphabetical

## Possible Repo States
The possible states I'm defining for my repos:
| State | Description |
| ----- | ----------- |
| **Active** | Supported and up-to-date, no major breaking changes planned |
| **Active - Refactoring Planned** | Supported and up-to-date, but the code is messy and could be made cleaner to improve maintainability and/or perforamnce |
| **Active - Extensive Rework Planned** | Supported and up-to-date, but there may be breaking changes coming in the future (will try to limit these where possible!) |
| **Active - Unstable** | Don't rely on this repo! Things may shift out of it at a moment's notice as I see fit! |
| **Development** | Working on this developing this repo currently. Will be released soon(TM) |
| **Private** | Working on this primarily for myself, may release at some point if I can see a reason why (mostly listed here to keep myself organized!) |
| **Paused** | Work has paused on this repo, but I want to return to it at some point |
| **Up-To-Date with Base Repo** | Fork from another repo with minimal changes, key in-sync with changes in base repo |
| **Abandoned/Archived** | No longer supported. Code is as-is (and likely terrible!) |

## Games
Games that I've created
Repo | Language | State | Summary
---- | -------- | ----- | -------
[CS323](https://github.com/vonderborch/CS323) | C# | Abandoned/Archived | A Bullet-Hell style game that was created for one of my classes in college (pretty rough code, but it did function and was pretty fun (balance aside)

<!--
[](https://github.com/vonderborch/) | C# | Active | A project to 
-->

## Apps
Apps that I've created
Repo | Language | State | Summary
---- | -------- | ----- | -------
[ColumnCopier](https://github.com/vonderborch/ColumnCopier) | C# | Paused (rework desired) | A project to copy spreadsheet data (seperated by tabs, spaces, semi-colans, etc.) and display it in column format (and allow copying of single columns, etc.). Handy for working with databases
[FnaUpdater](https://github.com/vonderborch/FnaUpdater) | C# | Active | A way to install and keep FNA up-to-date
[FolderSync](https://github.com/vonderborch/FolderSync) | C# | Abandoned/Archived | A project to keep two files in a source destination synced with a destination destination
[SolutionCreator](https://github.com/vonderborch/SolutionCreator) | C# | Active | A program that allows for creating solutions from custom-built templates. Not a great alternative to what is built-into Visual Studio, but can be easier to use when doing a complex template
[Stellaris Ironman Save Toggler](https://github.com/vonderborch/stellaris_ironman_toggle) | C# | Active | Toggles a Stellaris Ironman Save between being Ironman and not
[ToDoList](https://github.com/vonderborch/To-Do-List) | C# | Active | A simple to-do-list app I made for myself

<!--
[](https://github.com/vonderborch/) | C# | Active | A project to 
-->

## Bots
Bots that I've created
Repo | Language | State | Type | Demo/Link | Summary
---- | -------- | ----- | ---- | --------- | -------
[RandomizerBot](https://github.com/vonderborch/RandomizerBot) | C# | Paused | Discord | N/A | A simple (and pretty badly implemented atm) Discord bot used for personal purposes

<!--
[](https://github.com/vonderborch/) | C# | Active | Discord | N/A | A project to 
-->

## Packages - Game-dev Focused
Projects that I've worked on that are primarily meant to help with game or app development.

The overarching "utility" name I'm using right now is [Velentr](https://en.wikipedia.org/wiki/Wayland_the_Smith). I've tried many times making games only to get bogged down reworking the engine so many times nothing ever happens. With my latest attempt, I'm trying something different by taking a page from micro-services and working on/packaging different components of the overall engine/framework separately. This way even if I have plans to rework things, the impact to other packages can be made relatively small...most of the time. Hopefully this will keep me more on track (unless I decide to switch entirely to UE5 :) ).

All of these repos are written in C#.

#### Notes
Due to the timespan some of these libaries have developed over, I can't guarentee they will all work together anymore, particularly any FNA flavored ones. Also _most_ of the packages have broken FNA nuget packages (only the most recent or recently updated ones have been fixed).

There is also plenty of code duplication and places where I have helper packages that I created _after_ releasing another package and now I need to go back and utilize the helper everywhere I can.

#### Packages/Repos
Repo | State | Summary
---- | ----- | -------
[Velentr.AbstractShapes](https://github.com/vonderborch/Velentr.AbstractShapes) | Active | Generic definitions for various shape definitions (Points, Rectangles, Dimensions, and Circles)
[Velentr.Audio](https://github.com/vonderborch/Velentr.Audio) | Active - Extensive Rework Planned | A library for making interacting with audio easier. I'm planning on doing some extensive reworks of this repo in the future since I don't particularly like how this turned out...
[Velentr.Collections](https://github.com/vonderborch/Velentr.Collections) | Active | A variety of helpful collections
[Velentr.Collisions](https://github.com/vonderborch/Velentr.Collisions) | Active - Extensive Rework Planned | A simple collision detection helper library, not intended as a full physics engine 
[Velentr.Debugging](https://github.com/vonderborch/Velentr.Debugging) | Active | A WIP library containing some useful helpers for code profiling, performance testing, and debugging
[Velentr.FiniteStateMachine](https://github.com/vonderborch/Velentr.FiniteStateMachine) | Active | A simple implementation of a Finite State Machine
[Velentr.Font](https://github.com/vonderborch/Velentr.Font) | Active - Extensive Rework Planned | An alternative solution for Monogame/FNA/XNA-derived frameworks that utilizes SharpFont to draw text rather than the traditional SpriteFont approach, allowing the use of TTF/OTF files rather than SpriteFont files. I'm planning on doing some extensive reworks of this repo in the future to remove dependencies on external DLLs
[Velentr.Input](https://github.com/vonderborch/Velentr.Input) | Active - Refactoring Planned | A solution for handling input better for Monogame/FNA/XNA-derived frameworks. I'm planning on refactoring this in the future to make it more easily maintainable
[Velentr.Localizations](https://github.com/vonderborch/Velentr.Localizations) | Active | A simple and easy-to-use localization helper library
[Velentr.Logging](https://github.com/vonderborch/Velentr.Logging) | Active - Extensive Rework Planned | A simple and easy-to-use logging helper library
[Velentr.Math](https://github.com/vonderborch/Velentr.Math) | Active | A variety of math helpers that I've found useful
[Velentr.Miscellaneous](https://github.com/vonderborch/Velentr.Miscellaneous) | Active - Unstable | Miscellaneous helper methods and things that are useful for various purposes
[Velentr.Resolution](https://github.com/vonderborch/Velentr.Resolution) | Active | A library to make handling game resolutions (and pillarboxing/letterboxing) easier
[Velentr.Scaling](https://github.com/vonderborch/Velentr.Scaling) | Active | A library to make handling scaling on a 2D plane easier
[Velentr.Sprite](https://github.com/vonderborch/Velentr.Sprite) | Active | A handy growing library of sprite/texture enhancements, including Texture Atlas packing and eventually scene graphs, amongst other things
[Velentr.States](https://github.com/vonderborch/Velentr.States) | Active | A library to help make state management easier
[Velentr.UI](https://github.com/vonderborch/Velentr.UI) | Development | An easy-to-use UI library to XNA-derived frameworks like FNA and Monogame

<!-- 
[Velentr.](https://github.com/vonderborch/Velentr.) | Active | 
-->

## Packages - Other
These are small projects that I wrote to help out with some basic task.
Repo | Language | State | Summary
---- | -------- | ----- | -------
[Apertium.Net](https://github.com/vonderborch/Apertium.Net) | C# | Active | A helper library for using Apertium for machine translations
[FenrirFS](https://github.com/vonderborch/FenrirFS) | C# | Abandoned/Archived | A project to allow for consistent cross-platform file system access using PCL's. Abandoned due to similar stuff in .NET Standard
[PclNumberConverters](https://github.com/vonderborch/PclNumberConverters) | C# | Abandoned/Archived | A project to allow conversion between a variety of different measurement systems in a cross-platform way using PCL's
[PclSystemInfo](https://github.com/vonderborch/PclSystemInfo) | C# | Abandoned/Archived | A project to gather a variety of system information (processor count, ram amount, etc.) in a cross-platform way using PCL's
[SharpFont](https://github.com/vonderborch/SharpFont) | C# | Up-To-Date with Base Repo | A fork of [Robmaister's SharpFont](https://github.com/Robmaister/SharpFont) that builds on the work to allow the library to be used with .NET Standard

<!--
[](https://github.com/vonderborch/) | C# | Active | A project to 
-->

## Classwork (legacy)
I've uploaded all of my old classwork from college (retroactively) for posterity (and in some cases for my own reference). Not all of this still works as I've tried to remove any identifying info from it, in some cases through brute-force means that may make some projects no longer compile. Additionally, in some cases work has been lost. Please be gentle, there's also a lot of pretty bad programming practices in all this...you have been warned!
Repo | Class Name | Semester & Year | Language(s)
---- | ---------- | --------------- | -----------
[CS121](https://github.com/vonderborch/CS121) | Program Design and Development C/C++ | Fall 2011 | C
[CS122](https://github.com/vonderborch/CS122) | Data Structures C/C++ | Spring 2011 | C, C++ 
[CS223](https://github.com/vonderborch/CS223) | Advanced Data Structures C/C++ | Fall 2012 | C, C++
[CS260](https://github.com/vonderborch/CS260) | Introduction to Computer Architecture | Spring 2013 | MIPS Assembly
[CS322](https://github.com/vonderborch/CS322) | Software Engineering Principles I | Fall 2013 | C#
[CS323](https://github.com/vonderborch/CS323) | Software Design | Spring 2014 | C#
[CS355](https://github.com/vonderborch/CS355) | Programming Language Design | Fall 2013 | Python, Java, ML, Rocket
[CS360](https://github.com/vonderborch/CS360) | Systems Programming | Spring 2014 | C
[CS440](https://github.com/vonderborch/CS440) | Artificial Intelligence | Fall 2014 | C++, C
[CS451](https://github.com/vonderborch/CS451) | Introduction to Database Systems | Spring 2014 | C#, T-SQL
[CS460](https://github.com/vonderborch/CS460) | Operating Systems and Computer Architecture | Spring 2015 | C, Assembly, Shell Script
[CS464](https://github.com/vonderborch/CS464) | Distributed Systems | Spring 2015 | Java, Go
[CS483](https://github.com/vonderborch/CS483) | Web Development | Spring 2015 | HTML, PHP, JavaScript
