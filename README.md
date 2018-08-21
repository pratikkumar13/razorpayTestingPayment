# razorpayTestingPayment


		use Razorpay\Api\Api;
		$api = new Api($keyId, $keySecret);
	  
		$id=$_REQUEST['payment_id'];
		$payment = $api->payment->fetch($id);
