# CircleMUD

My copy of [CircleMUD](www.circlemud.org) version 3.1 with slight modifications to get a clean compile (no errors, no warnings) on [Windows 11](https://en.wikipedia.org/wiki/Windows_11) using [Visual Studio 2022 Community](https://visualstudio.microsoft.com/vs/community) with a target of [WSL](https://en.wikipedia.org/wiki/Windows_Subsystem_for_Linux) `Ubuntu-22.04.3-LTS` and the [Clang](https://clang.llvm.org) compiler.

If you are interested in exploring the CircleMUD codebase on Linux via a powerful IDE, this combination of tools makes that task very easy.

Where is `main()`? Look in `comm.c`, line 206.

This repo contains only the files required to compile and play around with CircleMUD in the above defined environment. The complete CircleMUD 3.1 is here: `https://www.circlemud.org/pub/CircleMUD/3.x/circle-3.1.zip`.

Here's a link that provides instructions to configure Visual Studio to target WSL

https://learn.microsoft.com/en-us/cpp/build/walkthrough-build-debug-wsl2?view=msvc-170#wsl-2-and-msbuild-based-linux-projects
