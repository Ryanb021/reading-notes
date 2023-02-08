# Class 13

## Local Storage And How To Use It On Websites [Source](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)

The main problem with HTTP as the main transport layer of the Web is that it is stateless. This means that when you use an application and then close it, its state will be reset the next time you open it. If you close an application on your desktop and re-open it, its most recent state is restored. This is why, as a developer, you need to store the state of your interface somewhere. Normally, this is done server-side, and you would check the user name to know which state to revert to. But what if you don’t want to force people to sign up? This is where local storage comes in. You would keep a key on the user’s computer and read it out when the user returns.

## What information should not be stored in local storage?

-Links to bootstrap
-Links to jQuery
-Links to Vue, React, Angular, etc.
-Links to any ad network code
-Links to Google Analytics
-Links to any tracking code
-Personal Identifiable Information
-Credit/Debit Card Information
-User name and Passwords to important sites

## Don’t Store JSON Web Tokens in Local Storage [Source](https://www.rdegges.com/2018/please-stop-using-local-storage/)

Using local storage in modern browsers is ridiculously easy. All you have to do is modify the localStorage object in JavaScript. You can do that directly or (and this is probably cleaner) use the setItem() and getItem() method:

![storage1](https://user-images.githubusercontent.com/120413183/217624672-5157a3ed-0110-40ee-b249-6f5bc0942268.png)

If you read out the favoriteflavor key, you will get back “vanilla”:

![storage2](https://user-images.githubusercontent.com/120413183/217624710-688e57b2-174f-473b-96b8-af9d7a07fc69.png)

To remove the item, you can use — can you guess? — the removeItem() method:

![storage3](https://user-images.githubusercontent.com/120413183/217624744-c16de58b-7e6b-4e15-859b-42fbcf70800d.png)

That’s it! You can also use sessionStorage instead of localStorage if you want the data to be maintained only until the browser window closes. [Source](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)
