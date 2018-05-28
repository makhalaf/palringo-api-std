# PalringoAPI for .net standard 2.0
A complete rewrite of the original [PalringoAPI](https://github.com/calico-crusade/PalringoApi) in .net standard 2.0

# Where can I use it?
I have tested it on Windows (.net Framework 4.5.1+ & Core 2.0) and on Mac (Core 2.0)

# How do I use it?
It is pretty simple to use. You can install it via Nuget (see below). There are 3 different packages available.

```
PM> Install-Package PalApi
```
The primary package that contains all of the useful stuff. Networking, Plugins, all of it. It does not contain anything related to imaging (See below).

```
PM> Install-Package PalApi.Imaging
```
This package handles all of the imaging (Bitmap) sort of things. This is due to GDI+ not being available in .net core out side of a pre-release package (System.Drawing.Common)

```
PM> Install-Package PalApi.Storage
```
This package is an extra-addon that is like a mini version of EntityFramework but with my own spin on it. Mostly because I was bored one day.

# Documentation
You can check the Examples libraries in the source. It should be pretty simple. Any questions? Be sure to reach out: [You can contact me via Pal](http://chat.palringo.com/u/43681734)

# Legal & Stuff
* By using this software you agree to the [Palringo Terms of Service](https://palringo.com/en/us/terms-and-conditions)
* Allow the logos and name usage adhere to the [Brand Guidelines](https://www.palringo.com/en/gb/brand-guidelines) set forth by Palringo
* If there are any questions regarding the use of the library, please contact me (method listed above)
* Use at your own risk, Palringo can bar or suspend your account for incorrect usage of the library
* Join the [Bot Approval](https://chat.palringo.com/bot+approval) group on Palringo for any questions regarding the use.
* Get your bots approved, kids.
* I am not liable or responsible for any outcome from using this library.
