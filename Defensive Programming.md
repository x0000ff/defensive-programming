autoscale: true  
slidenumbers: true  
theme: Next, 3

# [fit] Defensive
# [fit] Programming[^*]

<br/>

```swift
let author = "Konstantin Portnov"
let github = "github.com/x0000ff"
```

<br/>

![inline 60%](./img/logo.png)

![right](http://www.universityobserver.ie/wp-content/uploads/2017/04/Nokia_3310_front_side.jpg)

[^*]: Nokia 3310

---

## Why Nokia 3310?
### September 1, 2000

![inline](https://memegenerator.net/img/instances/52709117/my-love-for-you-is-like-nokia-3310-unbreakable.jpg)

https://en.wikipedia.org/wiki/Nokia_3310

---

![inline](http://images.ahoranoticias.cl/2017/02/14/190313_7_58a32a404b519.jpg)

> http://images.ahoranoticias.cl/2017/02/14/190313_7_58a32a404b519.jpg

---

![inline](http://i.computer-bild.de/imgs/4/3/7/6/7/3/8/Nokia-3310-745x559-37dcbd46bb4f4a7b.jpg)

> http://i.computer-bild.de/imgs/4/3/7/6/7/3/8/Nokia-3310-745x559-37dcbd46bb4f4a7b.jpg

---

![inline](http://www.panmedia.com.jm/files/images/blog/12-reasons-nokia-3310/nokia_3310.jpg)

> http://www.panmedia.com.jm/files/images/blog/12-reasons-nokia-3310/nokia_3310.jpg

---

![inline](http://i0.kym-cdn.com/photos/images/facebook/000/232/787/4aa.jpg)

> http://i0.kym-cdn.com/photos/images/facebook/000/232/787/4aa.jpg

---

![inline](https://img.memecdn.com/nokia-3310-a-weapon_o_195512.jpg)

> https://img.memecdn.com/nokia-3310-a-weapon_o_195512.jpg

---

![inline](https://pics.me.me/iphone-samsung-nokia-3310-17000637.png)

> https://pics.me.me/iphone-samsung-nokia-3310-17000637.png

---

## Why?

# 😐

---

# 😱 5522 crashes

**NSInvalidArgumentException**

```objectivec
-[__NSCFConstantString containsString:]: 
unrecognized selector sent to instance 0x3b34bae0
```

![right](./img/bugsnag-ios.png)

---

# JavaScript

![inline](./img/bugsnag-js.png)

---

# Whatever

![inline](./img/bugsnag.png)

---

# 🤔

---

# What’s the problem?

Part of JSON response 

![inline](./img/json.png)


---

# 🤔

---

# Code Complete
## `Steve McConnell`

![right](./img/code-complete.jpg)

---

# Do Not Ignore Errors & Warnings

![inline](./img/warnings.png)

---

# 👻

## “The whole point of defensive programming is guarding against errors you don’t expect”

    - Page 197, “Code Complete”

---

# 🕵🏻 
# Check Input Data

---

# Check Input Data

![inline](./img/castle.jpg)

---

# Check Input Data

![inline](./img/enemies.png)

---

# 👮🏻
# “Barricade Your Program to Contain the Damage Caused by Errors”.

    - Page 203, “Code Complete”

![right](./img/trump-barricades.jpg)

---

# Create Safe Areas

## Barricades are a damage-containment strategy.

One way to barricade for defensive programming purposes is to designate certain interfaces as boundaries to “safe” areas. Check data crossing the boundaries of a safe area for validity, and respond sensibly if the data isn’t valid.

---

# Create Safe Areas[^*]

![inline](./img/code-complete-204.png)

[^*]: Page 204, “Code Complete”

---

# Convert input data to the proper type at input time

| External | Internal |
|---|---|
| JSON | Model Object |
| `ok` | true
| `failed` | false |
| `4.300` | 4.3 |
| `3 USD` | `{ [Amount] Value: 3; Currency: USD }` |

---

# 💩
# Garbage IN
# Garbage OUT

---

# No one crash in Production

![inline](./img/crash.jpg)

---

# But! Make errors annoying

![inline](./img/crash.jpg)

---

# Code Complete
## `Steve McConnell`
### Chapter 8: Defensive Programming

![right](./img/code-complete.jpg)


---

# Q & A
# 🤔

---

# Thanks a lot!

☺️

![30% right fit](./img/thanks.jpg)

---

# **Me...**

![right 50%](./img/me.jpeg)

- ![:inline:](./img/me.jpeg) Konstantin Portnov 

- ![:inline:](./img/favicon.ico) [http://about.me/x0000ff](http://about.me/x0000ff)

- ![:inline:](./img/github.png) [https://github.com/x0000ff](https://github.com/x0000ff)

- ![:inline:](./img/twitter.png) [https://twitter.com/x0000ff](https://twitter.com/x0000ff)

- ![:inline:](./img/linkedin.png) [https://www.linkedin.com/in/KonstantinPortnov](https://www.linkedin.com/in/KonstantinPortnov)

---

# This Presentation
# 🙂
# http://bit.ly/2zZkCCD

---

# EOF
# 🍻