# Intro-Project
Introduction and project explain 


1) Intruduce Yourself : 

Good Morning sir , my name is Rushikesh Suryawanshi. I hold a B.tech degree in Civil Engineering from MGM's JNEC college, where I achieved a CGPA of 7.88. I am a 2021 passout and have recently completed the PG-DAC course from CDAC. My passion for technology and problem-solving led me to pursue a career in IT. I am particularly interested in utilizing my analytical and technical skills to design and develop software applications. I am well-versed in programming languages such as Java, Mysql, React, Javascript and ShellScripting and have experience in developing web applications using frameworks like SpringBoot , using my understanding of the technologies that i have learned i have also contributed to group project. Additionally, I have a strong foundation in data structures and algorithms, which allows me to create efficient and scalable solutions. I am excited to bring my skills and knowledge to the table and contribute to the success of this organization.


2) Project Explanation :

* RationEase - Modernizing Ration Distribution and Management :
 RationEase not only revolutionizes ration distribution in small Indian towns through its user-friendly online platform for registration, slot booking, and timely notifications, but it also empowers administrators with cutting-edge tools to seamlessly manage and optimize the entire process.	

The RationEase project development and implementation of dynamic web application aimed at simplifying the process of slot booking and communication between customer and vendors

For developing this application we used three tier application architecture - In Backend we used spring boot application In frontend we used React for the database we used Mysql 

2.1) what part you done :

I am delighted to talk about my project, which was an RATION EASE . It was an exciting project that we completed within a month, where I played a crucial role in its success. My primary contribution to the project was DEVLOPING APIs the application,  Additionally,I was also involved in developing authentication and authorization mechanisms using JWT. I was responsible for conducting Unit testing of various modules, such as REST API through Postman, which helped identify and eliminate any potential bugs before the release. My expertise in backend development allowed me to effectively integrate the frontend with the backend, ensuring the seamless functioning of the application. Through my dedicated efforts and hard work, we were able to complete the project on time with high quality.

3) why switched from civil to IT :

I changed my stream from Civil Engineering to IT because I found myself drawn to technology during my studies. While pursuing my degree in Civil Engineering, I realized that I was more interested in exploring the potential of programming languages and development tools. I began to explore these areas in my free time, and I found myself enjoying the process of problem-solving through technology.

As I delved deeper into the world of technology, I discovered that the IT industry was rapidly growing and evolving, offering tremendous opportunities for career growth and development. I was impressed by the wide range of roles available in the IT industry and the potential to work on innovative projects that could have a significant impact on people's lives.

Furthermore, I believed that my skills from my previous degree, such as analytical thinking, project management, and attention to detail, could be transferable to the IT industry. I was confident that I could leverage my existing knowledge and combine it with my newfound passion for technology to build a fulfilling and rewarding career.

Overall, my decision to switch from Civil Engineering to IT was driven by my passion for technology, the potential for career growth and development, and the belief that I could combine my existing skills with new knowledge to excel in the field.

4) what is JWT and OAUTH ?

JWT (JSON Web Token) and OAuth are both authentication and authorization protocols used in modern web applications.

JWT is a JSON-based open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. JWTs are commonly used for authentication purposes and can contain user ID, user roles, and other relevant information. JWTs consist of three parts: header, payload, and signature, and are typically used to authorize access to resources or services.

OAuth, on the other hand, is an open standard that allows third-party applications to access user resources on a server without exposing the user's credentials. OAuth is commonly used by web applications to allow users to sign in using their Google, Facebook, or Twitter accounts instead of creating a new account. OAuth provides a way for users to grant access to their resources to a third-party application without sharing their passwords or other sensitive information. OAuth works by exchanging a user's access token, which is obtained by the third-party application using the user's authentication provider (such as Google or Facebook), for a set of temporary credentials that can be used to access the user's resources on the server.

Overall, both JWT and OAuth are important components of modern web applications that help ensure security and privacy while allowing for seamless integration with third-party services.

5) what database schema you used in project ?

SNOWFLAKE SCHEMA - (automatically manages the dimension table : Normalization of Dimension Tables)

The snowflake schema is a variation of the star schema used in data warehousing to improve query performance and reduce storage requirements. In a snowflake schema, dimension tables are normalized, meaning that they are broken up into multiple related tables instead of being represented as a single table.

This normalization of dimension tables can result in a more complex schema design, but it offers benefits such as reduced data redundancy, improved query performance, and easier maintenance.

In a snowflake schema, the fact table contains foreign keys that link to a set of related dimension tables. Each dimension table is further normalized, meaning that it is broken down into multiple related tables that contain more specific information. For example, a product dimension table might be broken down into sub-tables that contain information about product categories, brands, and suppliers.

The name "snowflake schema" comes from the fact that the schema resembles a snowflake when viewed in a diagram, with the fact table at the center and dimension tables branching out like snowflakes.

6) what are fact table and dimension tables ?

Let's say we have a database for an e-commerce website, and we want to analyze sales data.

The fact table in this scenario might be a sales table, which contains the quantitative data that we want to analyze, such as sales revenue, quantity sold, and profit margin. Each row in the sales table represents a specific sale transaction, and it includes foreign keys that link to related dimension tables.

The dimension tables might include a product table, which contains information about the products that were sold, such as the product name, category, and price. Another dimension table might be a time table, which contains information about the date and time of each sale. Finally, we might have a customer table, which contains information about the customers who made the purchases.

By joining the sales table with the product, time, and customer tables, we can perform complex queries to analyze the data based on different dimensions and attributes. For example, we could analyze sales revenue by product category, or we could analyze the number of sales by customer age group.

In this way, the fact table and dimension tables work together to provide a comprehensive picture of the sales data and enable us to perform powerful data analysis.

for every dimension table there is one foreing key is present in fact table and every dimension table have one primary key of fact table


7) what is containerization ?
 # 8) Spring Security :
  - SS is a application security framework provide appliction lavel security
  - like login logout functionality
  - allow / block access to URL to logged in user and also certain roels (admin ,un resister user)

* why ss
  - Handles commen vulnerability - session fixation ,clickjacking,click site request forgery
  - widely adopted
 * what ss do
   -user name ,password authentication
   - application level authorization
   - intra application autherization like OAuth
   - Microservice security (using token JWT)
   - method level security

  # core concept in spring security 
   a) Authentication and Authorization 
    - Authentication :
      ask two question -1 who r u , 2 prove 
      * * thise authentication known as knowledge based  authentication -(stored user ID ,PASS)
      -Advantage- easy way to implement 
      -DisAdvantage - if some one has a pass then he can access

    b) Possession based authenrication :



















