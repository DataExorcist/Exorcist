# `E x o r c i s t`

Claim your privacy rights and exorcise your data from data brokers!

### Why I made this

while trying to clean up the mess of a digital footprint I have, I found that going through my saved passwords and going through the convoluted account deletion process or trying to email their privacy contact was difficult and often unreliable (When I say this I specifically am thinking of Ace Hardware, HP, and Facebook)

However, While trying to do this I stumbled across https://yourdigitalrights.org/ which had a simple to use tool to send email requests to companies for data deletion or requests. This tool greatly made things easier, but then I thought, what if I could automate this for every company in their database?

## What I want this organization (Exorcist) to be

Ideally, this will be a command line tool for all OSes to batch send emails using a users credentials (This is vital as it is how the company will see it is you, via the email headers.)

Perhaps in the future it will be hosted on a subdomain of my site, but I'm not to keen on handling other's email credentials anywhere on my server or site - even if not stored. Ideas on how to make this more streamlined are welcome. I've never written a GUI app.

I want anyone to be able to use this, including your grandmother.

## What exactly are we doing here?

I should say a lot of this is gonna be heavily based around https://yourdigitalrights.org/ works. I'm not trying to steal their thunder, I'm just making a simple way of automating it.

It's quite simple. We are running down a list of email addresses of broker companies (and in the future other data hoarders) and sending a filled in template. There will be APPI, CCPA, CPA, GDPR, DPA, LGPD, PIPEDA, and VCDPA templates. (More to be added as more come out.)
(These templates as of now will again, be stolen from yourdigitalrights.org, as I'm no lawyer)

## The S\*\*tlist:

Some companies will ignore these emails or direct you to a form on their site despite requesting not to. here is a known list, and if you find any more, please let me know so I can add them to the list.

-   [Paypal](https://www.paypal.com/)
-   [Twitter](https://twitter.com/)
-   [Advantage Credit Information](https://www.advcredit.com/)
-   [Advanced Background Checks](https://www.advancedbackgroundchecks.com/)
-   [Whitepages](https://www.whitepages.com/)
-   [Epsilon](https://www.epsilon.com/us)
-   [AllAreaCodes](https://www.allareacodes.com/)
-   [Amrent](https://www.amrent.com/)
-   [Lenovo](https://www.lenovo.com/us/en/)
-   [ADP](https://adp.com)
-   [Intelius](https://www.intelius.com/)
-   [NAI](https://thenai.org/)

## Some future plans - Ideas welcome

-   A GUI app for all OSes - if this happens totally do it with [Gluon](https://gluonjs.org/)
-   A website to do this all on (Probably via Oauth2)
