 `#BugBountyTips 👉 If you're hunting for low-hanging bugs in source code, grep and regex can help you to identify hotspots. 

For example, you might find basic rXSS in PHP with something like this:

grep -r ""echo.*\$_\(GET\|REQUEST\|POST\)"" . `

** source: https://twitter.com/Bugcrowd/status/1520253611795755008 **

