# heroku
Team Walkthrough
>Walkthrough for a team meeting on using Heroku Postgres to store versions of an app in development:

**Introduction to Heroku Postgres (5 minutes)**

Explain what Heroku Postgres is and its benefits, such as its reliability, scalability, and ease of use.
Highlight its features, such as automatic backups, data encryption, and support for multiple programming languages.
Emphasize that Heroku Postgres is a fully managed database service, meaning that the team doesn't have to worry about infrastructure, maintenance, or security.

### 1. Creating a new Heroku Postgres database (10 minutes)
 Show the team how to create a new Heroku Postgres database in the Heroku Dashboard or using the Heroku CLI.
Explain the different database plans and their pricing, as well as the differences between hobby-dev, standard, and premium plans.
Demonstrate how to connect to the new database using a database client, such as pgAdmin or DBeaver.

### 2. Storing versions of the app in development (20 minutes)
Discuss the importance of version control for software development, and how Heroku Postgres can be used to store different versions of the app.
Demonstrate how to dump and restore a PostgreSQL database using the Heroku CLI or the pg_dump and pg_restore commands.
Show how to create a new database snapshot before making changes to the app, so that the team can revert back to a previous version if needed.
Discuss best practices for database migrations, such as using a migration framework like Knex.js or Flyway.

### 3. Collaboration and access control (10 minutes)
  Explain how multiple team members can collaborate on the same database instance, and how to grant or revoke access to the database.
  Show how to create different database roles with different permissions, such as read-only, read-write, or superuser.
  Discuss security best practices, such as using SSL/TLS encryption, strong passwords, and limiting database access to trusted IP addresses.

### 4. Conclusion and Q&A (5 minutes)
  Recap the key points of the walkthrough and emphasize the benefits of using Heroku Postgres for version control.
  Allow time for team members to ask questions or provide feedback on the walkthrough.
  Provide additional resources for learning more about Heroku Postgres, such as the Heroku Dev Center, the PostgreSQL documentation, or online courses.


