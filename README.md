# EndtermProject
This is the Endterm Project repository
On the defense the CREATE methods were not working. After defense i checked and they were indeed working. I couldn't find the source of the mistake, but i probably tried to create objects with id which was already taken. So, CREATE methods of WORKERS and USERS should be fine. Products CREATE method, however, refuses to work - it creates an object with id=0, no matter which id you input in there. Probably some mistake during table creation.
