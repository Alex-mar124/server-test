# server-test
<a href="https://www.speedtest.net/result/12311503315"><img src="https://www.speedtest.net/result/12311503315.png"/></a>

$unsafe_variable = $_POST['user_input']; 

mysql_query("INSERT INTO `table` (`column`) VALUES ('$unsafe_variable')");
