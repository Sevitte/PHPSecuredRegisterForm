# Secured registration form connected to database.
Easiest way to run:

`$ php artisan serve`

- [ ] setup project
- [ ] configured database settings

## Frontend

Simple validation for fields checking:
- [ ] nickname pattern
- [ ] email pattern
- [ ] password pattern and complexity

Using:
- [jQuery](https://jquery.com/)
- [HTML](https://devdocs.io/html/)
- [CSS](https://devdocs.io/css/)


## Backend

Responsible for the security of the application:
- [ ] reCAPTCHA - to prevent spam and abuse
- [ ] sessionTimeout (10 min) - to prevent brute force attacks
- [ ] validation for all fields on the server side
- [ ] authentication and authorization
- [ ] spicy password hash
- [ ] small delay after each request - to prevent DDOS
- [ ] csrf token - to prevent CSRF
- [ ] htmlspecialchars function - to prevent XSS 
- [ ] prepared statements - to prevent SQL injection 

Using:
- PHP Framework [Laravel](https://laravel.com/)
- [MYSQL](https://www.mysql.com/)

## Tests
[Cypress](https://www.cypress.io/)

## Code editor

[Visual Studio Code](https://code.visualstudio.com/)
