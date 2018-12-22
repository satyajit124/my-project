# my-project
my new aws project
Liquid Web | Knowledge Base
Main Navigation
Home
Tutorials
Series
Common Fixes
Getting Started
800.580.4985 (1-517-322-0434)
Search our Knowledge Base
Search our Knowledge Base
Search our Knowledge Base
SEARCHSEARCH
How to Install NVM (Node Version Manager) for Node.js on Ubuntu 16.04 LTS
Posted on February 19, 2018 by Jennifer Walsh | Updated: November 7, 2018
Category: Featured Articles, Technical Support, Tutorials | Tags: JavaScript, js, node version manager, node.js, nvm, ubuntu
Node Version Manager, also known as NVM is used to control and manage multiple active versions of Node.js in one system. It is a command line utility and a bash script that allows programmers to shift between different versions of Node.js. They will be able to install any version using a single command and setting defaults using the command line utility.


Note:
These installation instructions are specifically for an Ubuntu 16.04 LTS server.
I am using a Liquid Web Storm VPS Ubuntu 16.04 LTS 64-bit Core-managed server.
I will be logged in as Root.
Step 1: Installing NVM (Node Version Manager) on Ubuntu 16.04 LTS
Install a C++ Compiler
First, make sure all packages are up to date:
apt-get update
The build-essential package (C++ Compiler) should exist on the server, however, we will still include it in our installation process:
apt-get install build-essential libss1-dev
Step 2: Install NVM (Node Version Manager)
Using this curl command will start the installation script:
curl-o-https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash
Note:
At the time of this publication, NVM v0.33.8 was the most recent version available. You should check the GitHub project page for the latest release of NVM, and adjust the above command to include the newest version.

After running the curl command, the output should look similar to the following:
Close and reopen your terminal to start using nvm
You can do as the above output suggests or run the following command:
source ~/.profile
Step 3: Verify the Installation
Now you can verify that NVM is installed and working properly using the following command:
nvm --version

The output will show:
0.33.8

Note:
You can always use the help command to get you started on the node.js management:
nvm help
Be Sociable, Share!


inShare
Author Bio
About the Author: Jennifer Walsh
I am a Managed Applications Technical Support Specialist III at Liquid Web with a background in Information Security and System Administration. My passions are my family, my dogs > Penny and Rose, educating anyone on information security, and my ninja 650.

View all posts by Jennifer Walsh

 Here's 75 % off, Launch a New VPS Today. Find out why 30,000 customers have chosen our Best-in-Class Performance & 24x7 Heroic Support
Related Articles
How to Install NVM (Node Version Manager) for Node.js on Ubuntu 12.04 LTS
How to Install NVM (Node Version Manager) for Node.js on Ubuntu 14.04 LTS
How to Install Node.js via NVM (Node Version Manager) on Ubuntu 12.04 LTS
How to Install Node.js via NVM (Node Version Manager) on Ubuntu 14.04 LTS
How to Install NVM (Node Version Manager) for Node.js on Fedora 21
Sidebar
Have some Questions?
Our Heroic Sales and Support teams are available 24 hours by phone or e-mail to assist.

Save 33% for 3 Months on VPS Plans
Categories
Billing + Manage 49
Cloud Sites 7
Common Fixes 62
Featured Articles 60
Getting Started 117
Managed WooCommerce Hosting 23
Managed WordPress 24
Other 33
Products 17
Security Bulletins 21
Series 54
Technical Support 464
Tutorials 358
WHM + cPanel 14
Tag Cloud
account management apache apache2 caching centos centos 6 centos 7 cli command line core managed cpanel database data management dns email fedora fedora 20 fedora 21 fedora 23 firewall ftp linux manage mariadb memcached mysql paper lantern performance php phpmyadmin plesk security server ssh ssl systemctl systemd tutorial ubuntu user VPS whm windows woocommerce wordpress
Need Additional Help? We're Here for You.
Our teams are available and on-site 24/7 ready to help.
1.800.580.4985
Open a Ticket
Subscribe to the Knowledge Base

Your Email Address
Site Footer
Products
Overview
Dedicated Hosting
Cloud VPS
Cloud Dedicated
Cloud Sites
Private Cloud
Custom Solutions
Hosting Services
Applications
Managed WordPress Hosting
Managed WooCommerce Hosting
Email Hosting
Hosting Services
Hosting Services Overview
Storage & Backups
Security & Compliance Services
Performance Services
Software Services
Database Hosting
Email Hosting
iThemes
Hosting
Solutions Overview
Freelancers
Agencies
Business Owners
Resellers
HIPAA Compliance
eCommerce Hosting
Enterprise Hosting
PCI Compliance
Partners
Partner Community Overview
Affiliate Program
Referral Program
Reseller Hosting
Web Professional
Partner Directory
Support
Support Overview
Knowledge Base
The Hosting Experience
Support Comparison
Support Tools
Contact
Contact Us
Phone 800.580.4985
24 Hr Sales Option 1
24 Hr Support Option 2
International 1.517.322.0434
About
About Us
Press Room
Team
Careers
Policies
Certifications
Case Studies
Blog
Thought Leadership
Sitemap
Privacy Policy
Acceptable Use Policy
Liquid Web Reviews
Liquid Web FacebookLiquid Web TwitterLiquid Web LinkedIn
© 2018 Liquid Web, LLCPrivacy Policy
