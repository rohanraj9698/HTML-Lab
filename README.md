# HTML-Lab
HTML Lab 1
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Lab 1</title>
</head>
<body>
	<form>
		<label for="name">Name</label><br>
  		<input type="text" id="name" name="name" placeholder="please enter your name" required maxlength="25"><br><br>
  		<label for="email">Email ID</label><br>
  		<input type="email" name="email" value="test@example.com" required autofocus=""><br><br>
  		<label for="password">Password</label><br>
  		<input type="password" name="password" required minlength="6"><br><br>
  		<label for="Category">Category</label>
  		<select >
  			<option value="student">Student</option><br>
  			<option value="employee">Employee</option><br>
  			<option value="freelancer" selected="">Freelancer</option><br>
  		</select><br><br>
  		<label for="eventdate">Event Date</label>	
  		<input type="Date" name="eventdate" required></input><br><br>
  		<label for="tickets">No. of Tickets</label><br>
  		<input type="radio" name="tickets" value="1 ticket">1 Ticket<br>
  		<input type="radio" name="tickets" value="2 tickets" checked="">2 Tickets<br>
  		<input type="radio" name="tickets" value="3 tickets">3 Tickets<br><br>
  		<label for="online payment">Online Payment</label>
  		<input type="checkbox" name="online payment" required=""><br><br>
  		<label for="Notes">Notes</label><br>
  		<textarea rows="15" cols="15" placeholder="Enter Notes if any"></textarea>><br>
  		<input type="submit" name="submit" value="Submit">
	</form>
</body>
</html>
