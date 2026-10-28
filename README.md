# 402Bypass - methods for bypass 402 protocols

💸  We found multiple ways to bypass the 402 paywalls!

"402 Payment Required" sat unused for ± 30-ish years;  Now, the protocols reviving it let us skip the paying part, and we show how in our new research article ‟Breaking HTTP (pay)walls (https://neplox.security/research/breaking-http-paywalls)”

 
▶️ 🔗  Read the Article:  neplox.security/research/breaking-http-paywalls
 


⏩Here's how paywalls in TypeScript / Go / Java served paid content for free:

1️⃣  [ PAY TO WHOEVER (https://neplox.security/research/breaking-http-paywalls#paying-to-whoever-yourself-say) ]
        (*️⃣including yourself!  )

x402 verify() checked the amount, the asset and the network; but not the recipient. What if we rewrite payTo in the console and payTo ourselves?


2️⃣  [ PAY FOR WHATEVER (https://neplox.security/research/breaking-http-paywalls#paying-for-whatever-getting-the-best) ]
        (*️⃣still get what you want!  )

MPP credential proves an invoice was paid, not what for. What if we pay 1 sat for /cheap, but spend it on the 100 sat /expensive?


3️⃣  [ DO NOT PAY AT ALL! (https://neplox.security/research/breaking-http-paywalls#not-paying-at-all) ]

The middleware prices one path, the server serves another;  & here is just 1 example out of many:

GET https://neplox.security/premium HTTP/1.1
Host: app.example

HTTP/1.1 200 OK
{"served": "PREMIUM CONTENT"}


*️⃣As you can see, every issue described negated the entire purpose of these products, even though they are "classic" Web2 problems;
