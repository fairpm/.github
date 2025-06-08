# Frequently Asked Questions

: Last Updated: 8 June 2025

# General Questions

## How do I use this?

Our MVP product is a WordPress plugin, the FAIR Plugin. You can install it just like you would any other plugin.

You can download the latest version from the [FAIR Plugin releases page](https://github.com/fairpm/fair-plugin/releases).

## Does it matter to users where or how they get their WordPress downloads?

It's true that many users do not actively think about where they get WordPress. As caretakers of a significant part of the web, we aim to provide secure and reliable access for them so they don't have to care, while helping developers ensure the right code rolls out. Federating the WordPress ecosystem adds redundancy and resilience.

## Will you do X, Y,or Z?

We're always happy for more community members and outside voices to suggest future paths for FAIR. If you have an idea you'd like to share, post in our [ideas forum][https://github.com/orgs/fairpm/discussions/categories/ideas].

For more information on our process, read up on our [Technical Steering Committee](https://github.com/fairpm/tsc).

# Security and Reliability

We take security very seriously and believe that using FAIR will fortify the WordPress supply chain. Using signing and authentication, FAIR mitigates unapproved takeovers or nulling of plugins or themes, restoring trust in deliverables. 

One of the main reasons the FAIR project exists is to ensure that all WordPress users, regardless of their host, continue to have access to WordPress, theme and plugin updates. This will give developers and users confidence in the security of their software.

## Could FAIR increase the risk of a DDoS attack on WordPress.org?

No. The plugin and theme repository mirroring part of FAIR currently uses AspirePress, which caches plugins and themes, significantly reducing traffic to WordPress.org. Their mirror has been running without issue since the middle of January 2025. Other APIs, such as the events listing or BrowseHappy, fully replace the official ones. This effectively reduces load rather than increasing it, as many APIs are no longer sending any traffic to WordPress.org at all.

## If you use AspirePress, how does AspirePress handle load to avoid overwhelming WordPress.org?

AspireSync, used by AspirePress, employs strict rate-limiting (no more than 10 simultaneous requests) and pauses to minimize impact. WordPress.org also has its own traffic shaping measures to manage potential overloads.

The FAIR and AspirePress projects will allow anyone who wants to set up their mirror to get their initial data from us rather than from WordPress.org, to protect .org.

## How secure is FAIR compared to centralized hosting on WordPress.org?

FAIR and AspirePress incorporate rigorous security practices and leverage infrastructure like Fastly CDN for improved reliability and security. with the help of industry experts, we are continually adapting our security measures.

We look forward to actively collaborating with the WordPress.org Security Team to enhance overall supply chain security.

# Distribution

## How do I add my plugin for distribution?

Right now, there is no way to add your plugins (or themes) for distribution. Our current sole distribution node is AspirePress, which is a mirror of WordPress.org's directory.

## How will this distribution work?

The [FAIR Protocol](https://github.com/fairpm/fair-protocol) is being refined, but it is based on AtProto (used by BlueSky). We recommend familiarizing yourself with the documentation.

# Trust and Transparency 

FAIR is a project under the Linux Foundation, with an [open charter with open governance](https://lfx-cdn-prod.s3.us-east-1.amazonaws.com/project-artifacts/fair-package-manager/fair-package-manager_Charter.pdf?v=1749049715416). Any contributor can become part of the Technical Steering Committee, and members of the TSC vote for the co-chair leadership.

## Why should we trust the FAIR project?

The FAIR project's core team includes experienced and respected contributors from the broader WordPress community. FAIR is governed transparently under the Linux Foundation, with open participation and independent oversight through the Technical Steering Committee (TSC).

## Has the FAIR team been sufficiently transparent?

Transparency has always been a fundamental goal. The project was initially developed privately, which is common practice to allow necessary early-stage discussions. The announcement itself has created the openness that the team has been working to create  and invites wider participation. FAIR’s governance under the Linux Foundation ensures accountability.

## Why was confidentiality important in the early stages of FAIR?

Confidentiality was necessary to protect early contributors who expressed concerns about potential professional repercussions or criticism. FAIR respects contributor confidentiality, especially given past documented challenges within the WordPress community environment.

# Analytics and Telemetry

## How does FAIR affect analytics and telemetry data?

Initially, download and install stats may experience minor inaccuracies due to decentralized data gathering. This is not new, as there are already existing mirror setups at several large hosts. FAIR is actively developing solutions to consolidate and improve the reliability and transparency of telemetry data, addressing issues already present with these existing mirror setups. See the Analytics section of our protocol docs for more information.

# Reviews and Ratings

## How does FAIR handle plugin reviews and ratings?

Currently, FAIR uses existing data from WordPress.org. Future plans include exploring an open and interoperable ratings system, ensuring authenticity and reliability of reviews and ratings.

