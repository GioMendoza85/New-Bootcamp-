## Activity File: Creating Domain OUs, Users, and Groups

In this activity, you are tasked with setting up users, groups, and organizational units for your domain.

- In this scenario, your company needs you to set up the domain accounts for the people who will be using the Windows workstations. 

- You will need to set up two users: `Andrew` and `Bob`. Andrew is in the development department, and Bob is in the sales department.

### Instructions

Complete the following tasks using the Active Directory Users and Computers (ADUC) tool:

1. Create a top-level `GC Users` organizational unit for each department's users.

    - Create a `Sales` sub-OU.

    - Create a `Development` sub-OU.

2. Create a user, `Bob`, in the `Sales` OU. 

    - Set their password to `Ilovesales!`.

3. Create a group, `Sales`, within the `Sales` OU.

    - Add user, `Bob`, to the group `Sales`.

4. Create a user, `Andrew`, in the `Development` OU.

    - Set their password to `Ilovedev!`.

5. Create a group, `Development`, within the `Development` OU. 

    - Add user, `Andrew`, to the group `Development`. 

6. Move the Windows 10 machine in the existing default `Computers` directory to a new `GC Computers` OU.

    - Create a `GC Computers` OU. It should be on the same level as `GC Users`.

--- 

© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.