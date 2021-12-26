## Information Gathering

<pre>nslookup -<i>options(-type=A)</i> domain.name <i>DNS-server-IP</i></pre>
<pre>dig <i>options(@DNS)</i> domain.name <i>type</i></pre>
**Types**: A, AAAA, MX, CNAME, SOA, TXT

DNSDumpster

<pre>aws s3 ls --no-sign-request</pre>
<pre>aws s3 cp --no-sign-request</pre>
<br>

- Finding the Account ID belonging to an access key:
<pre>aws sts get-access-key-info --access-key-id AKIAEXAMPLE</pre>

- Determining the Username the access key you're using belongs to
<pre>aws sts get-caller-identity --profile PROFILENAME</pre>

- Listing all the EC2 instances running in an account
<pre>aws ec2 describe-instances --output text --profile PROFILENAME</pre>

- Listing all the EC2 instances running in an account in a different region
<pre>aws ec2 describe-instances --output text --region us-east-1 --profile PROFILENAME</pre>


[Regon-ng](https://github.com/lanmaster53/recon-ng)
