<div style="display: flex; align-items: center;">
  <img src="https://github.com/furrofurry/Petals/blob/4fab0dad626ff1ca04f36a705defb185f7b502f7/images/petals.png" alt="Petals Logo" width="450" style="margin-right: 80px;">
  <h1 style="font-family: 'Arial', sans-serif;">Petals</h1>
</div>

<p style="font-style: italic;">Free as in Freedom</p>

---

Petals is a **strong bot and port scanner blocklist applier** designed to keep your infrastructure private and secure. By maintaining and applying an **individually curated blocklist**, Petals ensures that all scanners, including commercial ones, are treated as intruders. This proactive approach safeguards your systems from unauthorized access and potential abuse of your data by malicious actors or hackers in the future. With Petals, you can have peace of mind knowing that your infrastructure remains protected and you are not the first to fall victim to an attack.

## 🔒 **Why Petals?**

Petals offers comprehensive protection by applying a meticulously maintained blocklist that prevents malicious actors and automated tools from probing your network. This ensures that your infrastructure remains private and secure, reducing the risk of data breaches and abuse. Additionally, Petals prevents your IP from being listed on various intelligence databases that could lead to targeted attacks, making your infrastructure more invisible to potential threats. Continuously updated by dedicated maintainers, Petals stays effective against the latest threats, providing you with ongoing peace of mind.

## 🚫 **Why Not Use AbuseDB as the Main Blocklist?**

While AbuseDB is a valuable resource, it has several limitations that make it unsuitable as the primary blocklist for protecting your infrastructure:

- **Public Accessibility of Censys Data:** Censys, a commercial scanning tool, provides public access to its data, which can be exploited by malicious actors to identify and target vulnerable systems. In contrast, AbuseDB does not list Censys bots or other commercial scanners as intruders, which can lead to a false sense of security.

- **Commercial Scanners Not Blocked:** AbuseDB does not categorize commercial scanners like Censys as threats, meaning that legitimate scanning tools may not be adequately monitored. This oversight can allow bad actors to leverage these tools to gather intelligence on potential targets.

Petals addresses these concerns by maintaining a curated and private blocklist, ensuring that your infrastructure remains hidden from both legitimate and malicious scanners unless explicitly allowed.



### 🚫 **Avoiding Blacklisting Risks**
Public blocklists like SURBL can mistakenly blacklist your IP, especially with services like Cloudflare, disrupting access for legitimate users. The use of bot data for blacklisting increases the risk of false positives.

Petals addresses these issues with a private, curated blocklist that targets only malicious scanners, ensuring legitimate traffic remains unaffected and providing ongoing protection against the latest threats.
Continuously updated by dedicated maintainers, Petals stays effective against the latest threats, providing you with ongoing peace of mind.


## 📊 **Aggressive Scanners**

According to our data collection, the following domains are the most aggressive scanners on their respective networks:
(these bots are the ones that have PTR)

1. **googleusercontent.com**
2. **stretchoid.com**
3. **hinet.net**
5. **shadowserver.org**
6. **censys-scanner.com**
7. **binaryedge.ninja**
8. **ne.jp**
9. **internet-census.org**
10. **internet-measurement.com**
11. **net.tw**
12. **linodeusercontent.com**
13. **com.br**
14. **amazonaws.com**
15. **com.tr**
16. **criminalip.com**
17. **spectrum.com**
18. **shodan.io**

## 🌍 **Top Countries with Bot Activity**

Based on IP registrations as per ASN data, the following countries have the most bots. (incomming bot traffic):

1. 🇺🇸 USA
2. 🇬🇧 GB
3. 🇳🇱 NL
4. 🇨🇳 CN
5. 🇹🇼 TW
6. 🇰🇷 KR
7. 🇷🇺 RU
8. 🇩🇪 DE
9. 🇫🇷 FR
10. 🇹🇭 TH
11. 🇸🇬 SG
12. 🇭🇰 HK
13. 🇵🇱 PL
14. 🇧🇷 BR
15. 🇨🇦 CA
16. 🇧🇬 BG
17. 🇯🇵 JP
18. 🇸🇪 SE
19. 🇮🇹 IT
20. 🇮🇶 IQ
21. 🇹🇷 TR
22. 🇱🇹 LT

## 🚀 **Installation**

To get started with Petals, follow these simple steps:

```bash
# Clone the repository
git clone https://github.com/furrofurry/Petals.git

# Navigate to the Petals directory
cd Petals

# Install dependencies
pip install -r requirements.txt

# Run Petals
python petals.py
