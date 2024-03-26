Admin name : admin

Admin password : 123
 
 
 # MyInterviewPanel
                          Interview panel
    
                      Type of application : B 2 C

                      Target audiance : Admin

                      Development TIme : 7 Days

                      Tech Stack : Java  

Features :

● Admin user Login/logout(Session mantanance)

● Company Setup with basic details.

● Add Interviewer details.

● Add candidates details.

● Conduct an interview.

● Select candidates.

● Reject candidates.

Model classes :

  Company :
1. name : String
2. id : String
3. phoneNo : long
4. emailId : String
5. address : String


Credentials :
1. adminId : String
2. password : String

   
Admin:

1. name : String
2. userId : String
3. emailId : String
4. address : String

   
Candidates :

1. candidatesId : int
2. candidateName : String
3. phoneNo : String
4. emailId : String
5. address : String
6. result : boolean
