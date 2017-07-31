## Introduction

MonoUE (or Mono or Unreal Engine) is a plugin for Unreal Engine that allows writing gameplay code with C# and F#. 

The plugin has been developed with the support of Microsoft, but is currently a personal side project of several Microsoft employees. It is not officially supported by either Microsoft or Epic. It is being made freely available as source to all Unreal Engine licensees in the hope that the community considers it useful and participates in its development.

### Features

* Fully integrated with the Unreal object system and Unreal Editor.
* C# bindings are generated automatically for all Blueprint-accessible types and member.
* Objects and functions defined from C# can subclass types defined in C++, and can be used from Blueprint and from the Unreal Editor.
* Runs on Windows and Mac

Planned and in development:

* Visual Studio integration
* Debugging
* Hot reload
* Mobile platform support
* Cooked builds

### Installation

The plugin is currently available only as source, as it requires a patched build of the engine.

You will need [source access to Unreal Engine on GitHub](https://www.unrealengine.com/ue4-on-github).

Clone the https://github.com/mono-ue/UnrealEngine for of Unreal Engine, check out the *monoue-4.16* branch, and follow the instructions in the [Engine/Plugins/MonoUE/README.md](https://github.com/xamarin/UnrealEngine/blob/monoue-4.16/Engine/Plugins/MonoUE/README.md).

### Contact

The primary contact for MonoUE is [Mikayla Hutchinson](https://github.com/mhutch).

There is a MonoUE mailing list at https://lists.dot.net/mailman/listinfo/mono-ue
