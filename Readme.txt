Updater readme
==============

To see some examples of Updater, check out the examples
folder.

For more information, visit http://www.gvhsoftware.org

(+) Added
(*) Changed
(-) Removed
(x) Error / bug (fix)

**********************************************************
CURRENT VERSION: 0.8.1.6
**********************************************************

======================
UPDATER v 0.8.1.6
======================

Manual:
=======
v0.8.1.5

Language pack:
==============
v0.8.1.5

Added/fixed:
============
(x) Fixed bug when reading not-encrypted update file

To-do:
======
(+) Add scripting engine
(+) Add user data collection
(+) Add skinning engine
(*) Enhance ftp support
(*) Sequenced updating should calculate which actions should be taken
    so there is only 1 update needed while in real more updates are
    needed. Currently, the user can update only the next version, not
    immediatly to current version

Known bugs:
===========
-

**********************************************************

======================
UPDATER v 0.8.1.5
======================

Manual:
=======
v0.8.1.5

Language pack:
==============
v0.8.1.5

Added/fixed:
============
(+) Added new option for close application (user) so user can close the
    application by himself
(+) Updater can't be started anymore when no user is logged in to windows
(*) Replaced ARACrypt encryption by Rijndael encryption
(x) Fixed some bugs when using CLOSEAPPLICATION
(x) Fixed bug when writing data to the registry
(x) Fixed bug that some people were not able to download files
(x) Fixed bug when a custom settings file is used, the version
    is written to the custom settings file instead of the default one

To-do:
======
(+) Add scripting engine
(+) Add user data collection
(+) Add skinning engine
(*) Enhance ftp support
(*) Sequenced updating should calculate which actions should be taken
    so there is only 1 update needed while in real more updates are
    needed. Currently, the user can update only the next version, not
    immediatly to current version

Known bugs:
===========
-

**********************************************************

======================
UPDATER v 0.8.1.4
======================

Manual:
=======
v0.8.1.3

Language pack:
==============
v0.8.1.3

Added/fixed:
============
(x) Fixed bug when using CloseApplication
(x) Fixed unzipping bug

To-do:
======
(+) Add scripting engine
(+) Add user data collection
(+) Add skinning engine
(*) Enhance ftp support
(*) Sequenced updating should calculate which actions should be taken
    so there is only 1 update needed while in real more updates are
    needed. Currently, the user can update only the next version, not
    immediatly to current version

Known bugs:
===========
-

**********************************************************

======================
UPDATER v 0.8.1.3
======================

Manual:
=======
v0.8.1.3

Language pack:
==============
v0.8.1.3

Added/fixed:
============
(+) Settings file can be located anywhere when the -settingsfile
    parameter is used
(+) Temporary update files are deleted after a successful update
(+) Application will be restarted when a rollback is performed, but
    only when the application should start after a successful update
(+) (Local) relative paths are now supported
(+) Windows 98 is now supported
(+) Added new setting (application root, see user guide for more details)
(+) Added new constants (%updateserverpath%, %updateserverfile% and
    %approot%)
(*) Section files are now name to application name. This makes it
    possible to use one update executable for multiple applications.
(*) Updater is now Unicode compatible
(*) Improved user guide, example of server file lay-out is added
(*) Section file is only written to application folder when settings
    are really used
(x) Version numbers without sub numbers (i.e. 1 instead of 1.1) are
    parsed right so they can be used without any problems
(x) Other applications are closed properly now

To-do:
======
(+) Add scripting engine
(+) Add user data collection
(+) Add skinning engine
(*) Enhance ftp support
(*) Sequenced updating should calculate which actions should be taken
    so there is only 1 update needed while in real more updates are
    needed. Currently, the user can update only the next version, not
    immediatly to current version

Known bugs:
===========
-

**********************************************************

======================
UPDATER v 0.8.1.2
======================

Manual:
=======
v0.8.1.2

Language pack:
==============
v0.8.1.2

Added/fixed:
============
(+) Added log viewer so the log file can be viewed by simply using
    the -log parameter
(+) Added %windowsdirectory% constant
(+) Added download destination field
(+) Added new parameter -checkforupdates which checks for new updates
    in hidden mode
(*) Proxy password can now be stored in settings file by used
(*) HTTPS is now supported
(*) The status of the file is stripped in information, warning and
    error dialogs
(*) Extended log information
(*) All dialogs now support ClearType
(*) User guide is rewritten and improved
(*) Using a new version of the unzip library, which includes some
    bug fixes
(*) Improved user interface on non-Windows XP machines
(*) Fixed Dial-up issue, this also works if you have two connections
    e.g. dialup and wireless through proxy
(x) Fixed closeapplication bug
(x) Fixed registry bug
(x) Fixed some internet connection bugs
(x) Fixed bug when an invalid URL was used as update location
(x) Fixed bug that hyperlinks look blurry when using ClearType
(x) Fixed several bugs in silent, verysilent and hidden mode
(x) Fixed bug when parsing parameters

To-do:
======
(+) Add scripting engine
(+) Add user data collection
(+) Add skinning engine
(*) Enhance ftp support
(*) Sequenced updating should calculate which actions should be taken
    so there is only 1 update needed while in real more updates are
    needed. Currently, the user can update only the next version, not
    immediatly to current version

Known bugs:
===========
-

**********************************************************

======================
UPDATER v 0.8.1.1
======================

Manual:
=======
v0.8.1.1

Language pack:
==============
v0.8.1.1

Added/fixed:
============
(+) Added select language dialog;
(+) Added new event action: show notifier;
(+) Hyperlink colors can be customized now;
(+) Added manual proxy settings - still in beta phase.
(*) Improved download resume;
(*) Improved ftp, http and network downloads;
(*) Improved user interface;
(*) Renamed all parameters for Updater;
(*) Thanks to François Le Luhern a lot of features have been improved;
(*) When Updater runs in silent mode and has no custom popup menu items,
    it will finish and close automatically when install is finished.
(*) Converted language format from dll to xml;
(-) Removed custom language file;
(-) Removed OnOpen event since it was useless;
(x) XML Tags can be used as data now without problems;
(x) Fixed bug when registering ocx file;
(x) Fixed bug when update file was encrypted;
(x) Fixed bug when cancelling an update;
(x) A lot of minor bug fixes;

To-do:
======
(+) Add scripting engine;
(+) Add user data collection;
(+) Add skinning engine;
(*) Enhance ftp support;
(*) Sequenced updating should calculate which actions should be taken
    so there is only 1 update needed while in real more updates are
    needed. Currently, the user can update only the next version, not
    immediatly to current version;

Known bugs:
===========
-

**********************************************************

======================
UPDATER v 0.7.1.1
======================

Manual:
=======
v0.7.1.1

Language pack:
==============
v0.7.1.1

Added/fixed:
============
(+) Updater can now close any applications at all the events;
(+) User can be forced to update an application;
(+) Added several new path variables;
(+) Added shortcuts support;
(+) Added software protection mechanism;
(+) Added new file action -> register files;
(+) Added customizable popup notify for silent mode;
(+) Added a method to use different update files for different
    product editions;
(+) Added option to add bitmaps to popupmenu;
(+) Added restore feature, restore an older version of the product;
(*) Updater can now restart system after update;
(*) Check connection is disabled by default since this version;
(*) Updater switched to full mode on htmlmessage, license and
    selectupdate. If you want Updater to change to full mode, use
    the event action setmode on the events to set the mode, because
    Updater will not change UI automatically anymore;
(*) A type for registry items can now be specified;
(*) Extended log function, parsing of update file is completely logged
    so errors can be found more easily;
(*) When user presses cancel before the download action, rollback will
    not be enabled anymore;
(x) Fixed some memory leaks;
(x) Fixed bug that wrong page is displayed when user presses
    cancel;	
(x) When using close action at AfterInstall event, Updater did not
    finish update properly. Bug is fixed;	
(x) Fixed bug that Updater started installing too quick after closing
    application;	
(x) Fixed bug that sections could not be disabled;
(x) Fixed bug that Updater crashed when user cancels receiving the
    update file;
(x) Fixed some minor bugs.

To-do:
======
(+) Add scripting engine;
(+) Add user data collection;
(+) Add skinning engine;
(*) Sequenced updating should calculate which actions should be taken
    so there is only 1 update needed while in real more updates are
    needed. Currently, the user can update only the next version, not
    immediatly to current version;

Known bugs:
===========
-

**********************************************************

======================
UPDATER v 0.6.3.2
======================

Manual:
=======
v0.6.3.2

Language pack:
==============
v0.6.3.2

Added/fixed:
============
(+) Added new event action: start next task. This is useful when install
    should begin immediately after downloading;
(+) It is now possible to encrypt the update file using Updater Tool;
(*) Improved confirmation screens. Updater will explain why the user
    must confirm to file deletion, application closing or stop updating 
    with a nice user interface;
(*) Improved error screens. Updater will explain what happened and what
    the user can do about it in the future to prevent it from happening
    again with a nice user interface.
(*) Constants can be used in other constants too. However, the constants
    used must be declared first;
(*) When user was able to choose not to delete file, Updater froze.
    This bug is fixed;
(*) When file cannot be deleted, Updater will continue updating;
(*) Files can be checked by hash too (only when using check separately);
(*) Updater will not stop updating when trying to download a 0 bytes file;
(*) Updater can now load future language files. Normally, you needed
    the exact language file version;
(*) Self-update location can now be specified without rebuilding Updater;
(*) Updater will not fail anymore when gvhsoftware.org is not reachable and
    selfupdate is enabled;

To-do:
======
(+) Add registration & license management feature.
(*) Sequenced updating should calculate which actions should be taken
    so there is only 1 update needed while in real more updates are
    needed. Currently, the user can update only the next version, not
    immediatly to current version;

Known bugs:
===========
-

**********************************************************

======================
UPDATER v 0.6.3.1
======================

Manual:
=======
v0.6.3.1

Language pack:
==============
v0.6.3.1

Added/fixed:
============
(+) Added new feature (html message) so company or product information
    can be shown to the user as a html page;
(+) Added sequenced updating (see user guide for more details);
(+) Added option to disable proxy support;
(+) Added new parameters (checkconnection and enableproxy);
(+) It is now possible to add hyperlinks to new features to give the
    user more information about a specific feature;
(+) It is now possible to add hyperlinks to sections to give the
    user more information about a specific section;
(*) Fixed version checking mechanism. Only versions with dots (.)
    could be parsed. Thanks to Steve Greaves it is possible to use
    a lot of characters (. , | - _) in the version strings;
(*) When Updater can't connect to www.gvhsoftware.org to check for
    selfupdate, update will still continue;
(*) Fixed bug that system tray showed install progress while update
    was already finished;
(*) When switching from silent to full mode, Updater is now set as
    active (front) window;
(*) When running in silent mode and using sections, all sections
    were added twice. This bug is fixed;
(*) Sometimes updater did not load the right page when the user clicked
    cancel, this bug is fixed;
(*) Optimized event handling;
(*) In the section screen, the title and the description of the first
    section are displayed automatically;
(*) Some minor bug fixes and improvements.

To-do:
======
(*) Sequenced updating should calculate which actions should be taken
    so there is only 1 update needed while in real more updates are
    needed. Currently, the user can update only the next version, not
    immediatly to current version.

Known bugs:
===========
-

**********************************************************

======================
UPDATER v 0.6.2.3
======================

Manual:
=======
v0.6.2.3

Language pack:
==============
v0.6.2.3

Added/fixed:
============
(+) Proxy authentication support added, all proxies can be
    passed now;
(*) Fixed connection timeout;
(*) Sections can now be disabled.

To-do:
======
(+) Develop tool for creating the xml-files.

Known bugs:
===========
-

**********************************************************

======================
UPDATER v 0.6.2.2
======================

Manual:
=======
v0.6.2.1

Language pack:
==============
v0.6.2.1

Added/fixed:
============
* Fixed bug that Updater always changed version number in
  settings.ini. Now it is only changed when the update is
  successful and the version is newer;

To-do:
======
(+) Add authentication support;
(+) Develop tool for creating the xml-files.

Known bugs:
===========
(x) When behind a proxy with authentication, Updater is not
    able to download files;

**********************************************************

======================
UPDATER v 0.6.2.1
======================

Manual:
=======
v0.6.2.1

Language pack:
==============
v0.6.2.1

Added/fixed:
============
* Added sections also known as selective updating;
* Added license agreement task;
* Added feature to define custom constants in Updater file;
* Main icon can be customized now;
* Versions are compared very accurate since this version;
* Added username and password support for FTP downloads;
* Fixed some problems with parsing command line, the minus
  char can be used in quoted parameters now;
* Fixed bug when writing to registry;
* Fixed bug for UI in full mode. Sometimes the property
  pages were not created when adding them to the property
  sheet;
* Added a quick example how Updater is working. You can
  run Updater and it will show you how Updater works with
  a simple example;

To-do:
======
* Add authentication support;
* Develop tool for creating the xml-files.

Known bugs:
===========
* When behind a proxy with authentication, Updater is not
  able to download files;

**********************************************************

======================
UPDATER v 0.6.1.2
======================

Manual:
=======
v0.6.1.2

Language pack:
==============
v0.6.1.1

Added/fixed:
============
* Added download resume;
* Updater can now be renamed and will keep working;
* Selfupdate bug is fixed, v0.6.1.1 will not update itself
  because of this bug (!);
* Update file (xml) is deleted immediately after parsing,
  this way the user is not able to view the file;
* Bug with not correctly loading custom language file is
  fixed;
* Fixed shellexecute run directory bug;
* Fixed problem that application location could not use
  directory variables;
* Fixed bug that Updater crashed when cancelling a backup
  process;
* When exiting silent mode after no new version is found,
  onclose event will be handled;
* In hidden mode, rollback will not be enabled when no
  new version is found;
* Fixed small bug when working recursive with folders;

To-do:
======
* Add authentication support;
* Develop tool for creating the xml-files.

Known bugs:
===========
* When behind a proxy with authentication, Updater is not
  able to download files;

**********************************************************

======================
UPDATER v 0.6.1.1
======================

Manual:
=======
v0.6.1.1

Language pack:
==============
v0.6.1.1

Added/fixed:
============
* Added automatic proxy support;
* Updater can now update itself too;
* When checking for Update file, no crashes will occur anymore;
* Updater is now VC6 & VC7 compatible;
* New wizard look, logo sizes are changed (see user guide);
* Added new path to Common Application Data;
* Only one Updater instance can be started per application.
  This means there can run as much Updater instances as you
  want, but not using the same settings.ini;
* updater_temp folder name is changed to updater_temp_%app%;
* A newer version of the xml parser is used;
* A newer version of the unzip library is used;
* Added system menu to full (wizard) mode;
* When error occurred when installing files, the filename was
  always null. This is fixed;
* CheckConnection is now implemented into the settings.ini, not
  into the updatefile.xml;
* Implemented automatic support for about 30 languages now;
* It is now possible to execute a website address, for example
  this feature enables you to add a link to your website in the
  popup menu in silent mode;
* Read-only files can also be unzipped;
* New action added: setfileattr, which can be used to set the
  attributes for files and/or folders;
* Translated about box;
* Fixed some minor bugs.

To-do:
======
* Add authentication support;
* Download resume;
* Develop tool for creating the xml-files.

Known bugs:
===========
* When behind a proxy with authentication, Updater is not
  able to download files;

**********************************************************

======================
UPDATER v 0.5.2.5
======================

Manual:
=======
v0.5.2.5

Language pack:
==============
v0.5.2.3

Added/fixed:
============
* For date/time checking, Updater used last access
  date/time, now it uses last modification date/time.
* Added log, all actions are logged now;
* Added new mode (verysilent);
* Extended popup menu in silent and verysilent mode will 
  only be available when update is finished;
* When no new version is available, there will not be an
  error icon anymore, but a success icon.
* Fixed little bug when downloading files;
* It is now possible to specify if Updater should show
  error or not. If not, Updater jumps to hidden mode when
  an error occurs and will roll back changes;
* Updater is faster in silent mode;
* Added about box to Updater;
* It is now possible to specify if Updater should wait or
  continue immediatly after executing a file;
* Languages are now loaded automatically if the language
  setting is empty;

To-do:
======
* Add proxy support (almost ready);
* Add retry / ignore / cancel when an error occurs;
* Develop tool for creating the xml-files;

Known bugs:
===========
-

**********************************************************

======================
UPDATER v 0.5.2.4
======================

Manual:
=======
v0.5.2.4

Language pack:
==============
v0.5.2.3

Added/fixed:
============
* Since v0.5.2.3, updater could not download files from
  internet anymore. This is fixed!
* Some small fixes to backup system;
* When a user cancels a folder copy, the copy process
  still continued. This bug is fixed;
* It is now possible to customize the text for Updater
  with a custom xml language file (see user guide for
  more information).

To-do:
======
* Add proxy support (almost ready);
* Add retry / ignore / cancel when an error occurs;
* Develop tool for creating the xml-files;

Known bugs:
===========
-

**********************************************************

======================
UPDATER v 0.5.2.3
======================

Manual:
=======
v0.5.2.3

Language pack:
==============
v0.5.2.3

Added/fixed:
============
* Fixed bug when interacting with pop-up menu in silent
  mode;
* Users can now see the progress of the update process in
  silent mode by holding the mouse over the Updater icon;
* When copying a file, and folder does not exists, Updater
  creates the folder;
* When downloading a file, the date/time of the on the
  internet is saved to the file on the hard-disk, so date/
  time checking is more accurate (not depending on update
  date);
* Users can now see the progress of file copy;
* In hidden mode, not interaction will be made with the
  user anymore (such as closeapplication);
* Values in settings.ini can now be 255 characters long;
* Date/Time checking can now be done automatically, even
  before downloading the files;
* Files that needs to be downloaded are checked for
  corruption first;
* Unzip action IS rolled back now too;
* Fixed most memory leaks;
* Rollback screen (page) is back with a progress of
  the rollback process;
* The progress is being calculated with so-called action
  points, so the install progress will be better apportioned;
* When no new version was found, still the OnNewVersion event
  was called, this bug is fixed;
* Version in settings.ini if only changed when exiting, not
  after install. This is done because users can still cancel
  the process after installing the updates.

To-do:
======
* Add proxy support (almost ready);
* Develop tool for creating the xml-files;
* Add feature to customise UI text;

Known bugs:
===========
-

**********************************************************

======================
UPDATER v 0.5.2.2
======================

Manual:
=======
v0.5.2.1

Language pack:
==============
v0.5.2.1

Added/fixed:
============
* Since v0.5.2.1, updater could not download files from
  internet anymore. This is fixed!

To-do:
======
* Add proxy support;
* Develop tool for creating the xml-files;
* Check downloaded files for corruption first;

Known bugs:
===========
-

**********************************************************

======================
UPDATER v 0.5.2.1
======================

Manual:
=======
v0.5.2.1

Language pack:
==============
v0.5.2.1

Added/fixed:
============
* Added ability to use %username% and %password% in a
  download location. Some servers require this as
  identification;
* Added new action: unzip;
* Added customized popup menu, it's now possible to add
  10 items to the popup menu in silent mode;
* User can now see what action is performed with a file;
* In Windows XP, Updater has now the XP-look;
* Language files are checked for version so user is always
  using the right language file;
* Updater is now statically linked, so Updater is not
  depending on MFC dll's anymore;
* Ftp downloads with authentication are supported;
* Fixed some small bugs;

To-do:
======
* Add proxy support;
* Develop tool for creating the xml-files;
* Check downloaded files for corruption first;

Known bugs:
===========
-

**********************************************************

======================
UPDATER v 0.5.1.1
======================

Manual:
=======
v0.5.1.1

Added/fixed:
============
* Fixed display of some languages such as russian by
  setting font type to Arial Unicode MS instead of Arial;
* Added date checking for files;
* Due to new UPX compression, filesize is smaller now;
* When rollback was disabled, the finish button in the
  rollback screen did not get enabled - fixed;
* Added hidden mode, user can't interact with Updater and
  no trayicon or dialog is shown;
* Added multiple download location support (mirrors);
* Added MFC dll's. They are needed to run Updater;

To-do:
======
* Add proxy support;
* Develop tool for creating the xml-files;

Known bugs:
===========
-

**********************************************************

======================
UPDATER v beta 0.5.0.0
======================

Manual:
=======
v0.5.0.0

Added/fixed:
============
* For the ones using the source-code, it is completely
  rewritten;
* %temp% is now a folder in system temp instead of updater
  directory, %updatertemp% points to updater temp folder;
* Updater updates version in settings.ini itself;
* For version in settings.ini, you can now even use codes
  like %app%;
* Event system is added. You can now perform these actions:
  - close updater
  - skip next task
  - run file
  - change mode
  On these events:
  - OnNewVersion
  - OnNoNewVersion
  - BeforeDownload
  - AfterDownload
  - BeforeInstall
  - AfterInstall
  - BeforeRollback
  - AfterRollback
  - OnClose;
* Added rollback support so all actions can be rolled back
  when an error occurs or when the user presses cancel;

To-do:
======
* Add proxy support;
* Develop tool for creating the xml-files;

Known bugs:
===========
-

**********************************************************

================
UPDATER v0.4.1.1
================

Manual:
=======
v0.4.1.1

Added/fixed:
============
* New features can be added to Updater file. These features
  can be shown to the user;
* New architecture of the XML file;
* You can check version for each file now, so only update
  the new files;
* Added function to check whether there is a connection with
  internet -- THANKS TO NEVILLE FRANKS;
* Since VC6, it was not possible to load languages anymore.
  This problem is fixed;
* Several languages added:
  - Dutch
  - French -- THANKS TO MARC TISSOT
* Parameters property in run actions is now optional;
* Added new variables, Application Data Path (%AppData%)
  and User Home Directory (%UserProfile%), and the variables
  are now case insensitive;
* Instead of setting version in settings.ini, you can also
  enter a filename. Updater checks the version of this
  file itself;
* Now it's possible to use true, false or restart for the
  closeapplication option in the xml file. Restart will close
  the application during update, but will start it again;
* Network files can be downloaded now too, for example
  \\MyServer\MyFolder\MyFile.ext
* Several bug fixes.

To-do:
======
* Add proxy support;
* Develop a tool that helps you create Updater files;
* Add rollback so all actions are rolled back when an error
  occurres or when the user presses cancel.

Known bugs:
===========
-

**********************************************************

================
UPDATER v0.3.2.1
================

Manual:
=======
v0.3.2.1

Added/fixed:
============
* Update file is now in XML format;
* Code is converted to VC 6.0;
* Complete code clean-up;
* MainFunctions class is splitted into several classes;
* GetFreeDiskSpace is replaced by GetFreeDiskSpaceEx;
* Version of Updater is now shown in bottom left corner;
* Popup menu of silent mode was not working, problem is
  fixed;
* Crash in silent mode fixed;

To-do:
======
* support proxy servers;
* new architecture, so the version can be checked for
  every single file you want to update;
* new code to check whether there is an internet connection
  or not.

Known bugs:
===========
-

**********************************************************