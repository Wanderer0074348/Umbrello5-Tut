## Umbrello5 Entity Relationship Diagram
1. Umbrello UML Modeller is a UML diagram tool that can support you in the software development process
### Connect to your session using MobaXterm
1. Open MobaXterm
2. Go to Tunneling on the taskbar and click on new session<br>
![image](https://github.com/user-attachments/assets/9d6be6dd-9c6e-401a-bffa-c133fe3d2ce3)

3. Enter the following details
   1. Forwarded Port: 22
   2. SSH Server: 172.16.22.64
   3. SSH ID: YOUR BITS ID
   4. SSH PORT: 22
   5. REMOTE SERVER: 172.16.22.64
   6. REMOTE PORT: 22<br>
   ![image](https://github.com/user-attachments/assets/5456a713-883e-462a-b957-a877488fea7d)

4. Save and then go to sessions<br>
![image](https://github.com/user-attachments/assets/43adf081-75ae-48c6-8878-2fd54451f86f)
5. Select user sessions from the drop down and then go to ssh, and put the SSH SERVER and your id number as the values, put your password and login<br>
![image](https://github.com/user-attachments/assets/e2d660dd-c359-40eb-a541-69b7dcc28b75)

### Set-up Project
Launch Umbrello5 from MobaXterm session by using the following command
```bash
umbrello5
```
1. Select Entity Relationship Model from the side panel by double clicking on it<br>
![image](https://github.com/user-attachments/assets/72247ee5-020f-4a47-aa40-63cace88afe1)

2. Set a name, in this case `car insurance company`<br>
![image](https://github.com/user-attachments/assets/2b9fafb6-8bbd-4913-8c5a-7786d051e668)

3. Select `Entity` from the toolbar<br>
![image](https://github.com/user-attachments/assets/0699dec3-8a1e-4c14-9faa-754c5967a999)

4. Using the reference ER-Diagram from the question, add the rest of the Entities<br>
![image](https://github.com/user-attachments/assets/6f3cc843-b042-4b64-9edc-982cb645c78e)

### Adding Attributes

1. Add `attributes` to `Entities` by double clicking on the entity and going to attribute tab<br>
![image](https://github.com/user-attachments/assets/d013567f-ebb5-4274-8ca8-107ad274152c)

2. Fill in the details, like here, `customerid` is an integer and is unique, hit `OK` and `apply`, then close the window by hitting `OK`<br>
![image](https://github.com/user-attachments/assets/5e44d3f5-dee1-4db1-8d77-00cf41de1dfa)

3. Do the same for all the other attributes of all the other entities<br>
![image](https://github.com/user-attachments/assets/30b2ed69-535d-4ba9-8eff-ceccda5ff756)

4. Add Primary Keys to the Tables, but double clicking on the entity, then entity constraints, then new constraints<br>
![image](https://github.com/user-attachments/assets/0c84a3f2-8375-4cd6-935c-c3e6c3bedd25)

5. Click on `Primary Key` Constraint, then give a name to the constrain(optional), but make sure to select the correct attribute to apply the constraint to, here for `customer`, it would be `customer_id`, click on `Add` then `OK`<br>
![image](https://github.com/user-attachments/assets/584c3e7a-f3e8-4e45-b4d7-91f16ccc65f6)

6. Add the constraints to all the other Entity Attributes.

### Making Relationships
#### Making relationships in Umbrello differs slighty from the traditional book definition of the ER Diagram, i.e, the diamonds to show the relationship dont exist, it is simplified to one tool, the `relationship` tool
#### NOTE: THE RELATIOINSHIP TOOL ALSO DOES NOT IMPLY MULTIPLICITY, IT ONLY EXPLAINS THE DIRECTION IN WHICH THE RELATIONSHIP EXISTS

1. Click on the relationship tool, to select it, it looks like the one-many structure, but in UMBRELLO, it is only a relationship indicator, select and create the relationships between the entities<br>
![image](https://github.com/user-attachments/assets/9386291a-fa17-41bf-9acc-e0f5940c15fd)

2. Click on the relationship line to give it a name<br>
![image](https://github.com/user-attachments/assets/8789ecbd-ccc7-4140-87de-a4230c667307)

3. Change Multiplicity by going to the Roles tab and selecting multiplicity values from the drop-down menu<br>
![image](https://github.com/user-attachments/assets/28a6b4e8-96b1-44cd-8617-23b1f215ab0f)

4. Add the names to the relationships and assign the correct multipliers to the rest of the relationships between entities<br>
![image](https://github.com/user-attachments/assets/3b6be01c-6e1c-4c4b-a4cb-1a0be75dc452)

### Save and Exit
1. Save the Code by using `ctrl+s` and close the window
