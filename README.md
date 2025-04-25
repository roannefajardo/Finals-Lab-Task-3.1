# Finals-Lab-Task-3.1
- This project uses MySQL queries to demonstrate basic SQL techniques. It focuses on getting, summarizing, and organizing data from an existing dataset used to manage an online course system.

# Step-by-Step Process

**Step 1: Create the Database**  
- Open your MySQL tool (like MySQL Workbench or phpMyAdmin).  
- Use this command to make a new database:  
  `CREATE DATABASE online_courseDB;`  
  This will be the main place where your course data is stored.

**Step 2: Choose the Database**  
- Switch to the new database by running:  
  `USE online_courseDB;`  
  This makes sure your next steps happen inside the correct database.

**Step 3: Import the Data**  
- Download the `onlineCourse.l` file as directed.  
- Load or run the file in MySQL. It will:  
  - Create a `courses` table  
  - Add 20 course entries  
  - Include these columns:  
    - `id`: auto-incremented primary key  
    - `course_name`: text, required  
    - `category`: text, required  
    - `enrollment_limit`: number, required  
    - `students_enrolled`: number, required  

**Step 4: Perform the SQL Tasks**

- **Task 1: Under-Enrolled Courses**  
  - Show courses where enrolled students are fewer than the limit  
  - *Uses:* `SELECT` with `WHERE`

- **Task 2: Group by Category**  
  - Group courses by category and show total students in each group  
  - *Uses:* `GROUP BY`, `SUM()`

- **Task 3: Full Courses**  
  - Show courses that have reached their enrollment cap  
  - *Uses:* `WHERE` with equality

- **Task 4: Total Students**  
  - Add up the total number of enrolled students  
  - *Uses:* `SUM()`

- **Task 5: Sort Courses**  
  - List courses by increasing number of enrolled students  
  - *Uses:* `ORDER BY` (ascending)

**Final Step: Check the Results**  
- Make sure each query gives the correct output  
- Check that column names are correct and the data looks right

# Screenshots  
## Query Statements

1.) Task 1  
- ![Image](https://github.com/user-attachments/assets/196adc4d-fda2-498f-a748-90bcd5a8e93a)

2.) Task 2  
- ![Image](https://github.com/user-attachments/assets/60457f8b-f814-440b-8045-69c65c071116)

3.) Task 3  
- ![Image](https://github.com/user-attachments/assets/cd91bee7-8d8b-41ce-9bcb-1df1fef7a05e)

4.) Task 4  
- ![Image](https://github.com/user-attachments/assets/5c78e883-12d3-48c3-b34b-a11e76efe941)

5.) Task 5  
- ![Image](https://github.com/user-attachments/assets/225aacc5-85ab-41d7-9157-9231b0a7c65a)

## Output of Query Statements

1.) Task 1  
- ![Image](https://github.com/user-attachments/assets/522f4c0f-33ec-4762-848f-751357991336)

2.) Task 2  
- ![Image](https://github.com/user-attachments/assets/e3c2b57c-1798-489d-b0be-4ecb1f53b7dc)

3.) Task 3  
- ![Image](https://github.com/user-attachments/assets/bc183082-7ec5-45fa-a6df-787c3d11fc32)

4.) Task 4  
- ![Image](https://github.com/user-attachments/assets/f528e339-674a-4869-937f-3763002b1298)

5.) Task 5  
- ![Image](https://github.com/user-attachments/assets/0e5a2ce5-5823-4318-bd75-461cd5a2fb52)

