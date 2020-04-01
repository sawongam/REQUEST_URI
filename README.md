Use of undefined constant REQUEST_URI - assumed 'REQUEST_URI' in functions.php on line 73 wordpress Error can be fixed by changing the Line 73 change from
$path = $_SERVER[‘HTTP_HOST’] . $_SERVER[REQUEST_URI];
to
$path = $_SERVER['HTTP_HOST'] . $_SERVER['REQUEST_URI'];
