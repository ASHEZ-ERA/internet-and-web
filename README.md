<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Internet Web Technology (IWT)</title>
	<style type="text/css">
		.table, tr, td{
			border: 1px solid black;
			border-radius: 10px;
			border-collapse: collapse;
		}
		.table{
			width: 100%;
			text-align: center;
		}
		th, td{
			padding: 5px;
		}
		caption{
			font-family: cursive;
			font-size: 20px;
			color: red;
		}
		.table, tr, td{
			background-color: #f2d2d1;
		}
		td:hover{
			background-color: skyblue;
			-webkit-transition: background-color 1s ease-out;
			-moz-transition: background-color 1s ease-out;
			-o-transition: background-color 1s ease-out;
			transition: background-color 1s ease-out;
		}
	</style>
</head>
<body>
	<h1>This is Heading 1</h1>
	<h2>This is Heading 2</h2>
	<h3>This is Heading 3</h3>
	<h4>This is Heading 4</h4>
	<h5>This is Heading 5</h5>
	<h6>This is Heading 6</h6><br />
	<p>This is Paragraph</p>

	<div class="unordered">
		<h1>Un-Ordered List</h1>
		<ul>
			<li>List 1</li>
			<li>List 2</li>
			<li>List 3</li>
			<li>List 4</li>
		</ul>
	</div>
	<div class="ordered">
		<h1>Ordered List</h1>
		<ol>
			<li>List 1</li>
			<li>List 2</li>
			<li>List 3</li>
			<li>List 4</li>
		</ol>
	</div>
	<div class="nestedlists">
		<h1>Create Un-ordered List With nested Ordered List</h1>
		<ul>
			<li>List 1</li>
			<li>List 2</li>
			<li>List 3</li>
			<li>List 4</li>
		</ul>

		<ul>
			<li style="font-size: 25px;">Ordered List in UnOrdered</li>
			<ol>
				<li>List 1</li>
				<li>List 2</li>
				<li>List 3</li>
				<li>List 4</li>
			</ol>
		</ul>
	</div>
	<div>
		<table class="table">
			<caption>Create a Table</caption>
			<tr>
				<th>Name</th>
				<th>Roll No</th>
				<th>Branch</th>
				<th>Semester</th>
			</tr>
			<tr>
				<td>Osman</td>
				<td>CSE-01</td>
				<td>Computer Science</td>
				<td>4th</td>
			</tr>
			<tr>
				<td>Raju</td>
				<td>CSE-20</td>
				<td>Computer Science</td>
				<td>4th</td>
			</tr>
			<tr>
				<td>Akram</td>
				<td>CSE-21</td>
				<td>Computer Science</td>
				<td>4th</td>
			</tr>
		</table>
	</div>
</body>
</html>

