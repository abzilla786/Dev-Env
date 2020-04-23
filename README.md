# Node App Development Environment

This repository contains a Node application which is integrated with mongodb. To learn more about the app itself, please see the README.md file within the app folder.

## Prerequisites
To run this environment you will need the below (versions used included):

- Vagrant v2.2.7
- Git v2.24.1
- VirtualBox v6.1.4
- Dependencies

Before running the app you will need to install dependencies which will allow you to run the application. Steps are below:

Create the two virtual machines using Vagrant
```
vagrant up
```

Ssh into the application's virtual machine once the machines are running
```
vagrant ssh app
```

Navigate to the application's folder
```
cd app
```

Install application's dependencies (this step would have been completed automatically)
```
npm install
```
## How to Run

Steps are below:

Ssh into the applications virtual machine
```
vagrant ssh app
```

Navigate to the application's folder
```
cd app
```

Run the application
```
npm start
```


peace :)
