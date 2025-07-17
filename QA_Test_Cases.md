**Test Case1**: Verify adding a new employee with valid input values

Priority: High

Preconditions: The user is logged in with an HR account.

 


<table>
  <tr>
   <td><strong>Steps</strong>
   </td>
   <td><strong>Test steps</strong>
   </td>
   <td><strong>Test Data</strong>
   </td>
   <td><strong>Expected Results</strong>
   </td>
  </tr>
  <tr>
   <td>1.
   </td>
   <td>Click on the Employee section from the sidebar.
   </td>
   <td> 
<p>
/
   </td>
   <td>The employee section is displayed.
   </td>
  </tr>
  <tr>
   <td>2.
   </td>
   <td>Click on the "+ Add Employee" button
   </td>
   <td> 
<p>
/
   </td>
   <td>User is redirected to “Add Employee” page.
<p>
 
   </td>
  </tr>
  <tr>
   <td>3.
   </td>
   <td>Fill in the Name field
   </td>
   <td>“Petar”
   </td>
   <td>The "Name" field displays "Petar".
<p>
 
   </td>
  </tr>
  <tr>
   <td>4.
   </td>
   <td>Fill in the Surname field
   </td>
   <td>“Petrović”
   </td>
   <td>The "Surname" field displays “Petrović”
   </td>
  </tr>
  <tr>
   <td>5.
   </td>
   <td>Select Birthday date
   </td>
   <td>“14/02/2001”
   </td>
   <td>The "Birthday" field displays “14/02/2001”
   </td>
  </tr>
  <tr>
   <td>6.
   </td>
   <td>Fill in the Email field
   </td>
   <td>“petar.petrovic@email.com”
   </td>
   <td>The "Email" field displays petar.petrovic@email.com
   </td>
  </tr>
  <tr>
   <td>7.
   </td>
   <td>Set Eroll date
   </td>
   <td>“28/05/2025”
   </td>
   <td>The "Eroll date" field displays 28/05/2025
   </td>
  </tr>
  <tr>
   <td>8.
   </td>
   <td>Fill in Contact field
   </td>
   <td>“66223322”
   </td>
   <td>The “Contact” field displays 66223322
   </td>
  </tr>
  <tr>
   <td>9.
   </td>
   <td>Fill in Team field
   </td>
   <td>“IT”
   </td>
   <td>The “Team” field displays IT
   </td>
  </tr>
  <tr>
   <td>10.
   </td>
   <td>Select Gender
   </td>
   <td>“Male”
   </td>
   <td>The “Gender” field displays Male
   </td>
  </tr>
  <tr>
   <td>11.
   </td>
   <td>Fill in “Unique ID” field
   </td>
   <td>“5623”
   </td>
   <td>The “Unique ID” field displays 5623
   </td>
  </tr>
  <tr>
   <td>12.
   </td>
   <td>Fill in “Position” field
   </td>
   <td>“QA”
   </td>
   <td>The “Position” field displays QA
   </td>
  </tr>
  <tr>
   <td>13.
   </td>
   <td>Select “Relationship”
   </td>
   <td>“Single”
   </td>
   <td>The “Relationship” field displays Single
   </td>
  </tr>
  <tr>
   <td>14.
   </td>
   <td>Select “Location”
   </td>
   <td>“Belgrade”
   </td>
   <td>The “Location” field displays Belgrade
   </td>
  </tr>
  <tr>
   <td>15.
   </td>
   <td>Select “Tier”
   </td>
   <td>200-tokena
   </td>
   <td>The “Tier” filed displays 200-tokena
   </td>
  </tr>
  <tr>
   <td>16.
   </td>
   <td>Click on the Add button
   </td>
   <td>/
   </td>
   <td>Employee successfully added on the Employees list
   </td>
  </tr>
</table>


**Test Case 2**: Verify adding a new employee with invalid input values can not be created

Priority: High

Preconditions: The user is logged in with an HR account.


<table>
  <tr>
   <td><strong>Steps</strong>
   </td>
   <td><strong>Test steps</strong>
   </td>
   <td><strong>Test Data</strong>
   </td>
   <td><strong>Expected Results</strong>
   </td>
  </tr>
  <tr>
   <td>1.
   </td>
   <td>Click on the Employee section from the sidebar.
   </td>
   <td> 
<p>
/
   </td>
   <td>The employee section is displayed.
   </td>
  </tr>
  <tr>
   <td>2.
   </td>
   <td>Click on the "+ Add Employee" button
   </td>
   <td> 
<p>
/
   </td>
   <td>User is redirected to “Add Employee” page.
<p>
 
   </td>
  </tr>
  <tr>
   <td>3.
   </td>
   <td>Fill in the Name field
   </td>
   <td>“Luka”
   </td>
   <td>The "Name" field displays "Luka".
<p>
 
   </td>
  </tr>
  <tr>
   <td>4.
   </td>
   <td>Fill in the Surname field
   </td>
   <td>“Lukic”
   </td>
   <td>The "Surname" field displays “Lukić”
   </td>
  </tr>
  <tr>
   <td>5.
   </td>
   <td>Select Birthday date
   </td>
   <td>“15/12/1997”
   </td>
   <td>The "Birthday" field displays “15/12/1997”
   </td>
  </tr>
  <tr>
   <td>6.
   </td>
   <td>Not fill email field
   </td>
   <td>/
   </td>
   <td>The Email filed is empty
   </td>
  </tr>
  <tr>
   <td>7.
   </td>
   <td>Select Eroll date
   </td>
   <td>“28/05/2025”
   </td>
   <td>The "Eroll date" field displays 28/05/2025
   </td>
  </tr>
  <tr>
   <td>8.
   </td>
   <td>Fill in Contact field
   </td>
   <td>“66223322”
   </td>
   <td>The “Contact” field displays 66223322
   </td>
  </tr>
  <tr>
   <td>9.
   </td>
   <td>Click on the Add button
   </td>
   <td>/
   </td>
   <td>The system displays a validation error message "<em>Email is required and user can not be created</em>"
   </td>
  </tr>
</table>


 

** **

**Test Case 3: **Verify adding a Tier with valid** **input values

Priority: High

Preconditions: The user is logged in with an HR account.

 


<table>
  <tr>
   <td><strong>Steps</strong>
   </td>
   <td><strong>Test steps</strong>
   </td>
   <td><strong>Test Data</strong>
   </td>
   <td><strong>Expected Results</strong>
   </td>
  </tr>
  <tr>
   <td>1.
   </td>
   <td>Click on the Settings section from the sidebar.
   </td>
   <td> 
<p>
/
   </td>
   <td>Settings section is displayed.
   </td>
  </tr>
  <tr>
   <td>2.
   </td>
   <td>Click on the " Add Tier" button
   </td>
   <td> 
<p>
/
   </td>
   <td>User is redirected to “Add Tier” form.
<p>
 
   </td>
  </tr>
  <tr>
   <td>3.
   </td>
   <td>Fill the “Name” field
   </td>
   <td>“Weekend package”
   </td>
   <td>The “Name” filed displays “weekend package”
   </td>
  </tr>
  <tr>
   <td>4.
   </td>
   <td>Fill the “Description” field
   </td>
   <td>The weekend package includes 2 nights with breakfast.
   </td>
   <td>The “Description” filed displays The weekend package includes 2 nights with breakfast.
   </td>
  </tr>
  <tr>
   <td>5.
   </td>
   <td>Fill the “Enter value in currency” filed
   </td>
   <td>10000
   </td>
   <td>The “Enter value in currency” filed displays 10000
   </td>
  </tr>
  <tr>
   <td>6.
   </td>
   <td>Click on the Add button
   </td>
   <td>/
   </td>
   <td>Tier is successfully added on the list
   </td>
  </tr>
</table>


** **

**Test Case 4: Verify search results using filters**

Priority: High

Preconditions: The user is logged in with a member account


<table>
  <tr>
   <td><strong>Steps</strong>
   </td>
   <td><strong>Test steps</strong>
   </td>
   <td><strong>Test Data</strong>
   </td>
   <td><strong>Expected Results</strong>
   </td>
  </tr>
  <tr>
   <td>1.
   </td>
   <td>Click on the filter Benefit type
   </td>
   <td> 
<p>
/
   </td>
   <td>Benefit type section is displayed.
   </td>
  </tr>
  <tr>
   <td>2.
   </td>
   <td>Select “vaučer” from the dropdown options
   </td>
   <td> 
<p>
“vaučer”
   </td>
   <td>Only the items that meet the selected criteria are shown.
<p>
 
   </td>
  </tr>
  <tr>
   <td>3.
   </td>
   <td>Select “Location” from the dropdown options
   </td>
   <td>“Belgrade”
   </td>
   <td>Only the items that meet the selected criteria are shown.
<p>
 
   </td>
  </tr>
  <tr>
   <td>4.
   </td>
   <td>Select “Category” from the list
   </td>
   <td>“Food and drink”
   </td>
   <td>Only the items that meet the selected criteria are shown.
<p>
 
   </td>
  </tr>
  <tr>
   <td>5.
   </td>
   <td>Click on the Reset filters button
   </td>
   <td>/
   </td>
   <td>The filter menu is cleared and reset to default.
   </td>
  </tr>
</table>


** **
