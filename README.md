# Django chat app using Django Channel Sync Consumer

This module contains the implementation of a basic chat application using Django Channels and the SyncConsumer class.

Classes:
- ChatConsumer: Handles the WebSocket connections for the chat app.

Note: This is a basic implementation and can be extended to include additional features like user authentication, message persistence, etc.


## Installation

First clone the github repository

```bash
  git clone https://github.com/nmastepankaj/chat_app_django_channel_sync_consumer.git
```

Open the repository folder in any code editor (VS code) or open any terminal.
Move to the mysite folder and install all the requirements.

```bash
  cd mysite
```

You need to create virtual environment for the project. If you don't have virtualenv the install it using the below command :-

```bash
  virtualenv venv
```

Now, activate the virtual environment using the below command.
If you're window user :-

```bash
  ./venv/Scripts/activate
```


If you're linux user :-

```bash
  source venv/bin/activate
```

install all the project requirements

```bash
  pip install -r requirement.txt
```


Now, you need to create migrations and migrate all the migrations

```bash
  python manage.py migrate
```

Run your project

```bash
  python manage.py runserver
```

Now your application is ready to use.

Open this url (http://127.0.0.1:8000/chat/home/) in two different tabs and start messaging 

## Working Screenshots
![User1 messages](https://github.com/nmastepankaj/chat_app_django_channel_sync_consumer/blob/main/user1.png?raw=true)
![User2 messages](https://github.com/nmastepankaj/chat_app_django_channel_sync_consumer/blob/main/user2.png?raw=true)



## Authors

- [@nmastepankaj](https://www.github.com/nmastepankaj)


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://nmastepankaj.netlify.app/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nmastepankaj/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/nmastepankaj)


## 🚀 About Me
I'm a full LAMP stack developer with Django as backend and React as frontend.


## Feedback

If you have any feedback, please reach out to us at my profile link provided above.


## Support

For support, email support@codingnap.com or follow me on insta or linkedin (nmastepankaj).


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Appendix

Code of this project is taken from the [Django Channel](https://github.com/CodeWithHarry) official website.
- for more information visit [CodingNap](https://www.codingnap.com).
