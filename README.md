# CS-340 Client Server Development Portfolio Reflection

# How do you write programs that are maintainable, readable, and adaptable?

My focus in writing programs is keeping the code clear, organized, and easy to read. I like to ensure that every logic is clearly separated into a dedicated block and that no redundancy exists. 

The same principle was applied by separating the database logic into a dedicated CRUD Python module. This allowed the dashboard code to stay clean and focused only on displaying and interacting with data, instead of handling database operations directly. 

The advantage of this is that it improves readability and maintainability. If changes need to be made, I can update the CRUD module without affecting the dashboard interface. 

This also makes the program more adaptable because the same module can be reused in other applications.
In the future, the CRUD Python module can be used for different types of projects that need to interact with a MongoDB database. Projects such as web applications, APIs, or other dashboards.

# How do you approach a problem as a computer scientist?

When approaching problems, I try to break them down into smaller parts and create a plan/road map for the project. The goal is to understand what should happen and what the result should look like while also trying to account for any changes or roadblocks that could occur. 

The Grazioso Salvare project began with analyzing what was needed from the database and dashboard to meet their requirements. I began with setting up the database as the first step, followed by building the CRUD module, and finally integrating both into the working dashboard.

This approach was different from earlier assignments because it required connecting multiple components together instead of solving a single isolated problem. This meant I had to think about how different parts interacted with the system. 

# What do computer scientists do, and why does it matter?

Computer scientists design and build systems that solve real-world problems. Their work matters because it helps organizations make better decisions, automate tasks, and improve overall productivity.

For example, in this project, the dashboard and database system help a company like Grazioso Salvare quickly access and analyze animal data. This means instead of manually searching through records, the dashboard allows users to filter and view important information instantly. This saves time and allows them to focus more on their mission.
