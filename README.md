# chovy-gen by @dots_tb and Motoharu
Generate __sce_ebootpbp for the vita

This file is used to verify EBOOT.pbp files on the Vita to prevent tampering and is also used for version checking.

To generate a __sce_ebootpbp, you must have obtained your AID. One method of obtaining your AID is to copy it from an existing __sce_ebootpbp at offset 0x40 to 0x48 from a hex editor.


	CMD LINE (you use a thing command prompt, to find that, you use a thing called Google): ./chovy-gen <your aid ex: 0x123456789ABCDEF0> <EBOOT.pbp> 


With CBPS (https://discord.gg/2nDCbxJ) help especially:  @notzecoxao (and his friends?), @SiliCart, and @nyaaasen

Check out motoharu's project: https://github.com/motoharu-gosuto/psvcmd56/blob/master/src/CMD56Reversed/F00D/GcAuthMgrService.cpp#L1102

(He is aiming to make a fully functional f00d emulator).
