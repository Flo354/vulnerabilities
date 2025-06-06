On Gatling Enterprise versions below 1.25.0, When the permissions of the user are changed, the new permissions are not applied until the user generates a new "session-id" by logging-in back on the system.  
More importantly, a removed user with a valid "session-id" can still access the application as if it was existing.  
In top of that, since the sessions are not expiring ([broken logout](https://github.com/Flo354/vulnerabilities/blob/main/gatling-enterprise/broken-logout.md)), removed users can use the app indefinitely, as-long-as they keep the session-id.

![image](https://github.com/user-attachments/assets/68ef9171-f120-4231-b748-48cf98d72776)

![image](https://github.com/user-attachments/assets/f6712631-7a9b-453d-ad3a-57eda8a5dd50)

![image](https://github.com/user-attachments/assets/fe225c97-3228-4f83-bc6b-8869e06f4015)

![image](https://github.com/user-attachments/assets/0e8ddb31-2156-46e1-8720-bab243661303)

![image](https://github.com/user-attachments/assets/671936f1-bae9-48cb-8ea4-c0a957b60d2c)
