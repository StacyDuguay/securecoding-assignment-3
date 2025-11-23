### How did the AppScan CodeSweep scan performance compare to the previous code scanners you used?

Codesweep seems to be better at detecting secrets and insecure communication. It found 
the hardcoded credentials and the insecure http request while bandit caught the os injection, 
sql injection and using http instead of https. Once again it found some but not all which
is why you should never trust any one scanner.