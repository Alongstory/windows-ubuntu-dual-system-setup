# windows-ubuntu-dual-system-setup
I took a whole day working on this and getting frustated on reading all the forum discussion, get wrong and try gain.
Broke my windows system by this line "bcdedit /set {bootmgr} path \EFI\ubuntu\shim*.efi", telephoned and online talking with microsoft representitives who are pretending to be technicians. Telehphoned local technician who is asking $180 for windows reinstall.(Crazy)
Used a chinese made software (very barbarian but useful) to save my files from clean reinstall of windows 10.
The trial numbers are approaching 100.

The whole process is briefly like:
1.Burning the ubuntu linux to a USB
2.Allocate disk space for ubuntu
3.deactive the boot security mode of BIOS
4.Install ubuntu
5.Return to windows, use cmd type the magic line: "bcdedit /set {bootmgr} path \EFI\ubuntu\grubx64.efi"


All set!





