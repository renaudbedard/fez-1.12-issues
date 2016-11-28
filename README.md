# fez-1.12-issues
A public repository for FEZ 1.12 issue logging and tracking.

## Frequently asked questions

#### What's new in FEZ 1.12?

See the `Changelog.txt` file in the FEZ local content directory and this blog entry for the full 1.12 changelog : http://theinstructionlimit.com/fez-1-12
See here for the 1.12 "hotfix" update changelog (any updates that succeeded the original release of FEZ 1.12) : https://github.com/renaudbedard/fez-1.12-issues/wiki/1.12-Update-Changelog

#### The game refuses to update in the Steam client (schedules over and over but never updates, or says "An error occured while updating FEZ (content still encrypted)")

Delete local content for FEZ in Steam and reinstall it; you won't lose any save data.

#### The game hangs or does not complete while installing prerequisites (on Windows)

Try to install them manually :
- .NET Framework 4.0 : https://www.microsoft.com/en-ca/download/details.aspx?id=17851
- Visual C++ 2010 Redistributable (x86) : https://www.microsoft.com/en-ca/download/details.aspx?id=5555

#### The game crashes on start

Try updating your graphics card drivers :
- Intel : https://downloadcenter.intel.com/
- nVidia : http://www.nvidia.ca/Download/index.aspx?lang=en-us
- AMD : https://support.amd.com/en-us/download
 
If the game still crashes on start, please log an issue and join the debug log (see procedure below).

#### I'm having a gameplay issue or bug that was also present in prior versions of FEZ, should I log an issue?

Feel free to log one, but there's good chances that it'll be closed as "Won't Fix". As I've said in the [announcement post](http://theinstructionlimit.com/fez-1-12), v1.12 is the last major update to FEZ and the intent of this bug repository is to make sure that 1.12 did not break anything that worked before, and that its changes actually fix what they were supposed to fix.

That said, crashes are always problematic and I do intend to fix those, new or old.

## Procedure

Please log issues using the "Issues" tab. Include anything that could help reproduce and fix the issue : screenshots (you can paste them directly from your clipboard), context/repro steps.

Location of the `[YYYY-MM-JJ] Debug Log #NN.txt` file (prefix is the date, suffix is sequential) :

- Windows : `%APPDATA%\FEZ\`
- OS X : `~/Library/Application Support/FEZ/`
- Linux : `$XDG_DATA_HOME/FEZ/`

Please join this file for crash reports.

Thanks!
