# Trello REST API testing with Postman
## :mag_right: About project
The project was made during self-study and the course "Software Testing in Practice" prepared by Rafal Podraza. 
I created this project in order to practice, consolidate the acquired knowledge and document my skills.
During this challenge I learned the basics of REST API testing, became familiar with the Postman tool, created my own collection based on Trello documentation and made scripts for test automation.

The result of the project is a collection of Trello REST API tests performed in the Postman tool.
## :clipboard: Test scope based on [Trello API Documentation](https://developer.atlassian.com/cloud/trello/rest/api-group-actions/#api-group-actions)
- **Board**
  - Create a Board
  - Get a Board
  - Update a Board
- **List**
  - Create a new List
  - Get a List
  - Get Lists on Board
  - Update a List
  - Archive all Cards in List
- **Card**
  - Create a new Card
  - Get a Card
  - Update a Card
- **Checklist**
  - Create a Checklist
  - Get a Checklist
  - Create Checkitem on Checklist
- **Delete**
  - Delete Checkitem from Checklist
  - Delete a Checklist
  - Delete a Card
  - Delete a Board

## :electric_plug: How to get started?
#### :pushpin: List of steps needed to run collection and tests:
:one: [Postman installation](#one) 

:two: [Creating a Trello account](#two)

:three: [Trello authentication](#three)

:four: [Importing a file into Postman](#four)

:five: [Creating environment variables in Postman](#five)

:six: [Run collection and testing](#six)

--------
#### <a name="one">:computer: Postman installation</a>
1. Go to the [Postman website](https://www.postman.com/downloads/) and click the orange button with name of your operating system.
2. Download the installation file, then run the installer and follow the instructions that appear.
3. Postman is ready to use.

#### <a name="two">:e-mail: Creating a Trello account</a>
1. Go to the [Trello website](https://trello.com/) and click the blue button with text "Get Trello for free".
2. Create a Trello account by following the instructions that appear.
3. Your Trello account is ready to use.

#### <a name="three">:key: Trello authentication</a>
1. Log in to your Trello account.
2. Go to the [Trello developer API key generation page](https://trello.com/app-key).
3. Click on the "Go to the Power-Up Admin Portal", confirm acceptance of terms and conditions, then press the "new" button and enter the required details.
4. Generate a new API key. Copy and save it for later use in Postman.
5. Next, click on the "token" link that will appear next to the generated key.
6. Allow application to access your Trello account.
7. Your token will be displayed on the page. Copy and save it for later use in Postman.

#### <a name="four">:open_file_folder: Importing a file into Postman</a>
1. Go to [my Postman collection file](https://github.com/Martyelny/REST-API-Trello/blob/main/Trello.postman_collection.json).
2. Click on the three dots icon in the top right corner and click "Download".
3. Run Postman and click on "Import" button in the top left corner.
4. Drag and drop the downloaded file from the Download folder into the "Import" window.
5. The collection will appear in Postman, ready for use.

#### <a name="five">:earth_africa: Creating environment variables in Postman</a>
1. Click on the "Environment" dropdown in the top left corner in Postman.
2. Click on the "New" button to create a new environment and choose "Environment" icon.
3. Give your environment a name.
4. Create a "key", "token" and "baseURL" variable. You should enter the value "https://api.trello.com/1/" into the "baseURL" variable and the value of your key and token in the "key" and "token" variable. For collections from this repository, the API key variable is named {{key}}, the token variable is named {{token}} and the URL variable is named {{baseURL}}.
5. Click "Save" button to save the environment.
6. Click on the "Environment" dropdown in the top left corner and select the environment you just created.

#### <a name="six">:arrow_forward: Run collection and testing</a>
1. Click on the "Collections" icon in Postman.
2. From the list of collections, select the one named "Trello" and click on the icon with three dots that appears when you hover over the collection name.
3. Select "Run collection" from the list.
4. Click one the orange button "Run Trello".

-------
### If your view looks like the screenshot below you have successfully completed all the steps and tested my collection.
![Trello - Run results](https://github.com/Martyelny/REST-API-Trello/assets/115575209/9ecade6a-98de-4eb2-a6c2-5d8f313dcc8c)


![Trello Run results2](https://github.com/Martyelny/REST-API-Trello/assets/115575209/9d496bd7-4b52-4d2e-9837-592774d0e86e)


