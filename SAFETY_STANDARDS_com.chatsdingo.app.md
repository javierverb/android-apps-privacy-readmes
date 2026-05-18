# ChatsDingo — Safety & Security Standards (CSAE / Child Safety)

**Application:** ChatsDingo (Android)  
**Package name:** `com.chatsdingo.pymobi`  
**Document version:** 1.0  
**Effective date:** May 18, 2026  
**Published at:** https://github.com/javierverb/android-apps-privacy-readmes/blob/main/SAFETY_STANDARDS_com.chatsdingo.app.md

---

## 1. Purpose

This document describes ChatsDingo’s **published safety and security standards**, including our position on **child sexual abuse and exploitation (CSAE)** and related material (sometimes referred to as CSAM or CSEM). It is published externally so users, families, platform partners, and authorities can review our standards without installing the App.

ChatsDingo is an **IRC client**. It connects your device to **third-party IRC networks** that we do not operate. We do not run a central chat server, message archive, or social graph on our own infrastructure.

---

## 2. Zero tolerance for child sexual abuse and exploitation

We have **zero tolerance** for child sexual abuse and exploitation in connection with the App.

You must **not** use ChatsDingo to:

- Create, request, share, store, advertise, or distribute child sexual abuse material (CSAM) or any sexual content involving minors.
- Groom, solicit, or exploit minors in any way.
- Facilitate trafficking, extortion, or coercion involving minors.
- Use the App in any manner that violates laws protecting children.

Violations may result in **reports to law enforcement and child-safety organizations**, cooperation with IRC network operators, and any other action permitted by law. Because we do not host IRC traffic on our servers, enforcement on the network side is primarily the responsibility of the **IRC network operator** and **competent authorities**; we support that process as described below.

---

## 3. Age requirement

ChatsDingo is intended **only for adults aged 18 and over**.

Before using the App, users must confirm that they are **18 years or older** and accept our Terms of Service and Privacy Policy. We do not knowingly target or permit use by children. If we learn that a minor has used the App, we will take appropriate steps, including assisting with removal of locally stored App data and supporting reports to guardians or authorities where appropriate.

---

## 4. How the App works (relevant to safety)

| Aspect | ChatsDingo practice |
|--------|---------------------|
| Message routing | Direct client connection to IRC networks chosen by the user |
| Content hosting | **We do not host** user messages on ChatsDingo-operated servers |
| Moderation | **We do not moderate** IRC channels or private messages; IRC networks and channel operators do |
| Session data | Chat content exists in app memory during an active session; we do not maintain a central archive |
| Local storage | Blocked nicks, network preference, and channel-list cache on device only |

Users must understand that **other IRC users and network operators** control what appears in channels and private messages. Safety also depends on **each IRC network’s rules**, channel modes, and operator actions.

---

## 5. User safety features in the App

We provide tools to help users protect themselves on device:

- **Age and terms gate:** 18+ confirmation and acceptance of Terms and Privacy Policy before access.
- **Block / unblock contacts:** Users can block IRC nicks locally; blocked users are stored only on the device.
- **Leave channel / close private chat:** Users can leave a channel or close a query at any time.
- **Disconnect from IRC:** Users can log out of the IRC session from settings.
- **Transparency in the App:** Users are informed that content comes from third-party IRC networks and that we do not moderate IRC.

These features **do not replace** reporting to IRC operators or law enforcement when illegal or harmful activity occurs.

---

## 6. Prohibited conduct (summary)

In addition to CSAE prohibitions, users must not use the App to harass, threaten, defraud, distribute malware or spam, impersonate others to harm them, or violate applicable law or IRC network rules. Full rules are in our [Terms of Service](https://raw.githubusercontent.com/javierverb/android-apps-privacy-readmes/refs/heads/main/README_com.chatsdingo.app.md).

---

## 7. Reporting child safety concerns and illegal content

Because ChatsDingo does not operate IRC servers, **reports about messages or users on IRC should be directed as follows:**

### 7.1 On the IRC network

1. Note the **IRC network** (e.g. IRC-Hispano, Libera.Chat, OFTC), **channel name**, **nick(s)**, **date/time (UTC)**, and **relevant logs** if you have them safely.
2. Contact that network’s **abuse / security team** or channel operators using the procedures published on the network’s website.
3. Use the network’s tools (e.g. `/msg ChanServ`, operator mail, abuse@ addresses) as documented by that operator.

### 7.2 To law enforcement and child-safety hotlines

If you believe a child is in immediate danger, **contact local emergency services first**.

For CSAM or exploitation concerns, also report to appropriate authorities, for example:

| Region | Resource |
|--------|----------|
| **United States** | [NCMEC CyberTipline](https://report.cybertip.org/) — 1-800-843-5678 |
| **European Union** | National hotline via [INHOPE](https://www.inhope.org/EN/report) |
| **Spain** | [Internet Segura for Kids](https://www.internetsegura.org/) / national police |
| **Mexico** | [Te Protejo México](https://www.teprotejomexico.org/) |
| **International** | [INHOPE member hotlines](https://www.inhope.org/EN/report) |

### 7.3 To the ChatsDingo developer

For **App-specific** safety issues (e.g. vulnerabilities, misuse of the client, questions about this policy):

**Email:** [Contact Email]

Include: app version, Android version, IRC network name, description of the issue, and whether you have already reported to the IRC network or police. **Do not attach CSAM** in email; report media to law enforcement or NCMEC/INHOPE using their secure channels.

We will review good-faith reports and cooperate with lawful requests from authorities within the limits of data we actually hold (typically minimal, as we do not host IRC content).

---

## 8. Developer commitments

We commit to:

1. **Maintaining this published standard** and updating the effective date when material changes are made.
2. **Designing the App** without features intended to evade network bans for abuse or to facilitate distribution of illegal material.
3. **Requiring adult age confirmation** before use.
4. **Prohibiting CSAE** in our Terms of Service.
5. **Responding to valid legal process** and good-faith safety reports related to the App.
6. **Complying with Google Play’s Developer Program Policies**, including child safety and user-generated content requirements, for distribution on Google Play.
7. **Not using the App or related systems** to solicit, store, or transmit CSAM.

We **do not** commit to real-time monitoring of IRC traffic because we do not receive that traffic on our servers.

---

## 9. Cooperation with authorities and platforms

We will cooperate with **law enforcement** and recognized **child protection organizations** when we receive valid legal requests or credible reports related to the App, subject to applicable law and the data available to us.

We support **Google Play’s policies** on child safety and will provide this document’s URL in Play Console as our externally published CSAE standards.

---

## 10. Security practices (general)

- **Transport:** Default network presets may use unencrypted IRC (port 6667). Users who need confidentiality should use networks and configurations that support TLS, where available.
- **Credentials:** NickServ passwords are handled by the IRC network; users should use strong, unique passwords.
- **Device security:** Users should keep Android updated and avoid sharing devices with untrusted parties.
- **Personal data:** Do not share addresses, financial data, or images with untrusted IRC contacts.

More detail is in the [Privacy Policy](https://raw.githubusercontent.com/javierverb/android-apps-privacy-readmes/refs/heads/main/README_com.chatsdingo.app.md).

---

## 11. Changes to these standards

We may update this document. The **effective date** at the top will change when we do. Continued publication at the same repository path constitutes the current version.

---

## 12. Related documents

- [Privacy Policy & Terms of Service](https://raw.githubusercontent.com/javierverb/android-apps-privacy-readmes/refs/heads/main/README_com.chatsdingo.app.md)

---


*This document is published for Google Play Console “Safety standards” / CSAE disclosure and for public reference. It does not constitute legal advice.*
