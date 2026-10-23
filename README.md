# mars-
A tool that exploits a vulnerability in Facebook to reveal the name associated with a phone number; the exploit has an 88% success rate and was developed by me.

The tool functions by generating random cookies and tokens. It then sends a request to Facebook’s password reset endpoint, inputting the provided phone number. The server’s response will contain the name of the account linked to that number. If no name appears, or if the tool returns the same phone number as the output, it indicates that no account is linked to that number.
