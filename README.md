# Mod Name Data
You can make pull requests to add more variations to [the funny mod name generator](https://modname.mcmc.dev/)

## API
https://modname.mcmc.dev/generate - Generates random mod name
https://modname.mcmc.dev/generate/([id](https://github.com/Minecraft-Mod-Central/Mod-Name-Data/tree/master/modname)) - Generate a specific mod name, id has to be one of the modnames on GitHub
https://modname.mcmc.dev/(permalink)/raw - Plain text value of pre-generated mod name

### All of these include 3 headers:
- `x-modname-created` - Date it was first generated (Example: `2020-02-11T16:46:23Z`)
- `x-modname-history` - Date it was last generated / shown in history (Example: `2020-02-11T16:46:23Z`)
- `x-modname-permalink` - Permalink ID (Example: `XkLaX1GEQkFrkGPS`)
