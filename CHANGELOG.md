2.8.0.4  Corrected language files (by Michael Milette (mjm4842) on September 6, 2010)
         Enabled DROP TABLE IF EXISTS option by default.

2.8.0.3  File Backup now always available (by Michael Milette (mjm4842) on September 4, 2010)
         Replaced use of exec(ZIP) with a call to the PclZip library which
          is included with WebsiteBaker. Not only is it faster, but
          compatible with more systems. As a result, the file back option
          is now always available on all systems.
         For security purposes, in the event that the execution of the script
          times out before it finishes, the filename now includes unix
          timestamp number to minimize the possibility of someone guessing
          the file name.
         The http headers have been modified to be compatible with IE 6+.
         Upgrade from all previous versions now works properly.

2.8.0.2b File Backup fixes (by Michael Milette (mjm4842) on August 2, 2010)
         Fixed undeclared variables to eliminate related Notices.
         Now suppresses exec Warning message if exec is disabled in php.ini.
         Added tool tip for radio button showing reason if disabled.
         If PHP script timeout is less than 2 minutes, increased time limit.

2.8.0.2a Add new file backup option (by Michael Milette (mjm4842) on 1 August 2010)
         Note: Only works if PHP exec command is enabled and ZIP command
         is executable.

2.8.0    Add "drop table if exists" - option to the interface and backup-sql.
         Minor cosmetic code-changes.
         Add modul-version to the sql-dump.

2.7.x    QuickFix: 26. March 2010
