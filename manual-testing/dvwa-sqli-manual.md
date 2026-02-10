 Manual SQL Injection Testing – DVWA

### Objective
To understand how improper input validation can introduce SQL Injection vulnerabilities.

### Test Environment
- Kali Linux
- DVWA (Low security level)
- Local lab setup

### Testing Approach
1. Identified user input fields interacting with backend database
2. Entered unexpected input to observe application behavior
3. Compared normal and abnormal responses
4. Confirmed absence of proper input sanitization

### Observations
- Application behavior changed based on input
- Error messages and response differences were observed
- This indicated potential SQL Injection vulnerability
