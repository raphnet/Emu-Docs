## Emu-Docs

This is an archive of emulator documentation and test ROMs to assist anyone understand the underlying architecture of multiple consoles.

### How to easily browse the archive

In the future, we are planning to create a [GitHub pages front-end](https://pages.github.com/) but for now, just execute the following command: `git clone --depth=1 https://github.com/Emu-Docs/Emu-Docs.git`

### Resources to Archive

http://emu-docs.org/

http://www.zophar.net/documents/

https://github.com/franckverrot/EmulationResources

### Documentation Guidelines

1. If you're adding specific CPU/chip documentation, please put the appropriate documentation under "Shared Components". Inside the console's directory, create a relative symbolic link to the folder you created in "Shared Components". e.g. in the NES folder, there's a relative symbolic link to "CPU 65xx" in "Shared Components"

2. Consoles in the root directory should be named by the full name e.g. "Playstation 2" instead of "PS2"

3. Test ROMs are welcome and should be placed under a folder called "test_roms" in the console's directory. Documentation about certain games or ROM hacking should be placed under a folder called "game_documentation". SDKs/DDKs should be placed under a folder called "SDK" or "DDK".

4. Inside each folder, there should be a README.md describing the files in that directory
