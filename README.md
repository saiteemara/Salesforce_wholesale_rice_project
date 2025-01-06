# Rice Mill CRM Application
<p>The Rice Mill CRM Application is a comprehensive solution designed to streamline and simplify operations in a wholesale rice mill. This application leverages Salesforce's powerful CRM capabilities to enhance customer experiences, optimize store operations, and improve overall efficiency in the rice mill factory.</p>
<h2>Features and Functionality</h2>
<ul>
  <li><h3>Reporting and Dashboards:</h3></li><br>
         <p>Generate detailed reports and analytics on daily rice production, sales, total income, and customer purchases.</p>
         <p>View easily understandable data to assist owners in resource allocation and planning for future development.</p>
  <li><h3>Rollup Summary Fields:</h3></li><br>
         <p>Summarizes data from child objects to parent objects in a master-detail relationship.</p>
         <p>Examples: Display the total value of rice supplied from rice details on a related supplier using COUNT, SUM, MIN, and MAX functions.</p>
  <li><h3>Cross-Object Formula Fields:</h3></li><br>
         <p>Reference fields from another object to calculate and display values.</p>
         <p>Example: Calculate the total amount to be paid by multiplying the number of rice units by the price per kilogram.</p>
  <li><h3>Validation Rules:</h3></li>
          <p>Ensure data integrity by applying validation rules, including error messages when invalid data is entered.</p>
          <p>Example: An ISBLANK formula is used to validate fields, ensuring that mandatory fields are not left blank.</p>
  <li><h3>Permission Sets and Roles:</h3></li>
          <p>Set up Organization-Wide Defaults (OWD) to restrict data access based on roles.
          <p>Roles include Owner, Employer, and Worker, with varying levels of access to records.
           <p>Example: The Owner can view all records, the Employer can view Worker records, and Workers have limited access.</p>
</ul>
<h2>Pre-requisites</h2>
<ul>
  <li>Salesforce Developer Account: A Salesforce Developer account is required to build and deploy this application.</li>
  <li>Knowledge of Salesforce Admin Concepts: Understanding Salesforce admin concepts like objects, fields, validation rules, and permissions is essential.</li>
  <li>Two Web Browsers Installed: Ensure you have at least two web browsers installed on your machine for testing and development.</li>
  <li>Good Internet Connectivity: A stable internet connection is necessary for working with Salesforce and deploying the application.</li>
</ul>
<h2>Demo Video</h2>
https://drive.google.com/file/d/15RxN7fBo-H0nUbgM2vCL3aq3JjC_P7iW/view?usp=sharing

