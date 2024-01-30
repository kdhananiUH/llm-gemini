# Text-to-SQL-to-Answering-your-question

+ First of all, SQL or SQlite database is connected.
+ User can ask any question in the input, and the model will generate the SQL query of that question.
+ Then, it'll talk with database and will give an answer accordingly.
+ I have used 'genimi-pro'LLM model of Google GenerativeAI in this application.

+ For example, Let's take below database:

+-----------+---------------------+---------+-------+
|   NAME    |        CLASS        | SECTION | MARKS |
+-----------+---------------------+---------+-------+
|  Kaushal  |    Probability     |    A    |   90  |
+-----------+---------------------+---------+-------+
| Sudhanshu |     Statistics      |    B    |  100  |
+-----------+---------------------+---------+-------+
|  Dhagash  |    Probability     |    A    |   86  |
+-----------+---------------------+---------+-------+
|   Tirth   | Data Visualization |    C    |   50  |
+-----------+---------------------+---------+-------+
|  Jainish  |        DEVOPS       |    A    |   35  |
+-----------+---------------------+---------+-------+


Now, we'll test our model with some questions:

![Screenshot (34)](https://github.com/kdhananiUH/Q-A-with-SQL-database-using-google-gemini/assets/111707291/3bdda54a-fa30-4370-957f-cea607b6a587)

![Screenshot (33)](https://github.com/kdhananiUH/Q-A-with-SQL-database-using-google-gemini/assets/111707291/183d979f-8f3c-4e45-8bf6-f9f0ac89e572)

+ We can see, the model is giving correct answers
