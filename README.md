# Awesome-OSINT-Notes

- OSINT stands for Open Source Intelligence: it's a process of collecting and analyzing the publicly available information

# 📂 OSINT Notes – Index

A structured collection of OSINT resources and notes.

## 📑 Index

* [Full OSINT File](./OSINT/OSINT.md)

1. [Search Engines OSINT](./OSINT/01.%20Search%20Engines%20OSINT.md)
2. [DB Breach & Leak](./OSINT/02.%20DB%20brech%20&%20leack.md)
3. [Fake Identity](./OSINT/03.%20Fack%20Identity.md)
4. [SOCMINT](./OSINT/04.%20SOCMINT.md)
5. [Username OSINT](./OSINT/05.%20Username%20OSINT.md)
6. [People OSINT](./OSINT/06.%20People%20OSINT.md)
7. [Email OSINT](./OSINT/07.%20Email%20OSINT.md)
8. [Phone OSINT](./OSINT/08.%20Phone%20OSINT.md)
9. [Image OSINT](./OSINT/09.%20Image%20OSINT.md)
10. [Map OSINT](./OSINT/10.%20Map%20OSINT.md)
11. [Website OSINT](./OSINT/11.%20Website%20OSINT.md)
12. [OSINT Reporting](./OSINT/12.%20OSINT%20Reporting.md)
13. [OSINT Overview](./OSINT/OSINT.md)



# **🕵️ OSINT Tools & Resources – Complete Mega Index**

---

## **1. Digital Identity / Covert Accounts**

| Tool                       | Purpose                                                      | Link                                                                                            |
| -------------------------- | ------------------------------------------------------------ | ----------------------------------------------------------------------------------------------- |
| Fake Name Generator        | Creates full fake identities (name, DOB, email, phone, etc.) | [fakenamegenerator.com](https://www.fakenamegenerator.com/)                                     |
| This Person Does Not Exist | AI-generated human faces (not real people)                   | [thispersondoesnotexist.com](https://thispersondoesnotexist.com/)                               |
| This Person Not Exist      | Alternate AI fake profile generator                          | [thispersonnotexist.org](https://thispersonnotexist.org/)                                       |
| Fastmail                   | Secure private email, useful for puppet accounts             | [fastmail.com](https://www.fastmail.com/)                                                       |
| Mint Mobile SIM            | US prepaid SIM card for burner numbers                       | [BestBuy](https://www.bestbuy.com/site/mint-mobile-prepaid-sim-card-starter-kit-gold/6310601.p) |
| Lebara SIM                 | EU prepaid SIM card provider                                 | [lebara.nl](https://www.lebara.nl/en/home.html)                                                 |

---

## **2. Social Media OSINT (SOCMINT)**

| Tool                      | Purpose                                                    | Link                                                                                                                                                                                       |
| ------------------------- | ---------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Find ID FB                | Extracts Facebook profile numeric ID                       | [findidfb.com](https://findidfb.com/)                                                                                                                                                      |
| User-Agent Switcher       | Spoofs mobile/desktop for hidden Instagram data            | [Chrome](https://chromewebstore.google.com/detail/user-agent-switcher-and-m/bhchdcejhohfmigjafbampogmaanbfkg) / [Firefox](https://www.mozilla.org/en-US/firefox/download/thanks/?s=direct) |
| IG Follower Export Tool   | Exports Instagram followers/following to Excel             | [Extension](https://chromewebstore.google.com/detail/ig-follower-export-tool-i/kicgclkbiilobmccmmidfghnijgfamdb)                                                                           |
| Download All Images       | Bulk download Instagram images                             | [Extension](https://chromewebstore.google.com/detail/download-all-images/nnffbdeachhbpfapjklmpnmjcgamcdmm?hl=en)                                                                           |
| Unfurl Tool               | Expands TikTok/Twitter/LinkedIn URLs into IDs & timestamps | [dfir.blog/unfurl](https://dfir.blog/unfurl/)                                                                                                                                              |
| Freetik                   | Download TikTok videos without watermark                   | [freetik.co](https://freetik.co/)                                                                                                                                                          |
| Snapchat Story Downloader | Download public Snapchat stories                           | [snap.storyclone.com](https://snap.storyclone.com/)                                                                                                                                        |
| Snapcode Avatar           | Fetch avatar image from Snap username                      | `https://app.snapchat.com/web/deeplink/snapcode?username=USERNAME&type=SVG`                                                                                                                |

---

## **3. Username OSINT**

| Tool        | Purpose                                           | Link                                                 |
| ----------- | ------------------------------------------------- | ---------------------------------------------------- |
| ID Crawl    | Finds linked accounts from a username/email/phone | [idcrawl.com](https://www.idcrawl.com/)              |
| WhatsMyName | Searches usernames across hundreds of platforms   | [GitHub](https://github.com/WebBreacher/WhatsMyName) |
| Blackbird   | AI-powered reverse search of usernames/emails     | [GitHub](https://github.com/p1ngul1n0/blackbird)     |

---

## **4. People OSINT**

| Tool                    | Purpose                                             | Link                                                                            |
| ----------------------- | --------------------------------------------------- | ------------------------------------------------------------------------------- |
| FamilySearch            | US public records and genealogy                     | [familysearch.org](https://www.familysearch.org/en-united-states/)              |
| NamSor                  | Predicts origin/gender from names                   | [namsor.app](http://namsor.app/)                                                |
| FastPeopleSearch        | Reverse lookup (names, phones, addresses – US only) | [fastpeoplesearch.com](https://www.fastpeoplesearch.com/)                       |
| Nuwber                  | Aggregates public records (US only)                 | [nuwber.com](https://nuwber.com/)                                               |
| FastBackgroundCheck     | Provides addresses, DOB, relatives (US only)        | [fastbackgroundcheck.com](https://www.fastbackgroundcheck.com/)                 |
| ThatsThem               | Directory search (US only)                          | [thatsthem.com](https://thatsthem.com/)                                         |
| Radaris                 | Public info aggregator (US only)                    | [radaris.com](https://radaris.com/)                                             |
| VoterRecords            | Voter registration data (US only)                   | [voterrecords.com](https://voterrecords.com/)                                   |
| VoteRef                 | Public voter registration lookup (US only)          | [voteref.com](https://voteref.com/)                                             |
| BlackBook Voter Records | State voter DB directory (US)                       | [blackbookonline.info](https://www.blackbookonline.info/USA-Voter-Records.aspx) |
| Amazon Baby Registry    | Search baby registries                              | [amazon.com/baby-reg](https://www.amazon.com/baby-reg/search-results)           |
| Amazon Wedding Registry | Search wedding registries                           | [amazon.com/wedding](https://www.amazon.com/wedding/search)                     |
| MyRegistry              | Global gift registry                                | [myregistry.com](https://www.myregistry.com/search/)                            |
| TheKnot Registry        | Wedding registry                                    | [theknot.com](https://www.theknot.com/registry/couplesearch)                    |
| Target Registry         | Gift registry (US Target stores)                    | [target.com/registry-kiosk](https://www.target.com/registry-kiosk)              |

---

## **5. Email OSINT**

| Tool                    | Purpose                                 | Link                                                                                                             |
| ----------------------- | --------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| Email Permutator        | Generates likely email combos           | [metricsparrow.com](http://metricsparrow.com/toolkit/email-permutator/)                                          |
| Experte Email Finder    | Validates possible emails               | [experte.com](https://www.experte.com/email-finder)                                                              |
| ContactOut              | Extracts hidden LinkedIn emails         | [Extension](https://chromewebstore.google.com/detail/email-finder-by-contactou/jjdemeiffadmmjhkbbpglgnlgeafomjo) |
| SignalHire              | Find LinkedIn/GitHub emails & numbers   | [Extension](https://chromewebstore.google.com/detail/signalhire-find-email-or/aeidadjdhppdffggfgjpanbafaedankd)  |
| GetProspect             | LinkedIn-based email discovery          | [Extension](https://chromewebstore.google.com/detail/email-finder-getprospect/bhbcbkonalnjkflmdkdodieehnmmeknp)  |
| Hunter.io               | Finds company email formats             | [hunter.io](https://hunter.io/dashboard)                                                                         |
| Phonebook.cz            | Email search by domain                  | [phonebook.cz](https://phonebook.cz/)                                                                            |
| Dehashed                | Breach data search (credentials, leaks) | [dehashed.com](https://dehashed.com/)                                                                            |
| LeakPeek                | Find leaked accounts                    | [leakpeek.com](https://leakpeek.com/)                                                                            |
| BreachDirectory         | Search leaks database                   | [breachdirectory.org](https://breachdirectory.org/)                                                              |
| Epieos                  | Reverse email lookup                    | [epieos.com](https://epieos.com/)                                                                                |
| CastrickClues           | OSINT lookup for emails & usernames     | [castrickclues.com](https://castrickclues.com/)                                                                  |
| PredictaSearch (Paid)   | Shows sites where email is registered   | [predictasearch.com](https://www.predictasearch.com/)                                                            |
| Gravatar Email Check    | Find linked Gravatar profiles           | [gravatar.com](https://gravatar.com/site/check)                                                                  |
| OSINT.Industries (Paid) | Email search across 300+ sites          | [osint.industries](https://www.osint.industries/)                                                                |
| GHunt Online            | Gmail OSINT (profile, GAIA ID, reviews) | [gmail-osint.activetk.jp](https://gmail-osint.activetk.jp/)                                                      |

---

## **6. Phone Number OSINT**

| Tool                           | Purpose                              | Link                                                                             |
| ------------------------------ | ------------------------------------ | -------------------------------------------------------------------------------- |
| Truecaller                     | Caller ID & spam detection           | [truecaller.com](https://www.truecaller.com/)                                    |
| Sync.me                        | Reverse phone lookup                 | [sync.me](https://sync.me/)                                                      |
| Numlookup                      | Free reverse phone search            | [numlookup.com](https://www.numlookup.com/)                                      |
| Spydialer                      | Caller info & voicemail access       | [spydialer.com](https://www.spydialer.com/)                                      |
| CallerID Test                  | Lookup unknown caller IDs            | [calleridtest.com](https://calleridtest.com/)                                    |
| OldPhoneBook                   | Search old US phone records          | [oldphonebook.com](https://oldphonebook.com/)                                    |
| TruePeopleSearch               | People & phone lookup (US)           | [truepeoplesearch.com](https://www.truepeoplesearch.com/)                        |
| FastBackgroundCheck            | Phone lookup (US only)               | [fastbackgroundcheck.com](https://www.fastbackgroundcheck.com/)                  |
| ThatsThem                      | Reverse lookup (US only)             | [thatsthem.com](https://thatsthem.com/)                                          |
| Nuwber                         | US phone + people search             | [nuwber.com](https://nuwber.com/)                                                |
| IntelTechniques Telephone Tool | Phone-based OSINT                    | [inteltechniques.com](https://inteltechniques.com/tools/Telephone.html)          |
| HaveIBeenZuckered              | Check Facebook breach exposure       | [haveibeenzuckered.com](https://haveibeenzuckered.com/)                          |
| PhoneInfoga                    | Advanced phone number reconnaissance | [PhoneInfoga](https://sundowndev.github.io/phoneinfoga/getting-started/install/) |

---

## **7. Image OSINT**

| Tool                   | Purpose                                 | Link                                                                             |
| ---------------------- | --------------------------------------- | -------------------------------------------------------------------------------- |
| Google Images          | Reverse image search across the web     | [google.com/images](https://www.google.com/imghp?hl=en&ogbl)                     |
| Bing Images            | Reverse search & product detection      | [bing.com](https://www.bing.com/)                                                |
| Yandex Images          | Strong face & text recognition          | [yandex.com/images](https://yandex.com/images/)                                  |
| TinEye                 | Image source & modified image detection | [tineye.com](https://tineye.com/)                                                |
| Numlookup Image Search | Free reverse image lookup               | [numlookup.com](https://www.numlookup.com/reverse-image-search)                  |
| Search4Faces           | Facial recognition OSINT                | [search4faces.com](https://search4faces.com/)                                    |
| PimEyes                | Find similar faces online               | [pimeyes.com](https://pimeyes.com/en)                                            |
| FaceCheck              | Reverse face search                     | [facecheck.id](https://facecheck.id/)                                            |
| CyberChef              | Forensics & data/image processing       | [gchq.github.io](https://gchq.github.io/CyberChef/)                              |
| GeoSpy                 | AI-based image geolocation              | [geospy.ai](https://geospy.ai/)                                                  |
| EXIF Tools             | Extract hidden image metadata           | [exif.tools](https://exif.tools/)                                                |
| Metadata2Go            | Online metadata viewer                  | [metadata2go.com](https://www.metadata2go.com/)                                  |
| EXIF Viewer (Firefox)  | Browser metadata viewer                 | [Firefox Extension](https://addons.mozilla.org/en-US/firefox/addon/exif-viewer/) |

---

## **8. Map OSINT**

| Tool                  | Purpose                                  | Link                                                                                                                                            |
| --------------------- | ---------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Google Maps           | Maps, traffic, Street View               | [maps.google.com](https://www.google.com/maps/?authuser=3)                                                                                      |
| Bing Maps             | Maps + Bird’s Eye View                   | [bing.com/maps](https://www.bing.com/maps?cp=23.061248%7E72.587722&lvl=11.4)                                                                    |
| Yandex Maps           | Strong coverage in Russia/Eastern Europe | [yandex.com/maps](https://yandex.com/maps/?ll=10.854186%2C49.182076&z=4)                                                                        |
| Satellites Pro        | Switch between Google/Apple/Yandex maps  | [satellites.pro](https://satellites.pro/)                                                                                                       |
| KartaView             | Street-level crowdsourced imagery        | [kartaview.org](https://kartaview.org/landing)                                                                                                  |
| Mapillary             | Street imagery contributed by users      | [mapillary.com](https://www.mapillary.com/)                                                                                                     |
| Bellingcat OSM Search | Find landmarks/features with OSM         | [osm-search.bellingcat.com](https://osm-search.bellingcat.com/)                                                                                 |
| Bellingcat How-To     | Tutorial on OSM geolocation              | [bellingcat.com](https://www.bellingcat.com/resources/how-tos/2023/05/08/finding-geolocation-leads-with-bellingcats-openstreetmap-search-tool/) |
| Google Earth          | Historical and 3D satellite views        | [google.com/earth](https://www.google.com/earth/about/versions/)                                                                                |

---

## **9. Website OSINT**

| Tool                        | Purpose                             | Link                                                                                                                                                                                                                              |
| --------------------------- | ----------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| WHOIS Lookup                | Domain owner info                   | [who.is](https://who.is/)                                                                                                                                                                                                         |
| Reverse WHOIS               | Find related domains                | [osint.sh/reversewhois](https://osint.sh/reversewhois/)                                                                                                                                                                           |
| Reverse Domain Lookup       | Domain investigations               | [osint.sh/domain](https://osint.sh/domain/)                                                                                                                                                                                       |
| Wappalyzer                  | Detect website tech stack           | [Chrome](https://chromewebstore.google.com/detail/wappalyzer-technology-pro/gppongmhjkpfnbhagpmjfkannfbllamg?hl=en) / [Firefox](https://addons.mozilla.org/en-US/firefox/addon/wappalyzer/) / [osint.sh](https://osint.sh/stack/) |
| Subdomain Finder            | Discover hidden subdomains          | [osint.sh/subdomain](https://osint.sh/subdomain/)                                                                                                                                                                                 |
| CRT.sh                      | Certificate transparency subdomains | [crt.sh](https://crt.sh/)                                                                                                                                                                                                         |
| DNSDumpster                 | DNS mapping                         | [dnsdumpster.com](https://dnsdumpster.com/)                                                                                                                                                                                       |
| DNSHistory                  | Track DNS changes                   | [osint.sh/dnshistory](https://osint.sh/dnshistory/)                                                                                                                                                                               |
| ViewDNS                     | DNS analysis & OSINT tools          | [viewdns.info](https://viewdns.info/)                                                                                                                                                                                             |
| Reverse Analytics Search    | Find sites with same GA ID          | [dnslytics.com](https://dnslytics.com/reverse-analytics/) / [hackertarget.com](https://hackertarget.com/reverse-analytics-search/)                                                                                                |
| Wayback Machine             | View archived/deleted websites      | [archive.org](https://archive.org/)                                                                                                                                                                                               |
| FOCA                        | Extract metadata from public docs   | [GitHub](https://github.com/ElevenPaths/FOCA)                                                                                                                                                                                     |
| .NET Framework 4.7.1        | FOCA dependency                     | [dotnet](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net471)                                                                                                                                                     |
| Microsoft XML Parser        | FOCA dependency                     | [ms.com XML](https://www.microsoft.com/en-us/download/details.aspx?id=26999)                                                                                                                                                      |
| Microsoft Core XML Services | FOCA dependency                     | [ms.com CoreXML](https://www.microsoft.com/en-us/download/details.aspx?id=42299)                                                                                                                                                  |

---

## **10. OSINT Reporting**

| Tool                  | Purpose                        | Link                                                          |
| --------------------- | ------------------------------ | ------------------------------------------------------------- |
| OSINTracker           | Create OSINT relationship maps | [osintracker.com](https://www.osintracker.com/)               |
| OSINT Flowcharts      | Visualize OSINT processes      | [inteltechniques.com](https://inteltechniques.com/osintbook/) |
| MyOSINT Training Yoga | Pre-made OSINT workflows       | [yoga.myosint.training](https://yoga.myosint.training/)       |

