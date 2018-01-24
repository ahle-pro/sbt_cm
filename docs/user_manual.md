## How to do that ?




## Issues

### I cannot connect to the eyetracker from HN Pro platform, what to do ?

In some cases, Happy Neuron Pro cannot connect to the Eyetracker service due to the constraints by [same origin policy](https://developer.mozilla.org/en-US/docs/Web/Security/Same-origin_policy).

Solution: change the protocol HTTPS to HTTP to help the HN Pro could connect to the eyetracker.

For example:

| http://www.scientificbraintrainingpro.fr/  | OK   |   |
|--------------------------------------------|------|---|
| https://www.scientificbraintrainingpro.fr/ | Fail |   |
 
 NOTE: after login, the site automatically changes to HTTPS protocol. It should be changed to HTTP for working.
 
 Useful information:
 [How to know HTTPS or HTTP in browser ?](https://www.howtogeek.com/292076/how-do-you-view-ssl-certificate-details-in-google-chrome/)
