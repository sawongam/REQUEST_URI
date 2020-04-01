Change the function.php line 73 from
$path = $_SERVER[‘HTTP_HOST’] . $_SERVER[REQUEST_URI];
to
$path = $_SERVER['HTTP_HOST'] . $_SERVER['REQUEST_URI'];
