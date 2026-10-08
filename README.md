# AWESOME 2016 FORKITHON

![My *handmade* Roblox Logo](https://github.com/user-attachments/assets/ced623cd-6692-4759-8e46-e9453f5454fc)

<p align="center">
<img alt="GitHub Repo Size" src="https://img.shields.io/github/repo-size/P0L3NARUBA/roblox-2016-source-code">
<img alt="GitHub Release" src="https://img.shields.io/github/v/release/P0L3NARUBA/roblox-2016-source-code?color=violet">
<img alt="GitHub Last Commit" src="https://img.shields.io/github/last-commit/P0L3NARUBA/roblox-2016-source-code/master">
</p>

so basically this is an awesome 2016 roblox source fork thing

the goal of this project is to take the 2016 roblox source and actually do something with it instead of it just sitting here lol

this is mainly about bringing back the old 2016 roblox experience, getting the client/studio stuff working, making it easier to build, and adding the old revival features that people actually care about.

we're not trying to make modern roblox again. the point is **2016 roblox.**

## what is this

this source originally came from **[robloxsrc.zip](https://mega.nz/file/mrxkSRRK#n5YmV1iPUPZCfiI6IDWkT3eDq9k3-yA7rl_hURked8Y)** which was going around for a while and then became annoying to find.

this fork is for messing with that source and turning it into an actual usable 2016-style project.

stuff like:

- getting RobloxStudio building
- getting WindowsClient building
- getting RCCService working
- getting the old networking/server stuff working
- making a playable 2016-style client
- bringing back old features from 2016 revivals
- fixing the absolutely ancient build environment
- making the whole thing easier for other people to build
- generally seeing how far we can push this thing

## the big goal

**make a usable 2016 roblox revival from the source.**

not just:

> "look guys we have the source"

and then nothing happens 😭

the goal is to eventually have something where you can build the client, run the server stuff, join a game, use old features, and actually mess around with it like an old Roblox revival.

obviously this is going to take a while because this source is from **2016** and a lot of the dependencies/build tools are ancient.

but thats kinda the point.

## current status

this is still a work in progress.

a lot of the source already exists, but getting every project to compile and getting all the pieces to actually work together is a completely different story.

current build status from the original work was around **34/68 projects**.

some of the important ones we're interested in are:

- RobloxStudio
- WindowsClient
- RCCService
- RobloxProxy
- Network
- CSG
- GfxBase
- GfxCore
- GfxRender
- graphics3D
- ShaderCompiler

some of these build and some absolutely do not lol

## revival stuff

this project is also focused on stuff that old Roblox revival projects did.

### things we want to look at

- **Hitius**
- **Graphictoria**
- **Economy Simulator**
- old 2016 client behavior
- old Studio behavior
- old networking
- old server behavior
- old Roblox features that were removed later

the idea isn't to copy one specific revival.

it's more like taking all the interesting stuff from that era and seeing what can actually be implemented into the source.

## features

currently this source/fork has work related to:

- Color3uint8
- Color3.fromRGB()
- :Connect() and :Wait()
- newer mesh versions
- new fonts
- various compilation fixes
- source cleanup
- reverse engineered C# components
- Rocknet support
- changed splash screen/copyright dates

and probably a bunch of other random 2016 source stuff i forgot about

## Rocknet

**[Rocknet](https://github.com/P0L3NARUBA/Rocknet)** is the server/networking project made for this source.

you may need it if you want to actually launch the game instead of just compiling everything.

eventually the goal is to make the whole setup way less annoying than:

1. build 500 ancient projects
2. install 900 ancient dependencies
3. sacrifice a computer
4. maybe the client starts

## building

if you actually want to build this thing, read **[BUILDING.md](/BUILDING.md)** first.

seriously

there are a lot of old dependencies and weird build requirements here and just randomly opening the solution and pressing build probably isn't going to work.

there is also **[BUILDING_CONTRIBS.md](/BUILDING_CONTRIBS.md)** for the contributed libraries.

## tools

some of the tools used while working on the source:

- [ILSpy](https://github.com/icsharpcode/ILSpy/releases)
- [HxD](https://mh-nexus.de/en/downloads.php?product=HxD20)

reverse engineering is mostly useful here for figuring out how missing/closed-source pieces were supposed to work and making old components usable again.

## dependencies

this thing uses a ridiculous amount of old libraries because, well, it's 2016.

some of the major ones include:

- Boost 1.56.0
- cpp-netlib 0.11.0
- OpenSSL 1.0.0c
- Qt 4.8.5
- SDL2 2.0.4
- curl 7.43.0
- zlib 1.2.8
- RakNet 5
- Mesa 7.8.1
- TBB 4.1
- gSOAP 2.7.10

they're all in the repository in the various contrib folders.

## stuff that still needs to happen

there is a LOT.

- [ ] Get more of the source compiling
- [ ] Get RobloxStudio fully building
- [ ] Get WindowsClient fully building
- [ ] Get RCCService building and running
- [ ] Get the client and server communicating properly
- [ ] Make the setup easier
- [ ] Fix old networking problems
- [ ] Fix keyboard shortcuts
- [ ] Add proper UTF/Unicode support
- [ ] Add/port newer Lua support where useful
- [ ] Add R15
- [ ] Add a proper dark Studio theme
- [ ] Fix in-game recording
- [ ] Improve bootstrappers
- [ ] Get 64-bit support working where possible
- [ ] Look into Android support
- [ ] Look into MacOS support
- [ ] Implement more old revival features
- [ ] Make a proper playable 2016-style setup

and probably 500 more things

## current bugs

there are still a ton of old source bugs.

one known issue is that Undo/Redo can mess up Color3 values and snap them toward BrickColor values.

if you find something broken, **make an issue instead of silently suffering**.

## contributions

if you know C++, old Roblox internals, reverse engineering, networking, graphics, build systems, or just have an unhealthy amount of patience for Visual Studio errors, you're probably useful here.

pull requests are welcome.

## credits

this project wouldn't exist without the people who originally preserved and worked on the source.

see **[CONTRIBUTORS.md](/CONTRIBUTORS.md)** for the existing credits.

also huge thanks to everyone who worked on old Roblox revival projects and figured out how this stuff worked in the first place.

## links

- **[Build Instructions](/BUILDING.md)**
- **[Releases](https://github.com/P0L3NARUBA/roblox-2016-source-code/releases/)**
- **[Issues](https://github.com/P0L3NARUBA/roblox-2016-source-code/issues)**
- **[Rocknet](https://github.com/P0L3NARUBA/Rocknet/tree/main)**
- **[Contributors](/CONTRIBUTORS.md)**

---

# AWESOME 2016 FORKITHON

2016 roblox source

2016 roblox revival

old roblox

funny ancient C++

server stuff

client stuff

studio stuff

make it work lol
