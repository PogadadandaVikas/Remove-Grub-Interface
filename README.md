# Remove-Grub-Interface
<h>This repository deals with.. How to remove the Grub interface for windows.
GRUB is a bootloader package from GNU project. It creates a bootloader interface between windows and other OS
that probabily can be a Linux. If you are multi boot OS user and want to switch from multi boot to single OS 
you would like to remove the Grub interface to switch between the OS.</h>

This tutorial steps would help you:

<p>step 1. Run windows cmd as admin</p>
<p>step 2. Press diskpart</p>
<p>step 3. Press list disk</p>
<p>step 4. Press select disk <diskname></p>
<p>step 5. Press list partition</p>
<p>step 6. Press select partition <partition with (system)></p>
<p>step 7. Press assign letter=x</p>
<p>step 8. Press exit</p>
<p>step 9. Press x:</p>
<p>step 10. Press dir</p>
<p>step 11. Press cd EFI</p>
<p>step 12. Press dir</p>
<p>step 13. Press rd <name of os> /s</p>
<p>step 14. Press Y </p>

The Gurb-Interface dual boot for the linux os will be removed from the system.
