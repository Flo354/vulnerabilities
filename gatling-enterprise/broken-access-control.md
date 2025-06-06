On Gatling Enterprise versions below 1.25.0, at least two read endpoints reserved for "admins" are targetable by users having only the "view" role
- /api/private/teams
- /api/private/repositories

For non-privileged users, the endpoint that is accessible should only be:
- /api/private/roles/teams, which gives only the "id" and "name" of the team required for the page "Simulations"

![image](https://github.com/user-attachments/assets/3048aa5b-0d4c-4b68-8f8a-120e4e1990f9)

![image](https://github.com/user-attachments/assets/c822df71-c4f0-4767-94b1-934bc360a5b0)

![image](https://github.com/user-attachments/assets/44520fe8-bcfc-4033-a6fc-037c105eb8a3)

![image](https://github.com/user-attachments/assets/7990fd52-bdbf-4fca-9b8d-72307fe3f111)

![image](https://github.com/user-attachments/assets/d6b5d862-60c4-4f3e-b965-7ed4e9ceaa65)

![image](https://github.com/user-attachments/assets/541d385e-6e36-4cf9-9829-d848e7309df3)
