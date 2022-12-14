# Google Click ID From Legacy Cookie

**Custom Variable Template for Server-Side Google Tag Manager**

Read existing client-side `_gcl_aw` cookie and returns stored click id

[![Template Status](https://img.shields.io/badge/Community%20Template%20Gallery%20Status-published-green)](https://tagmanager.google.com/gallery/#/owners/mbaersch/templates/legacy-click-id) ![Repo Size](https://img.shields.io/github/repo-size/mbaersch/legacy-click-id) ![License](https://img.shields.io/github/license/mbaersch/legacy-click-id)

---

## Usage
Create a new variable with this template. There is no configuration required. The variable will either extract an existing click id from a cookie, whenever a request gets processed and return the value. If no cookie is found or does not fit the expected format, the variable returns `undefined`. 
