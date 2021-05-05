# User Management Screen


#### Content List

- The Goal Of The Project
- Requirements and Details
- Sample Project

## The Goal Of The Project

- To design a visually simple and understandable interface developed to enable users who do not have any programming knowledge to use computer programs or machines containing computer programs and commands.
- Information on examining the control questions of the system
- Design of question-answer dialogue scenarios
- Performing interface access controls
- Defining the necessary authorizations
- Tracking of activity status

## Requirements and Details
- There will be a new record button
- New registration panel will be shown to the authorized user
- Questions to be asked in new registration
1) UserName:
2) DisplayName:
3) Phone:
4) Email:
5) User Roles(guest,admin,superadmin)
6) Enabled
- After the necessary information is entered, the order can be changed as desired.
- When the Save button is clicked, the necessary documents will be sent to the database and the information of the required persons will be shown on the same screen
- Records will be table
- There will be a box next to each entrance



## Sample Project
- Made with Bootstrap 4.0.0 , To run it, please install it
[![image](https://r.resimlink.com/4APoO.jpg)](https://resimlink.com/4APoO)
```html

<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

    <title>Proje</title>
<style>
        .yazinewuser {
          font-style: bold;
            }
            .backgroundheader{
             background-color: #f2f2f2;
            }
            .marginheader
            {
              margin-top:10px;
              margin-bottom:10px;

            }
             .marginheader2
            {
              margin-top:15px;
              margin-bottom:15px;

            }

             .marginheader3
            {
              margin-top:10px;
              margin-bottom:10px;
            }
            .marginbodytop
            {
              margin-top:10px;
              
            }
             .lifloatleftıd
             {
               margin-left:10px;
             }
            .lifloatleftother
            {
              margin-left:50px;
            }
            .bodyleftbackground
            {
              background-color:#4bcbe9;
              color:white;
            }
            .bgtable
            {
              background-color:#4bcbe9;
            }

     </style>

  </head>
  <body>
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
  
<div class="container">


<div class="row backgroundheader">
    <div class="col-lg-2 col-md-2 col-sm-2">
      
      <button type="button" class="btn btn-primary yazinewuser marginheader">+New User</button>
    </div>
    
    
   <div class="form-check marginheader2">
  <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
  <label class="form-check-label" for="defaultCheck1">
    Hide Disabled User
  </label>
</div>
     
      <div class="col-lg-6 col-md-6 col-sm-6">

      </div>

  <div class="col-lg-2 col-md-2 col-sm-2 marginheader3">
     <button type="button" class="btn btn-info">Save User</button>
    </div>


  </div>

<div class="row">
  
  
  <div class="col-lg-6 col-md-6 col-sm-6 marginbodytop ">
 <table class="table table-striped ">
  <thead class="bgtable">
    <tr>
      <th scope="col">Id</th>
      <th scope="col">UserName</th>
      <th scope="col">Email</th>
      <th scope="col">Enabled</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>AdminUser</td>
      <td>Admin@piworks.com</td>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>TestUser</td>
      <td>testuser@piworks.com</td>
      <td>true</td>
    </tr>
    
  </tbody>
</table>

</div>







<div class="col-lg-6 col-md-6 col-sm-6 marginbodytop">
<nav aria-label="breadcrumb">
  <ol class="breadcrumb">
    <li class="breadcrumb-item active" aria-current="page">New User</li>
  </ol>
</nav>

<form>
  <div class="form-group row">
    <label for="inputEmail3" class="col-sm-2 col-form-label">UserName:</label>
    <div class="col-sm-10">
      <input type="email" class="form-control" id="inputEmail3" placeholder="">
    </div>
  </div>
  <div class="form-group row">
    <label for="inputEmail3" class="col-sm-2 col-form-label">DisplayName:</label>
    <div class="col-sm-10">
      <input type="email" class="form-control" id="inputEmail3" placeholder="">
    </div>
  </div>
   <div class="form-group row">
    <label for="inputEmail3" class="col-sm-2 col-form-label">Phone:</label>
    <div class="col-sm-10">
      <input type="email" class="form-control" id="inputEmail3" placeholder="">
    </div>
  </div>

   <div class="form-group row">
    <label for="inputEmail3" class="col-sm-2 col-form-label">Email:</label>
    <div class="col-sm-10">
      <input type="email" class="form-control" id="inputEmail3" placeholder="">
    </div>
  </div>



 <div class="input-group mb-3">
  <div class="input-group-prepend">
    <label class="input-group-text" for="inputGroupSelect01">User Roles</label>
  </div>
  <select class="custom-select" id="inputGroupSelect01">
    <option selected>Select User Roles...</option>
    <option value="1">Guest</option>
    <option value="2">Admin</option>
    <option value="3">SuperAdmin</option>
  </select>
</div>






  <div class="form-group row">
    <div class="col-sm-2">Enabled</div>
    <div class="col-sm-10">
      <div class="form-check">
        <input class="form-check-input" type="checkbox" id="gridCheck1">
        <label class="form-check-label" for="gridCheck1">
          
        </label>
      </div>
    </div>
  </div>

</form>
</div>



</div>









</div>
 </body>
</html>

