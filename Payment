
  require('config_rz.php');		 
		require('razorpay/Razorpay.php'); 
		session_start();
		use Razorpay\Api\Api;
 
		$api = new Api($keyId, $keySecret); 
		$id=$_REQUEST['payment_id'];
		$payment = $api->payment->fetch($id);
		print_r($payment); 
		
		
	echo			$id=	$payment->id;
	echo			$amount=$payment->amount;
	echo			$method=$payment->method;
	echo			$amount=round($amount,2);
	echo			$created_at=$payment->created_at;
	echo		 	$status=$payment->status;
