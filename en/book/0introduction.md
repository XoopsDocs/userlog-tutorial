# Introduction

Userlog is a node logger which can log your user/visitor activities in your site from a preferred node.

This is a very useful tool for Webmasters in busy sites. For example, you can log your other Admins navigation. 

###Features:


- Log user activities and navigations.

Examples:
```
1- The possibility to list all the IPs used from a certain user, and conversely to list all the users logged from a defined IP to find duplicate users.

2- Find deleted items from your database.

3- Find admin user activities(webmasters, moderators, ...)

4- Find users who come to your site from Google.
```
- Can log users by getting User ID, User group or visitor IP.

- Logs can be stored in file, database or both.

- Any below user information and/or page data can be selected to be logged.

```
User ID,Username,Is Admin?(y/n),Groups,User Last Visit,User IP,User agent,URL (Request URI),Script name,Referer URI,Page title,Is Page admin?(y/n),Module dirname,Module name,Item name,Item ID,Request method (GET, POST, ...),$_GET,$_POST,$_REQUEST,$_FILES,$_ENV,$_SESSION,$_COOKIE,Headers list,Logger
```
- Any active module in your installation can be selected and userlog will log users activities only in those modules.

- You can navigate/delete/purge/export to CSV user logs in admin/logs.

- You can render logs from database or file source engine in admin/logs.php.

- To search for logs based on a criteria you have an advance form in admin/logs.php

- You can see/delete/rename/copy/merge/compress(zip)/export to CSV log files in admin/file.php.

- You can see total module views, total user views, total group views in admin/stats.php

- you have an advance form to see any item views using some criteria like what is the module/link/log time/viewer uid/viewer group id of the item in admin/stats.php

- by activating the views block you can set a most viewed items in a module or in the whole website in a specific period of time. e.g.: today most viewed (hot) news

- You can set the module as Active or Idle in preferences.

- If you need to store logs in a file, you can set the working path, working file size, working file name, ... in preferences.

- If you need to store logs in database, you can set the maximum logs thresholds (maximum number of logs and maximum time that logs are stored in the database) in preferences.

- Can be used as a backup/restore tool.

- Used JSON format to store arrays to database for better performance (instead of xoops core serialize).
