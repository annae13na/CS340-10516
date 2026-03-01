# CS340-10516
Client/Server Development
CS 340 Portfolio Reflection

**Writing Maintainable, Readable, and Adaptable Programs:**  Writing maintainable and readable programs involves organizing code so that each part has a clear responsibility. In this project, the CRUD Python module developed in Project One helped separate the database logic from the dashboard interface. By keeping all MongoDB operations in one module, the dashboard code remained easier to read and modify. This approach also made the project more adaptable because changes to the database queries could be handled in the CRUD module without affecting the rest of the application. In the future, a similar CRUD structure could be reused in other applications that interact with databases or require organized data access.

**Problem Solving as a Computer Scientist:**  When working on this project, I approached the problem by breaking it into smaller tasks and completing them step by step. First, I ensured that the MongoDB database and CRUD Python module worked correctly. After that, I developed the dashboard using the Dash framework and connected it to the database. Finally, interactive components such as filtering options, charts, and a geolocation map were added. Compared to earlier programming assignments, this project required integrating multiple technologies together, including MongoDB, Python, Pandas, and Dash. This experience reinforced the importance of testing each component before combining them into a larger system.

**The Role of Computer Scientists:**  Computer scientists develop systems that help organizations manage and analyze data more effectively. In this project, the dashboard allows Grazioso Salvare to filter and visualize animal shelter data to identify dogs that may be suitable for search-and-rescue training. By transforming raw data into an interactive dashboard, the application makes it easier for users to interpret information and make decisions. Projects like this demonstrate how software development can support real-world organizations by improving efficiency and accessibility to important data.

**References:**
MongoDB, Inc. (2023). MongoDB documentation. https://www.mongodb.com/docs/

Plotly Technologies Inc. (2023). Dash documentation. https://dash.plotly.com/

Austin Animal Center. (2020). Austin Animal Center outcomes dataset. https://doi.org/10.26000/025.000001
