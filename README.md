# nvidia-lists
Provides list files to detect the appropriate Nvidia driver to apply in Batocera Linux

How to create the list file:

1. Navigate to https://www.nvidia.com/en-us/drivers/unix/
2. Choose the Production driver
   As of writing the latest Legacy driver is 515.48.07
   Located here - https://www.nvidia.com/Download/driverResults.aspx/188877/en-us
3. Select the Additional Information tab
4. Then choose README - http://us.download.nvidia.com/XFree86/Linux-x86_64/470.129.06/README/index.html
5. From there, choose the hyperlink for A. Supported NVIDIA GPU Products
   http://us.download.nvidia.com/XFree86/Linux-x86_64/515.48.07/README/supportedchips.html
6. Copy the list into production.list whilst avoiding other driver revision sections
7. Do the same for the appropriate 'legacy' driver section into legacy.list
8. As of writing just the 470.xx section of supported devices

