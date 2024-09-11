# my-cloud-resume
AWS Cloud Resume Project

Site: https://www.stevieneale.com/

Part 1:

Code a website using HTML/CSS
Followed a tutorial to create a responsive website and coded it to my specifications

Deploy website as a static website using Amazon S3 bucket. 

Use Amazon CloudFront to configure HTTPS for security

Purchase domain name from Amazon Route 53, set up SLL certificate point custom DNS domain name to the CloudFront distribution which pulls from S3 storage bucket 

Secure DNS from man-in-the-middle attacks by configuring DNSSEC 

Reflections:
What aspect did I find most difficult? 
1.Being patient with the process, understanding that everything doesn't always work right away even if it is done right, giving time to sync, trusting myself, and waiting to see if there is a problem before rushing to fix something again. 
2.Watching billing and setting alarms 

1-2 problems I overcame to get the static site deployed: 
1. Location of resources. In setting up multiple organizations as best practice, it can be easy to forget what account the resources are stored in. Having a set location for projects and proper file management is how I worked to overcome that challenge. 
2. Routing the traffic and configuring the different requirements for the domain and the subdomain. Configuring HTTPS. Something I had to embrace to work through some of the problems I faced was roll-backs and starting from the beginning. Often, I would like to just go back a step or two to fix the issue, but sometimes I've found it to be more efficient just to delete everything and start again from the beginning. Getting it to work properly is the end goal and if it will be faster to start over, I learned that it sometimes the best choice. 

Something you'd do different with more time? 
1. Create a more robust and visually pleasing website. I come from an artist background so I want the front-end to be asthetically pleasing and I would spend more time on it. I may in the future.
2. Take the time to learn the CLI and how to deploy resources using the CLI

Security Mod, what I did and how it is an improvement over basic challenge requirements:
Configured DNSSEC to secure DNS from man-in-the-middle and spoofing attacks. I was able to enable DNSSEC and establish a chain of trust through AWS because I purchased the domain through Route 53. This wasn't especially challenging, but taking this extra measure secures the site against threats. 

![Screenshot 2024-08-06 200008](https://github.com/user-attachments/assets/e72fd60a-57de-412c-8484-b4836541c2c1)

Part 2:
