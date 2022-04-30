 
> #BugBountyTips 👉 If you're hunting for low-hanging bugs in source code, grep and regex can help you to identify hotspots. 
> For example, you might find basic rXSS in PHP with something like this:
> `grep -r ""echo.*\$_\(GET\|REQUEST\|POST\)"" .`

*source: https://twitter.com/Bugcrowd/status/1520253611795755008*

> Other PHP sources to grep for:
> ```
> $_COOKIE
> $_SERVER (for some keys, e.g. HTTP_ prefixed ones for headers)
> $_FILES for file uploads
> php://input and php://stdin for raw reading of POST bodies (e.g. in JSON or XML APIs)
> ```
> Example gf file for finding them: https://t.co/GDXTaBgRiJ

*source: https://twitter.com/TomNomNom/status/1520299005233803264*
