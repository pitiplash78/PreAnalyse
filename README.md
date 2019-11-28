# PreAnalyse


PreAnalyseExtended
************************


Description:
----------------
This graphical program is is used for screening, modifying and analysis for linear time series in Geosciences and Physics. The data is organised in projects and well organised as sorted to work on different projects at different times. The screening and modifying is carried out graphical by using the mouse and keyboard for fast clean progress. For analysing the data exists several functions. The exchange of data between different users can simple carried out by export and import the whole project that each user has the same information and modified data, as the knowledge of their history.
The program is written in .NET C#, running natively in Windows. The program can run under Linux using the last version of Mono. The use in Linux is limited but should work.


Start up:
-----------
The compressed file can be unzipped to more or less everywhere.
If needed especially in Windows can be set a to program_root_folder/PreAnalyseExtended.exe and just start the program. 
In Linux the program call is on the command line $mono  program_root_folder\PreAnalyseExtended.exe
A start up using Linux ‘wine’ is outstanding. 

After start up the first time a window defining the needed working folders appears. For best performance it is recommended to set the three path in your comfortable way. It is asked for:
+ The standard base directory for data files. This option is mandatory but very useful. It is
  also recommend to use the according check box. Following that a project being created,
  generates a data folder of the same name. All data produced inside a project are stored 
  there.
+ The standard director for log-files. This mandatory option is only useful, if log files created by LaborLog
+ The directory exporting project is used for exporting projects. If that routine of the program is used all exported  
  projects are stored there. These compressed files get be transferred to other users.


Brief introduction to use the program:
-------------------------------------------------

The data is organised in projects. After starting the program a selection window open for several options: 
+ It can be opened just a data set. There is automatically created a project.
+ An already existing project can be opened again to work on it.
+ Or just a blanc project can be created
- This window can be closed and everything can be carried out manually using the menu.
After this selection the part of file and data organisation is visible. It can be simple switched between the three part ‘FILE ORGANISE’, ‘SCREENING’ and ‘ANALYSIS’ using the menu or the three symbols upper right. 

In ‘FILE ORGANISE’ many options, as save the data file, delete data file off the project, additional data manipulations and contained channel (stream) changes can be carried out. The most important point is the selection of the channel to be screened. Four channels can be selected at the right of the window.

To screen the selected data channel the menu:Screening or the most left button up right is used. The navigation and manipulation of the stream is done by using the mouse and keyboard. The most important functions are:
+ Navigate through the data:
    - shift the shown time window: [mouse wheel]; [Page down]; [Page up]
    - zoom the shown time window: [Ctrl]+[mouse wheel]; [Gray+]; [Pos1]; [Gray-]; [End]
    - activation of magnifier: [Ctrl]+[G] + mouse action
+ select the different data for manipulation as active (multiple selection are possible using [Shift]:
    - channel 1: [1]; [Y]
    - channel 2: [2]; [X]
    - channel 3: [3]; [C]
    - channel 4: [4]; [V]
+ Using mouse:  !!!Every click causes a reaction!!!
    - moving the mouse over the window moves the cursor show information of the channels
    - Interpolation of gaps: left click into data gap
    - Interpolation of data: hold left mouse button drag a range and lose
    - Cut data: hold right mouse button drag a range and lose
    - Cut outliers: hold [Shift] + hold mouse button (left for cut above the limit; right for cut below the limit) and drag 
      a range and lose 
   - Offset corrections: right click on a data point and a context menu open to select the wanted function

To analyse data using several contained methods switch to ‘ANALYSIS’. The newly opened window allows the selection of a function. According to that different possibilities are provided for data (channel) selection. Finally the selection is to be confirmed by button ‘Continue...’. 

Example data:
-------------
Example test data set as the different possible formats are found in the menu: File>Open Example Files.

Further help can give menu: Help>....
