# A social networking site made using React,Django and bootstrap

## Instructions to run
1. open terminal in root directory
2. run command cd website
3. run command npm run build
4. run command cd ..
5. run command python manage.py runserver

## API

## Register user
localhost/api/account/register
accepts POST request with json data
```
{
   "username" : "myusername",
   "password" : "mypassword",
   "re_password" : "mypassword",
   "email" : "myemail",
   "first_name" : "myfirst",
   "last_name" : "mylast"
} 
```

### Login user
localhost/api/account/login
accepts POST request with json data
```
{
   "username" : "myusername",
   "password" : "mypassword",
}
```

## Logout user
localhost/api/account/logout
accepts POST request with no json data

##Delete user
localhost/api/account/delete
accepts DELETE request with no jsond data


localhost/api/account/logout

