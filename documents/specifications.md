<h1>Specifications of requirements</h1>
<h2>Purpose of the application</h2>
The purpose of this application is for users(family members) to have an easy access to a centralized website that contains all of the familys recipes.
In there after creating an account for themself they will be able to easily add, edit, delete and comment into recipes that other family members have added there. 
This will be working as a solution so that each time they wish to share recipes in between each others they dont need to be calling for it over and over again but can just simply login to the website and go checkout the detials themself.
<h2>Users</h2>
Users have the ability to add, edit, and delete their own posts. They can also comment on other posts and maybe in later versions be able to add some recipes in their favorites.

<h2>Programs functionality</h2>
<h3>Before login</h3>

- User can choose between login or creating a new account
  - By choosing the create a new account they will be forwarded to a section for this purpose
    - Account creation section will require the user to provide username, email, password and re-entering password.
    - This information will be stored in the database so that there can be multiple users for the website.
  
   - Login screen
      - There will be a username and password boxes and a login button that should be pressed after typing in the information that were used when registering the account.
      - If the username or password does not match with the information in the database there will be a notification for this and the user will be asked to double check their information.
      - If the login details match with the databse information the user will be forwarder to mainscreen of the application.

<h3>After login</h3>

  - In the main site there will be the latest added recipes showing in a slide for a quick access to them. Also there is some major categories the user can click on to go browse recipes that they contain.
    - In the top navigation menu the user can select a search based on some given criterias and a button for adding new recipes and logging out.
     ---
     - <h3>Add new recipe</h3>
       
       When user chooces the add new recipe function at the navigation menu they will be forwarded to a new page which contains the following functionality.
        
        - Explanation field where the user can explain what food is this.
        - Easy to add function for adding ingridients where the user has to choose the ammount and type out the name of the ingrient.
        - They have to upload atleast 1 photo that will act as the main photo for the food. If they wish they can add more photos later.
        - Step adder where they will add step by step explanation for making the food.
        - By pressing complete the new recipe will be added in the website and all the details of the recipe are going to be stored in the database.
       ---
       
      - <h3>Browse</h3>
      
        When user chooses the browse option they can see all the added recipes in the alphabetical order if they wish to. In here it is also possible to do more indept search that can remove some of the shown recipes.
      
      ---
<h3>Logout</h3> 

By clicking the logout icon the user will be logged out of the website and directed back on the main page.

<h2>Ideas for further developement</h2>

After creating the working basic version of the application it may be expanded by adding some of the following functionalities.
- Favorites section.
- Possible to like other recipes.
- More toned up UI.
- Email verification / a quiz to pass so that users that are not meant to access the site cant register.
- Password recovery option.
