# Study on Secure Authentication in the Web 2.0 Ecosystem

This repository contains the latex source code for my bachelor thesis. The thesis is written in Italian and it is the result of the work I did during my internship at [Quindi](https://www.quindi.ai/).

## Abstract

Every day we share a vast amount of personal and confidential information through various web services, from social networks to banks. If these informations are not adequately protected by various authentication methods, they can become an easy target for cyberattacks. In fact, every account access, every online transaction, and even a simple login contain data that, if it falls into the wrong hands, could cause significant damage.

For several years now, access to protected online resources has become a very frequent process for most people, and we often don’t realize how important it is to protect our login credentials. A weak or reused password can become the element that a malicious actor could exploit to access sensitive information. And it’s not just a matter of passwords: the entire authentication process needs to be secure.

These methods, in addition to verifying the identity of a user before allowing access to protected resources, must also ensure that the data transmitted during the authentication process remains confidential and intact. But what are the protocols and technologies that make this possible? And how can we be sure that our information is truly protected when we access an online service?

This project aims to conduct a study capable of answering these questions by analyzing authentication through JSON Web Token (JWT) and the necessary protocols to ensure the complete security of the authentication process.

## Build

To build the thesis, you need to have a LaTeX distribution installed on your machine. You can compile the document using the following command:

```bash
latexmk thesis.tex
```
