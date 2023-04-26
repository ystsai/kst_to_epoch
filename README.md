# KST to Epoch Time converter

KST to Epoch Time converter takes a given time in Korean Standard Time (KST) and converts it to Epoch or Unix time. 

Why? Discord makes messaging about time easy with [a markdown for Unix Timestamp](https://discord.com/developers/docs/reference#message-formatting-timestamp-styles). Most online Epoch Time converters I've seen take UTC or local time as input. But Kpop events are given in KST. Unless the message writer lives in the KST timezone, finding the Epoch Time involves converting KST to UTC or local time, then converting to Epoch  with existing websites. This webpage simplifies the process in one step.

This started as a simple script I wrote in Python for my own use. Then I thought about ways to make it available online.

### Components 

Single HTML file, [Bootstrap](https://getbootstrap.com/) for a clean front-end, [Pyodide](https://pyodide.org) to run Python inside JavaScript 