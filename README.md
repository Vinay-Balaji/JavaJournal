Welcome to the Java Journal! We are a powerful task management application designed to help you stay organized and productive throughout your busy week. With an intuitive user interface and robust features, it's the perfect tool for managing your tasks and events effectively. Here are the main features of our application:

Week View: View an entire week visualization of all events and tasks in the Java Journal
Task Creation and Editing: Easily create and edit tasks with a simple and user-friendly interface.
Commitment Warnings: Allow clients to set the maximum number of events and tasks each day
Persistence: Let the user click Save to persist the data in a Week to a file
Task Queue: A queue sidebar which contains all tasks for the week and whether they are completed or not
Categories: This feature allows each event or task to be categorized
Quotes & Notes: A designated section where the user can type and save a quote or note on their Week.
Mini Viewer: A view option which can open any single Event or Task in a new mini window displaying all details
Takesie-backsies: A delete button in which a user can delete tasks and events
Auto #tags: Prepending a category name with a # when titling a Task/Event automatically assign an associated category
Mind Changes: Edit button in which users can edit any aspect of any existing Event or Task from the Week view.
Weekly Starters(Steps for creating template: 1. Create new file 2. Set Max Tasks & Events 3. Creates Event or Task with desired category 4.Delete all events and tasks till empty 5. Save Template with desired name.) : Get template from .bujo file and override file at will.


Solid Principles:
Single Responsibility: We utilized Single Responsibility Principle in our program as we delegated numerous tasks to multiple controllers. This is evident as we have 11 separate controllers that each handle a single responsibility with the entire Java Journal application. In addition, each class and object in our model also contains a single responsibility as associated with the name of the class.

Open-Closed Principle: We utilized Open-Closed Principle in our program as our program is designed to be open for extension but closed for modification. We can add new features and functionality by implementing the current existing interfaces without modifying any code. For instance, if we wanted to implement a new type of item such as "homework" we can simply extend the current item interface in place. As a result, our program follows the open-closed principle

Interface Segregation Principle: The Item interface in the model of the application is necessary in the implementation of both Task and Event Objects. They both use all the methods in the interface. There are no useless methods between them. It effectively encapsulates the datatype and its corresponding functionalities

Liskov Substitution Principle: After further review, we found that our program does not significantly follow the Liskov Substitution Principle. This is due to the fact that we do not present any derived classes in our program due to the nature of the program and the way that we implemented each feature. However, if we were to extend this project in the future we will definitely consider creating derived class to reduce code reuse and allow objects from their derived classes to be substituted for objects of their base classes.

Dependency Inversion Principle: This principle is seen through the design of the main method which calls the abstracted interfaces of the corresponding view and controller. This makes it less coupled and easier to swap out corresponding elements in the application.

How we can extend our program: To further enhance the functionality of this program, we can consider adding a collaboration feature. This feature would allow users to share tasks and collaborate with other team members. In addition, we can extend this feature to allow users to assign tasks to specific individuals in a project or even track the progress of a specific task. Furthermore, we can support file attachments to each event or task. By adding file attachments, each event or task will have more detail and information associated with it than ever before. Lastly, we can expand the week view into a month view that can load all the tasks in a month like a Google calendar. All in all, with these changes we can enhance the functionality of the program and empower users to achieve their goals efficiently.
