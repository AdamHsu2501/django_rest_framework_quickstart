# django_rest_frameworkw_quickstart


1. Install Python <https://www.python.org/>
2. Open ****cmd****
    ```
    # download repo
    > git clone https://github.com/AdamHsu2501/django_rest_frameworkw_quickstart.git
    > cd django_rest_frameworkw_quickstart
    
    # install pipenv
    > pip install pipenv
    
    # Install packages
    > pipenv install
    
    # Start virtual envirment
    > pipenv shell
    > cd tutorial
    
    # Start server
    > python manage.py runserver
    ````
3. Test
    * Test with ****Git Bash****
    ```
    $ curl -H 'Accept: application/json; indent=4' -u admin:admin http://127.0.0.1:8000/users/
    {
        "count": 2,
        "next": null,
        "previous": null,
        "results": [
            {
                "url": "http://127.0.0.1:8000/users/2/",
                "username": "AAA",
                "email": "AAA@example.com",
                "groups": [
                    "http://127.0.0.1:8000/groups/2/"
                ]
            },
            {
                "url": "http://127.0.0.1:8000/users/1/",
                "username": "admin",
                "email": "admin@example.com",
                "groups": []
            }
        ]
    }
    ```
    * Test with broswer http://127.0.0.1:8000/ & login with acount: admin, password: admin 
![](https://i.imgur.com/OJnwbxY.png)