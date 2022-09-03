# State of DRM in 2022

![DRM](https://i.imgur.com/pW6R9un.jpg)

Digital rights management, better known as DRM, is the use of technology to control and manage access to copyrighted material and intellectual property from theft or misuse. The core aim of DRM is to safeguard the rights of copyright holders and prevent content from unauthorized distribution, modification, and use.

According to the [US Chamber of Commerce](https://www.ibc.org/trends/digital-piracy-costs-us-economy-30bn-annually/4037.article), online piracy costs the US economy about $30 billion and over 200,000 jobs annually. People rarely want to pay for something that they can get for free. DRM is a flexible and effective solution to protect copyrighted materials from unauthorized access.

In this article, you will learn about DRM; what it is, why it is important, as well as its evolution. You will also get familiar with the different ‌DRM systems (and their platform support) and DRM encryption types. The article also highlights how DRM is a mess right now and recommends [Gumlet](https://gumlet.com), one of the latest DRM solutions for video content creators.

## Why DRM is Important

As entertainment and media entities distribute their content to the global audience, some of this content spreads through torrent sites, peer-to-peer file sharing platform, and online piracy. DRM is a necessity to help content creators and media companies to not only guard against piracy and copyright infringements but also protect against cybersecurity challenges ‌all entities face.

DRM enables content creators (musicians, authors, and moviemakers, and others) to clarify and control what users can and cannot do with their material. Using DRM, content creators/owners can protect their copyrighted material, safeguard their financial and creative investment, and prevent people from stealing or sharing their media illegally. This is critical for safeguarding copyright and intellectual property.

## The evolution of DRM

In 1998, the United States ratifies the Digital Millennium Copyright Act (DMCA), sanctioning against illegal access and use of copyrighted works. The European Copyright Directive passed on May 22, 2001 to protect copyrighted works. In 2001, Apple released its iPod, preventing users from freely transferring MP3 files. This defined one of the earliest forms of DRM measures. Apple stored music files on servers, safeguarding the content using encrypted IDs.
Fast forward to today, many industries worldwide use a similar system to help content creators and publishers protect their digital intellectual property and copyrights.

## How DRM works

While copyright laws aim to prevent unauthorized access, sharing, distribution, and modification of digital content, it is challenging to monitor the internet continuously for illegal activity. DRM provides a solution by putting measures in place to protect digital content.

DRM typically uses encryption technologies to prohibit content copying or limit the access of a product on different devices. Content creators can also deploy applications that control what users can or cannot do with their material.

DRM allows content creators and copyright holders to:

- Prohibit or limit users from accessing and sharing paid content.
- Automatically blocks or limits user access to content after expiry dates
- Limit specific devices from accessing media based on factors such as IP address, locations, and time, e.t.c.
- Assert ownership and identity of documents and images using watermarks.

## Types of DRM systems

DRM offers content creators/owners high control over who can access their content. There is a wide range of DRM systems in the market today. Some of the common DRM systems include Google’s Widevine Modular, Microsoft’s PlayReady, and Apple’s FairPlay. The following sub-sections provide details on some of these systems.

### Google Widevine Modular

Google deploys its Widevine Modular system in Chrome web browsers and Android devices. Widevine Modular is like Microsoft's PlayReady. It uses MPEG-DASH with CENC, with AES-128 in CTR and CBC modes. Content vendors don't need to download additional files to support it.

**The advantages of Widevine DRM***

* Offers reliable protection across multiple platforms and devices
* Supports sped up decryption, which reduces CPU usage and enables playback of Ultra High Definition content on low-end devices.
* Standardized media container formats (MP4 and WebM)
* HTML5-compatible; supports complete control and flexibility and is compatible with legacy devices.

**Demerits of Widevine DRM**

Widevine's browser support is an L3 level security. Google continues to upgrade this innovation to newer versions.

### Apple FairPlay

Apple's Fairplay offers some capabilities as other DRM offerings, but with an additional ‌flexibility. However, this comes with the cost of increased complexity of implementation. FairPlay only works in Apple products, requires a registered Apple developer to set-up, and can only support streaming HLS video. Regarding technology, FairPlay uses the AES-128 encryption in CBC mode, MPEG2, and fragmented MP4 containers. Apple's use of CBC mode requires a local installation of additional files on your storage. In addition, FairPlay does not provide out-of-the-box capabilities, such as offline play. Thus, an entity will need to build these from scratch.

**Advantages of FairPlay DRM**

* Flexible to support entity rules under licence requests.
* Offers strong security for major Hollywood studios and leading broadcasters.
* Supports rapid deployment.

**Demerits of FairPlay DRM**

It's difficult to convert HLS audio and video it into other file formats.

### Microsoft PlayReady

Microsoft’s PlayReady DRM, introduced in 2007, is one of the most popular DRM technologies in the market. The system supports MPEG-DASH with AES-128 in both CTR and CBC modes and supports fragmented MP4 containers. Microsoft deploys PlayReady to web environments, Smart TVs, and web-enabled devices. PlayReady offers sophisticated rights management, supports pre-distribution of licenses, offline viewing, and time-based licences. PlayReady covers all the benefits that Google's Widevine and Apple's FairPlay offer.

**Advantages of PlayReady DRM**

- Widely used globally, proven and scalable.
- Offers secure delivery, with each client having their own unique licence.
- Offers flexible business models for content creators/owners.
- Supports multiple platforms including Android, iOS, and windows.
- Supports multi-codec modes such as H.26, H.264, and H.265.

**Demerits of PlayReady DRM**

Initial set-up can be complex and sometimes can have slow runtimes.

## DRM Encryption Algorithms

There are various DRM technologies that video publishers can choose from. The general approach is to consider a system's strength of protection and its barriers to reaching users. Besides influencing user experience, there are technology costs to consider, such as the additional cost of development and maintenance of complex workflows. More advanced systems have richer features, like TVE and offline viewing. You need to consider these factors before committing to a particular system.

### AES-128
The Advanced Encryption Standard (AES) is an encryption method for safeguarding content from hackers or pirates. Companies use AES in various technologies around us, for example, messaging apps like WhatsApp. While AES-128 is one of the most secure video encrypting techniques, it does not guarantee complete security. Its strength depends on the security of content keys. Without a secure way of exchanging content keys, AES-128 does not protect content.

### SAMPLE-AES

While AES-128 encrypts the whole segment (using a 128-bit key), SAMPLE-AES allows fine grained encryption modes. It encrypts blocks over which the protection process is required.

### DASH Clear Key Encryption
DASH Clear Key encryption is an interface built on Encrypted Media Extensions (EME). DASH eliminates the need for third party plugins like Adobe Flash to play HTML5 videos. DASH Clear Key can deliver MPEG-DASH content. The Media Presentation Duration (MPD) contains all the relevant information needed for decryption. 

### HLS with FairPlay

A HTTP Live Streaming (HLS) stream is an adaptive video stream that keeps playing without buffering. This technology protects videos streamed on iOS devices, Apple TV, and in Safari on macOS.

### Multi-DRM with MPEG-CENC

Different customers watch content on different browsers and platforms. This means that content providers must use multiple DRM encryptions, in parallel, to support full coverage across all devices. To allow for full coverage, content providers use the MPEG Common Encryption (MPEG-CENC) standard. MPEG-CENC allows for the efficient use of multiple DRM encryptions. This works by allowing developers to create multiple DRM encryptions on a single video, leaving the video player to decide which encryption to activate based on the platform and/ or browser in use. However, Apple devices and browsers do not support MPEG-CENC. Instead, they require HLS packaging.

### CMAF and CENC with ClearKey

The Common Media Application Format (CMAF) is a combination of currently available and tested tools from the MPEG body of technologies. CMAF aims to eliminate the problem of holding multiple versions of the same content because of different container formats and encryption modes. CMAF uses Common Encryption (CENC) for encryption mode and fragmented MP4 for container format. Currently, all playback platforms support CMAF. Arguably, it is a major step towards encoding, packaging, and storing content in a single copy.
CMAF can significantly reduce content delivery time or latency, hence reducing cost and improving user experience.
**Browser and Device support for DRM**

The table summarizes browser and device support for DRM. While most technologies do roughly the same thing, there are some minor variations — mostly based on device and browser.

![Browser and Device support for DRM](https://i.imgur.com/CVwzCDI.png)

From the table, ‌DRM is still messy. There need for a unified approach across platforms. You can find more details from this [community](https://websites.fraunhofer.de/video-dev/is-this-the-end-of-cenc-an-overview-of-drm-codec-support-in-2021/).

## CENC and CBCS

The Common Encryption Scheme (CENC) specifies standard encryption and key mapping methods for DRM systems. If DRM systems support CENC, these systems can decrypt any content as long as they use the same key IDs and content keys. This allows content providers to serve the same content encrypted once to a broader range of devices using different DRM systems. While PlayReady and WideVine support both CENC and CBCS, Apple only supports CBCS. The good thing is that CBCS is available across devices today.

## What are the Pros and Cons of DRM

### Pros of DRM

- Restriction of copyrighted material safeguards the rights of the copyright holder against piracy.
- Preventing illegal sharing of content ensures that content creators and owners benefit from their investment.
- DRM also benefits consumers by providing features that protect vulnerable groups, such as minors, from accessing disturbing content.

### Cons of DRM

- DRM can limit users from rightfully using the content as they wish, despite legitimately purchasing it.
- DRM can adversely affect revenue, as consumers shy away from secured content.
- Some DRM techniques may intrude on customer privacy by collecting personal information.
- Consumers pay for securing content with DRM at high prices.
- DRM systems are not foolproof. Hackers can crack almost all DRM systems.
- DRM can limit access to content that is even in the public domain.

The debate over DRM shows no signs of abating ‌soon. Developers need to focus on improving DRM technologies to make them as user-friendly as possible, while mitigating the inconveniences of piracy.

## Conclusion

In this article you learned ‌DRM is a highly complicated subject. There are many factors to consider, from technical and enterprise perspective. These include cost, complexity, user experience, and, of course, content protection. The article covered various DRM platforms and technologies and their adoption on different devices and browsers. The article concluded with an overview of the pros and cons of DRM. Indeed, the debate on DRM still rages. There is a need to make DRM technologies more user-friendly, while strengthening their ability to ward-off pirates.

[Gumlet](https://gumlet.com) a video processing and streaming platform that allows content creators to make eye-catching, optimized videos easily. Gumlet also provides detailed insights on video engagements from viewers. Gumlet offers three products:

- Gumlet Video,
- Video Insights, and
- Image optimization

Gumlet fully manages solutions for developers, content creators, brands, and companies to deliver innovative user experience across devices globally. Gumlet serves over a billion media files daily and has a client base of over 6,000 customers. 
