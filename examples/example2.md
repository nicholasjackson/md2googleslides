---
{style="layout: 01 Main Title - Consul"}

# Security

## Nic Jackson

<!--
This only appears as a speaker note.
-->

---
{style="layout: 09 Section Title - Consul"}

# Why

<!--
Before we dive into the how I think it is really important to understand why, why do we need to secure our Kubernetes networking.  I mean we already have a perimeter firewall right, and we have a decent authentication layer which is protecting us from external threats.
-->

---
{style="layout: 14 Title at Top"}

## Easy to bypass the perimeter by attacking code

![](https://raw.githubusercontent.com/nicholasjackson/md2googleslides/custom_layout/examples/images/example2/bypass.png)

<!--
What if I told you that an attacker could quite possibly by pass that external defence, that they had the possibility to gain access to the internal network without even trying to touch external firewall but by looking for application code level vulnerabilities which allows them direct access to your internal systems?

You might believe me, you might say no chance, you might say I have heard about this approach but it would never happen to me we patch our systems regularly and take a secure code review of the application code we write. 
-->

---
{style="layout: 11-3 Code Editor"}

# Slides can have code

```javascript
// Print hello
function hello() {
  console.log('Hello world');
}
```
