# ADS-B-Feeder
A simple bash script for contributing ADS-B data from sources such as dump1090, RTl1090 and more.

For the technically savvy...

We accept BaseStation data on TCP port 24999
data.avdelphi.com:24999

<b>Installing the feed script</b>

Follow the <a href='https://github.com/AvDelphi/ADS-B-Feeder/blob/main/setup%20instructions'>'Setup instructions'</a> for a step-by-step installation installation guide.


<b>After installation</b>

Create an account at AvDelphi so you can claim your feed and receive the benefits of an ADSB contributor.  Sign-up at https://www.avdelphi.com/login

Once your feed script is running you can check if we can see your feed at https://www.avdelphi.com/myfeed.html

Once we see your data flowing for a while, you will get an automatic account status bump to 'ADSB Contributor' status. 

To verify that a feed is controlled by you, visit https://www.avdelphi.com/claim_feed.html from the same IP as you are sending from, or run the following command on the machine you are sending from. 

wget -q -O /tmp/claim_status.log https://www.avdelphi.com/ext/claim_feed_adsb.php?uid=your_email_address_here ; cat /tmp/claim_status.log 

  or

curl https://www.avdelphi.com/ext/claim_feed_adsb.php?uid=your_email_address_here

Be sure to use the same email address you signed up to AvDelphi with. 
Watch for the mesasge <b>OK Your feed has been claimed</b> 

Start watching your planes at https://www.avdelphi.com/track

Check out the special spotter modes in the config popup as well as radar scope mode and spotsky for a live narrated view of any airport with coverage.
