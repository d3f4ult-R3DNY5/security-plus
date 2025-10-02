### Server side Request Forgery
---
Server-side request forgery (SSRF) attacks exploit a similar vulnerability but **instead of tricking a user's browser into visiting a URL, they trick a server into visiting a URL based on user-supplied**
**input.** SSRF attacks are possible when a **web application accepts URLs from a user as input** and then retrieves information from that URL.