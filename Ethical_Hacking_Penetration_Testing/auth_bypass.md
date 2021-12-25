** OTP Bypass
Cause: 
  1. Verifying the code at client side only.
  2. Checking only whether otp is right or wrong.
  3. allowing logging into true or false condition.

Steps: 
  1. Sign up on the website application.
  2. Enter any no in the otp verification.
  3. Intercept the request using burp suit.
  4. Modify the response saying incorrect otp to correct otp.
  5. Check the status on the webpage, if account is getting created then the otp bypass vulnerability exists on the webpage.
  
