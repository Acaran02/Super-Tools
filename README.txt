================================================================
ANTI-CAPCHA GOOGLE SITE SEARCH JAVASCRIPT BOOKMARKLET
================================================================

PROBLEM: 
After certain amounts of "site" searches, Google throws you a 'Capcha' page before you can continue searching. Sometimes it throws several consecutive Capcha pages before allowing you to proceed.

SOLUTION: 
Javascript Bookmarklet that rotates through 51 Google Englisht Country Codes (CCTLDs) to minimize Capcha pages when site searching.

NOTES:
math.floor(math.random()); - used to randomize CCTLD generation
Array Object carries 51 CCTLDs in total
Special Prompt function allows user to specify what they want to site search prior to Opening Google SERP.

================================================================
