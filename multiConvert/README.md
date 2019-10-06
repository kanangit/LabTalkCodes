# multiConvert script

Origin software allows automation using a script language called LabTalk. I have written a script which, I hope, would be useful to anyone who need to plot a lot of similar graphs. The scripts imports a folder of .CSV files and makes a plot for each file and saves an origin project file with the plot for every original .csv file.

The script multiConvert.ogs is in the folder source. I also provide test files to check the script in the folder samples.

To see how the script works, please do the following:

1. Create a folder  D:\originScripts. Copy the file multiConvert.ogs to the folder.
2. Copy the folder sources to D:\. so that the CSV files would be in the folder D:\samples\.
3. Open Origin software.
4. Press ALT+3. A "command window"  should pop up. If it didn't, press ALT+3 again.
5. In the Command window, enter the command :
     cd "D:\originScripts\"
and press Enter.
6. Enter command
     dir
   and pres Enter
7. Enter the command 
    multiConvert
 and press Enter.

The Origin would create graphs in the same folder as the original CSV files.

Hope it will be useful for you. One can edit the script, changing parameters of the graphs (axis scales, fonts, etc.). In fact, anything you do using menus of the Origin, you can do with the script. Please feel free to ask me if you have any questions how to modify the script.

