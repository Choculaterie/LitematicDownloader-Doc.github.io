# Installation Guide

Get LitematicDownloader up and running in just a few simple steps.

## Prerequisites

### Required Software
Before installing LitematicDownloader, ensure you have:

- **Minecraft**: Version 1.21.6 or higher
- **Fabric Loader**: Latest version recommended
- **Fabric-API**: Required dependency mod

### Important Notes
- LitematicDownloader is currently **only available for Fabric**
- Support for other loaders like Quilt or NeoForge is not provided
- Ensure you're using the latest versions for the best experience

## Step-by-Step Installation

### Step 1: Install Fabric Loader
1. Visit the [Fabric website](https://fabricmc.net/use/installer/)
2. Download the Fabric Installer
3. Run the installer and select your Minecraft version (1.21.6+)
4. Click "Install" to set up Fabric

### Step 2: Install Fabric-API
1. Go to [Fabric-API on Modrinth](https://modrinth.com/mod/fabric-api) or CurseForge
2. Download the version matching your Minecraft version
3. Place the Fabric-API `.jar` file in your `mods` folder

### Step 3: Download LitematicDownloader
1. Visit the [Modrinth page](https://modrinth.com/mod/litematicdownloader) or the [GitHub Releases page](https://github.com/Choculaterie/LitematicDownloader/releases)
2. Download the latest version compatible with your Minecraft version
3. Save the mod `.jar` file to your computer

### Step 4: Install the Mod
1. Navigate to your Minecraft installation directory
2. Open the `mods` folder (create it if it doesn't exist)
3. Place the LitematicDownloader `.jar` file into the `mods` folder

### Step 5: Launch and Verify
1. Launch Minecraft using the Fabric profile
2. Check that LitematicDownloader appears in your mods list
3. Enter a world and press "N" to open the mod interface
4. Verify the interface opens correctly

## Default Controls

### Opening the Interface
- **Default Keybind**: "N"
- **Customization**: Change in Minecraft's vanilla keybind menu
- **Menu Location**: Controls → Key Binds → LitematicDownloader

### Alternative Access Methods
If the keybind doesn't work:
1. Check for keybind conflicts in the controls menu
2. Try resetting to default keybinds
3. Restart Minecraft after making changes

## Folder Structure

After installation, your Minecraft directory should look like this:
```
.minecraft/
├── mods/
│   ├── fabric-api-[version].jar
│   ├── litematica-[version].jar
│   └── litematic-downloader-[version].jar
└── config/
    └── litematic-downloader-settings.json

```

## Verification

### Test Installation
1. Launch Minecraft with Fabric
2. Load or create a world
3. Press "N" to open LitematicDownloader
4. Try browsing the schematic library
5. Test downloading a simple schematic

### Common First-Time Setup
- Grant network permissions if prompted
- Allow the mod to create necessary folders
- Test the connection to choculaterie.com
- Verify schematics appear in file manager

## Network Permissions

### Windows
- Windows Defender may prompt for network access
- Click "Allow access" for both private and public networks
- Add Minecraft to firewall exceptions if needed

### macOS
- macOS may ask for network permissions
- Grant access in System Preferences → Security & Privacy
- Ensure Minecraft has full disk access if needed

### Linux
- Most distributions don't require special permissions
- Check firewall settings if connection issues occur
- Ensure Java has network access permissions

## Troubleshooting Installation

### Mod Not Loading
- Verify Fabric Loader is properly installed
- Check that Fabric-API is in the mods folder
- Ensure all mods are compatible with your Minecraft version
- Review the launcher logs for error messages

### Interface Won't Open
- Check the keybind configuration (default: "N")
- Look for keybind conflicts with other mods
- Try resetting keybinds to default
- Restart Minecraft after making changes

### Connection Issues
- Verify your internet connection
- Check if choculaterie.com is accessible
- Review network permissions for Minecraft
- Try refreshing the schematic list

## Getting Help

If you encounter issues during installation:
1. Check the [FAQ section](troubleshooting.md#frequently-asked-questions)
2. Join the [Discord Community](https://discord.gg/pD5hFXjwc2)
3. Report issues on [GitHub](https://github.com/Choculaterie/LitematicDownloader/issues)

When seeking help, please include:
- Your Minecraft version
- Fabric Loader version
- List of installed mods
- Any error messages or crash logs