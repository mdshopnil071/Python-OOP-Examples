Python OOP tasks

<table border="1" cellspacing="0" cellpadding="8">
  <tr>
    <th>Task</th>
    <th>Details</th>
  </tr>

  <tr>
    <td><b>1. Create the StudentDatabase class</b></td>
    <td>
      Define a class named <code>StudentDatabase</code> with one class attribute named <code>student_list</code>.<br>
      Initially, it should be an empty list. Create a class method <code>add_student()</code> to insert an object of the <code>Student</code> class into <code>student_list</code>.
    </td>
  </tr>

  <tr>
    <td><b>2. Create the Student class</b></td>
    <td>
      Define a class <code>Student</code> with the following instance attributes:<br>
      - student_id: Unique identifier for the student.<br>
      - name: Full name of the student.<br>
      - department: The department of the student.<br>
      - is_enrolled: A boolean indicating if the student is currently enrolled.
    </td>
  </tr>

  <tr>
    <td><b>3. Initialize Student Object</b></td>
    <td>
      In the constructor of the <code>Student</code> class, initialize the attributes. Insert the <code>Student</code> object into <code>student_list</code> using the method <code>add_student()</code>. This part will be done manually, i.e., no need for a menu option.
    </td>
  </tr>

  <tr>
    <td><b>4. Implement enroll_student() method</b></td>
    <td>
      Add a method <code>enroll_student()</code> in the <code>Student</code> class that checks if the student is not already enrolled. If not, change <code>is_enrolled</code> to <code>True</code>.
    </td>
  </tr>

  <tr>
    <td><b>5. Implement drop_student() method</b></td>
    <td>
      Add a method <code>drop_student()</code> in the <code>Student</code> class that changes <code>is_enrolled</code> to <code>False</code> to indicate that the student has dropped out.
    </td>
  </tr>

  <tr>
    <td><b>6. Implement view_student_info() method</b></td>
    <td>
      Add a method <code>view_student_info()</code> in the <code>Student</code> class to display the details of the student including <code>student_id</code>, <code>name</code>, <code>department</code>, and enrollment status.
    </td>
  </tr>

  <tr>
    <td><b>7. Menu System</b></td>
    <td>
      Create a menu-driven system with the following options:<br>
      1. View All Students<br>
      2. Enroll Student<br>
      3. Drop Student<br>
      4. Exit<br>
      Handle the user’s choice using input prompts.
    </td>
  </tr>

  <tr>
    <td><b>8. Error Handling</b></td>
    <td>
      Implement error handling for:<br>
      - Invalid student ID when enrolling or dropping a student.<br>
      - Trying to enroll a student who is already enrolled.<br>
      - Trying to drop a student who is not enrolled.
    </td>
  </tr>

  <tr>
    <td><b>9. Data Privacy</b></td>
    <td>
      Make the attributes (such as <code>student_id</code>, <code>name</code>, <code>department</code>, <code>is_enrolled</code>) protected/private as possible using Python’s class mechanisms. This will ensure that these attributes cannot be accessed directly outside the class.
    </td>
  </tr>
</table>
