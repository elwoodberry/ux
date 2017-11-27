# Vender Management Application
**Portfolio UI/UX**  

## Outline
1. [Authentication](#authentication)
1. [App Navigation](#app-navigation)
1. [Vendors](#vendors)
## +

## Authentication
There is only one type of user. The independent contractor. If the user does not have an active account they must register an account. Once active the user will log in to their vendor management application using a username and password.  

| View Stack [01]       | "Sign In"           |
| :------------- |:-------------:|
| <dl><dt>Sign In</dt><dd>Displays the company branding with an image(png, gif or jpg) background. See possible attributes for other possible background display options.</dd><dt>Username</dt><dd>Required for sign in, the user must provide the email that was used to register an account.</dd><dt>Password</dt><dd>Required at sign in, the user must provide the password that was created upon registration.</dd><dt>Forgot Password?</dt><dd>If the user has forgotten their username or password an option to reset that information is made available.</dd></dl><h4>Attributes</h4><ul><li>Animate the background color over the course of one minute. Animate through the spectrum of color.</li></ul>   |   ![Layout](https://raw.github.com/elwoodberry/ux/master/portfolio/vendor-management/_img/wireframes/00__auth__state-01__sign-in.png)   |

## App Navigation

| Diagram 001        | Image           |
| :------------- |:-------------:|
| <dl><dt>Dashboard</dt><dd>A series of small widgets that capture the useful details the user needs to see.</dd><dt>Vendors</dt><dd>The addition, updating and deletion of vendors. Any inbound call should be managed through this workflow of interfaces.</dd><dt>Locations</dt><dd>The management of geo locations and the number of signs placed at these locations.</dd><dt>Pick Ups</dt><dd>A qualified vendor becomes a pickup. This is the management of vendors that sell the company their supplies.</dd><dt>Settings</dt><dd>The management of other features of the application that are not needed on a regular bases (expenses, reports).</dd></dl>      | ![Layout](https://raw.github.com/elwoodberry/ux/master/portfolio/vendor-management/_img/wireframes/01__app-nav__state-01__mngmnt-app.png)

## Vendors
| View Stack [01]       | "List, All"           |
| :------------- |:-------------:|
| <dl><dt>All Vendors</dt><dd>A vendor can be one that sells the company their supplies or they do not sell the company supplies. This filter shows all vendors no matter what their status is.</dd><dt>Simple</dt><dd>The term "Simple" represents a vendor that has not sold the company their supplies to the company.</dd><dt>Premium</dt><dd>The term "Premium" represents a vendor that has sold the company their supplies to the company.</dd></dl>   |   ![Layout](https://raw.github.com/elwoodberry/ux/master/portfolio/vendor-management/_img/wireframes/02__vendor__state-01__all-vendors.png)   |

As an end user I need to be able to:  
1. View A list of vendors
1. Add a new vendor.
    1. First Name
    1. Last Name
    1. Phone Number
    1. Address 1
    1. Address 2  
    1. City
    1. State
    1. Zip
    1. Group Classification
        1. What type of strips do you have?

1. Edit an existing vendor.
1. Delete a vendor

### Pickups
![Picksup Flow Chart](https://raw.github.com/elwoodberry/ux/master/portfolio/vendor-management/_img/flowcharts/fc_04_pickups.png)
