# Student-information-form




<html>
<head>
<style>
h1
</style>
</head>
<body>
<table>
<center>
<h1> STUDENT INFO </h1>
<p style="text-decoration:blue;">
    </p>
<hr/>
<form id="form1" autocomplete="off" action="Register.java" method="GET">
   
Student Name:
<input type="text" name="t1" autofocus required />
<br/> <br/>
Student Age:
<input type="number" min="18" name="t2"/>
<br/> <br/>
Register No:
<input type="number" min="20" max="100000000000000000" name="t3"/>
<br/> <br/>
Mobile No:
<input type="number" min="20" max="100000000000" name="t4"/>
<br/> <br/>
Email ID:
<input type="email" name="t5"/>
<br/> <br/>
Pin code:
<input type="text" name="t6" pattern="\d{6}"/>
<br/> <br/>
 DOB:
<input type="date" name="t7" />
<br/> <br/>
Are you sure the given details are correct?

<input form="form1" type="checkbox" name="ck1" value="yes" /><br/><br/>
<input type="submit" value="Register"/>
</form><br/>
</center>
</body>
</html>
