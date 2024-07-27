# Researching APT Groups

## Lazarus Group
- North Korean government’s Reconnaissance General Bureau (RGB).
- Known for:
  - Operation Troy
  - Hack of Sony Pictures
  - Operation Blockbuster
  - WannaCry
  - Crypto attack 2017

## LAPSU$$
[Who are Lapsus and what do they want?](https://www.zdnet.com/article/who-are-lapsus-and-what-do-they-want/)
- UK based, Teens who hacked GTA were 16,17.
- Grand Theft Auto hack of 2022, Microsoft Hack in 2022, and Okta.
- Data exfiltration of Nvidia, Data breach of Samsung stole its source code for Samsung Galaxy smartphones.
- Known for stealing source of Bing, Bing Maps, Cortana, GTA 5.
- Data exfiltration expertise.
- Main software used is mimikatz.

## Equation Group aka Shadow Brokers
[Chinese experts uncover details of Equation Group](https://thehackernews.com/2022/02/chinese-experts-uncover-details-of.html)
[Equation Group details](https://www.globaltimes.cn/page/202202/1252952.shtml)
- Been around for 2 decades.
- Has ties to NSA TAO (Tailored Access Operations) and intrusions tied to Lamberts which is the CIA.
- Known as the crown creator of cyber espionage, been active since 2001, has ties to Stuxnet.
- Shadow Brokers exposed its malware toolset.
- Operation Telescreen – cover backdoors used to monitor 45 countries over a decade, top of the line backdoor, the backdoor is well hidden and can self-destruct.

## Charming Kitten
[Charming Kitten Overview](https://www.clearskysec.com/charmingkitten/)
[APT Attacks](https://securityaffairs.co/wordpress/107644/apt/charming-kitten-apt-whatsapp-linkedin.html)
[APT Attacks Explanation](https://dzone.com/articles/apt-attacks-what-is-fancy-bear-charming-kitten-and)
- Iranian cyberespionage group – state-sponsored, APT 35.
- Known for phishing and impersonations.
- Attack Clearsky replicating its website.
- Uses sophisticated phishing techniques and backdoor trojan named Downpaper.
- Data exfiltration of 1TB of data of HBO workers.

## Fancy Bear
[APT Attacks Explanation](https://dzone.com/articles/apt-attacks-what-is-fancy-bear-charming-kitten-and)
- Established in 2004.
- Russian cyber espionage group.
- Known for email hacking the Democratic party to sway election results.
- Exploited two Microsoft zero days.
- Executed spear phishing to White House and NATO using Java zero day.
- Knocked the German parliament IT systems offline for a few days.

## Double Dragon
[APT41 Double Dragon](https://www.ontheblock.site/blog/apt41-double-dragon)
- Chinese APT group, APT 41.
- State-sponsored espionage and financial attacks for personal gains.
- Initially targeted the video game industry by changing in-game currency and stealing certificates from video game developers.
- Later started supply chain targeting by putting malicious code in legitimate software.
- Hacked a hotel network surveillance system before a China diplomat visited.
- Uses passive backdoors, known for a kernel rootkit component that acts like a listener.
- Bootkits – malicious code that targets the MBR or VBR, modifies that sector of the volume so when it initializes it will load the bootkit and components. The group uses ROCKBOOT.
- Dead Drop Resolver (DDR) C&C:
  - Attacker creates a valid user account on a third-party website.
  - Attacker embeds an encoded string with malware; the infected machine will call the third-party site.
  - Infected machine parses HTML code, looking for a delimiter that would point to the encoded malware; that encoded string contains the C2 server.

## APT1 (PLA UNIT 61398)
[Top Famous and Active APT Groups](https://medium.datadriveninvestor.com/top-famous-and-active-apt-groups-who-can-turn-life-to-a-nightmare-5d130168f43)
[Mandiant APT1 Report](https://web.archive.org/web/20130219155150/http://intelreport.mandiant.com/Mandiant_APT1_Report.pdf)
- Chinese cyber espionage unit 61398.
- Uses unique tools and techniques like GETMAIL and MAPIGET.
- Known for large data exfiltration.
- Operation Ghostnet, Aurora, Shady RAT:
  - Operation Aurora: The attack was aimed at dozens of other organizations including Adobe Systems, Akamai Technologies, Juniper Networks, Rackspace, Yahoo, Symantec, Northrop Grumman, Morgan Stanley, Dow Chemical, and BlackBerry.

## APT29 (COZY BEAR)
[APT Buyers Guide](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjR5ubHjov8AhWVIDQIHSseC4IQFnoECAsQAQ&url=https%3A%2F%2Fwww.gsa.gov%2Fcdnstatic%2FAPT_Buyers_Guide_v2_July_2022.pdf&usg=AOvVaw3Bj0WXFjTShh2j_wwbKXfN)
- Russian state-sponsored.
- Known for SolarWinds in 2020.
- Technically advanced and sophisticated attacks.
- Deploys backdoors and fixes it features, uses compromised servers for C2C.
- Uses social media sites like Twitter and GitHub.

## The Dukes
- Russian-based, APT 29.
- Targets government organizations in western countries via spear phishing campaigns.
- Group drops ISO disk images containing LNK, evades by using DLL side-loading, uses payload cobalt strike which fetches payload from Slack and Google Drive.

## Gamaredon
- One of the most active Russian APT groups.
- Targets Ukrainian government entities.
- Uses Telegram channels to get IP addresses to C2C servers and uses PowerShell to create malicious tool sets.

## SparklingGoblin
- Chinese-based APT, very active.
- Uses Linux backdoor based off of Sidewalk called Specter RAT.
- Targeted a university in 2022.
- Used a rootkit to get backdoors on IP cameras, NVR, DVR devices – rootkit called StealthyElf.
- Used CVE-2022-26134 to target a German-based food manufacturing company – leveraging Confluence vulnerability.
