Qt Creator version 4.9.1 contains bug fixes.

The most important changes are listed in this document. For a complete
list of changes, see the Git log for the Qt Creator sources that
you can check out from the public Git repository. For example:

    git clone git://code.qt.io/qt-creator/qt-creator.git
    git log --cherry-pick --pretty=oneline origin/v4.9.0..v4.9.1

Editing

* Fixed folding for generic highlighter (QTCREATORBUG-22346)

QMake Projects

* Fixed unnecessary reparsing on file save (QTCREATORBUG-22361)

CMake Projects

* Fixed deployment with `QtCreatorDeployment.txt` (QTCREATORBUG-22184)

Debugging

* Fixed ambiguity of `F10` shortcut (QTCREATORBUG-22330)
* CDB
    * Fixed `Start and Break on Main` (QTCREATORBUG-22263)

Test Integration

* Fixed `Uncheck All`

Platform Specific

Android

* Fixed AVD creation for Google Play images

Remote Linux

* Fixed crash when running `Custom Executable` on remote Linux target
  from Windows host (QTCREATORBUG-22414)
* Fixed SSH connection sharing on macOS (QTCREATORBUG-21748)
* Deployment via SFTP
    * Fixed `Unexpected stat output for remote file` (QTCREATORBUG-22041)
    * Fixed deployment of symbolic links (QTCREATORBUG-22307)
* Deployment via rsync
    * Fixed compatibility issue with command line parameters
      (QTCREATORBUG-22352)

Credits for these changes go to:  
André Pönitz  
BogDan Vatra  
Christian Kandeler  
Christian Stenger  
David Schulz  
Eike Ziller  
Jaroslaw Kobus  
Jonathan Liu  
Leena Miettinen  
Mitch Curtis  
Nikolai Kosjar  
Robert Löhning  
Thomas Hartmann  
Ulf Hermann  
Ville Nummela  
