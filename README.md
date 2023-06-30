# NoDPTF
Registry file and BAT script to disable and prevent self-reinstallation of Intel DPTF/IPF.

Intel Innovation Platform Framework, also known as Intel Dynamic Platform and Thermal Framework, dynamically imposes Power Limits on the CPU, limiting the performance of Intel laptops.

DPTF/IPF drivers can be removed in Device Manager, but Windows tends to automatically reinstall them upon reboot.

NoDPTF.reg inserts Group Policies directly in the Registry to block Windows from automatically reinstalling DPTF drivers. RemoveDPTF.bat automates the initial removal of these devices and the merging of NoDPTF.reg.

For more information, see https://bradshacks.com/disable-dptf/.
