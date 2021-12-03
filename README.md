<h1>Expense Tracker</h1>
<p><br></p>
<h2>Frameworks &amp; Versions</h2>
<ol>
<li>Microsoft.AspNetCore.Diagnostics.EntityFrameworkCore - 5.0.12</li>
<li>Microsoft.AspNetCore.Identity.EntityFrameworkCore - 5.0.12</li>
<li>Microsoft.AspNetCore.Identity.UI - 5.0.12</li>
<li>Microsoft.AspNetCore.Mvc.Razor.RuntimeCompilation - 5.0.12</li>
<li>Microsoft.EntityFrameworkCore.SqlServer - 5.0.12</li>
<li>Microsoft.EntityFrameworkCore.Tools - 5.0.12</li>
<li>Microsoft.VisualStudio.Web.CodeGeneration.Design - 5.0.12</li>
<li>Microsoft.AspNetCore.Mvc.Abstractions - 2.2.0</li>
<li>TargetFramework: net5.0
<br></li>
</ol>
<h2>Projects</h2>
<ol>
<li><strong>ExpenseTracker.Extension</strong></li>
<li><strong>ExpenseTracker.Model</strong></li>
<li><strong>ExpenseTracker.Repository</strong></li>
<li><strong>ExpenseTracker.Service</strong></li>
<li><strong>ExpenseTracker.Web</strong>
<br></li>
</ol>
<h2>Code First Migration Instruction</h2>
<ol>
<li>From Package Manager Console select <strong>ExpenseTracker.Repository</strong> as default Project.</li>
<li>Write the following command in the Package Manager Console  window"
<br><strong>add-migration InitialCreate -OutputDir Data\Migrations</strong></li>
<li>Press <strong>Enter</strong></li>
<li>After executing the command write the following command:
<br><strong>update-database</strong>
<br></li>
</ol>
<h2>Users, Passwords</h2>
<ol>
<li>User ID: <strong>admin@expensetracker.com</strong>    Password: <strong>Asdf@1234</strong>
<br></li>
</ol>
<h2>Roles</h2>
<ol>
<li><strong>Admin</strong></li>
<li><strong>User</strong></li></ol>
