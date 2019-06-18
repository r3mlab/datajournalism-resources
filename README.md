# datajournalism-resources

A compilation of links to datajournalism & OSINT tools, guides and resources I find useful to keep at hand. PRs welcomed!

<small>by [r3mlab](https://github.com/r3mlab) | License: [CC-BY-NC 4.0](LICENSE)</small>

#### Legend:
- :globe_with_meridians: = online tool/service/database
- :computer: = software
- :book: = guide/tutorial
- :pencil: = list of tools/resources
- :snake: = Python module
- 💲 = paid or paid-only tool/service

## Contents
- [APIs](#apis)
- [Archival](#archival)
- [Breached Data](#breached-data)
- [Companies](#companies)
- [Data Analysis & Manipulation](#data-analysis--manipulation)
- [Email](#email)
- [Lists of tools & resources](#lists-of-tools--resources)
- [Location, Maps, Satellite Imagery](#location-maps-satellite-imagery)
    - [Interpretation](#interpretation)
    - [Mapping services & software](#mapping-services--software)
    - [Tools & techniques](#tools--techniques)
    - [User generated content](#user-generated-content)
- [Military/Weapons](#militaryweapons)
- [Multi-purpose tools](#multi-purpose-tools)
- [News](#news)
- [Phone numbers](#phone-numbers)
- [Pictures, Photos, Videos](#pictures-photos-videos)
    - [Pictures Metadata](#pictures-metadata)
    - [Reverse search](#reverse-search)
    - [Search](#search)
    - [Verification & Analysis](#verification--analysis)
- [Social Networks](#social-networks)
    - [All/General](#all-general)
    - [Discord](#discord)
    - [Facebook](#facebook)
    - [Github](#github)
    - [Instagram](#instagram)
    - [Linkedin](#linkedin)
    - [Reddit](#reddit)
    - [Snapchat](#snapchat)
    - [Telegram](#telegram)
    - [Twitter](#twitter)
    - [VKontakte](#vkontakte)
    - [Youtube](#youtube)
- [Text & Documents](#text--documents)
    - [Documents Metadata](#documents-metadata)
    - [Indexing & searching](#indexing--searching)
    - [PDF](#pdf)
    - [OCR](#ocr)
    - [Text Processing & Analysis](#text-processing--analysis)
- [Transportation](#transportation)
    - [Containers & Shipments](#containers--shipments)
    - [Planes](#planes)
    - [Ships](#ships)
- [Visualization](#visualization)
    - [Graphs](#graphs)
    - [Maps](#maps)
    - [Mindmaps & Network graphs](#mindmaps--network-graphs)
    - [Timelines](#timelines)
- [Weather](#weather)
- [Websites](#websites)
    - [Dark Web & Onion services](#dark-web--onion-services)
    - [Scraping](#scraping)
    - [Searches, info, related entities](#searches-info-related-entities)
- [Misc](#misc)


## APIs
- [Postman](https://www.getpostman.com/) :computer: - API development environment offering useful tools for crafting and debugging API requests.
- [ProgrammableWeb](https://www.programmableweb.com) :pencil: - A good API directory.
- [Public APIs](https://github.com/abhishekbanthia/Public-APIs) :pencil: - A categorized list of APIs.

## Archival

-  [archive.today](https://archive.fo/) :globe_with_meridians: - Saves pages as screenshots, useful for websites the WayBack Machine can't handle.
-  [Firefox Screenshots](https://screenshots.firefox.com/) :computer: - Firefox can take a screenshot of a full page (i.e. 'scrolling' screenshot).
-  [How to Archive Open Source Materials](https://www.bellingcat.com/resources/how-tos/2018/02/22/archive-open-source-materials/) :book: (Bellingcat)
-  [Hunch.ly](https://www.hunch.ly/) :globe_with_meridians:💲 - Web capture tool designed for online investigations ($129.99/y).
- [Internet Archive Wayback Machine](https://web.archive.org/) :globe_with_meridians:
    -  [waybackpack](https://github.com/jsvine/waybackpack) :computer::snake: - Command-line utility & Python library to download content from the Wayback Machine. See [this example](https://www.bellingcat.com/resources/2016/12/06/vacuuming-image-metadata-wayback-machine/).
- [view-page-archive](https://github.com/dessant/view-page-archive) :computer: - Browser extension to search for a page's archives on 15+ web archival/caching sites.


## Breached Data
- [Breach Data Search Engines Comparison](https://inteltechniques.com/blog/2018/09/30/breach-data-search-engines-comparison/) :pencil: (IntelTechniques)
- [CardPwn](https://github.com/itsmehacker/CardPwn) :computer: - Find out if a credit card number appears in a breach.
-  [Dehashed](https://dehashed.com/) :globe_with_meridians:💲 - Find cleartext & hashed password from data breaches (paid, $4/week, $11/mo).
- [GhostProject](https://ghostproject.fr) :globe_with_meridians: - Check if an email appears in a breach. Shows the first 3 characters of the password for free.
- [h8mail](https://github.com/khast3x/h8mail) :computer: -  Find passwords through different breach and reconnaissance services. Can also search the BreachedCompilation torrent.
- [Have I Been Pwned?](https://haveibeenpwned.com/) :globe_with_meridians: - Check if an email appears in a breach, set up alerts.
- [pwndb.py](https://github.com/davidtavarez/pwndb) :computer: - Command-line tool for searching leaked credentials using the Onion service with the same name.
- [WhatBreach](https://github.com/Ekultek/WhatBreach) :computer: - Search for breached emails and their corresponding database.

## Companies
- [CompaniesHouse Short Guide](https://www.bellingcat.com/resources/how-tos/2017/06/23/companies-house-short-guide/) :book: (Bellingcat) - A guide about the UK online company registry.
- [DocumentCloud Search](https://www.documentcloud.org/public/search/) :globe_with_meridians: - Search public documents uploaded to DocumentCloud, a publishing plateform used by many journalists and media.
- [ICIJ's Offshore Leaks Database](https://offshoreleaks.icij.org/) :globe_with_meridians: - Data on offshore companies, foundations and trusts from the Panama Papers, the Offshore Leaks, the Bahamas Leaks and the Paradise Papers investigations.
- [List of company registers](https://en.wikipedia.org/wiki/List_of_company_registers) :pencil: (Wikipedia) - A list of all companies registers, by country.
- [OCCRP Data](https://data.occrp.org/) :globe_with_meridians: - Fantastic search tool & resources made available by OCCRP. Public records, leaks, scraped business registers, and more.
- [OCCRP Investigative Dashboard](https://investigativedashboard.org/databases/) :pencil: - Collection of the most useful public data sources for investigative reporting. Many business registries listed.
- [OpenCorporates](https://opencorporates.com/) :globe_with_meridians: - A very comprehensive companies database. Has an [API](https://api.opencorporates.com/).
- [Open Ownership Register](https://register.openownership.org/) :globe_with_meridians: - Explore beneficial ownership data. Aggregates many datasets.

## Data Analysis & Manipulation
<small>See also: [Visualization](#visualization)</small>
- [csvkit](https://github.com/wireservice/csvkit) :computer: - A suite of command-line tools for converting to and working with  CSV files.
- [OpenRefine](https://github.com/OpenRefine/OpenRefine) :computer: - Clean & transform messy data.
- [pandas](https://pandas.pydata.org/) :snake: - Powerful Python data analysis library. Best used in a [Jupyter notebook](https://jupyter.org/).

## Email
<small>See also: [Breached Data](#breached-data)
- [emailrep.io](https://emailrep.io/) :globe_with_meridians: - Public email reputation search & API. Can find social media profiles.
- [Infoga](https://github.com/m4ll0k/Infoga) :computer: - Gather email accounts information (ip, hostname, country, etc) from different public sources.
- [theHarvester](https://github.com/laramies/theHarvester) :computer: - Python command-line tool to search several search engines for mail addresses from a particular domain.
- [The most complete guide to finding anyone's email](https://www.blurbiz.io/blog/the-most-complete-guide-to-finding-anyones-email) :book: (Blurbiz)
- [Trumail](https://trumail.io/) :globe_with_meridians: - Free email verification API.

## Lists of tools & resources
- [Citadel](https://github.com/jakecreps/Citadel) :computer: - A library of OSINT tools.
- [IntelTechniques.com]( https://inteltechniques.com) :pencil: - Blog, podcast, and paid OSINT/privacy training courses.
- [Guides](https://bellingcat.com/category/resources/how-tos/) :book: (Bellingcat) - OSINT & Datajournalism how-tos.
- [Online Investigation Toolkit](https://docs.google.com/document/d/1BfLPJpRtyq4RFtHJoNpvWQjmGnyVkfE2HYoICKOGguA/edit) :pencil: (Bellingcat)
- [awesome-osint](https://github.com/jivoi/awesome-osint) :pencil: - A curated list of open source intelligence tools and resources.
- [OSINT framework](https://github.com/lockfale/OSINT-Framework) :pencil: - Tree list of OSINT tools & resources.
- [OSINT Collection](https://github.com/Ph055a/OSINT-Collection) :pencil: - Collection of OSINT related resources.
- I-Intelligence's [Open Source Intelligence Tools and Resources Handbook 2018](https://www.i-intelligence.eu/wp-content/uploads/2018/06/OSINT_Handbook_June-2018_Final.pdf) :pencil: - Very complete list of OSINT tools & resources, organized by category. No descriptions.
- [AutomatedOSINT.com](http://www.automatingosint.com/blog/) :book: - A Blog about automating OSINT techniques using Python.
- [netbootcamp](https://netbootcamp.org/osinttools/) :pencil: - Custom search forms and lists of resources by theme.
- [Week in OSINT](https://medium.com/week-in-osint) :pencil: - Fresh links to OSINT tools, resources and investigations every week.

## Location, Maps, Satellite Imagery

### Interpretation
- [How To Use Google Earth’s Three Dimensional View](https://www.bellingcat.com/resources/how-tos/2019/03/05/how-to-use-google-earths-three-dimensional-view-feat-syria-yemen-sudan/) :book: (Bellingcat)
- [Identify Burnt Villages on Satellite Imagery](https://www.bellingcat.com/resources/how-tos/2018/09/04/identify-burnt-villages-satellite-imagery%e2%80%8a-case-studies-california-nigeria-myanmar/) :book: (Bellingcat)
- [Photo Interpretation Student Handbook](https://sites.miis.edu/geospatialtools2012/files/2012/07/Photo-Interpretation-Student-Handbook.-Photo-Interpretation-Principles.pdf) :book: (US Defense Mapping Agency, 1996) - Old unclassified handbook on analyzing aerial & satellite imagery. General principles & specifics for buildings, industries, transportation & communication facilities.
- [Using Time Lapse Satellite Imagery to Detect Infrastructure Changes](https://www.bellingcat.com/resources/how-tos/2018/11/19/using-time-lapse-satellite-imagery-detect-infrastructure-changes-case-studies-via-myanmar-nigeria-south-china-sea) :book: (Bellingcat)

### Mapping services & software

- [Baidu Maps](https://map.baidu.com/) :globe_with_meridians: - Streetview = Panorama (百度全景)
- [Bing Maps](https://www.bing.com/maps) :globe_with_meridians:
- [GeoNames](http://www.geonames.org/) :globe_with_meridians: - Geographical database.
- [GoogleMaps](https://maps.google.com) :globe_with_meridians:
- [Google Earth](https://www.google.com/earth/) :globe_with_meridians:
    - [Google Earth Outreach](https://www.google.com/earth/outreach/learn/) - Advanced Google Earth tutorials. Example: [Image & Photos Overlay](https://www.google.com/earth/outreach/learn/creating-photos-image-overlays-in-google-earth/)
    - [Google Earth Engine](https://earthengine.google.com/) - Datasets, case studies, etc.
    - [GEarth Blog](https://www.gearthblog.com) - Resources & how-tos about Google Earth
- Satellite imagery providers:
    - [Copernicus Open Access Hub](https://scihub.copernicus.eu/) :globe_with_meridians: - Free access to imagery from the European Sentinel satellites.
    - [Descartes Labs](https://www.descarteslabs.com/) :globe_with_meridians:💲
    - [DigitalGlobe Discover](https://discover.digitalglobe.com/) :globe_with_meridians: - Search for satellite imagery of a particular location. Ability to download images (low-resolution compared to Google Earth).
    - [EOS Landviewer](https://eos.com/landviewer/) :globe_with_meridians:💲
    - NASA [EarthData](https://search.earthdata.nasa.gov/) & [EarthViewer](https://worldview.earthdata.nasa.gov/) :globe_with_meridians:
    - [USGS Earth Explorer](https://earthexplorer.usgs.gov/) :globe_with_meridians: - NASA Landsat imagery
- [Here WeGo](https://wego.here.com) :globe_with_meridians:
- [SentinelHub](https://www.sentinel-hub.com/) :globe_with_meridians: - Satellite imagery, historical data from several sources, vegetation infrared & index, image exports & comparison. 2 products:
    - [Playground](https://apps.sentinel-hub.com/sentinel-playground/) - Data discovery, playing around
    - [EO Browser](https://apps.sentinel-hub.com/eo-browser/) - Compare full resolution images from several sources (Landsat, Sentinel), make time lapses & export to GIF (free signup required).
    - See also the [custom scripts](https://github.com/sentinel-hub/custom-scripts) to highlight fire, snow, metals, type of terrain, etc.
    - [Zoom Earth](https://zoom.earth/) :globe_with_meridians: - NASA satellite and aerial images of the Earth.
- [Yandex Maps](https://yandex.com/maps) :globe_with_meridians: - Has a "Streetview" feature.

### Tools & techniques
- [Geographic Bounding Box Drawing Tool](http://www.automatingosint.com/blog/geographic-bounding-box-drawing-tool/)  :globe_with_meridians: - Draw a rectangle over a map and get the coordinates of its points & center.
- [PeakFinder](https://www.peakfinder.org) :globe_with_meridians: - Show names of all mountains and peaks from any coordinates with a 360° panoramic mountain view.
- [Shadows and Angles: Measuring Object Heights from Satellite Imagery](https://www.gislounge.com/shadows-angles-measuring-object-heights-satellite-imagery/) :book: (GISLounge)
- [Shadows and Suncalc](https://medium.com/quiztime/lining-up-shadows-2351ae106cec) :book: - Great tutorial on using Google Earth & Suncalc to calculate time based on shadows.
- [SunCalc](https://suncalc.org/) :globe_with_meridians: - Historical solar data (sun orientation & elevation, shadow length, etc).
- [TerraPattern](http://www.terrapattern.com/) :globe_with_meridians: - Scan large geographical areas for specific visual features using machine learning. Only available for 7 cities.

### User generated content
<small>See also: [Social Networks](#social-networks)</small>
- [EchoSec](https://www.echosec.net/) :globe_with_meridians:💲 - Search and analyze social media data based on location. ($499/mo)
- [GeoCreepy](http://www.geocreepy.com/) :computer: - Geolocation information gathering through social networking platforms (discontinued).
- [Kamerka](https://github.com/woj-ciech/kamerka) :computer:- Create an interactive map of cameras, printers, tweets and photos based on your coordinates.
- [OpenStreetMap](https://openstreetmap.org) :globe_with_meridians: - User generated locations & maps. Use [taginfo](https://taginfo.openstreetmap.org) and/or [overpass-turbo.eu](https://overpass-turbo.eu/) to search a location by key/value tags (see [OSM's Wiki](https://wiki.openstreetmap.org))
- [Mapillary](https://www.mapillary.com/app/) :globe_with_meridians: - Interactive map of crowdsourced geotagged photographs.
- [OpenStreetCam](https://openstreetcam.org/) :globe_with_meridians: - Map of crowdsourced street-level photographs.
- Social networks ([see category](#social-networks))
- [Surveillance under Surveillance](https://kamba4.crux.uberspace.de/) :globe_with_meridians: - User-contributed map of cameras and guards.
- Tourism & review websites: [Foursquare](https://foursquare.com/), [TripAdvisor](https://www.tripadvisor.com/), [Yelp](https://www.yelp.com/), etc. :globe_with_meridians:
- [Vkontakte](https://vk.com) :globe_with_meridians: - Use `near:<coordinates>` in a  search.
- [Wikimapia](http://wikimapia.org/) :globe_with_meridians: - User-generated locations & descriptions. Has an API.

## Military/Weapons
- [CalibreObscura](https://www.calibreobscura.com/) :globe_with_meridians: - A blog about weapons & their uses in Middle East conflicts.
- [CamoPedia](http://www.camopedia.org) :globe_with_meridians: - Camouflage encyclopedia. Search & compare camouflage patterns.
- [ENAAT Data Browser](http://enaat.org/eu-export-browser) :globe_with_meridians: - Browse EU Arms Export Data.
- [How to Digitally Verify Combatant Affiliation in Middle East Conflicts](https://www.bellingcat.com/resources/how-tos/2018/07/09/digitally-verify-middle-east-conflicts/) :book:  (Bellingcat)
- [ICUS Camouflage Index](http://camouflageindex.camouflagesociety.org/index-2.html) :globe_with_meridians:
- [International Encyclopedia of Uniform Insignia](http://www.uniforminsignia.org/) :globe_with_meridians:
- [Investigating and Tracking the Global Arms Trade](https://docs.wixstatic.com/ugd/54261c_d7604b49e589454abddcf0bef37d721b.pdf
) :book: (Corruption Watch UK) - Good presentation, full of resources of all types on Arms Trade.
- [List of Comparative Military Ranks](https://en.wikipedia.org/wiki/List_of_comparative_military_ranks) :globe_with_meridians: (Wikipedia)
- Omega Research Foundation's [Identification](https://omegaresearchfoundation.org/identification-tools) & [Documentation](https://omegaresearchfoundation.org/documentation-tools) guides :book: - Guides on identifying and documenting police & military equipment.
- [SEESAC Reports](http://www.seesac.org/Reports/) & [Map](http://www.seesac.org/AVMP/) :globe_with_meridians: - Database of firearms-related incidents in South East Europe.
- [SIPRI Arms Transfers Database](https://www.sipri.org/databases/armstransfers) :globe_with_meridians: - Information on all transfers of major conventional weapons from 1950 to the current year.
- [Sketchfab](https://sketchfab.com/) :globe_with_meridians: - User-made 3D models sharing platform with lots of weapons. Useful to compare, check different angles, etc.
- Small Arms Survey’s [Weapon ID database](http://www.smallarmssurvey.org/weapons-and-markets/tools/weapons-id-database.html) :globe_with_meridians: - Search for small arms by caliber, type, location, etc.
- [Small Arms Survey: Documenting Small Arms and Light Weapons](http://www.smallarmssurvey.org/fileadmin/docs/G-Issue-briefs/SAS-IB14-Documenting-Small-Arms.pdf) :book: - International policy recap & identification guide.
- [UN Comtrade Database](https://comtrade.un.org/) :globe_with_meridians: - Official international trade statistics, including arms trade.
- [UNROCA](https://www.unroca.org/) :globe_with_meridians: - UN Register of Conventional Arms. Country-level data on arms exports.
- [World Army Pictures](https://www.worldarmypictures.com/) :globe_with_meridians: - Pictures of armies from all over the world.

## Multi-purpose tools
- [Buscador](https://inteltechniques.com/buscador/index.html) :computer: - A very handy VM with plenty of pre-installed & pre-configured OSINT tools.
- [DataSploit](https://github.com/DataSploit/datasploit) :computer: - A collection of python scripts which automates open source intelligence searches about domain names, email addresses, IP addresses and usernames.
- [IntelligenceX Tools](https://intelx.io/tools) :globe_with_meridians: - Various search, email and domain tools.
- [Maltego CE](https://www.paterva.com/web7/buy/maltego-clients/maltego-ce.php) :computer: - Interactive data mining & mapping tool.
- [Spiderfoot](http://www.spiderfoot.net/) :computer: - Open source intelligence automation tool. Gathers intelligence about a given target, which may be an IP address, domain name, hostname, network subnet, ASN, e-mail address or person's name.

## News
- [AllYouCanRead](https://www.allyoucanread.com) :pencil: - Database of news outlets by country.
- [NewsLookup](http://newslookup.com/) :globe_with_meridians: - News search engine with useful filters.
- [NewsNow](https://www.newsnow.co.uk) :globe_with_meridians: - News search engine with useful filters.
- [NewspaperMap](https://newspapermap.com/) :globe_with_meridians: - Newspapers world map with feeds and automatic translation.

## Phone numbers
- [NumberWay](https://www.numberway.com/) :globe_with_meridians: - International directory of white pages and yellow pages phone books.
- [PhoneInfoga](https://github.com/sundowndev/PhoneInfoga) :computer: - Information gathering & OSINT reconnaissance tool for phone numbers.
- [Using Phone Contact Book Apps For Digital Research](https://www.bellingcat.com/resources/how-tos/2019/04/08/using-phone-contact-book-apps-for-digital-research/) :book: (Bellingcat)

## Pictures, Photos, Videos

### Pictures Metadata
- [Exiftool](http://owl.phy.queensu.ca/~phil/exiftool/) :computer: - Read and edit metadata. [Linode Tutorial](https://linoxide.com/linux-how-to/install-use-exiftool-linux-ubuntu-centos/)
- Exif Viewer ([Firefox](https://addons.mozilla.org/en-US/firefox/addon/exif-viewer/)/[Chrome](https://chrome.google.com/webstore/detail/exif-viewer/https://chrome.google.com/webstore/detail/exif-viewer/mmbhfeiddhndihdjeganjggkmjapkffm)) :computer:
- [FotoForensics](https://fotoforensics.com) :globe_with_meridians: - Online pictures metadata viewer.
- [Ghiro](https://github.com/ghirensics/ghiro) :computer: - Automated image forensics tool.
- [Jeffrey's Image Metadata Viewer](http://exif.regex.info/exif.cgi) :globe_with_meridians:
- [mat2](https://0xacab.org/jvoisin/mat2) :computer: - Metadata removal tool.
- [mat2-web](https://mat2-web.dustri.org/) :globe_with_meridians: - Online version of mat2.
- [StolenCameraFinder](https://www.stolencamerafinder.com/) :globe_with_meridians: - Search the web for pictures with a specific camera serial number.

### Reverse search
- [Bing Images](https://www.bing.com/images/) :globe_with_meridians: - Can search part of an image by resizing on the fly.
- [CitizenEvidence](https://citizenevidence.amnestyusa.org/) :globe_with_meridians: - Google Images reverse search on Youtube thumbnails.
- [EagleEye](https://github.com/ThoughtfulDev/EagleEye) :computer: - Find Instagram, FB and Twitter profiles using image recognition and reverse image search.
- [Google Images](https://images.google.com/) :globe_with_meridians:
- [Search by Image](https://github.com/dessant/search-by-image) :computer: - Browser extension to quickly reverse-search an image on 20+ search engines.
- [TinEye](https://tineye.com/) :globe_with_meridians:
- [Yandex Images](https://yandex.com/images/) :globe_with_meridians:

### Search
- [How to Conduct Comprehensive Video Collection](https://www.bellingcat.com/resources/how-tos/2017/10/17/conduct-comprehensive-video-collection/) (Bellingcat) :book:
- [PimEyes](https://pimeyes.com) :globe_with_meridians: - Face-recognition matching search engine.
- [SearchFace.ru](https://searchface.ru) :globe_with_meridians: - Face recognition search engine for the Russian VK social network. See this [guide](https://www.bellingcat.com/resources/how-tos/2019/02/19/using-the-new-russian-facial-recognition-site-searchface-ru/) from Bellingcat for a tutorial.
- [SocialMapper](https://github.com/SpiderLabs/social_mapper) :globe_with_meridians: - Social Media Mapping Tool that correlates profiles via facial recognition. Supports LinkedIn, Facebook, Twitter, Instagram, VKontakte, Weibo, Douban.

### Verification & Analysis
- [Advanced Guide on Verifying Video Content](https://www.bellingcat.com/resources/how-tos/2017/06/30/advanced-guide-verifying-video-content/) :book: (Bellingcat)
- [face_recognition](https://github.com/ageitgey/face_recognition) :computer::snake: - Command-line tool and python library for recognizing known faces on a batch of pictures.
- [How to verify photos and videos on social media networks](http://observers.france24.com/en/20151110-observers-guide-verifying-photos-videos-social-media-networks) :book: (France24)
- [InVID Verification Plugin](https://www.invid-project.eu/tools-and-services/invid-verification-plugin/) :computer: - Verification “Swiss army knife” Firefox extension.
- [Photo Verification Cheatsheet](https://firstdraftnews.org/wp-content/uploads/2017/03/FDN_verificationguide_photos.pdf) & [Video Verification Cheatsheet](https://firstdraftnews.org/wp-content/uploads/2017/03/FDN_verificationguide_videos.pdf) :book: (FirstDraftNews)
- [Verification 101](https://medium.com/1st-draft/verification-101-storyful-s-advice-for-checking-out-material-from-social-media-and-putting-it-750495792876) :book: - Storyful’s advice for checking out material from social media, and putting it into practice.
- [Verification Handbook](http://verificationhandbook.com/book/) :book: - Handbook by the European Journalism Centre about verifying digital content in emergency coverage.


## Social Networks

### All/General
- [EagleEye](https://github.com/ThoughtfulDev/EagleEye) :computer: - Find Instagram, FB and Twitter profiles using image recognition and reverse image search.
- [HashAtIt](https://www.hashatit.com) :globe_with_meridians: - Hashtag search across Twitter, Instagram, Pinterest, Facebook and Youtube.
- [Sherlock](https://sherlock-project.github.io/) :computer: - Search for a username across 135 social media sites.
- [SocialMapper](https://github.com/SpiderLabs/social_mapper) :globe_with_meridians: - Social Media Mapping Tool that correlates profiles via facial recognition. Supports LinkedIn, Facebook, Twitter, Instagram, VKontakte, Weibo, Douban.
- [WhatsMyName](https://github.com/WebBreacher/WhatsMyName) :computer: - Search for usernames on 180+ web sites.

### Discord
- [dis.cool](https://dis.cool/) :globe_with_meridians: - Discord search engine.

### Facebook
- [fb-search](https://sowdust.github.io/fb-search/) :globe_with_meridians: - Simple Graph query crafter. Made after Facebook sudden closure of Graph Search.
- [FFFF Finds Facebook Friends](https://github.com/sowdust/ffff) :computer: - Builds a relationship graph of a target user. Partially reconstructs hidden friend lists. :fire:.

### Github
- [gitrob](https://github.com/michenriksen/gitrob) :computer: - Find potentially sensitive files pushed to public repositories on Github. Requires a GitHub access token.
- [Zen](https://github.com/s0md3v/Zen) :computer: - Find emails of Github users.

### Instagram
- [instaloader](https://github.com/instaloader/instaloader) :computer: - Download pictures (or videos) along with their captions and other metadata from Instagram.
- [instagram-scraper](https://github.com/rarcega/instagram-scraper) :computer: - Scrape a user's photos and videos.
- [searchmybio](https://www.searchmy.bio/) :globe_with_meridians: - Search Instagram users biographies.

### Linkedin
- [An Investigative Guide To LinkedIn](https://www.bellingcat.com/resources/how-tos/2019/03/21/bellingcats-invitation-is-waiting-for-your-response-an-investigative-guide-to-linkedin/) :book: (Bellingcat)
- [CrossLinked](https://github.com/m8r0wn/crosslinked) :computer: - LinkedIn enumeration tool to extract valid employee names from an organization.
- [LinkedIn Operators Tip Sheet](https://booleanstrings.com/2018/12/06/linkedin-operators-one-more-tip-sheet/) :book:
- [raven](https://github.com/0x09AL/raven) :computer: - Linkedin information gathering tool. Extracts employee data for a given company.
- [The Endorser](https://github.com/eth0izzle/the-endorser) :computer: - Draw out relationships between people on LinkedIn via endorsements/skills.

### Reddit
- [Reddit Comment Search](https://redditcommentsearch.com/) :globe_with_meridians: - Search through comments of a particular reddit user.
- [Reddit Insight](https://www.redditinsight.com/#trackuser) :globe_with_meridians: - Collect info on a Reddit profile, list all posts & comments.
- [Reddit Investigator](http://www.redditinvestigator.com/) :globe_with_meridians: - Collect info on a Reddit profile.
- [Reddit Search](https://redditsearch.io/) :globe_with_meridians: - Reddit search engine with filters.
- [ReSavr](https://www.resavr.com/) :globe_with_meridians: - Search deleted comments.

### Snapchat
- [Snapdex](https://www.snapdex.com/) :globe_with_meridians: - Searchable database of Snapchat usernames.
- [Snap Map](https://map.snapchat.com) :globe_with_meridians: - Official Snapchat map.

### Telegram
- [Buzz.im](https://search.buzz.im/) :globe_with_meridians: - Search in open telegram messages.
- [Lyzem](https://lyzem.com/) :globe_with_meridians: - Telegram search engine.
- [Telegago](https://cse.google.com/cse?q=+&cx=006368593537057042503:efxu7xprihg) :globe_with_meridians: - Google Custom Search Engine for Telegram users & content. Can discover private groups.
- [tlgrm.eu](https://tlgrm.eu/channels) :globe_with_meridians: - Search for Telegram channels.
- [tgstat.ru](https://tgstat.ru/en/search) :globe_with_meridians: - Telegram analytics & seach tool.

### Twitter
- [DMI-TCAT](https://github.com/digitalmethodsinitiative/dmi-tcat) :computer: - PHP web interface to retrieve and analyze tweets.
- [SocialBearing](https://socialbearing.com/) :globe_with_meridians: - Statistics on keywords, hashtags, users.
- [SpoonBill](https://spoonbill.io/) :globe_with_meridians: - Track changes in Twitter profiles & bios. Requires a Twitter account.
- [tinfoleak](https://github.com/vaguileradiaz/tinfoleak) :computer: - Very complete open-source tool for Twitter intelligence analysis. Needs API credentials.
- [twarc](https://github.com/DocNow/twarc) :computer::snake: - A command line tool and Python library for archiving Twitter in JSON format.
- [Tweetdeck](https://tweetdeck.twitter.com/) :globe_with_meridians:
- Tweetdeck [Location Search Tutorial](http://thoughtfaucet.com/search-twitter-by-location/tweetdeck-twitter-location-search-tutorial/) :book:
- [Tweet Map](https://www.omnisci.com/demos/tweetmap/) :globe_with_meridians: - Explore the world and find geo-tagged tweets.
- [Tweets Analyzer](https://github.com/x0rz/tweets_analyzer) :computer: - Twitter profile analyzer with tweet activity charts, locations, most used hashtags, etc. Can save tweets to JSON. Requires a Twitter API key.
- [tweetsmapper](https://github.com/r3mlab/tweetsmapper) :computer: - Generates a Leaflet map for a given user or from an existing collection of tweets. Can retrieve full timelines.
- [TWINT (Twitter Intelligence Tool)](https://github.com/twintproject/twint) :computer: - Advanced Twitter scraping tool, no API key needed. Can export to text, CSV, JSON, SQLite, Elasticsearch. Can detect emails, phone numbers, profiles.
- [Who Tweeted It First?](http://ctrlq.org/first/) :globe_with_meridians: - Find out who was the first person who tweeted a link, video, quote or any piece of text.

### VKontakte
- [SnRadar](https://snradar.azurewebsites.net/) :globe_with_meridians: - Search VKontakte content by location.

### Youtube
- [Unlisted Videos](https://unlistedvideos.com/) :globe_with_meridians: - Search & submit unlisted YouTube videos. No registration required.

## Text & Documents

### Documents metadata
- [Apache Tika](https://tika.apache.org/) :computer: - Extract metadata and text from over a thousand different file types.
- [FOCA](https://github.com/ElevenPaths/FOCA) :globe_with_meridians::computer: - Find metadata and hidden information in Microsoft Office, Open Office, or PDF files.
- [ICIJ Extract](https://github.com/ICIJ/extract) :computer: - A command line tool for parallelized, distributed content-extraction.

### Indexing & searching
- [Aleph](https://github.com/alephdata/aleph) :computer: - A toolkit for data search, management and analysis in investigative reporting.
- [Blacklight](https://github.com/projectblacklight/blacklight) :computer: - Open source Solr user interface discovery platform.
- [Datashare](https://datashare.icij.org/) :computer: - Index & search documents on your computer, automatically detect people, organizations and locations with NLP.
- [DumpsterDiver](https://github.com/securing/DumpsterDiver) :computer: - Analyze big volumes of various file types in search of secrets, credentials, etc.
- [ICIJ Extract](https://github.com/ICIJ/extract) :computer: - A command line tool for parallelized, distributed content-extraction.
- [searchbox](https://github.com/StephenGrey/searchbox) :computer: - A simple out-of-the-box web interface to search through thousands of unstructured documents using Solr.

### OCR
- [NewOCR.com](https://www.newocr.com/) :globe_with_meridians: - Recognizes several languages. Can resize images & has shortcuts to Google & Bing Translate.
- [Tesseract](https://github.com/tesseract-ocr/tesseract) :computer: - Open-source OCR engine.

### PDF
- [PDF Text Extraction](https://r3mlab.github.io/python/osint/2018/08/09/PDF-text-extraction.html) with PyPDF2, Tika & PDF Miner. :computer:
- [tabula](https://tabula.technlogy) :computer: - Tool for liberating data tables trapped inside PDF files.

### Text Processing & Analysis
- [topia](https://pypi.org/project/topia.termextract/) :snake: - Python module to determine important terms within a given piece of content.
- [TXM](http://textometrie.ens-lyon.fr/?lang=en) :computer: - Lexicometry and text statistical analysis for large bodies of text.

## Transportation

### Containers & Shipments
- [BIC Code Register](https://www.bic-code.org/bic-codes/) :globe_with_meridians: - Business Identifier Codes lookup. The website also has other search tools and useful information on container markings.
- [Prefix List](https://www.prefixlist.com/prefix.html) :globe_with_meridians: - Find the owner of a container from its prefix.
- [track-trace](https://www.track-trace.com/) :globe_with_meridians: - Track parcels/shipments, air cargo, containers and post.

### Planes
- Flights tracking:
    - [FlightAware](https://uk.flightaware.com) :globe_with_meridians:
    - [FlightRadar24](https://www.flightradar24.com) :globe_with_meridians:
    - [PlaneFinder](https://planefinder.net/) :globe_with_meridians:
    - [RadarBox](https://www.radarbox24.com/) :globe_with_meridians:
- [PlaneMapper](https://www.planemapper.com/) :globe_with_meridians: - Flights, airports, airlines and aircrafts databases.

### Ships
- [Inmarsat Ships Directory](https://www.inmarsat.com/ships-directory/) :globe_with_meridians: - Find contact details from a ship's name or number.
- [Maritime Connector](http://maritime-connector.com/) :globe_with_meridians: - Maritime jobs listings & search.
- [Maritime Database](https://www.maritime-database.com/) :globe_with_meridians: - Lists and details of shipping-related businesses and ports of the world.
- Ship search & track:
    - [VesselsFinder](https://vesselfinder.com/) :globe_with_meridians:
    - [MyShipTracking](https://www.myshiptracking.com/) :globe_with_meridians:
    - [Fleetmon](https://www.fleetmon.com) :globe_with_meridians:
    - [Shipfinder](http://www.shipfinder.com/) :globe_with_meridians:
    - [Marine Traffic](https://www.marinetraffic.com/) :globe_with_meridians:
    - [CruiseMapper](https://www.cruisemapper.com/) :globe_with_meridians:

## Visualization

### Graphs
- [Data Visualisation Catalogue](https://datavizcatalogue.com/index.html) :book: - Find which visualisation is right for what you want to show. Plenty of tips & resources.
- [DataWrapper](https://www.datawrapper.de) :globe_with_meridians:💲 - Easy to use graph & map tool. Free plan available.
- [Google Fusion Tables](https://support.google.com/fusiontables/answer/2571232) - Create maps & charts from data. Will shut down on Dec. 2019.
- [Matplotlib](https://matplotlib.org/) :snake: - Python 2D plotting library. Best used with pandas in a Jupyter notebook.
- [RawGraph](https://app.rawgraphs.io/) :globe_with_meridians::computer: -  Generate static graphs through a very user-friendly interface. Can be run locally.

### Maps
- [ArcGIS](https://www.esri.com/en-us/home) :computer:💲 - Mapping & analysis software (proprietary, paid, 21-day trial)
- [Folium](https://python-visualization.github.io/folium/) :snake: - Python library to create Leaflet.js maps. Can be used in a Jupyter Notebook to map data from pandas.
- [Geopy](https://github.com/geopy/geopy) :snake: - Python geocoding library. Supports OSM Nominatim, Google, Bing, GeoNames & many more.
- Google:
    - [MyMaps](https://www.google.com/mymaps) :globe_with_meridians:
    - [Earth](https://www.google.com/earth/) :globe_with_meridians:
    - [Earth Pro](https://www.google.com/earth/versions/):computer:
    - [Earth Studio](https://www.google.com/earth/studio/) :globe_with_meridians::computer:
- [Humanitarian Data Exchange](https://data.humdata.org/) :globe_with_meridians: - Useful resources of shapefiles, especially for administrative boundaries.
- [KML Interactive Sampler](https://googlemaps.github.io/kml-samples/interactive/index.html) :globe_with_meridians: - Lots of KML templates.
- [QGIS](https://www.qgis.org/en/site/about/index.html) :computer: - Free & open-source alternative to ArcGis.

### Mindmaps & Network graphs
- [Draw.io](https://www.draw.io/) :globe_with_meridians::computer: - Open-source diagramming tool. Can be run locally.
- [Gephi](https://gephi.org/) :computer: - Powerful visualization and exploration software
- [Visual Investigative Scenarios](https://vis.occrp.org/) :globe_with_meridians: (OCCRP)
- [yEd Graph Editor](https://www.yworks.com/products/yed) :computer:


### Timelines
- [Tik Tok](https://datanews.github.io/tik-tok/) :computer: - Javascript tool to easily create simple, mobile-friendly, vertical timelines. Open-source.
- [TimelineJS](https://timeline.knightlab.com/) :computer:


## Weather
- [timeanddate.com](https://www.timeanddate.com/weather) :globe_with_meridians: - Weather history.
- [Ventusky](https://www.ventusky.com/) :globe_with_meridians: - Live & past wind, rain and temperature maps.
- [Wolfram Alpha](https://www.wolframalpha.com) :globe_with_meridians: - Weather history. *What was the weather in New York on January 1st 2017?*
- [Wunderground History](https://www.wunderground.com/history/) :globe_with_meridians: - Weather history


## Websites
<small>See also: [Archival](#archival)</small>

### Dark Web & Onion services
- [DarkSearch](https://darksearch.io/) :globe_with_meridians: - Dark web search engine.
- [OnionScan](https://github.com/s-rah/onionscan) :computer:
    - DarkWeb OSINT with Python & OnionScan :book: (AutomatingOSINT.com) - [part1](http://www.automatingosint.com/blog/2016/07/dark-web-osint-with-python-and-onionscan-part-one/) / [part2](http://www.automatingosint.com/blog/2016/08/dark-web-osint-with-python-part-two-ssh-keys-and-shodan/) / [part3](http://www.automatingosint.com/blog/2016/08/dark-web-osint-with-python-part-three-visualization/)
- [OSINT Tools for the Dark Web](https://jakecreps.com/2019/05/16/osint-tools-for-the-dark-web/) (Jake Creps) :pencil: - Presentation of several tools to help investigate the dark web.

### Scraping
- [Photon](https://github.com/s0md3v/Photon) :computer: - Crawl a website (or its archive from the WayBack machine) and extract URLs, emails, social media accounts, files, keys, subdomains, etc.
- Python scraping libraries:
    - [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) :snake:
    - [cloudflare-scrape](https://github.com/Anorov/cloudflare-scrape) :snake:
    - [Selenium](https://www.seleniumhq.org/) :snake:
    - [Scrapy](https://scrapy.org/) :snake:
- [Scrape Interactive Geospatial Data](https://www.bellingcat.com/resources/how-tos/2018/09/05/scrape-interactive-geospatial-data/) :book: (Bellingcat)

### Searches, info, related entities
- Advanced Google searches
    - [Google Search Operators](https://moz.com/learn/seo/search-operators) :book: (moz.com)
    - [Mastering Google Search Operators in 67 steps](https://moz.com/blog/mastering-google-search-operators-in-67-steps) :book: (moz.com)
    - [Google Hacking Database](https://www.exploit-db.com/google-hacking-database/) :book: (Exploit.db)
    - [Google Search Operators: The Complete List](https://ahrefs.com/blog/google-advanced-search-operators/) :book: (ahrefs.com)
- [CarbonDate](https://github.com/oduwsdl/CarbonDate) :computer: - Estimate the age of web resources. Has an [non-HTTPS online version](http://carbondate.cs.odu.edu/)
- [crt.sh](https://crt.sh/) :globe_with_meridians: - Certificates search.
- [Domain_OSINT](https://github.com/Ph055a/Domains_OSINT) :pencil: - Ph055a's list of tools to investigate domains & IoT devices.
- [DNSDumpster](https://dnsdumpster.com/) :globe_with_meridians: - Domain research tool that can discover hosts related to a domain.
- [FinalRecon](https://github.com/thewhiteh4t/FinalRecon) :computer: - All-in-one tool : whois, headers, SSL certificates details, image & links crawling.
- [NerdyData Search](https://search.nerdydata.com/) :globe_with_meridians: - Source code search engine.
- [OpenLinkProfiler](https://openlinkprofiler.org) - Search & analyze the links of a website. Good replacement for Google's defunct `link:` operator.
- [PublicWWW](https://publicwww.com/) :globe_with_meridians: - Search the source code of pages.
- [pymeta](https://github.com/m8r0wn/pymeta) :computer: - Find document files on a domain, download them and extract metadata.
- [SpyOnWeb](http://spyonweb.com/) :globe_with_meridians: - Search by URL, IP address, analytics codes. API with free plan. See [this Belligcat how-to](https://www.bellingcat.com/resources/2017/07/31/automatically-discover-website-connections-tracking-codes/) for automation.
- [Sublist3r](https://github.com/aboul3la/Sublist3r) :computer: - Subdomains enumeration tool.
- [Unveiling hidden site connections with Google Analytics IDs](https://www.bellingcat.com/resources/how-tos/2015/07/23/unveiling-hidden-connections-with-google-analytics-ids/)  :book: (Bellingcat)

## Misc
- [awesome-selfhosted](https://github.com/Kickball/awesome-selfhosted) :pencil: - A list of Free Software network services and web applications which can be hosted locally
- [grayhatwarfare](https://buckets.grayhatwarfare.com/) :globe_with_meridians: - Search open Amazon S3 buckets content.
- [Shodan](https://www.shodan.io/) :globe_with_meridians: - Internet of Things search engine
- [World License Plates](http://www.worldlicenseplates.com/) :globe_with_meridians: - Pictures of license plates from all around the world.

## License

This list is under the [Creative Commons Attribution-NonCommercial 4.0 International Public License](LICENSE) License.
