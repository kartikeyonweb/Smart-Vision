# Smart-Vision

Smart-Vision is a facial recognition app made with React on the front-end and Node on the back-end.  

The app has basic user authentication by storing hashed passwords in the Postgres database. New users can register with their email and password, which don't actually have to be real. After logging in, users can submit the URL of a .jpg file and the app will outline the first face it detects in the image with a blue box.

The backend API was implemented in a separate repository, which can be found [here](https://github.com/kartikeyonweb/Smart-Vision-Backend).


