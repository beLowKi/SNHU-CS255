# SNHU-CS-255
Course repository for CS 255 System Analysis and Design

# Response Questions
- Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?

The client of DriverPass wanted to create an application that would support people in the United States that didn't have their driver's license. It would allow them to take practice tests, an online course, and schedule on-the-road lessons with a licensed instructor. This is done through a package-based system where Customers can purchase packages with different perks; more expensive ones including the online course and more on-the-road hours. I was asked to design a system that could support a database of users, instructors, and course-related information and be notified when the DMV (Driver and Vehicle Services) updates their policies. It also needed to work with web-based clients for all the most popular operating systems: Windows, MacOS, and Linux.
  
- What did you do particularly well?

I think I did a good job designing the database(s) structure. In my class diagram, I defined the objects/tables that would be in the SQL database--using primary and foreign keys to show the relationships between objects. While the project's description, mainly the mock interview with the owner of DriverPass, didn't suggest that it needed to be scaleable, I chose to make it so. It seemed the most practical thing to do, and it didn't change the overall design much. I also think this would make it easier to implement the database since all the columns and relationships of the would-be tables are already defined.

- If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I'd want to streamline the business requirements document I made for Project One because, in my opinion, it's a little verbose. I tried to use nested bullet points to organize it better, but it still feels a little too busy for my liking in a few areas. The "System Components and Design" section could be rewritten now that I have a clearer idea of what the system will look like. I think the "Objectives and Goals" portion focused too much on the system's technical requirements when it should've been a brief summary of its functional and non-functional requirements. It also would've made a better transition into the next sections: functional and non-functional requirements. 

- How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?

I had users' needs in mind when determining the functional requirements of the user interface. Users need to be able to sign up, log in, make reservations, see instructor notes, access course information, and take practice tests. Thus, the UI needs to support each of those use cases. It's important to consider the user's needs when designing because, generally, they're who the system is for; it's intended to serve them. Therefore, the user's needs are the system's needs.

- How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?

I usually design software from the ground up starting at the base functional requirements and ending with non-functional ones. As long as you keep your designs modular and scaleable, the order in which you design different parts of a software shouldn't effect its functionality, but I think starting with the highest priority requirements can help contextualize what later designs need to achieve. In the future, I'd want to use the same incremental design strategies I used in this course. It aligns with Scrum-Agile, which I learned about in a different course, and I think that design philosophy synergizes with programming especially well. 
