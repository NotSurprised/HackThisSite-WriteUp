# HTS Javascript 7

Let's see the source:

![](https://i.imgur.com/uSklNG8.png)

It seems a obfucate javascript as the title.

Let's find a online javascript deobfucate tool:

![](https://i.imgur.com/H9hAmkJ.png)

The answer should be `j00w1n`.

---

Well, this time it's something strange that there's a shortcut to take the flag out.

![](https://i.imgur.com/kM8oaC3.png)

Yes, dev tool. It seems a mistake that javascript obfucate function should not use javascript to print within the HTML onclick action.

As a HTML code, it will be translated from Hex to ASCII that make obfucate useless.

It should be remained as javascript function and more complicated algorithm like encrypt input with odd name function or parameter, then set onclick action to trigger the encrypt function.