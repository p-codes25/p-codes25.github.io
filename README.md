# Paul's Open Source Projects
This page contains some projects I've uploaded to GitHub. I hope you find them useful!
# Viewer for SMS Backup & Restore Files
This is a Windows application which loads and displays backup files created by the [SMS Backup & Restore app for Android, by SyncTech](https://www.synctech.com.au/).  I have no affiliation with them - I just wrote this program using their [documented backup file format](https://www.synctech.com.au/sms-backup-restore/fields-in-xml-backup-files/).

SMS Backup & Restore is an awesome app for backing up SMS/MMS messages and phone call logs from an Android phone.  It writes the backups to an XML-formatted file which can be transferred to a Windows PC and opened and viewed using the SMS_MMS_Reader app.

There were several existing options for viewing the XML backup files that SMS Backup & Restore produces, but I wasn't satisfied with any of those.  I had many thousands of text messages and hundreds of images and videos in MMS conversations, and my SMS/MMS backup files were several hundred MB to 1GB or larger in size, and the existing viewers didn't seem to handle that volume of messages very well.

I wanted the ability to quickly view and search those backed-up messages at any time, with an easy-to-use Windows interface that could load and display the XML backup files without having to manually execute commands or scripts.

So, I wrote the [SMS_MMS_Reader project](https://github.com/p-codes25/SMS_MMS_Reader), hosted on GitHub.  It's written in C++ and MFC for Microsoft Visual Studio, and I built a release and uploaded that in case you want to download and run it right from there.
