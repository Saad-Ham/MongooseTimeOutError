# MongooseTimeOutError
This repository helps you solving the timeOut error while using mongoDB

There are three methods to go about this which worked for me.

1. [internet connection] : Try switching your internet source, there may be an issue with your internet source.
2. [Windows firewall] : It's possible that Your system firewall is blocking access to the database, you can try turning it off.
3. [Connection String (mongoDB atlas)] : When you are getting the connection string from mongoDB atlas, there is a dropdown menu right above it, mentioning nodeJS {version},
   try changing the version to {2.12.2 or later}, it worked for me.
