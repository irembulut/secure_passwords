# Secure Passwords with Password Manager App

ID:20150807016

Name: İrem Sultan BULUT

Youtube Link: https://youtu.be/Srjw9cwpjo8

## Methodology and Findings:

As everyone knows, interest in cryptocurrency has increased with many applications we use today. 
While our personal information is stored in other applications, our money, which is our livelihood,
is stored in the crypto part. These platforms are given a password on login and in some cases a unique name
for the username. In such cases, it becomes more and more difficult to remember our passwords and usernames.
That's why we want to keep our passwords somewhere. At this point, our application will come into play.

Password manager application is an application that you can use to store your passwords and usernames.
While designing this application, we first load our libraries.
The most important of these libraries and the ones we need to know in this section are secureStorage,
hive and encrypt.
You will store your passwords by changing them according to the encrypt format you have determined 
with the encrypt library.
Generating encryption data class to use every transaction. This class has two functions for encrypting and decrypting the transaction.
AES algorithm works with Key and IV parameters. These parameters can be stored as env file in the asset folder.
In this project, we used the IV parameter to decrypt the data.

Hive and securestorage library is a library that allows you to store your data on your own phone.
With the Hive library, you can store all your data on your phone,
and when you add the securestorage library to this library,
you can now store your passwords in an encrypted form.
We save our necessary passwords on hive, so we can read, edit or delete the passwords
we have saved on the phone when there is no internet.






## Registration page

![alt text](https://github.com/irembulut/secure_passwords/blob/main/findings/save.png)


## Encrypted password

![alt text](https://github.com/irembulut/secure_passwords/blob/main/findings/encryptedpass.png)


## Decrypted password

![alt text](https://github.com/irembulut/secure_passwords/blob/main/findings/decryptedpass.png)
