# whois-app

whois in the browser because reasons
(a la https://who.is )

This repo has been modified to work in a Google Cloud AppEngine instance.

So running ./AppEngineDeployment.sh will start the deployment process.

To Build Locally:

go build should automatically do everything

run the binary webserver

go to localhost:8080

alternatively host on an actual server

type in host and get whois information on it

Lots of credit to Domain Research LLC for implenting whois in Go!
