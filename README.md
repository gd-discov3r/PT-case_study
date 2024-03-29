# WAPT-case_study
My findings

> #1 **Broken Link Hijacking**

Over here, there were employee pictures of the company with their LinkedIn accounts attached. Clicking on each employee's picture would redirect you to their respective LinkedIn accounts. While checking each account to ensure the redirection was correct, I encountered a 404 error indicating that one employee's LinkedIn account didn't exist. Surprisingly, I found two more accounts with the same 404 error.

As a hacker, one idea came to mind immediately. Let's claim those usernames associated with the 404 accounts and test if the company's page will now redirect everyone to our fake employee accounts using those usernames. To execute this plan, I asked my friend DK to create a LinkedIn account with one of the non-existing usernames, while I created another account with the remaining username. As expected, when we accessed the company's page, we were redirected to our fake employee LinkedIn accounts. It was quite an amusing outcome.
</br>
> Poc 1
[<img src="https://i.ytimg.com/vi/DMXnr0FqNmk/maxresdefault.jpg" width="50%">](https://www.youtube.com/embed/DMXnr0FqNmk "Poc : 1")     </br> > Poc 2 
[<img src="https://i.ytimg.com/vi/VjzGqnbjCK0/maxresdefault.jpg" width="50%">](https://www.youtube.com/embed/VjzGqnbjCK0 "Poc : 2")
</br>

> #2 **Csrf Client Side Request Forgery**
 
Cross-Site Request Forgery (csrf) attack targets the user to execute malicious requests on behalf of the attackeror we can say attack that forces authenticated users to submit a request to a Web application against which they are currently authenticated. 
</br>
>Poc 1
[<img src="https://i.ytimg.com/vi/7bTNMSqCMI0/maxresdefault.jpg" width="50%">](https://www.youtube.com/embed/eev99zyamS8 "Poc : 1")      </br> 

> #3 **Cross Site Scripting**

Cross-site scripting (xss) is an attack in which an attacker injects malicious executable scripts into the code of a trusted application or website.
</br>
>Poc 1
[<img src="https://i.ytimg.com/vi/VjzGqnbjCK0/maxresdefault.jpg" width="50%">](https://www.youtube.com/embed/ljr_cl4WAWI "Poc : 1")      </br> 
         
> #4 **Web Cache Poisoning Through Host Header Attack **
 
web cache poison The goal of poisoning the cache is to make the clients load unexpected resources partially or controlled by the attacker.The poisoned response will only be served to users who visit the affected page while the cache is poisoned. As a result, the impact can range from non-existent to massive depending on whether the page is popular or not.
</br>
>Poc 1
 [<img src="https://i.ytimg.com/vi/PO280MV8pmw/maxresdefault.jpg" width="50%">](https://www.youtube.com/embed/PO280MV8pmw "Poc : 1")      </br> 

> #5 **OTP Bypass - Bruteforce And Responce Manipulation **

Create a profile using a mobile no. that I don’t own? to ( Identity theft ) & get access to the account of a person, if all I know is their username or mobile number? When i entered the correct OTP and checking the Response to this Request. Response code is very simple HTTP/1.1 200 and “success” then i think let’s bypass OTP Verification.
</br>
>Poc 1 - Bruteforce
 [<img src="https://i.ytimg.com/vi/efqR1hs7B3A/maxresdefault.jpg" width="50%">](https://www.youtube.com/embed/efqR1hs7B3A "Poc : 1 Bruteforce")      </br> 
>Poc 2 - Responce Manipulation
 [<img src="https://i.ytimg.com/vi/vcliMO3VA4I/maxresdefault.jpg" width="50%">](https://www.youtube.com/embed/vcliMO3VA4I "Poc : 2 Responce Manipulation")      </br> 
>Poc 3 
 [<img src="https://i.ytimg.com/vi/-tP-Dohgqhc/maxresdefault.jpg" width="50%">](https://www.youtube.com/embed/-tP-Dohgqhc "Poc : 3")      </br> 
> #6 **Open Redirection**

An attacker could supply a URL that redirects an unsuspecting victim from a legitimate domain to an attacker's phishing site.
</br>
>Poc 1
[<img src="https://i.ytimg.com/vi/xtIe9f94LNw/maxresdefault.jpg" width="50%">](https://www.youtube.com/embed/tBaHuRQKtg8 "Poc : 1")     </br> 
> #7 **Parameter Tempering  **

Parameter tampering is a simple attack targeting the application business logic. This attack takes advantage of the fact that many programmers rely on hidden or fixed fields (such as a hidden tag in a form or a parameter in a URL) as the only security measure for certain operations.
</br>
>Poc 1
[<img src="https://i.ytimg.com/vi/xtIe9f94LNw/maxresdefault.jpg" width="50%">](https://www.youtube.com/embed/HeUdcGxZ0hE "Poc : 1")     </br> 
>Poc 2 
 [<img src="https://i.ytimg.com/vi/wHTYBIxLzw0/maxresdefault.jpg" width="50%">](https://www.youtube.com/embed/wHTYBIxLzw0 "Poc : 2 ")      </br> 
 > #8 **Cookies Hijacking**
 
Cookie hijacking is an attack in which cybercriminals steal your session cookies. Session cookies contain your session ID which is essentially what lets you log in to an online service. Cookie manipulation is the process through which they then forge cookies using your session ID to log in to your accounts.
</br>
>Poc 1
[<img src="https://i.ytimg.com/vi/yJEjtIxR4b8/maxresdefault.jpg" width="50%">](https://www.youtube.com/embed/yJEjtIxR4b8 "Poc : 1")     </br> 
