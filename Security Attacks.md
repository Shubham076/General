### CSRF
Csrf also known as XSRF, is an attack where an attacker tricks a user into unknowingly submitting a request to a web application on which the user is authenticated. This can lead to unauthorised actions being performed on the application, such as changing account details or initiating transactions. The attacker exploits the trust that the application has in the user’s browser, and the attack typically occurs on the client-side, hence it is often referred to as client-side request forgery.

### SSRF
SSRF On the other hand, is an attack where an attacker tricks the server into making requests to other servers or resources within the internal network. This can lead to unauthorised access to internal resources, data leakage, or even remote code execution. The attacker exploits the trust that the server has in itself or other internal systems.


The key difference in CSRF vs SSRF lies in their targets and attack vectors. CSRF targets the user’s browser and exploits the trust that the application has in the user, while SSRF targets the server and exploits the trust that the server has in itself or other internal systems. Both attacks can have severe consequences, and it is crucial to implement proper security measures to protect against both CSRF and SSRF attacks.
