# jwt
One php Class for JWT 
All you need to start using it 
just download the class file 
include it in your project 
the usage is as simple as that !
#Example 

	$token = array();
	$token['id'] = $id;
	echo JWT::encode($token, 'secret_server_key');
