#                                                       Demo Script
 _________________________________________________________

**Step 1:** Navigate to Readme.md and follow instructions to install KOB

![image](https://user-images.githubusercontent.com/33585301/85214081-37b6c000-b384-11ea-836e-ac73281e5fb6.png)

 _________________________________________________________

**Step 2:** Tryout a) version of kob installed b) kob help

![image](https://user-images.githubusercontent.com/33585301/85214138-f7a40d00-b384-11ea-947d-39f757a8ecaa.png)
 _________________________________________________________

 **Step 3:** kob list

![image](https://user-images.githubusercontent.com/33585301/85214146-199d8f80-b385-11ea-8e2d-72c7a2293926.png)
 _________________________________________________________

**Step 4:**

Mention what softwares will be installed as a part of the environment you have selected e.g in case of KOBman , mention vscode ,kobman source code along with test cases will be install from your fork. This can also be other environment as well,  Idea is to show a webpage or application running after the installation

 _________________________________________________________

**Step 5:**
Listing out command and its expected outputs:

    kob install --env KOBman --version 0.0.2(kob status)

![image](https://user-images.githubusercontent.com/33585301/85214242-0d660200-b386-11ea-8938-1fb47a356761.png)


    kob install --environment KOBman --version 0.0.2  (already in local system)

![image](https://user-images.githubusercontent.com/33585301/85214266-3d150a00-b386-11ea-855c-fafb6ba98463.png)


    kob install --environment KOBman --version 0.0.a  (wrong version)

![image](https://user-images.githubusercontent.com/33585301/85214282-62097d00-b386-11ea-962b-9af5f1c77c5a.png)

    kob install --environment KOBman (default version )

![image](https://user-images.githubusercontent.com/33585301/85214294-849b9600-b386-11ea-88f3-9fb5b6bc0ee0.png)
 _________________________________________________________

**Step 6:** kob status

in order for us to understand how kob status works let open up an terminal window and

-[tree command should be displayed on ~/.kobman/envs/]

![image](https://user-images.githubusercontent.com/33585301/85214313-b7458e80-b386-11ea-9cc0-ee23b67a200c.png)

-[cat value of current file in each envi ~/.kobman/envs/kob_env_*/current ]

![image](https://user-images.githubusercontent.com/33585301/85214331-e8be5a00-b386-11ea-96c1-404d1fe1618b.png)


-[tree command should be displayed on ~/Dev_KOBman]

![image](https://user-images.githubusercontent.com/33585301/85214353-1c997f80-b387-11ea-9a96-a12c7192d240.png)


**Step 7:** Bring up show all the application you had mentioned you would install in Step 4. Navigate to the src code that has been installed by the environment script.
