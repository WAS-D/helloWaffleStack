<p align="center">
<img width="450" src=".github/images/murder_logo.png" alt="Murder logo">
</p>

<h1 align="center">Your hello world (3d) in Murder Engine!</h1>

This is a fork of Hello Murder that showcases how to add a custom importer and render. Using a simple 3d .obj as example

Welcome to this fantastic experience that is trying out your very first game with the Murder Engine.

### 💾 Enlisting
This uses **git submodules** for the engine references. Make sure that all the submodule directories are up-to-date:

```bash
git clone --recurse-submodules https://github.com/isadorasophia/hellomurder
```

or, after cloning:
```bash
git submodule update --init --recursive
```

### ⚙️ How to build it?
We _should_ have (at one point) more documentation explaining the onboarding process of [creating a new project](https://github.com/isadorasophia/murder) with Murder. The main purpose of this project is to serve as a baseline when quickly starting with a fresh new game on the engine.

**\> _Terminal_**

```bash
cd src/HelloMurder.Editor
dotnet build
dotnet run
```

**\> _Visual Studio_**

Open `HelloMurder.sln` on Visual Studio 2022, set `HelloMurder.Editor` as startup project and hit F5. 🎉

### 🎮 How do I play the game?
You can either press **F5** in the editor or switch the startup project to `HelloMurder`. And that's it!
