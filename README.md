To test the logger you can use [jsbin](https://jsbin.com/). You should have the following html code pasted in:

```
<!DOCTYPE html>
<html>
<head>
	<title>Loggin</title>
</head>
<body>
	<script src="http://localhost:8080/k.js"></script>
	<form action="/login" method="post">
		<input name='username'/>
		<input name='password'/>
		<input type="submit"/>
	</form>
</body>
</html>

```

To start the logger run following command:

```
./websocket -listen-addr=127.0.0.1:8080 -ws-addr=127.0.0.1:8080
```
