# First-Hands-On-With-Burpsuit

Creating this repo for my first experience on Burpsuit, how I captured and even later modified HTTP request. I used Chat gpt to understand about this in detail.

---

## ⚙️ Tools Used
- Kali Linux (2025.1)
- Burp Suite (Community Edition)
- Firefox Browser (configured to use Burp Proxy)

---

## 🧪 What I Did

I was very confused with the tool first and took chat gpt's help here to what does what.. I did everything in the temporary project as I was just excited about it.
I then learnt about intercept, like how it helps us to understand every requests and responses being made for every new search/new page open. 
I Was first confused when I turned intercept on and wondered why the page is not loading... but saw a long list of GET requests in the HTTP history column. 
I then turned it off again. I then just tried searching "Hello World", That generated one GET request, I sent it to the repeater. 
I tried reading through the request And changed the "Hello World" to "Cybersecurity". and then sent it, the result was amusing as I got the new search in the render tab, but not on the firefox browser, which I was using for my actual search, as it still showed the search results for "Hello World".

I tried this 2 weeks ago but thought I should just make a blog about it and I will be exploring other tools too on Kali linux.

---

## 💡 What I Learned

- Burp Suite acts as a **man-in-the-middle** proxy to capture traffic between browser and server.
- The **Repeater** tool allows manual editing and replaying of requests.
- Modifying requests gives visibility into how web apps process user input.

---

## 🧠 Bonus Realization

Even though I changed the request manually, Burp **still sent it to the real server** — so it behaved like a browser without actually using one. This is the foundation for real-world web app testing.

---

This was my first exercise with Burp Suite and web application testing — just logging my journey as I go. Excited to learn more 😁

---
