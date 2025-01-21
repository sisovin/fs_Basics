# F# Overview

F# is a functional-first programming language that also supports object-oriented and imperative programming. It is known for its concise syntax, powerful type inference, and seamless interoperability with .NET libraries.

## How F# Runs

F# code is compiled into Intermediate Language (IL) code, which runs on the .NET runtime. This allows F# programs to run on any platform that supports .NET, including Windows, macOS, and Linux.

## How to Install, Configure, and Run F #

### Installation

1. Install the .NET SDK from the [official .NET website](https://dotnet.microsoft.com/download).
2. Install an IDE that supports F#, such as Visual Studio, Visual Studio Code, or JetBrains Rider.

### Configuration

To create a new F# project, use the following command:

```sh
dotnet new console -lang F# -o MyFSharpApp
cd MyFSharpApp
```

### Running F# Code
#### Type of F# File

In F#, `.fs` and `.fsx` files serve different purposes:

- **`.fs` files**: These are used for compiled F# code. They are part of an F# project and are compiled into an assembly (DLL or EXE) when you build the project. They are typically used for larger applications and libraries.

- **`.fsx` files**: These are F# script files. They are used for scripting and interactive development. You can run them using F# Interactive (FSI) without needing to compile them into an assembly. They are useful for quick experiments, prototyping, and scripting tasks.

In summary, use `.fs` for compiled code in projects and `.fsx` for scripts and interactive work.

To run an F# script file (`.fsx`), use F# Interactive (FSI):

```sh
fsi MyScript.fsx
```

To run an F# project, use the `dotnet run` command:

```sh
dotnet run
```

## Choosing an IDE

- **Visual Studio**: A full-featured IDE with excellent F# support.
- **Visual Studio Code**: A lightweight, cross-platform editor with the Ionide extension for F#.
- **JetBrains Rider**: A powerful cross-platform IDE with great F# support.

## How to Build and Run F #

To build the project, use the following command:

```sh
dotnet build
```

To run the project, use the following command:

```sh
dotnet run
```

## How to Push F# Project to GitHub

1. Initialize a new Git repository:

```sh
git init
```

2. Add all files to the repository:

```sh
git add .
```

3. Commit the changes:

```sh
git commit -m "Initial commit"
```

4. Add the remote repository:

```sh
git remote add origin https://github.com/sisovin/fs_Basics.git
```

5. Push the changes to GitHub:

```sh
git push -u origin master
```

## Example Output

```sh
PS D:\FsProjects\hello-world> fsi --version
Microsoft (R) F# Interactive version 12.9.101.0 for F# 9.0
PS D:\FsProjects\hello-world> dotnet run
Hello World! from F#
PS D:\FsProjects\hello-world> ./bin/debug/net9.0/hello-world.exe
Hello World from F#
```
