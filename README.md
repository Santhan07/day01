Resume data on JSON format
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Create your own resume data in JSON format
    </h1>
    <script src="script.js"></script>
</body>
</html> 

script.js
let myResume={
    "basics": {
      "name": "SANTHA NEELAN M",
      "email": "santhaneelan202001@gamil.com",
      "phone": 7598060535,
      "degree": "B.E",
      "location": {
        "address": "15/16 Sainath Enclave ShenoyNagar",
        "postalCode": 600030,
        "city": "Chennai",
        "state": "Tamilnadu",
        "country": "India"
      },
      "profiles": [
        {
          "website": "https://www.linkedin.com/in/rajarajan-t-685958219/",
          "github":"https://github.com/RAJARAJAN-RT"
        }
      ]
    },
    "work": [
      {
        "company": "The Photophilehub PVT",
        "position": "Business Executive",
        "startDate": "2020-11-04",
        "endDate": "2021-08-15",
        "summary": "i am the business executive handling various task and gaining lots of experience",
      },
    ],
    "education": [
      {
        "institution": "Thiagarajar College Of Engineering",
        "department": "Mechatronics",
        "studyType": "fulltime",
        "batch start year": 2015,
        "batch end year": 2019,
        "gpa": 7.5,
      }
    ],
    "skills": [
      {
        "name": "python,javascript",
        "level": "beginer",
        "project": [
          "automatic attendance maintaing system using python language"
        ]
      }
    ],
    "languages": [
      {
        "language": "Tamil,Enlish",
      }
    ],
    "interests": [
      {
        "name": "script writter,youtuber,",
      }
    ]
  }
  console.log(myResume);
