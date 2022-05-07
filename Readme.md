# README file has some visualizations that adminpagesapis folder dont have thats the only diff between readme and adminpagesapisfolder




https://api421.herokuapp.com/competencyevaluations/{competencyevaluationid}

### (this api is to delete competency evaluation form which is created by faculty in competency table row)


1. https://api421.herokuapp.com/admin/student/getall/{batchname} 

    (api to display all students in database in a table as shown below.)

    <img src="https://github.com/JyothiAdabala/Apidoc/blob/main/img/std1.png" width="500">

2. https://api421.herokuapp.com/admin/student/addcsvfile/{batchname}

    (api to add bulk number of students at a time to database using csv file.)

    <img src="https://github.com/JyothiAdabala/Apidoc/blob/main/img/std2.png" width="500">

3. https://api421.herokuapp.com/admin/student/add/batch/{batchname}

    (api to add single student to existing batch.)

    <img src = "https://github.com/JyothiAdabala/Apidoc/blob/main/img/createstdent.png" width="500">

4. https://api421.herokuapp.com/admin/student/update

    (api to edit details of students if necessary on long press on that partisular row)

5. https://api421.herokuapp.com/admin/student/delete/{personid}

    (api to delete student on long press on that partisular row)

    <img src= "https://github.com/JyothiAdabala/Apidoc/blob/main/img/updatestudent.png" width="500">

6. https://api421.herokuapp.com/admin/faculty/getall/{email}

    (api to display all existing faculty in database)

    Response : 

    {
    "adminname": "",
    "adminmail": "",
    "speciality": "",
    "adminsdetails": [
    {
    "personid": 4,
    "firstname": "jyothi",
    "lastname": "adabala",
    "password": "welcome123",
    "phone": "9848935444",
    "email": "jyothiadabala321@gmail.com",
    "facultyid": "vdc1",
    "speciality": "surgeon"
    }]
    }

    <img src = "https://github.com/JyothiAdabala/Apidoc/blob/main/img/getfaculty.png" width="500">

7. https://api421.herokuapp.com/admin/faculty/addcsvfile

    (api to add bulk number of faculty at a time to database using csv file.)

8. https://api421.herokuapp.com/admin/faculty/insert

    (api to add faculty to database)

    <img src= "https://github.com/JyothiAdabala/Apidoc/blob/main/img/createfaculty.png" width="500">

9. https://api421.herokuapp.com/admin/faculty/update

10. https://api421.herokuapp.com/admin/faculty/delete/{personid}

    (apis to edit details of faculty and to delete faculty on long press on particular row)

    <img src="https://github.com/JyothiAdabala/Apidoc/blob/main/img/editfaculty.png" width="500">

11. https://api421.herokuapp.com/admin/getall/{email}

    (api to display all other admins and details of present logged in admin)

    Response : 

    {
    "adminname": "babu gogineni",
    "adminmail": "babu@gmail.com",
    "adminsdetails": [
    {
    "person_id": 274,
    "first_name": "babu",
    "last_name": "gogineni",
    "password": "welcome123",
    "Phone": "9838955489",
    "Email": "babu@gmail.com"
    }]
    }

    <img src="https://github.com/JyothiAdabala/Apidoc/blob/main/img/getadmin.png" width="500">

12. https://api421.herokuapp.com/admin/insert

    (api to insert new admin to database)

    <img src="https://github.com/JyothiAdabala/Apidoc/blob/main/img/insertadmin.png" width="500">

13. https://api421.herokuapp.com/admin/update

14. https://api421.herokuapp.com/delete/{personid}

    (apis to edit details of admins and to delete admin on long press on particular row)

    <img src="https://github.com/JyothiAdabala/Apidoc/blob/main/img/editadmin.png" width="500">

15. https://api421.herokuapp.com/admin/addcsvfile

    (api to add bulk number of admins at a time to database using csv file.)

16. https://api421.herokuapp.com/admin/speciality/add/{specialityname}

    (api to create a speciality)
    
17. https://api421.herokuapp.com/admin/speciality/update/{specialityname}/{specialityid}

    (api to update speciality)
    
18. https://api421.herokuapp.com/admin/student/getbacthnames

    (api to display all batches)
    
    Response : 
    
    [
        {
        "batch_name": "2018",
        "batch_id": 18
        },
        {
        "batch_name": "2019",
        "batch_id": 19
        }
    ]
    
19. https://api421.herokuapp.com/fdashboard/competencydetails/{speciality}

    (api to get all competencies names)

    Response : 

    {
    "details": [
    {
    "competencyname": "competency1",
    "competencyid": 4
    },
    {
    "competencyname": "competency2",
    "competencyid": 14
    }]
    }

20. https://api421.herokuapp.com/studentdashboard/specialities

    (api to get all specialities names)

    Response : 

    {
    "details": [
    {
    "specialityName": "surgeon",
    "SpecialityId ": 14
    },
    {
    "specialityName": "upperteeth",
    "SpecialityId ": 24
    }]
    }



