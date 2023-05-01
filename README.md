# Global Hospital



# Global Hospital-documentation

<p align="center">
  <a href="" rel="noopener">
 <img width=500px height=200px src="HomePage.png" alt="Project logo"></a>
</p>


<h3 align="center">HomePage</h3>

---

<p align="center"> In my project, I had implemented hospital management system in which I create login, create user, patient, register and pharmacist as users and create prescription, item and view doctor list.
  <br> 
</p>

## 📝 Table of Contents
- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Flow Chart](#flowchart)
- [TODO](../TODO.md)
- [Contributing](../CONTRIBUTING.md)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>
This project Hospital Management system includes registration of patients, storing their details into the system and also booking their appointments with doctors.It  has the facility to give a unique id for every patient and stores the details of every patient.Receptionist can search availability of doctor and details of patient using id. The hospital management system can be entered using  username and password and it is accessible by Receptionist.


## 🏁 Getting Started <a name = "getting_started"></a>
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

1.Open NetBeans IDE and select new project and give your project name

2.Right click on project and select JFrame form and design the form using pallete properties

3.Download MySQL-connector jar file and add into libraries

4.Using that, Give database connection using JDBC

5.To perform database operations download SQLYOG 

### Prerequisites
we have to install

NetBeans IDE

SQLYOG version 5

### Installing
A step by step series of examples that tell you how to get a development env running.

You need to download NetBeans here,

https://netbeans.apache.org/download/index.html

 And download SQLYOG here

 https://sqlyog.en.softonic.com/?ex=DINS-635.2

End with an example of getting some data out of the system or using it for a little demo.

## 🔧 Running the tests <a name = "tests"></a>
Before run the project we have to make sure that,

1.Right click on the pannel and select properties, then select code on the top right corner after that click generate center

2.Click on source and right click then select Run File

### Break down into end to end tests
Patient registration and admission:

a. Verify that a new patient can be registered with valid information, including name, age, contact information, and medical history.

b. Verify that a patient can be admitted to the hospital with a valid diagnosis, and that the admission is properly recorded in the system.

Appointment scheduling and management:

a. Verify that patients can schedule appointments with doctors or other medical professionals using the system.

b. Verify that the system tracks appointment and generates prescription based on patient appointments.


## 🎈 Usage <a name="usage"></a>
Receptionist-create user ,view doctor , create channel , create item 

Doctor-view their records, channel, create prescription

Pharmacist-create item, view doctor, view prescription

## 🚀 Deployment <a name = "deployment"></a>
The first step in deploying an HMS is to assess the hospital's needs. This includes identifying the hospital's size, the number of patients, staff, departments, and the types of services provided. This information will help determine the requirements for the HMS and the hardware and software needed to support it.

To deploy the application to a production environment follow these steps:

1. Ensure that you have installed the reqired softwares and the necessary environment variables, such as the database connection variables.
2. Start the application by selecting source and then select "Run file"
3. Use proper JDBC code for database connectivity.

## ⛏ Flow Chart <a name = "flowchart"></a>

![bg width:1000px](./LoginPageflowchart.png)

- [MySQL](https://www.mysql.com/) - Database
- [NetBeans](https://netbeans.com/) - software

## ✍️ Authors <a name = "authors"></a>
- [@SkillLync](https://github.com/kylelobo) - FSD

See also the list of [contributors](https://github.com/kylelobo/The-Documentation-Compendium/contributors) who participated in this project.

## 🎉 Acknowledgements <a name = "acknowledgement"></a>
- I would like to thank the following individuals for their contributions to this project:
- The team at Skill-Lync for generously providing the data used in this project
- References:

https://copyassignment.com/hospital-management-system-project-in-java/