# disposable_windows_for_linux_user
>One time use windows for linux user who only need to use office from Microsoft 

Everyone knows Microsoft Office make most profit for Microsoft, therefore there are thousands of reasons why Microsoft never want to have a Linux versioin of Office.  

![screen shot 2017-02-05 at 9 01 45 pm](https://cloud.githubusercontent.com/assets/5915590/22633416/d5c1fb98-ebe6-11e6-9dd8-c72ea7f2ba54.png)

For linux users there are LibreOffice, OpenOffice ,Calligra Suite... but Microsoft continuously changing their format so people can nerver leave Windows since you never know if your business patners will one day just couldn't open your OpenOffice files and you end up losing your time or busisness opportunities.

This solution is for those who have a Linux working enviroment but nobody needs anything from Windows besides Microsoft Office.

1. First we create a Windows image in VirtualBox. Install and register everything you need (Don't forget to install VirtualBox Guest Additions as well for NFS mount later).

2. Make sure Windows boot up normally and shut it down. 

3. Go to your home directory and copy the .VirtualBox folder back to your NFS share storage space.

4. Use my script "startwin" and put it into a NFS PATH and modify it to fix your enviroment.

5. Voilà!!

![screen shot 2017-02-05 at 10 04 01 pm](https://cloud.githubusercontent.com/assets/5915590/22634509/13842272-ebf0-11e6-933c-4514ac58e4e2.png)

The best part is the this Windows image won't get any bigger since everyone is sharing the same image once they shut the Windows down and start again everything get clean out and every user in your working enviroment only needs one Windows license. (Just make sure users save their files back to their home directory).



