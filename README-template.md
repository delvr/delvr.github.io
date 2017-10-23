# ${modName}

[![${modName} logo](src/main/resources/${modLogoFile})](${modUrl})

[![${modName} versions](http://cf.way2muchnoise.eu/versions/${modId}.svg)](https://minecraft.curseforge.com/projects/${modId}/files)
[![${modName} downloads](http://cf.way2muchnoise.eu/full_${modId}_downloads.svg)](https://minecraft.curseforge.com/projects/${modId}/files)

${modDescription}

For more information please visit the mod's [homepage](${modUrl}).

For help with the build process please read the [ForgeGradle documentation](https://forgegradle.readthedocs.io/en/latest/) first.

Note: IDE-specific instructions are for IntelliJ IDEA; see the ForgeGradle documentation for Eclipse equivalents.

## Dependencies Setup
...TODO...

## IDE Setup
The IDEA `Update` run configuration will run `setupDecompWorkspace` and `genIntellijRuns`.
After running `Update`, synchronize Gradle in IntelliJ IDEA to set up module configs.
If using IntelliJ 2016 or later, make sure the Gradle plugin setting "Create separate module per source set" is NOT checked.

## Testing
Run the generated `Minecraft Client` or `Minecraft Server` configuration.

## Building
Run the `build` configuration. Jars will be generated in `build/libs`.
