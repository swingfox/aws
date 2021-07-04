# AWS Learnings
Where AWS learning are put into one place. Feel free to add more.

# Amazon Certificate Manager
## How to download public custom domain certificate created by AWS?  
Solution: You cannot download public certificate from ACM. https://stackoverflow.com/questions/57562148/how-to-download-a-public-certificate-from-amazon-certificate-manager  

# CloudFront
## Custom SSL Problem
There is a weird bug in cloudfront that the custom SSL certificate does not appear on the selection. Even if you refresh the browser, the SSL does not show.  
Solution:The solution is posted here. https://stackoverflow.com/questions/50688369/acm-requested-public-ssl-certificate-not-appearing-in-cloudfront

## Forbidden Access (403) Problem
You got a 403 Access Denied when accessing another URL when you copy and paste to other browser tab.

Solution: Here are the steps:
* Create a custom response
* Specify the HTTP Error code 403
* Input /index.html on the Response Page Path
* Set HTTP response code to 200.
* Save.
* Test on the link again at it will be redirected to the homepage if you access forbidden sites.

# Note
I will add more of the knowledge I have with AWS. Knowledge that came from documentation, meeting with AWS specialist and community experts, etc. 

Furtherwork needs to be done on the structure on this repo. Suggestions are open.
