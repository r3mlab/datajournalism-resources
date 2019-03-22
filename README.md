# datajournalism-resources

A compilation of links to datajournalism & OSINT tools, guides and resources I find useful to keep at hand. PRs welcomed!

#### Legend:
- :globe_with_meridians: = online tool/service/resource
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
- [Multi-purpose tools](#multi-purpose-tools)
- [Phone numbers](#phone-numbers)
- [Pictures, Photos, Videos](#pictures-photos-videos)
    - [Metadata](#metadata)
    - [Military/Weapons](#militaryweapons)
    - [Reverse search](#reverse-search)
    - [Search](#search)
    - [Verification & Analysis](#verification--analysis)
- [Social Networks](#social-networks)
    - [General](#general)
    - [Facebook](#facebook)
    - [Instagram](#instagram)
    - [Linkedin](#linkedin)
    - [Reddit](#reddit)
    - [Twitter](#twitter)
- [Text & Documents](#text--documents)
    - [Indexing & searching](#indexing--searching)
    - [PDF](#pdf)
    - [OCR](#ocr)
    - [Text Processing & Analysis](#text-processing--analysis)
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
-  [Hunch.ly](https://www.hunch.ly/) :globe_with_meridians:💲 - Web capture tool designed for online Investigations ($129.99/y).
- [Internet Archive Wayback Machine](https://web.archive.org/) :globe_with_meridians:
    -  [waybackpack](https://github.com/jsvine/waybackpack) :computer::snake: - Command-line utility & Python library to download content from the Wayback Machine. See [this example](https://www.bellingcat.com/resources/2016/12/06/vacuuming-image-metadata-wayback-machine/).


## Breached Data
- [Breach Data Search Engines Comparison](https://inteltechniques.com/blog/2018/09/30/breach-data-search-engines-comparison/) :pencil: (IntelTechniques)
-  [Dehashed](https://dehashed.com/) :globe_with_meridians:💲 - Find cleartext & hashed password from data breaches (paid, $4/week, $11/mo).
-  [GhostProject](https://ghostproject.fr) :globe_with_meridians: - Check if an email appears in a breach. Shows the first 3 characters of the password for free.
-  [h8mail](https://github.com/khast3x/h8mail) :computer: -  Find passwords through different breach and reconnaissance services. Can also search the BreachedCompilation torrent.
-  [Have I Been Pwned?](https://haveibeenpwned.com/) :globe_with_meridians: - Check if an email appears in a breach, set up alerts.

## Companies
- [CompaniesHouse Short Guide](https://www.bellingcat.com/resources/how-tos/2017/06/23/companies-house-short-guide/) :book: (Bellingcat) - A guide about the UK online company registry.
- [ICIJ's Offshore Leaks Database](https://offshoreleaks.icij.org/) :globe_with_meridians: - Data on offshore companies, foundations and trusts from the Panama Papers, the Offshore Leaks, the Bahamas Leaks and the Paradise Papers investigations.
- [List of company registers](https://en.wikipedia.org/wiki/List_of_company_registers) :pencil: (Wikipedia) - A list of all companies registers, by country.
- [OCCRP Data](https://data.occrp.org/) :globe_with_meridians: - Fantastic search tool & resources made available by OCCRP. Public records, leaks, scraped business registers, and more.
- [OpenCorporates](https://opencorporates.com/) :globe_with_meridians: - A very comprehensive companies database. Has an [API](https://api.opencorporates.com/).

## Data Analysis & Manipulation
- [csvkit](https://github.com/wireservice/csvkit) :computer: - A suite of command-line tools for converting to and working with CSV files.
- [OpenRefine](https://github.com/OpenRefine/OpenRefine) :computer: - Clean & transform messy data.
- [pandas](https://pandas.pydata.org/) :snake: - Powerful Python data analysis library. Best used in a [Jupyter notebook](https://jupyter.org/).

## Email
- [Infoga](https://github.com/m4ll0k/Infoga) :computer: - Gather email accounts information (ip, hostname, country, etc) from different public sources.
- [theHarvester](https://github.com/laramies/theHarvester) :computer: - Python command-line tool to search several search engines for mail addresses from a particular domain.
- [The most complete guide to finding anyone's email](https://www.blurbiz.io/blog/the-most-complete-guide-to-finding-anyones-email) :book: (Blurbiz)

## Lists of tools & resources
- [IntelTechniques.com]( https://inteltechniques.com/menu.html) :pencil: - Resources, links & OSINT tools, organized by target data.
- [Guides](https://bellingcat.com/category/resources/how-tos/) :book: (Bellingcat) - OSINT & Datajournalism how-tos.
- [Online Investigation Toolkit ](https://docs.google.com/document/d/1BfLPJpRtyq4RFtHJoNpvWQjmGnyVkfE2HYoICKOGguA/edit) :pencil: (Bellingcat)
- [awesome-osint](https://github.com/jivoi/awesome-osint) :pencil: - A curated list of open source intelligence tools and resources.
- [OSINT framework](https://osintframework.com/) :pencil: - Tree list of OSINT tools & resources.
- [OSINT Collection](https://github.com/Ph055a/OSINT-Collection) :pencil: - Collection of OSINT related resources.
- I-Intelligence's [Open Source Intelligence Tools and Resources Handbook 2018](https://www.i-intelligence.eu/wp-content/uploads/2018/06/OSINT_Handbook_June-2018_Final.pdf) :pencil: - Very complete list of OSINT tools & resources, organized by category. No descriptions.
- [AutomatedOSINT.com](http://www.automatingosint.com/blog/) :book: - A Blog about automating OSINT techniques using Python.
- [netbootcamp](https://netbootcamp.org/osinttools/) :pencil: - Custom search forms and lists of resources by theme.

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
    - [NASA EarthData](https://search.earthdata.nasa.gov/) & NASA [EarthViewer](https://worldview.earthdata.nasa.gov/) :globe_with_meridians:
    - [USGS Earth Explorer](https://earthexplorer.usgs.gov/) :globe_with_meridians: - NASA Landsat imagery
- [SentinelHub](https://www.sentinel-hub.com/) :globe_with_meridians: - Satellite imagery, historical data from several sources, vegetation infrared & index, image exports & comparison. 2 products:
    - [Playground](https://apps.sentinel-hub.com/sentinel-playground/) - Data discovery, playing around
    - [EO Browser](https://apps.sentinel-hub.com/eo-browser/) - Compare full resolution images from several sources (Landsat, Sentinel), make time lapses & export to GIF (free signup required).
    - See also the [custom scripts](https://github.com/sentinel-hub/custom-scripts) to highlight fire, snow, metals, type of terrain, etc.
- [Yandex Maps](https://yandex.com/maps) :globe_with_meridians: - Has a "Streetview" feature.

### Tools & techniques
- [Geographic Bounding Box Drawing Tool](http://automatingsint.com/blog/geographic-bounding-box-drawing-tool/)  :globe_with_meridians: - Draw a rectangle over a map and get the coordinates of its points & center.
- [Shadows and Angles: Measuring Object Heights from Satellite Imagery](https://www.gislounge.com/shadows-angles-measuring-object-heights-satellite-imagery/) :book: (GISLounge)
- [SunCalc](https://suncalc.org/) :globe_with_meridians: - Historical solar data (sun orientation & elevation, shadow length, etc).
- [TerraPattern](http://www.terrapattern.com/) :globe_with_meridians: - Scan large geographical areas for specific visual features using machine learning. Only available for 7 cities.

### User generated content
- [EchoSec](https://www.echosec.net/) :globe_with_meridians:💲 - Search and analyze social media data based on location. ($499/mo)
- [GeoCreepy](http://www.geocreepy.com/) :computer: - Geolocation information gathering through social networking platforms (discontinued).
- [OpenStreetMap](https://openstreetmap.org) :globe_with_meridians: - User-generated locations & maps. Use [taginfo](https://taginfo.openstreetmap.org) and/or [overpass-turbo.eu](https://overpass-turbo.eu/) - To search a location by key/value tags (see [OSM's Wiki](https://wiki.openstreetmap.org))
- Social networks ([see category](#social-networks))
- Tourism & review websites: [Foursquare](https://foursquare.com/), [TripAdvisor](https://www.tripadvisor.com/), [Yelp](https://www.yelp.com/), etc. :globe_with_meridians:
- [Vkontakte](https://vk.com) :globe_with_meridians: - Use `near:<coordinates>` in a  search.
- [Wikimapia](http://wikimapia.org/) :globe_with_meridians: - User-generated locations & descriptions. Has an API. Also allows to switch between satellite imagery from Google, Bing, OSM.


## Multi-purpose tools
- [Belati](https://github.com/aancw/Belati) :computer: - Command-line OSINT tool with whois, subdomain enumeration, mail harvesting, and more.
- [Buscador](https://inteltechniques.com/buscador/index.html) :computer: - A very handy VM with plenty of pre-installed & pre-configured OSINT tools.
- [DataSploit](https://github.com/DataSploit/datasploit) :computer: - A collection of python scripts which automate open source intelligence searches about domain names, email addresses, IP addresses and usernames.
- [Maltego CE](https://www.paterva.com/web7/buy/maltego-clients/maltego-ce.php) :computer: - Interactive data mining & mapping tool.
- [Spiderfoot](http://www.spiderfoot.net/) :computer: - Open source intelligence automation tool. Gathers intelligence about a given target, which may be an IP address, domain name, hostname, network subnet, ASN, e-mail address or person's name.

## Phone numbers
- [NumberWay](https://www.numberway.com/) :globe_with_meridians: - International directory of white pages and yellow pages phone books.
- [PhoneInfoga](https://github.com/sundowndev/PhoneInfoga) :computer: - Information gathering & OSINT reconnaissance tool for phone numbers.

## Pictures, Photos, Videos

### Metadata
- [Exiftool](http://owl.phy.queensu.ca/~phil/exiftool/) :computer: - Read and edit metadata. [Linode Tutorial](https://linoxide.com/linux-how-to/install-use-exiftool-linux-ubuntu-centos/)
- Exif Viewer ([Firefox](https://addons.mozilla.org/en-US/firefox/addon/exif-viewer/)/[Chrome](https://chrome.google.com/webstore/detail/exif-viewer/nafpfdcmppffipmhcpkbplhkoiekndck)) :computer:
- [Ghiro](https://github.com/ghirensics/ghiro) :computer: - Automated image forensics tool
- [Jeffrey's Image Metadata Viewer](http://exif.regex.info/exif.cgi) :globe_with_meridians:
- [StolenCameraFinder](https://www.stolencamerafinder.com/) :globe_with_meridians: - Search the web for pictures taken with a specific camera serial number

### Military/Weapons
- [CalibreObscura](https://www.calibreobscura.com/) :globe_with_meridians: - A blog about weapons & their uses in Middle East conflicts.
- [CamoPedia](http://www.camopedia.org) :globe_with_meridians: - Camouflage encyclopedia. Search & compare camouflage patterns.
- [How to Digitally Verify Combatant Affiliation in Middle East Conflicts](https://www.bellingcat.com/resources/how-tos/2018/07/09/digitally-verify-middle-east-conflicts/) :book:  (Bellingcat)
- [ICUS Camouflage Index](http://camouflageindex.camouflagesociety.org/index-2.html) :globe_with_meridians:
- [Immaga](https://imagga.com/auto-tagging-demo) :globe_with_meridians:💲 - Pictures auto-tagging tool (Demos + Free API Plan 2000 images/mo, or 14$/mo)
- [International Encyclopedia of Uniform Insignia](http://www.uniforminsignia.org/) :globe_with_meridians:
- [List of Comparative Military Ranks](https://en.wikipedia.org/wiki/List_of_comparative_military_ranks) :globe_with_meridians: (Wikipedia)
- Small Arms Survey’s [Weapon ID database](http://www.smallarmssurvey.org/weapons-and-markets/tools/weapons-id-database.html) :globe_with_meridians: - Search for small arms by caliber, type, location, etc.

### Reverse search
- [Bing Images](https://www.bing.com/images/) :globe_with_meridians: - Can search part of the image
- [CitizenEvidence](https://citizenevidence.amnestyusa.org/) :globe_with_meridians: - Google Images reverse search on Youtube thumbnails.
- [Google Images](https://images.google.com/) :globe_with_meridians:
- [IntelTechniques.com](https://inteltechniques.com/menu.html) :globe_with_meridians:- Various image search & reverse search tools and lists of resources.
- [TinEye](https://tineye.com/) :globe_with_meridians:
- [Yandex Images](https://yandex.com/images/) :globe_with_meridians:
### Search
- [How to Conduct Comprehensive Video Collection](https://www.bellingcat.com/resources/how-tos/2017/10/17/conduct-comprehensive-video-collection/) (Bellingcat) :book:
- [IntelTechniques.com](https://inteltechniques.com/menu.html) :globe_with_meridians: - Various video search & reverse search tools and lists of resources.
- [PimEyes](https://pimeyes.com) :globe_with_meridians: - Face-recognition matching search engine
- [SearchFace.ru](https://searchface.ru) :globe_with_meridians: - Face recognition search engine for the Russian VK social network. See this [guide](https://www.bellingcat.com/resources/how-tos/2019/02/19/using-the-new-russian-facial-recognition-site-searchface-ru/) from Bellingcat for a tutorial.
- [SocialMapper](https://github.com/SpiderLabs/social_mapper) :globe_with_meridians: - Social Media Mapping Tool that correlates profiles via facial recognition. Supports LinkedIn, Facebook, Twitter, Instagram, VKontakte, Weibo, Douban.
- [Youtube Geo Search Tool]( https://youtube.github.io/geo-search-tool/search.html) :globe_with_meridians: - Search YT videos by location & time frame.

### Verification & Analysis
- [Advanced Guide on Verifying Video Content](https://www.bellingcat.com/resources/how-tos/2017/06/30/advanced-guide-verifying-video-content/) :book: (Bellingcat)
- [How to verify photos and videos on social media networks](http://observers.france24.com/en/20151110-observers-guide-verifying-photos-videos-social-media-networks) :book: (France24)
- [InVID Verification Plugin](https://www.invid-project.eu/tools-and-services/invid-verification-plugin/) :computer: - Verification “Swiss army knife” Firefox extension.
- [Photo Verification Cheatsheet](https://firstdraftnews.org/wp-content/uploads/2017/03/FDN_verificationguide_photos.pdf) & [Video Verification Cheatsheet](https://firstdraftnews.org/wp-content/uploads/2017/03/FDN_verificationguide_videos.pdf) :book: (FirstDraftNews)
- [Verification 101](https://medium.com/1st-draft/verification-101-storyful-s-advice-for-checking-out-material-from-social-media-and-putting-it-750495792876) :book: - Storyful’s advice for checking out material from social media, and putting it into practice.
- [Verification Handbook](http://verificationhandbook.com/book/) :book: - Handbook by the European Journalism Centre about verifying digital content in emergency coverage.


## Social Networks

### General
- [Sherlock](https://sherlock-project.github.io/) :computer: - Search for a username across 135 social media sites.

### Facebook
- [Scrape Facebook with your browser](https://docs.google.com/presentation/d/15Uyk90ApliDE4AloCaNfDwSRDwp7b6QYAq0pfoVeQvQ/edit#slide=id.g1ba6b7ca38_0_226) :book: (J++)

### Github
- [gitrob](https://github.com/michenriksen/gitrob) :computer: - Find potentially sensitive files pushed to public repositories on Github. Requires a GitHub access token.
- [Zen](https://github.com/s0md3v/Zen) :computer: - Find emails of Github users.

### Instagram
- [InstaLooter](https://github.com/althonos/InstaLooter) :computer: - Download all pictures & videos from an Instagram profile. No API key needed.

### Linkedin
- [An Investigative Guide To LinkedIn](https://www.bellingcat.com/resources/how-tos/2019/03/21/bellingcats-invitation-is-waiting-for-your-response-an-investigative-guide-to-linkedin/) :book: (Bellingcat)
- [LinkedIn Operators Tip Sheet](https://booleanstrings.com/2018/12/06/linkedin-operators-one-more-tip-sheet/) :book:
- [raven](https://github.com/0x09AL/raven) :computer: - Linkedin information gathering tool. Extracts employee data for a given company.
- [The Endorser](https://github.com/eth0izzle/the-endorser) :computer: - Draw out relationships between people on LinkedIn via endorsements/skills.

### Reddit
- [Reddit Insight](https://www.redditinsight.com/#trackuser) :globe_with_meridians: - Collect info on a Reddit profile, list all posts & comments.
- [Reddit Investigator](http://www.redditinvestigator.com/) :globe_with_meridians: - Collect info on a Reddit profile.

### Twitter
- [tinfoleak](https://github.com/vaaguileradiaz/tinfoleak) :computer: - Very complete open-source tool for Twitter intelligence analysis. Needs API credentials.
- [twarc](https://github.com/DocNow/twarc) :computer::snake: - A command line tool and Python library for archiving Twitter in JSON format.
- [Tweetdeck](https://tweetdeck.twitter.com/) :globe_with_meridians:
- Tweetdeck [Location Search Tutorial](http://thoughtfaucet.com/search-twitter-by-location/tweetdeck-twitter-location-search-tutorial/) :book:
- [Tweets Analyzer](https://github.com/x0rz/tweets_analyzer) :computer: - Twitter profile analyzer: tweet activity, locations, most used hashtags, etc. Can save tweets to JSON. Requires a Twitter API key.
- [TWINT (Twitter Intelligence Tool)](https://github.com/twintproject/twint) :computer: - Advanced Twitter scraping tool, no API key needed. Can export to text, CSV, JSON, SQLite, Elasticsearch. Can detect emails, phone numbers, profiles.

## Text & Documents

### Indexing & searching
- [Aleph](https://github.com/alephdata/aleph) :computer: - A toolkit for data search, management and analysis in investigative reporting.
- [Blacklight](https://github.com/projectblacklight/blacklight) :computer: - Open source Solr user interface discovery platform.
- [Datashare](https://datashare.icij.org/) :computer: - Index & search documents on your computer, automatically detect people, organizations and locations with NLP.
- [DumpsterDiver](https://github.com/securing/DumpsterDiver) :computer: - Analyze big volumes of various file types in search of secrets, credentials, etc.
- [ICIJ Extract](https://github.com/ICIJ/extract) :computer: - A command line tool for parallelized, distributed content-extraction.
- [searchbox](https://github.com/StephenGrey/searchbox) :computer: - A simple out-of-the-box web interface to search through thousands of unstructured documents using Solr.

### OCR
- [NewOCR.com](https://www.newocr.com/) :globe_with_meridians: - Recognizes several languages, can resize images, shortcuts to Google & Bing Translate.
- [Tesseract](https://github.com/tesseract-ocr/tesseract) :computer: - Open-source OCR engine.

### PDF
- [PDF Text Extraction](https://r3mlab.github.io/python/osint/2018/08/09/PDF-text-extraction.html) with PyPDF2, Tika & PDF Miner. :computer:

### Text Processing & Analysis
- [topia](https://pypi.org/project/topia.termextract/) :snake: - Python module to determine important terms within a given piece of content.
- [TXM](http://textometrie.ens-lyon.fr/?lang=en) :computer: - Lexicometry and text statistical analysis for large bodies of text.

## Visualization

### Graphs
- [DataWrapper](https://www.datawrapper.de) :globe_with_meridians:💲 - Easy to use graph & map tool. Free plan available.
- [Google Fusion Tables](https://support.google.com/fusiontables/answer/2571232) - Create maps & charts from data. Will shut down on Dec. 2019.
- [Matplotlib](https://matplotlib.org/) :snake: - Python 2D plotting library. Best used with pandas in a Jupyter notebook.

### Maps
- [ArcGIS](https://www.esri.com/en-us/home) :computer:💲 - mapping & analysis software (proprietary, paid, 21-day trial)
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
- [Gephi](https://gephi.org/) :computer: - Powerful visualization and exploration software
- [Visual Investigative Scenarios](https://vis.occrp.org/) :globe_with_meridians: (OCCRP)
- [yEd Graph Editor](https://www.yworks.com/products/yed) :computer:


### Timelines
- [Tik Tok](https://datanews.github.io/tik-tok/) :computer: - Javascript tool to easily create simple, mobile-friendly, vertical timelines. Open-source.
- [TimelineJS](https://timeline.knightlab.com/) :computer:


## Weather
- [Wolfram Alpha](wolframalpha.com) :globe_with_meridians: - Weather history. *What was the weather in New York on January 1st 2017?*
- [Wunderground History](https://www.wunderground.com/history/) :globe_with_meridians: - Weather history


## Websites

### Dark Web & Onion services
- [OnionScan](https://github.com/s-rah/onionscan) :computer:
    - DarkWeb OSINT with Python & OnionScan :book: (AutomatingOSINT.com) - [part1](http://www.automatingosint.com/blog/2016/07/dark-web-osint-with-python-and-onionscan-part-one/) / [part2](http://www.automatingosint.com/blog/2016/08/dark-web-osint-with-python-part-two-ssh-keys-and-shodan/) / [part3](http://www.automatingosint.com/blog/2016/08/dark-web-osint-with-python-part-three-visualization/)

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
    - [How to use Google dork for hacking](http://www.tekgyd.com/2015/07/how-to-use-google-dork-for-hacking.html) :book: (tekgyd.com)
    - [Google Hacking Database](https://www.exploit-db.com/google-hacking-database/) :book: (Exploit.db)
    - [Google Search Operators: The Complete List](https://ahrefs.com/blog/google-advanced-search-operators/) :book: (ahrefs.com)
- [NerdyData Search](https://search.nerdydata.com/) :globe_with_meridians: - Search the source code of pages.
- [PublicWWW](https://publicwww.com/) :globe_with_meridians: - Search the source code of pages.
- [SpyOnWeb](http://spyonweb.com/) :globe_with_meridians: - Search by URL, IP address, analytics codes. API with free plan. See [this Belligcat how-to](https://www.bellingcat.com/resources/2017/07/31/automatically-discover-website-connections-tracking-codes/) for automation.
- [Sublist3r](https://github.com/aboul3la/Sublist3r) :computer: - Subdomains enumeration tool.
- [Unveiling hidden site connections with Google Analytics IDs](https://www.bellingcat.com/resources/how-tos/2015/07/23/unveiling-hidden-connections-with-google-analytics-ids/)  :book: (Bellingcat)
- Whois
:globe_with_meridians:/:computer: - Get registrar, owner info.


## Misc
- [awesome-selfhosted](https://github.com/Kickball/awesome-selfhosted) :pencil: - A list of Free Software network services and web applications which can be hosted locally
- [grayhatwarfare](https://buckets.grayhatwarfare.com/) :globe_with_meridians: - Search open Amazon S3 buckets content.
- [Shodan](https://www.shodan.io/) :globe_with_meridians: - Internet of Things search engine


## License

This list is under the [Creative Commons Attribution-NonCommercial 4.0 International Public License](LICENSE) License.
