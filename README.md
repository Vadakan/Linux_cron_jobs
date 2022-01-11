# Linux_cron_jobs

**Cron job format**


![image](https://user-images.githubusercontent.com/80065996/148992081-5ab435bb-b176-43a7-838c-504687108295.png)


**Below are the cron examples on how to handle cron jobs scheduling**


![image](https://user-images.githubusercontent.com/80065996/148994605-289ed4ef-af1c-44ea-b92a-0a1327afde6c.png)


**How to Set up cron:**

1) **issue command 'cat /etc/crontab' to check whether cron is set up already in your system**

if you get output like below, then crontab is installed and set up in your system. Or else you have to install cron on your system


![image](https://user-images.githubusercontent.com/80065996/148995055-685b68f9-f4a6-489d-b245-274df326ec4e.png)

2) check the status of cron - whether it is 'Active' or 'NOT' by using command in below screenshot

![image](https://user-images.githubusercontent.com/80065996/148995811-029278fa-c2e2-4dcd-b337-bc2ff0df410e.png)

3) **crontab -l ** is the command used to check the contents inside the crontab

![image](https://user-images.githubusercontent.com/80065996/148996182-699075aa-ceca-4cdc-be74-ef32d87d5e2a.png)

4) **contab -e ** is the command used to edit the contents inside the crontab. Initially it will ask for the type od editor (choose nano editor)
  
  ![image](https://user-images.githubusercontent.com/80065996/148996403-28aacdd7-4d8d-4409-937d-3f21f1a6558f.png)
  
  Edit in the nano editor and press CTL+X to save and (capital Y to confirm ) and press enter to save and close
  
  ![image](https://user-images.githubusercontent.com/80065996/148996434-8079e487-1660-4c5d-9dd8-e3bc50d28715.png)
  
  5) all set your crone is active

  6) **To remove the crontab **


![image](https://user-images.githubusercontent.com/80065996/148996665-1d81907e-9e0c-4a69-b6f8-dd4e4bb12db3.png)

now to try to see the cron, there wont be any cron available

![image](https://user-images.githubusercontent.com/80065996/148996867-2392a375-3801-4dcc-9d09-8caee9cfe7e7.png)


7) open empty crontab using "crontab -e" and start updating the contents

![image](https://user-images.githubusercontent.com/80065996/148997257-25aa38ef-13e7-421f-8a19-99808bf6ba33.png)

![image](https://user-images.githubusercontent.com/80065996/148997281-1eb0e3ee-e51d-49fc-8a6f-06cfedb4f0b5.png)


