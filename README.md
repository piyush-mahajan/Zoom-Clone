## How the App looks-

![Screenshot (69](https://user-images.githubusercontent.com/98900169/226881714-f257596b-6751-453f-83c9-c1584c03a30b.png)
![Screenshot (70](https://user-images.githubusercontent.com/98900169/226881724-4a1ad2f3-e50d-473e-921b-7a090fd5922f.png)
![Screenshot (71](https://user-images.githubusercontent.com/98900169/226881732-64f0f7d4-878e-4630-a557-c1188ddd00da.png)
![Screenshot (72](https://user-images.githubusercontent.com/98900169/226881737-503d313b-12ac-4047-af76-d53cc9c13b47.png)
![Screenshot (73](https://user-images.githubusercontent.com/98900169/226881739-fadf6cd4-867f-49bf-80c7-de42f7668cbc.png)
![Screenshot (74](https://user-images.githubusercontent.com/98900169/226881708-9e49f0e4-70bb-48ad-9c80-142efb931b9b.png)



## Running the demo - Client Side.
To run the demo follow these steps:

1. [Head to CometChat Pro and create an account](https://app.cometchat.com/signup)
2. From the [dashboard](https://app.cometchat.com/apps), add a new app called **"zoom-clone"**
3. Select this newly added app from the list.
4. From the Quick Start copy the **APP_ID, APP_REGION and AUTH_KEY**. These will be used later.
5. Also copy the **REST_API_KEY** from the API & Auth Key tab.
6. Navigate to the Users tab, and delete all the default users and groups leaving it clean **(very important)**.
7. Download the repository or by running `git clone https://github.com/hieptl/zoom-clone.git` and open it in a code editor.
8. Create a file called **.env** in the root folder of your project.
9. Create the content of the **.env** file as follow.

```js
REACT_APP_COMETCHAT_APP_ID=xxx-xxx-xxx-xxx-xxx-xxx-xxx-xxx
REACT_APP_COMETCHAT_REGION=xxx-xxx-xxx-xxx-xxx-xxx-xxx-xxx
REACT_APP_COMETCHAT_AUTH_KEY=xxx-xxx-xxx-xxx-xxx-xxx-xxx-xxx
```

10. Make sure to exclude **.env** in your gitIgnore file from being exposed online.
11. Run the following command to install the app.

```sh
    npm install
    npm run start
```

## Running the Demo - Server Side

To run the demo follow these steps:

1. We will use the MySQL database. For this reason, this section describes how to create the database and its table. Before proceeding, you need to make sure that you have installed the MySQL database on your computer already. To create the database and its table, you need to get the zoom.sql and run it.
2. Create .env file and replace the below information with the information of your database connection.
```js
PORT=xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx
DB_HOST=xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx
DB_USER_NAME=xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx
DB_USER_PASSWORD=xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx
DB_NAME=xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx
DB_PORT=xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx
```
3. Install all the dependencies of the applicatoin by running
```js
npm install
```
4. Because we are installing the nodemon library. Therefore you can run one of the follow statements to run your project.
```js
node index.js 
or 
npx nodemon index.js
```
5. Make sure to include the .env file in your gitIgnore file from being exposed online.

