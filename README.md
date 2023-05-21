# PT-case_study
My findings

#1 **Broken Link Hijacking**
<br>
<br>
Over here, there were employee pictures of the company with their LinkedIn accounts attached. Clicking on each employee's picture would redirect you to their respective LinkedIn accounts. While checking each account to ensure the redirection was correct, I encountered a 404 error indicating that one employee's LinkedIn account didn't exist. Surprisingly, I found two more accounts with the same 404 error.

As a hacker, one idea came to mind immediately. Let's claim those usernames associated with the 404 accounts and test if the company's page will now redirect everyone to our fake employee accounts using those usernames. To execute this plan, I asked my friend DK to create a LinkedIn account with one of the non-existing usernames, while I created another account with the remaining username. As expected, when we accessed the company's page, we were redirected to our fake employee LinkedIn accounts. It was quite an amusing outcome
Poc 1
[<img src="https://i.ytimg.com/vi/DMXnr0FqNmk/maxresdefault.jpg" width="50%">](https://www.youtube.com/embed/DMXnr0FqNmk "Poc : 1")                             Poc 2 [<img src="https://i.ytimg.com/vi/VjzGqnbjCK0/maxresdefault.jpg" width="50%">](https://www.youtube.com/embed/VjzGqnbjCK0 "Poc : 2")

