# PetroHub - Your shopping site for gas stations
![Screenshot (13)](https://github.com/nathankuts/PetroHub/assets/158057320/7756b868-d458-4620-8231-10846dfc488e)

## Introduction

### The Project
Any cat parent knows that although you love your cat, taking care of them may not be the easiest task on earth. You sometimes worry whether you are giving them enough food, attention or the best care and love. That's were KittyKnowhow comes in.

KittyKnowhow is a mobile application where users interact with other cat parents and share experiences and knowledge about living with cats. They get to create posts asking questions or even sharing valuable experiences that other users can comment on. The application provides the platform for learning from other people's experiences.

Other features include: viewing posts without creating an account or signing in.

### The Context
This project is a Portfolio Project that marks the conclusion the Foundations Year at ALX. This was a solo project.

### Developer
Nathan Makhombe [@nathanielkhombe](https://twitter.com/nathanielkhombe)    [Nathan-Makhombe](https://www.linkedin.com/in/nathan-makhombe-4663582a7/)

### Blog Post
After the development, I wrote a blog post to show the jorney to realising PetroHub

[KittyKnowhow: The journey](https://medium.com/@dillysannan/kittyknowhow-the-journey-b7cddcbb8453)

### User Interface
A little glimpse of the user interface

![Screenshot (9)](https://github.com/nathankuts/PetroHub/assets/158057320/6ca1f6a6-9269-4c8d-aefa-060a8f954cbe)



## Architecture
### Overview
This web app was built using Front end technologies(HTML5, CSS3, and Javascript). A lot of work was put into developing a front-end that was simple but easy to use. 

![Screenshot (15)](https://github.com/nathankuts/PetroHub/assets/158057320/8aedc83b-efd3-435e-97c4-5e7d3abb1a95)

### Flutter and Dart
For this project, I decided to use a framework that was not taught in the foundations year to learn more about the framework. 

All the pages in the app were built using the Flutter stateful widget. Some custom components and widgets were built using both stateful and stateless widgets.

For routing within the application the MaterialPageRoute was used.

### Supabase
I decided to go with Supabase form my backend/database as it provides all the functionality I need to develop this project such as authentication, database storage and cloud storage. The relational database structure made calling any required information simple.

Images are kept in the Supabase buckets.

As the app connects people and their cats and allows post creation and commenting, authentication is a necessity. Suapbase provides a straightforward and easy-to-implement solution. Users simply sign up with an existing email address and a password of their choice. Supabse Authentication does the heavy lifting to sign in users.

## Acknowledgement
-ALX staff - For the help, advice and resources they provided us with during this project and during all our curriculum.

-Cohort 14 and all ALX students - For your friendship, invaluable support, and insight not only for this project, but over the last year.

-KitKat - For being his cute and cuddly self and bringing me joy with his furry self

-Sven - For encouraging me when I was struggling to fix bugs

-YOU - For reading this documentation and testing out KittyKnowhow. I hope you enjoy it!
