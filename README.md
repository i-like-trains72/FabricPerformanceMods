# FabricPerformanceMods
I try to keep them updated. For 1.17.1!
**THESE MODS ARE NOT OWNED BY ME THEREFORE THEIR LICENSE STILL REMAINS. GIVE THE DEVS CREDIT, NOT ME! I AM ONLY USING THIS AS A WAY FOR PEOPLE TO EASILY DOWNLOAD PERFORMANCE MODS!**

-You can now find updates in #overlord-lair in my Discord!

-Sodium-iris and Iris-starline are incompatible with Sodium/next.

-C2me may cause issues on very low-end devices.

-Fabric API **may or may not** be needed, this guide assumes you know how to read simple crash log errors and fix them, i.e. not having Java 16 or updating Fabric API

-------------------- Keys ---------------------------------

-Mods that are mostly/completely safe (meaning any possible errors can be fixed without permanent damage) will be marked with: ✔️

-Mods that are *not* mostly/completely safe will be marked with: ✖️

-Mods that are mixed will be marked with: ❗

-Please read the Additional Notes section, it has vital information

---------------------------------- Mod Descriptions ---------------------------------------------

**C2me** - Multithreads chunks to make them load fast https://github.com/YatopiaMC/C2ME-fabric ❗

**Cadmium** - Optimizes the DFU to run faster when it's used https://github.com/LucilleTea/cadmium-fabric ❗

**ClientSideNoteBlocks** - Reduces client-side lag when playing noteblocks on the server https://www.curseforge.com/minecraft/mc-mods/client-side-noteblocks ✔️

**Cull Leaves** - Makes leaves look like Optifine's Smart leaves, providing an FPS boost https://www.curseforge.com/minecraft/mc-mods/cull-leaves ✔️

**DashLoader** - Makes startup times insanely fast by caching data (can cause issues when loading resourcepacks; when you load one, restart your game afterwards) https://www.curseforge.com/minecraft/mc-mods/dashloader  ❗

**EntityCulling** - Makes entities not render when not visible https://www.curseforge.com/minecraft/mc-mods/entityculling ✔️

**FerriteCore** - Reduces ram usage https://github.com/malte0811/FerriteCore ✔️

**Iris (Starline)** - Allows shaders to be ran on Sodium Iris STARLINE SNAPSHOT https://github.com/IrisShaders/Iris ✔️

**Krypton** - Network trafic reducer https://github.com/astei/krypton/commits/master ❗

**LazyDFU** - Makes DFU "lazy" (does not compile DFU rules until needed) https://github.com/astei/lazydfu ✔️

**Lithium** - General performance improvements https://github.com/CaffeineMC/lithium-fabric ✔️

**ModMenu** - You can see if your mods are loaded properly https://www.curseforge.com/minecraft/mc-mods/modmenu/files ✔️

**RecipeCache** - Stores recipes so they can be easily accessed https://www.curseforge.com/minecraft/mc-mods/recipe-cache ✔️

**Sodium Extra** - Adds more options to sodium https://www.curseforge.com/minecraft/mc-mods/sodium-extra ✔️

**Sodium** - Insane FPS boosting mod. Many, many, *many* times better than vanilla and Optifine.  (results may vary) https://github.com/CaffeineMC/sodium-fabric ✔️

**Sodium IRIS (STARLINE)** - Sodium for shaders with Iris https://github.com/IrisShaders/sodium-fabric ✔️

**Starlight** - New lighting engine about 100X faster than vanilla https://github.com/Spottedleaf/Starlight ✔️


---------------------------------- Videos ----------------------------------

Sodium - https://www.youtube.com/watch?v=XmTWwfxVcWI

DashLoader - https://www.youtube.com/watch?v=V1U6l71FYYk&lc=UgwFgYJMeWzevEJ7DAt4AaABAg.9MtOQo_uFHp9N3aLU69319

Starlight/c2me - https://www.youtube.com/watch?v=oOpOW8Y7OWQ

LazyDFU - https://www.youtube.com/watch?v=gXDqJ598kKA

Sodium, Lithium, Phosphor https://www.youtube.com/watch?v=OBWGZsQ1pcE


---------------------------------- ADDITIONAL NOTES ----------------------------------

Iris and Starline and Sodium Starline and all of that is going to be OFFICIALLY released on June 8th, 2021. Depending on any bugs found, their ratings will change accordingly
Sodium Extras is INCOMPATIBLE WITH IRIS AND ITS FORKS. Also incompat with Sodium 0.2.0

Some more notes on Sodium and Iris since it's kind of confusing
1) You can choose between Sodium and normal Iris
2) You can choose betwen Sodium and the Starline fork of Iris
3) The Starline fork has a configuration menu for shaders while standard Iris does not
You can choose what to use, just **don't combine both of the Iris mods**

**Dashloader crashes with numerous mods that add custom baked models (like things from Adorn and tech mods that add things like pipes) and it crashes with Hydrogen (memory optimization mod from CaffeineMC). It also crashes with the standard Curseforge release of Sodium. It can also randomly not work for some users, I do not recommend it if you change resourcepacks or mods often.**

-Cadmium may crash sometimes

-Phosphor is a lighting engine optimization mod from CaffeineMC, Starlight is faster but is **incompatible with Phosphor** and is also experimental. Chunk loading speeds are improved
-Krypton is a bit weird sometimes **when running it on servers**, be cautious
