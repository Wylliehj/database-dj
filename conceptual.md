### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?

PostgreSQL is an open source RDMS that we can use to store data in rows and columns like a table that is built off the SQL language.

- What is the difference between SQL and PostgreSQL?

The difference is that PostgreSQL offers support for a wider variety of languages than vanilla SQL, also PostgreSQL is an object-relational database that offers more ways to store complex data types making it a bit more challenging but much more adaptive to a developers needs

- In `psql`, how do you connect to a database?

\c 'database_name'

- What is the difference between `HAVING` and `WHERE`?

`WHERE` is essentially a 'filter_by' where we can select from a table based on a certain condition, using this `WHERE` query. `HAVING` is used with the `GROUP BY` query where we group by a certain parameter and can choose to include a conditional, using this `HAVING` query.

- What is the difference between an `INNER` and `OUTER` join?

An `INNER` join returns only the rows that match the condition in both table, the overlap. An `OUTER` join includes the 'overlap' plus additional information from another table based on the kind of outer join, left, right, full.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?

`LEFT` returns everything from the left table, plus the matching rows from the right, and `RIGHT` is the same except all the rows from the right table instead of the left.

- What is an ORM? What do they do?

Object-Relational Maapper, essentially is a translation service so that we can write queries in a prefered language that will then be translated into the language used by our database

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?

Server side requests are more secure, if we need to include things like an authentication token(key) to access a certain API for development, storing that key in a client side file would not be secure.

- What is CSRF? What is the purpose of the CSRF token?

Cross-Site Request Forgery, the purpose of these tokens is to ensure that your server doesnt accept any requests from a submitted form that did not come from your website. This protects users and prevents people attempting to act maliciously

- What is the purpose of `form.hidden_tag()`?

In our template this makes it so that the HTML includes the data even if they have a 'hidden' tag, such as our CSRF token. Without this the point of the CSRF is mute. These do not show as they have a 'hidden' tag and we include a line that shows everything but fields including a 'hidden' tag to properly display the form.
