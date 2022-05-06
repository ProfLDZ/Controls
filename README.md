# Controls
A repository of controls, for ease of loading.

# Standard
When adding new controls, please follow the standard.

- The file containing the controls should be named exactly that of their Minecraft Username.
- **Talent** controls are to be put in the *Talent* folder.
- **Developer** controls are to be put in the *Dev* folder.

> *(For example, I'm a developer and my username is PivotPoint, so my controls would be saved as: `Devs/PivotPoint.txt`)*

# Important Changes
Remember to remove the following from your controls:
- resourcePacks
- incompatibleResourcePacks

Lastly, find the option `lastServer:` and if there's an IP after the `:`, remove it.
> Here's an before/after example:
> ### Before
> ```
> renderClouds:true
> resourcePacks:["Fabric Mods","vanilla","file/blank"]
> incompatibleResourcePacks:[]
> lastServer:192.168.0.0:25565
> lang:en_us
> ```
> ### After
> ```
> renderClouds:true
> lastServer:
> lang:en_us
> ```
