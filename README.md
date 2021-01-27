# Beshcan

This project came to my mind when I had a feeling that maybe some services like [shecan](https://shecan.ir/) have something more than just bypass sanctions in their mind. We don't know what they are logging from us in their servers right now, even with DNS over TLS; I can't feel safe. However, few recent weeks (from the start of July 2020), we have severe censorship over DNS in Iran, based on [OONI](https://ooni.org/post/2020-iran-dot/), we don't have privacy and freedom on the internet. The government censored lots of websites and services for Iranians; on the other hand, the USA sanctioned Iran on many international services. We're sitting ducks and can't do much about it.

Don't forget that there is nothing we can't do :)

I came up with an idea after reading this tweet from [Iranian Offsec](https://twitter.com/offsecmag/status/1281320182313517058) about DNS over TLS/HTTPS, and this [article](https://arxiv.org/pdf/1906.09682.pdf) about DNS over Tor.

So let's talk about what I have in my mind. I want to make a **private DNS resolver for everyone on their private servers without logging and completely secure using DNS over HTTPS with random packet size to bypass censorship**.

I intentionally don't use any database for logging and error collecting; besides, I will explicitly redirect every log or error to `/dev/null/` or disable any logging functions or services for users' data privacy.

## Tools used on this project
- [ ] Docker and Kubernetes
- [ ] Reverse Proxy with NGINX or Envoyproxy
- [ ] Python or Go or Rust or C
- [ ] Scapy for Packet Manipulation

## Installation
:)

## Usage
:)

## Resources
1. DNS over HTTPS (DOH)
   - [RFC 8484](https://tools.ietf.org/html/rfc8484)
   - [Google Developers](https://developers.google.com/speed/public-dns/docs/doh)
2. DNS over TLS (DOT)
   - [RFC 7858](https://tools.ietf.org/html/rfc7858)
   - [RFC 8310: Usage Profiles for DOT](https://tools.ietf.org/html/rfc8310)
   - [Google Developers](https://developers.google.com/speed/public-dns/docs/dns-over-tls)
3. Other
   - [Using NGINX as a DoT or DoH Gateway](https://www.nginx.com/blog/using-nginx-as-dot-doh-gateway/)
   - [How To Host Your Own DNS-over-HTTPS And DNS-over-TLS Services](https://blog.technitium.com/2020/07/how-to-host-your-own-dns-over-https-and.html)

## Contributing
See [contributor's guide](./CONTRIBUTING.md) for more details.

## License
This project licensed under the GPL-3.0 License - see the [LICENSE](./LICENSE) file for details.
