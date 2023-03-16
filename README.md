<h1>Search Engine Hacking</h1>

<h2>Description</h2>
In this lab, I learned how search engines work and generally how we can abuse this index scraped content to enumerate and filter for higher-quality results.
<br />


<h2>Operating System Used</h2>

- <b>Kali Linux</b> 

<h2>Program walk-through:</h2>

<p align="center">
First Search: 4,610,00 results. <br/>
<img width="1271" alt="Screenshot 2023-03-15 at 9 56 03 PM" src="https://user-images.githubusercontent.com/127968338/225489798-0a9937f6-c5f8-42a4-96e9-e6963fa1c6a2.png">
<br />
<br />
Second search: More precise results (8 results).  <br/>
<img width="1271" alt="Screenshot 2023-03-15 at 9 44 13 PM" src="https://user-images.githubusercontent.com/127968338/225489566-b27676dc-7737-4f1c-b978-dd53bd4fad7b.png">
Third Search: The "@" we have added in the search bar indicated we are looking for emails results. Let's click on the first result to see if there are any publicly exposed emails. <br/>
<img width="1271" alt="Screenshot 2023-03-15 at 10 03 49 PM" src="https://user-images.githubusercontent.com/127968338/225491283-8bb09433-2a80-419b-9276-2b5efc2ab656.png">
<br />
<br />
As we now see, there is a user called Dr Ktobin that has their email publicly exposed. Let's see if this user is on any other webpage. <br/>
<img width="1271" alt="Screenshot 2023-03-15 at 10 08 33 PM" src="https://user-images.githubusercontent.com/127968338/225491870-be85d952-5c8e-4fed-992f-bca6741337c1.png">
We have narrowed down our result to 1.
 <br/> <img width="1271" alt="Screenshot 2023-03-15 at 10 21 17 PM" src="https://user-images.githubusercontent.com/127968338/225493140-7bf13fd1-f03f-4eab-bc25-f3f17ad2bfeb.png">

<h2>Conclusion</h2>

- We have narrowed done and learned a new way to make search results more precise. However, it is important to know that many of the information that doesn't make it into search engines is the result of "security through obscurity". Information is hidden in an attemp to decieve or slow down an adversary. We will see more about this in upcoming projects.



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
