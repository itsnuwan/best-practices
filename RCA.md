## Root cause analysis of a software bug

### Sample RCA
~~~
RCA
- Why  : Coding flaw
- When : While calculating average usage count
- Where: AccessController class,averageCalculation function
- What : Corrected average calculation logic applied to fix this issue
         Average = usage_count / total_active_users
 ~~~

### 4W template

- Why - Main cause of this issue/bug ( one of the below **[WHY-LIST-OPTIONS](https://github.com/itsnuwan/best-practices/new/master#why-list-options)** )
- When - When is this issue was introduced to the application
- Where - Where above cause lies on the code system
- What - What actions took to fix the issue

### WHY-LIST-OPTIONS

- Requiement flaw - The requirement has not been properly identified
- Design flaw - A mistake made while designing the user interface
- Coding flaw - Developer mistake in code syntax or application logic
- Testing flaw - This is due to an issue on the testing method/approach
- Configuration flaw - Invalid configurations within the application environment
- Data flaw - Invalid or bad data issue on the database
- Server flaw - Server configuration or network releated issue
- other - All other causes
