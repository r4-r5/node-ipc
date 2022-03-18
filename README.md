Foreword
================
Since **Brandon Nozaki Miller** (or [RIAEvangelist](https://github.com/RIAEvangelist)) can no longer be trusted, I would remove all dependencies not only on the node-ipc repository itself, but on all others maintained by this guy.

The explanation below is copied from [IdealismIncinerator/node-ipc](https://github.com/IdealismIncinerator/node-ipc/blob/ae9b64d4ba5725bcc9ecd68101d3a26befb4712d/README.md)

node-ipc
================

A great solution for overwriting all of your files with a passive-aggressive shithead's symbol for "love" and "peace"!

Thank you, **Brandon Nozaki Miller** (or [RIAEvangelist](https://github.com/RIAEvangelist)) for your backwards logic, hypocrisy, and feeble attempts to cover up your literal crimes.

![Protestware is Adware](https://raw.githubusercontent.com/IdealismIncinerator/node-ipc/master/BANNER.png)

*And unsarcastically, thank you to KiwiFarms for the various sources used here.*

## The Malware

[This commit was discovered and unobfuscated.](https://gist.github.com/BrandonMiller97528/671a8bbb8da41ca34b30105db1edde1d)<br>
That large block of code is *malware.* What does it do? Well, simply:

- From a 50/50 random chance, it decides whether to stop executing.
- If it continues, it uses an online geolocation API to retrieve the user's location via their IP address.
- If the user lives in Russia or Belarus, it will proceed to recursively overwrite all of their files with a "❤️", effectively wiping the whole computer.

This is *obviously malicious* and, [coming from someone preaching "peace"](https://github.com/RIAEvangelist/peacenotwar), incredibly hypocritical.<br>
**Note:** The API key used for geolocation within `node-ipc` is no longer active; therefore, this malware no longer works, but was still responsible for affecting many innocent users while it was up.

## Geolocation, VPNs, and the Innocent

Of course, this is no attack against *just* Russian/Belarusian officials.<br>
This is a prejudiced attack of the citizens of the respective regions, and even those living in countries not responsible for Ukraine's invasion.

1. ["IP-based geolocation services provide 55 percent to 80 percent accuracy for a user's region or state."](https://www.if-so.com/geo-targeting/#:~:text=IP%2Dbased%20geolocation%20services%20provide,the%20location%20of%20the%20device.) Because of this, anyone even remotely close to Russia or Belarus were at risk of this malware.
2. Anyone using a VPN that places them with a Russian/Belarusian IP, although not living in said countries, was still at risk of this malware. This applies to people anywhere in the world who are completely unresponsible for the invasion.
3. In addition to this malware not even correctly targeting the Russian people and supposedly affecting people from other uninvolved countries, this malware actually actively *damages* the anti-war effort. By bricking the computers of Russian citizens, it is actively ruining their only chance of getting free, open, and most importantly, not Putin-approved information.

## A Major Victim

After a lot of this surfaced, Brandon was faced with major amounts of criticism (which is still ongoing as of 3/17/2022),
mostly people who were gravely, and undeservingly affected by this malware.

**Brandon attempted to cover up a large case in which he wiped war crimes recorded by a human rights organization stationed in Russia/Belarus.**

On top of that, he held no accountability for his actions, instead opting to antagonize said organization.

[Source](https://archive.ph/emyJb)

```
We are an American NGO based in Washington, D.C. that monitors human rights infringements
by authoritarian regimes in Belarus, Russia and other post-Soviet states.

Since our start in 2014, we have been in contact with over 2,500 whistleblowers
that provided us with detailed reports on various kinds of abuse happening there.

Due to internet censorship there, one of the web services used to contact us securely was hosted on servers located inside Belarus.
Normally, we backup the received content to an external server on 20th day of every month,
as this is reasonable given the volume we usually get,
but since the start of the invasion on February 24th, traffic to our web service has increased over fiftyfold.

Our staff has been working round the clock to accomodate the influx and during one of their tasks,
package containing node-ipc module was updated on a production server,
which resulted in executing your code and wiping over
30,000 messages and files detailing war crimes commited in Ukraine by Russian army and government officials.

Due to the way the files were stored on the server, we are not able to recover any data and it's most likely gone forever.
For some of the senders, this might as well have been their last contact with the outside world,
as many of them were front-line soldiers that could've been killed in action during the offensive.

Personally, me and my colleagues are absolutely devastated.
All I can say that your little shenanigan did more damage to us than Putin or Lukashenka ever could.
Profesionally, our counsel suggested filing criminal charges federally and it's likely we'll be proceeding this way.
```

Brandon's response?

![@bdsmith72 imagine if this was a real attack what your NGO could have gone through. Shore up your security, please.](https://raw.githubusercontent.com/IdealismIncinerator/node-ipc/master/chrome_hA4M7c4h4E.png)

This is a dismissal of responsibility, and as a later commenter said, he is "blaming the victim for \[his\] own bad behavior."

## More Cover-Ups

For a few more examples of Brandon trying to cover-up his crimes (and argue that his code isn't malicious, amongst other things), I've given a few sources and screenshots:

[Source 1](https://github.com/vuejs/vue-cli/issues/7054) [Source 2](https://github.com/RIAEvangelist/node-ipc/issues/233)

Multiple replies to an issue were deleted by Brandon, including information given by @MidSpike (who, funnily enough, he credits as coming up with the term "protestware," although being completely against it) that exposed `node-ipc` as malware.

![Brandon censoring all naysayers](https://user-images.githubusercontent.com/159840/158437949-c56a9713-f639-4619-8a87-b81e56288777.png)

He also stated the following:

- `It's not really possible to run that code. It poses no threat, but it does look scary for sure.`
- `Can confirm no malicious code.`
- `Also I don't think you understand the code you were referring to. It is not possible for that code to overwrite user files.`
- `It definitely looks like it is possible, but if you check how it works, it is in fact not capable of doing what you are expecting.`

These are blatant lies constructed to distract from his wrongdoing.

## What Do I Do?

You may continue to use `node-ipc` *if* you absolutely require it. IdealismIncinerator recommends using an older version of it that does not include his aforementioned "protestware" `peacenotwar` project as a dependency, as to not burden your users.

And one last message: **Brandon Nozaki Miller should never be trusted again.**
