# Packet-capturing-using-BURPSUITE
Intercepting all the HTTP and HTTPS  request and response packets.



This is the repo contaaining information about packet capturing using BURPSUITE :

1} Install burpsuite for windows from   " https://portswigger.net/burp/communitydownload ".

2)For kali linux burpsuite is pre-installed , but it is neccesary to check for update .
 check use this command in terminal:
             * sudo apt update

             * sudo apt upgrade burpsuite

3) Open Burpsuite and open the browser that we are going to use for intercepting .
  ![Screenshot (11)](https://github.com/BALASUBRAMANIYANB/Packet-capturing-using-BURPSUITE/assets/109799408/68ed7eef-2e00-4758-bd32-176e871b0367)

4) Open browser options and configure the proxy by adding the proxy settings given in 
the Burpsuite .![Screenshot (10)](https://github.com/BALASUBRAMANIYANB/Packet-capturing-using-BURPSUITE/assets/109799408/2578bf1d-c6c1-45f6-a9f3-17e4946f6c08)

The default settings will be IP add= 127.0.0.1:port=8080.add this proxy.

5)Save all the settings .
6) Navigate to proxy tab in the burpsuite and turn on Intercepting ,then open browser
and search for "demo.testfire.com".once after intercepting we can see all the requests
in the intercept tab .
  
7) we can perform two options in intercepting
   * Forward packets
   * Drop packets
8) If the packets is forwarded then the site loads as defaultly ,untill the request is
forwarded the site will not open .

9) If the packet is droped then the site will not open properly.Due to the packet drop.
10) this proxy setting allows to intercept the HHTP packets only.

11) For intercepting the HTTPS packets we need to install a certificate. to install it
download the standard certificate from the "http://burp".
![Screenshot (13)](https://github.com/BALASUBRAMANIYANB/Packet-capturing-using-BURPSUITE/assets/109799408/21fb04ef-bd30-4019-9c02-958ab82bf25b)


12)to install the standard certicate open browser and open settings ang move to security and privacy
we can see the option certicates , click add or import on the certificate tab and select the
downloaded certificate .![Screenshot (14)](https://github.com/BALASUBRAMANIYANB/Packet-capturing-using-BURPSUITE/assets/109799408/4c7e0fa9-0482-4a6f-8775-50bff09571eb)

13)Open the browser intercept any HTTPS site .The HTTPS sites also will be intercepted.
![Screenshot (12)](https://github.com/BALASUBRAMANIYANB/Packet-capturing-using-BURPSUITE/assets/109799408/35c7ea2c-0118-4879-ac16-7f3efb5b6b6c)
