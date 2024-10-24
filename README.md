# CS_360_Mobile_Architect_And_Programming
This is a repository of my project files and final submission for my final portfolio for the CS-360 Class at SNHU.

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The app I developed for my CS-360 Mobile Architecture and Programming course was designed with the primary goal of delivering an intuitive platform for users to organize and track their upcoming events. This app focused on simplicity, targeting users like busy professionals, students, and event planners, helping them stay organized without the overhead of unnecessary features. It needed to support user authentication, event management through CRUD functionality (Create, Read, Update, Delete), and timely event notifications. As laid out in my initial proposal in Project One, the app centers around ensuring user accessibility, focusing on the needs of users to manage their schedules efficiently​.

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

To create a user-centered design, the app included key screens such as the login screen, a grid-based event management screen, and a notification permissions screen. The login screen allowed users to either create a new account or log in with an existing one. I ensured that the interface remained simple by using standard UI elements like text fields for usernames and passwords, with clear feedback for errors or invalid input. The grid-based event management screen presented event details in a clean, card-style format, allowing users to quickly view, add, edit, or delete events​. The SMS permissions screen allowed users to opt-in for notifications, further enhancing the user experience by keeping them informed without being obtrusive. By adhering to Android’s Material Design principles, I ensured a consistent, intuitive visual hierarchy that made the app easy to use while maintaining a modern, clean design​.

How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

My approach to coding followed a modular, user-focused strategy. I began by building out the login system, ensuring secure authentication by using SQLite to store user credentials. I then developed the CRUD functionalities for managing event data, with SQLite serving as the persistent database solution. I made sure to implement key best practices in code, such as using clear, consistent naming conventions and including detailed in-line comments to maintain readability and scalability​. I also relied on object-oriented programming to break the project into manageable components. For future applications, this modular approach will ensure that I can maintain and update individual sections without affecting the whole app. This strategy, tested iteratively using Android’s built-in emulator, allowed me to identify and address bugs early in the development cycle.

How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

Testing was essential to ensuring that the app functioned as intended. I tested the app thoroughly using both unit and manual tests in Android Studio’s emulator. For example, I tested the login functionality by inputting valid and invalid credentials and ensuring appropriate feedback. Additionally, I tested database interactions such as adding, updating, and deleting events, ensuring that all CRUD operations worked as expected. This rigorous testing process allowed me to identify bugs early, such as the failure of the notification system when permissions were not granted, and to resolve those issues. The result was a robust, error-free app.

Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

One of the biggest challenges I faced was integrating the SMS notifications feature. Handling dynamic permissions in Android while ensuring that the app continued to function without the SMS feature required careful planning. To overcome this, I implemented fallback mechanisms that allowed the app to continue operating seamlessly when permissions were denied. This required innovation and flexibility, as it ensured users were not limited by the app’s inability to send SMS notifications​.

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

One component where I successfully demonstrated my knowledge was the implementation of secure login functionality and database management using SQLite. I developed this feature with a strong focus on security, ensuring that user credentials were stored securely and that only authenticated users could access the event management system. This not only showcased my understanding of secure coding practices but also my ability to deliver a user-friendly solution that met project specifications.

Through careful planning and attention to user needs, I was able to develop an app that was both functional and easy to use, meeting the project requirements while also addressing the real-world needs of my target users.
