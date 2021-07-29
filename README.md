# CSS-Form-design
 <title>My css Form</title>
    <style>
       input[type=text]{
           width: 100%;
           padding: 10px 20px;
           margin: 20px 0;
           font-size: 1rem;
           box-sizing: border-box;
           border: 3px solid salmon;
           border-radius: 5px;
           
       }
     #search{
           background-image: url("https://freeicons.io/uploads/iconsets/convimages/business-and-online-icons.png");
           width: 150px;
           background-repeat: no-repeat;
           background-position: 8px 12px;
           font-size: 1rem;
           padding: 15px 40px;
           transition: width 0.3s ease-in-out;

        }
        #search:focus{
            background: olive;
            width: 100%;
        }
    </style>
<body>
    <form action="">
<input type="text" name="search" id="search" placeholder="search">
 <p></p>
  <label for="fname">First Name</label>
  <input type="text" name="fname" id="fname">

  <label for="lname">last Name</label>
  <input type="text" name="lname" id="lname">
    </form>
           
</body>
