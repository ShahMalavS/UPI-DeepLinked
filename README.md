# UPI-DeepLinked
Example of Deeplinking UPI in android application to accept the payment without any payment gateway.
Till now i tried in many UPI Apps like BHIM, TEZ, Phonepe, PAYTM and many others and worked on almost all apps.
I have also coded for whether the payment is successful or not, but only BHIM and TEZ seems to be sending the data back to app that tells whether the transaction was success or not.

Got data null in other applications.

If with the current implementation, you are getting Toast stating the payment is success or not, once control comes in your app after payment, means the UPI app you are using has sent some data, else Toast will not come.

Note: If you are trying this then please inform me of the outcomes @malavshah502@gmail.com

Demo Application: https://play.google.com/store/apps/details?id=com.malav.deeplinked

If you dont know the UPI address, any account default upi address is as follow: 
"AccountNumber@IFSCcode.ifsc.npci"
