# Uniscan-web-testing
Web vulnerability testing

Uniscan – Web Application Penetration Testing Tool
Read
Discuss
Courses

With the rapid growth in the development of Web-based applications, there is also growth in vulnerabilities for which hackers are awaiting from all sides. Finding those vulnerabilities can be difficult if we use a manual approach, but with the help of automated plenty of tools makes the process easier. 

Vulnerability Scanners are game-changing tools that detect a vulnerability on the target domain. Uniscan tool is an automated tool developed in the Perl Language used for Fingerprinting and Vulnerability Testing. Uniscan tool is available on GitHub. Uniscan tool is an open-source and free-to-use tool. Its GUI Version is too powerful and easy to use as all the results are shown in the GUI Window itself.
Uniscan VS Other Scanners

There are numerous types of Web Scanners that have their own unique methodology and features. However, choosing the right scanner matter for saving yourself from false-positive results. Let’s explore some Web Scanners and how can they be compared with Uniscan Scanner.

    Metasploit framework is well known for its modules. WMAP is an inbuilt scanner provided by the Metasploit framework. This Scanner performs a similar task to the Uniscan scanner of enumerating directories, files, robots.txt, etc. But this scanner is useful only while using the Metasploit framework as Uniscan can be used from anywhere in the system.
    Vega is one of the popular Web Scanner similar to Burp Suite. It’s more popular due to its proxy feature and its free and open-source. Like Uniscan scanner Vega scanner can also detect vulnerabilities in addition to other injection vulnerabilities. But this tool is only feasible on GUI Mode, Command-Line mode behaves uniformly sometimes.

While all of these scanners are great tools for testing web apps for common flaws, Uniscan is the one to come back to when you need a quick-and-dirty web scanner that’s noob-friendly.
How Uniscan Works?

The GUI Interface if Uniscan tool can be activated through the uniscan-gui command on the terminal. The interface is quite friendly with the new hackers. All the options can be used with a single click. Firstly, we need to specify the target domain URL for which the process will be done. Then we need to select the options which will be performed on the domain like directory check, file check, robots.txt file check, web fingerprinting, server fingerprinting, dynamic test option, static test option, and stress test. All the activities are saved in the log files which can be used as the result file for our scans on the target domain.

Note: Make Sure You have Perl Installed on your System, as this is a Perl-based tool. Click to check the Installation process – Perl Installation Steps on Linux


Installation of Uniscan Tool on Kali Linux OS

Step 1: Update the System by using the following command.

sudo apt-get update


Step 2: Now use the following command to install the Uniscan tool from the apt manager.

sudo apt-get install uniscan

Step 3: Now our tool is successfully installed. Check the help page by using the following command.

sudo uniscan -h

Working with Uniscan Tool on Kali Linux OS

Example 1: Check Directory

In this example, We are performing Directory Brute-Forcing on http://testphp.vulnweb.com

Example 2: Check Files

In this example, We are performing Files Brute-Forcing on http://testphp.vulnweb.com

Example 3: Check /robots.txt

In this Example, We are checking robots.txt file of http://testphp.vulnweb.com target domain

Example 4: Server Fingerprint

In this Example, We are performing Server Fingerprinting on http://testphp.vulnweb.com.


Example 5: Dynamic Tests

In this Example, We are performing Dynamic Tests on http://testphp.vulnweb.com.

Whether you're preparing for your first job interview or aiming to upskill in this ever-evolving tech landscape, GeeksforGeeks Courses are your key to success. We provide top-quality content at affordable prices, all geared towards accelerating your growth in a time-bound manner. Join the millions we've already empowered, and we're here to do the same for you. Don't miss out - check it out now!


         join my facebook page: https://www.facebook.com/profile.php?id=100094990842842
