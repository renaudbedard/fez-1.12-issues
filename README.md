# fez-1.12-issues
A public repository for FEZ 1.12 issue logging and tracking.

## Frequently asked questions

#### The game refuses to update in the Steam client (schedules over and over but never updates, or says "An error occured while updating FEZ (content still encrypted)")

Delete local content for FEZ in Steam and reinstall it; you won't lose any save data.

#### The game hangs or does not complete while installing prerequisites (on Windows)

Try to install them manually :
- .NET Framework 4.6 : https://www.microsoft.com/en-ca/download/details.aspx?id=48130
- Visual C++ 2010 Redistributable (x86) : https://www.microsoft.com/en-ca/download/details.aspx?id=5555

#### The game crashes on start

Try updating your graphics card drivers :
- Intel : https://downloadcenter.intel.com/
- nVidia : http://www.nvidia.ca/Download/index.aspx?lang=en-us
- AMD : https://support.amd.com/en-us/download
 
If the game still crashes on start, please log an issue and join the debug log (see procedure below).

## Procedure

Please log issues using the "Issues" tab. Include anything that could help reproduce and fix the issue : screenshots (you can paste them directly from your clipboard), context/repro steps.

Location of the `[YYYY-MM-JJ] Debug Log.txt #NN` file (prefix is the date, suffix is sequential) :

- Windows : `%APPDATA%\FEZ\`
- OS X : `~/Library/Application Support/FEZ/`
- Linux : `$XDG_DATA_HOME/FEZ/`

Please join this file for crash reports.

Thanks!
