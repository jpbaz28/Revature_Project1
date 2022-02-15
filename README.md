# Revature_Project1

## Links to Github Repos

[Backend(RESTful API)](https://github.com/jpbaz28/Project1_Back_End)
[Frontend(Web/React)](https://github.com/jpbaz28/Project1_Front_End)
[Frontend(Mobile/ReactNative)](https://github.com/jpbaz28/Project1_Back_End)

## Project Description

- Meta Repository For Project 1 Expense Reimbursement System. Contains links for the Project1_Backend, the Project1_Frontend, and the Project1_Mobile_Frontend.

## Technologies Used

- Backend written in TypeScript is a RESTful API. Routes handled by Express, and data is stored in a CosmosDB on Azure.
- Web Frontend written in React.
- Mobile Front End written in React-Native.

## Features

- Allows for login for either an employee or manager.
- Employees can submit a reimbursement request that can be approved or denied by a Manager.
- Employees can view all of their previously submitted Reimbursements.
- Managers can log in and see a list of all reimbursements, pending, approved, and denied.
- Managers can approve or deny pending reimbursements.
- Managers can see a statistics page that shows the employee with the highest amount of reimbursements, and the average cost of reimbursements.
- Mobile app just allows for managers to log in.

## To-Do List

- Improve Mobile experience.

## Usage

- Clone Repos(links at top)
- Setup CosmosDB instance on azure.
- Copy connection string on Azure and make an environment variable on your local machine and name it: COSMOS_CONNECTION.
- Run npm start from whichever front end you would like to use on local machine.
- Server will start on localhost:3000
