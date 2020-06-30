E-Commerce Mobile WebApp

#Technology Stack
Backend:Nodejs+Express
Reactjs as frontend framework
Mongodb as a database in memory
Contextjs for passing on the props directly into the needy components

#Features Of the Application:
Front page of the web application consists of the two routes i.e,the Signin and the Register 
After Signing in or Registering the user will be able to route between the 3 components namely
1.contact
2.products
3.mycart

(you may signin by using the id demo@gmail.com password:demo)

1.contact contains the contact no. of the owner of the web application.
2.Products contain the mobile products available for the users to purchase.
The products contains the 2 buttons one is for adding the mobile selected in the cart 
The second one is for buying the mobile (which is currently inactive .)
On Clicking the selected mobile it will provide with the details of the mobile .This component contains 2 buttons one is for adding the mobile in the cart and the other one is back to the products.
3.In the third component we will see the selected mobiles on our cart as the cartitems .again it contains the 3 buttons
one is for incrementing the mobile number and the other one is for deducting the number.
The third button is a cross button which cancels the product by setting the count value of the item as 0 and removing the item from the mycart component.
After loging out the data will be saved in the database.
After Signing in again we will see the cartitems as it is when selected during the last login/register session.

#Installation Guide:

Enter the shopping folder and run the command 'npm start' in your bash for running the frontend server
Enter the shopping_api folder and run the command 'npm start ' for running the backend server.
if unable to login or register then see for the url it should be likewise 'url/' and not like 'url/details'
 
 If even then unable to signin or login then feel free to contact
 jatajay004@gmail.com
