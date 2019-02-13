# datajournalism-resources

A compilation of links to datajournalism & OSINT tools, guides and resources I find useful to keep at hand. Feel free to explore the list and to submit pull requests.

## Table of contents
- [APIs](#apis)
- [Archival](#archival)
- [Companies](#companies)
- [Data Analysis & Manipulation](#data-analysis-manipulation)
- [Email](#email)
- [Lists of tools & resources](#list-of-tools-resources)
- [Location, Maps, Satellite Imagery](#location-maps-satellite-imagery)
 - [Mapping services & software](#mapping-services-software)
 - [Tools & techniques](#tools-techniques)
 - [User generated content](#user-generated-content)
 - [Interpretation](#interpretation)
- [Multi-purpose tools](#multi-purpose-tools)
- [Pictures, Photos, Videos](#pictures-photos-videos)
 - [Search](#search)
 - [Metadata](#metadata)
 - [Reverse search](#reverse-search)
 - [Verification & Analysis](#verification-analysis)
 - [Military/Weapons](#military-weapons)
- [Social Media](#social-media)
 - [Facebook](#facebook)
 - [Twitter](#twitter)
 - [Instagram](#instagram)
- [Text & Documents](#text-documents)
- [Indexing & searching](#indexing-searching)
- [OCR](#ocr)
- [Natural Language Processing](#natural-language-processing)
- [PDF](#pdf)
- [Visualization](#visualization)
 - [Maps](#maps)
 - [Mindmaps & Network graphs](#mindmaps-network-graphs)
 - [Timelines](#timelines)
- [Weather](#weather)
- [Websites](#websites)
 - [Searches, info, related entities](#searches-info-related-entities)
 - [Scraping](#scraping)
 - [Dark Web & Onion services](#dark-web-onion-services)
- [Whistleblowing software](#whistleblowing-software)
- [Misc](#misc)


## APIs
- [Public APIs](https://github.com/abhishekbanthia/Public-APIs) : a categorized list of APIs.
- [Postman](https://www.getpostman.com/): API development environment offering useful tools for crafting and debugging API requests.
- [ProgrammableWeb](https://www.programmableweb.com): good API directory.

## Archival
- [Internet Archive Wayback Machine](https://web.archive.org/)
 - [waybackpack](https://github.com/jsvine/waybackpack) Command-line utility & python library to download content from the Wayback Machine. See [this example](https://www.bellingcat.com/resources/2016/12/06/vacuuming-image-metadata-wayback-machine/).
- [archive.today](https://archive.fo/): saves pages as screenshots, which is useful for social media websites the WayBack Machine can't handle.
- [Hunch.ly](https://www.hunch.ly/): web Capture Tool Designed For Online Investigations ($129.99/y).
- [How to Archive Open Source Materials](https://www.bellingcat.com/resources/how-tos/2018/02/22/archive-open-source-materials/) (Bellingcat)
- [Firefox Screenshots](https://screenshots.firefox.com/): Firefox can take a screenshot of a full page (i.e. 'scrolling' screenshot).


## Companies
- [OCCRP Data](https://data.occrp.org/): fantastic search tool & resources made available by OCCRP. Public records, leaks, scraped business registers, and more.
- [OpenCorporates](https://opencorporates.com/): a very comprehensive companies database. Has an [API](https://api.opencorporates.com/)
- [ICIJ's Offshore Leaks Database](https://offshoreleaks.icij.org/): data on offshore companies, foundations and trusts from the Panama Papers, the Offshore Leaks, the Bahamas Leaks and the Paradise Papers investigations.
- [List of company registers](https://en.wikipedia.org/wiki/List_of_company_registers) (Wikipedia): a list of all companies registers, by country.
- [CompaniesHouse Short Guide](https://www.bellingcat.com/resources/how-tos/2017/06/23/companies-house-short-guide/) (Bellingcat): guide about the UK online company registry.

## Data Analysis & Manipulation
- [OpenRefine](https://github.com/OpenRefine/OpenRefine): clean & transform messy data.
- [csvkit](https://github.com/wireservice/csvkit): a suite of command-line tools for converting to and working with CSV files.
- [pandas](https://pandas.pydata.org/): powerful Python data analysis library. Best used in a [Jupyter notebook](https://jupyter.org/).

## Email
- [theHarvester](https://github.com/laramies/theHarvester): Python command-line tool to search several search engines for mail addresses from a particular domain.
- [The most complete guide to finding anyone's email](https://www.blurbiz.io/blog/the-most-complete-guide-to-finding-anyones-email) (Blurbiz)

## Lists of tools & resources
- [IntelTechniques.com]( https://inteltechniques.com/menu.html): resources, links & OSINT tools, organized by target data. Check out [Buscador](https://inteltechniques.com/buscador/index.html), their very handy OSINT VM.
- Bellingcat's [Guides](https://bellingcat.com/category/resources/how-tos/). OSINT & Datajournalism how-tos. For a list of tools, see their [Online Investigation Toolkit (Google Doc)](https://docs.google.com/document/d/1BfLPJpRtyq4RFtHJoNpvWQjmGnyVkfE2HYoICKOGguA/edit)
- [awesome-osint](https://github.com/jivoi/awesome-osint): a curated list of open source intelligence tools and resources.
- [OSINT framework](https://osintframework.com/): Tree list of OSINT tools & resources.
- [OSINT Collection](https://github.com/Ph055a/OSINT-Collection): collection of OSINT related resources.
- I-Intelligence's [Open Source Intelligence Tools and Resources Handbook 2018](https://www.i-intelligence.eu/wp-content/uploads/2018/06/OSINT_Handbook_June-2018_Final.pdf): very complete lists of OSINT tools & resources, organized by category. No descriptions.
- [AutomatedOSINT.com](http://www.automatingosint.com/blog/): Blog about automating OSINT techniques using Python.

## Location, Maps, Satellite Imagery

### Mapping services & software
- [GoogleMaps](https://maps.google.com)
- [Google Earth](https://www.google.com/earth/)
 - [Google Earth Outreach](https://www.google.com/earth/outreach/learn/): Advanced Google Earth tutorials. Example: [Image & Photos Overlay](https://www.google.com/earth/outreach/learn/creating-photos-image-overlays-in-google-earth/)
 - [Google Earth Engine](https://earthengine.google.com/): Datasets, case studies, etc.
  - [GEarth Blog](https://www.gearthblog.com): resources & how-tos about Google Earth
- [DigitalGlobe Discover](https://discover.digitalglobe.com/): Search for satellite imagery of a particular location. Ability to download images (low-resolution compared to Google Earth).
- [Yandex Maps](https://yandex.com/maps): Google Streetview alternative.
- [SentinelHub](https://www.sentinel-hub.com/): satellite imagery, historical data from several sources, vegetation infrared & index, image exports & comparison. 2 products:
 - [Playground](https://apps.sentinel-hub.com/sentinel-playground/): data discovery, playing around
 - [EO Browser](https://apps.sentinel-hub.com/eo-browser/): compare full resolution images from several sources (Landsat, Sentinel), make time lapses & export to GIF (free signup required).
 - See also the [custom scripts](https://github.com/sentinel-hub/custom-scripts) to highlight fire, snow, metals, type of terrain, etc.

### Tools & techniques
- [Geographic Bounding Box Drawing Tool](http://automatingsint.com/blog/geographic-bounding-box-drawing-tool/) (AutomatingOSINT.com). Draw a rectangle over a map and get the coordinates of its points & center.
- [Shadows and Angles: Measuring Object Heights from Satellite Imagery](https://www.gislounge.com/shadows-angles-measuring-object-heights-satellite-imagery/)

### User generated content
- Foursquare, TripAdvisor, Yelp...
- [Wikimapia](http://wikimapia.org/): user-generated locations & descriptions. Has an API. Also allows to switch between satellite imagery from Google, Bing, OSM.
- [OpenStreetMap](https://openstreetmap.org):  user-generated locations & maps. Use [taginfo](https://taginfo.openstreetmap.org) and/or [overpass-turbo.eu](https://overpass-turbo.eu/) to search a location by key/value tags (see [OSM's Wiki](https://wiki.openstreetmap.org))
- [Vkontakte](https://vk.com): use `near:<coordinates>` in a  search
- [EchoSec](https://www.echosec.net/) ($499/mo): Search and analyze social media data based on location.
- [GeoCreepy](http://www.geocreepy.com/): Geolocation information gathering through social networking platforms (discontinued).

### Interpretation
- [Identify Burnt Villages on Satellite Imagery](https://www.bellingcat.com/resources/how-tos/2018/09/04/identify-burnt-villages-satellite-imagery%e2%80%8a-case-studies-california-nigeria-myanmar/) (Bellingcat)
- [Using Time Lapse Satellite Imagery to Detect Infrastructure Changes](https://www.bellingcat.com/resources/how-tos/2018/11/19/using-time-lapse-satellite-imagery-detect-infrastructure-changes-case-studies-via-myanmar-nigeria-south-china-sea) (Bellingcat)
- [Photo Interpretation Student Handbook](https://sites.miis.edu/geospatialtools2012/files/2012/07/Photo-Interpretation-Student-Handbook.-Photo-Interpretation-Principles.pdf) (US Defense Mapping Agency, 1996): Old unclassified handbook on analyzing aerial & satellite imagery. General principles & specifics for buildings, industries, transportation & communication facilities.

## Multi-purpose tools
- [Belati](https://github.com/aancw/Belati):  command-line OSINT tool with whois, subdomain enumeration, mail harvesting, and more.
- [Maltego](https://www.paterva.com/web7/buy/maltego-clients/maltego-ce.php): interactive data mining & mapping tool.
- [DataSploit](https://github.com/DataSploit/datasploit): a collection of python scripts that automate open source intelligence searches about domain names, email addresses, IP addresses and usernames.
- [Buscador](https://inteltechniques.com/buscador/index.html): a very handy VM with plenty of pre-installed & pre-configured OSINT tools.


## Pictures, Photos, Videos

### Search
- [PimEyes](https://pimeyes.com): face-recognition matching search engine
- [SocialMapper](https://github.com/SpiderLabs/social_mapper): Social Media Mapping Tool that correlates profiles via facial recognition. Supports LinkedIn, Facebook, Twitter, Instagram, VKontakte, Weibo, Douban.
- [How to Conduct Comprehensive Video Collection](https://www.bellingcat.com/resources/how-tos/2017/10/17/conduct-comprehensive-video-collection/) (Bellingcat)
- [Youtube Geo Search Tool]( https://youtube.github.io/geo-search-tool/search.html):
Search YT videos by location & time frame.
- [IntelTechniques.com](https://inteltechniques.com/menu.html):
Various video search & reverse search tools and lists of resources.

### Metadata
- Exif Viewer ([Firefox](https://addons.mozilla.org/en-US/firefox/addon/exif-viewer/)/[Chrome](https://chrome.google.com/webstore/detail/exif-viewer/nafpfdcmppffipmhcpkbplhkoiekndck))
- [Jeffrey's Image Metadata Viewer](http://exif.regex.info/exif.cgi)
- [Exiftool](http://owl.phy.queensu.ca/~phil/exiftool/): Read and edit metadata. [Linode Tutorial](https://linoxide.com/linux-how-to/install-use-exiftool-linux-ubuntu-centos/)
- [StolenCameraFinder](https://www.stolencamerafinder.com/): Search the web for pictures taken with a specific camera serial number
- [Ghiro](https://github.com/ghirensics/ghiro): Automated image forensics tool
- Thunar Custom Actions: [Exiftool](https://www.linuxliteos.com/forums/tutorials/thunar-custom-action-for-viewing-a-file's-copyright-or-exif-information/), [ffmpeg](https://help.ubuntu.com/community/ThunarCustomActions#Grab_Metadata_From_Media_File)

### Reverse search
- [IntelTechniques.com](https://inteltechniques.com/menu.html):
Various image search & reverse search tools and lists of resources.
- [Google Images](https://images.google.com/)
- [TinEye](https://tineye.com/)
- [Bing Images](https://www.bing.com/images/) Can search part of the image
- [CitizenEvidence](https://citizenevidence.amnestyusa.org/): Google Images reverse search on Youtube thumbnails.

### Verification & Analysis
- [InVID Verification Plugin](https://www.invid-project.eu/tools-and-services/invid-verification-plugin/): verification “Swiss army knife”.
- FirstDraftNews: [Photo Verification Cheatsheet](https://firstdraftnews.org/wp-content/uploads/2017/03/FDN_verificationguide_photos.pdf) & [Video Verification Cheatsheet](https://firstdraftnews.org/wp-content/uploads/2017/03/FDN_verificationguide_videos.pdf). Also offers verification courses.
- [How to verify photos and videos on social media networks](http://observers.france24.com/en/20151110-observers-guide-verifying-photos-videos-social-media-networks) (France24)
- [Advanced Guide on Verifying Video Content](https://www.bellingcat.com/resources/how-tos/2017/06/30/advanced-guide-verifying-video-content/) (Bellingcat)
- [Verification Handbook](http://verificationhandbook.com/book/): Handbook by the European Journalism Centre about verifying digital content in emergency coverage.
- [Verification 101](https://medium.com/1st-draft/verification-101-storyful-s-advice-for-checking-out-material-from-social-media-and-putting-it-750495792876): Storyful’s advice for checking out material from social media, and putting it into practice

### Military/Weapons
- [How to Digitally Verify Combatant Affiliation in Middle East Conflicts](https://www.bellingcat.com/resources/how-tos/2018/07/09/digitally-verify-middle-east-conflicts/) (Bellingcat)
- [CamoPedia](http://www.camopedia.org): Camouflage encyclopedia. Search & compare camouflage patterns. See also the [ICUS Camouflage Index](http://camouflageindex.camouflagesociety.org/index-2.html)
- [International Encyclopedia of Uniform Insignia](http://www.uniforminsignia.org/). See also [List of Comparative Military Ranks](https://en.wikipedia.org/wiki/List_of_comparative_military_ranks)
- Small Arms Survey’s [Weapon ID database](http://www.smallarmssurvey.org/weapons-and-markets/tools/weapons-id-database.html): search for small arms by caliber, type, location, etc.
- [Immaga](https://imagga.com/auto-tagging-demo): pictures auto-tagging (Demos + Free API Plan 2000 images/mo, or 14$/mo)


## Social Media

### Facebook
- J++: [Scrape Facebook with your browser](https://docs.google.com/presentation/d/15Uyk90ApliDE4AloCaNfDwSRDwp7b6QYAq0pfoVeQvQ/edit#slide=id.g1ba6b7ca38_0_226)

### Twitter
- [Tweetdeck](https://tweetdeck.twitter.com/)
- Tweetdeck [Location Search Tutorial](http://thoughtfaucet.com/search-twitter-by-location/tweetdeck-twitter-location-search-tutorial/)
- [Tweets Analyzer](https://github.com/x0rz/tweets_analyzer): Twitter profile analyzer: tweet activity, locations, most used hashtags, etc. Can save tweets to JSON. Requires a Twitter API key.
- [TWINT (Twitter Intelligence Tool)](https://github.com/twintproject/twint): advanced Twitter scraping tool, no API key needed. Can export to text, CSV, JSON, SQLite, Elasticsearch. Can detect emails, phone numbers, profiles.
- [twarc](https://github.com/DocNow/twarc): a command line tool (and Python library) for archiving Twitter in JSON format.

### Instagram
- [InstaLooter](https://github.com/althonos/InstaLooter): download all pictures & videos from an Instagram profile. No API key needed.

## Text & Documents

### Indexing & searching
- [Aleph](https://github.com/alephdata/aleph): A toolkit for data search, management and analysis in investigative reporting.
- [Blacklight](https://github.com/projectblacklight/blacklight): open source Solr user interface discovery platform.
- [ICIJ Extract](https://github.com/ICIJ/extract): a command line tool for parallelized, distributed content-extraction.
- [searchbox](https://github.com/StephenGrey/searchbox): a simple out-of-the-box web interface to search through thousands of unstructured documents using Solr.

### OCR
- [NewOCR.com](https://www.newocr.com/): recognize several languages, resize images, shortcuts to Google & Bing Translate.
- [Tesseract](https://github.com/tesseract-ocr/tesseract): open-source OCR engine.

### Natural Language Processing
- [topia](https://pypi.org/project/topia.termextract/): Python module to determine important terms within a given piece of content.

### PDF
- [PDF Text Extraction](https://r3mlab.github.io/python/osint/2018/08/09/PDF-text-extraction.html) with PyPDF2, Tika & PDF Miner.

## Visualization

### Maps
- Google Sheets, Google MyMaps, Google Fusion Tables, Google Earth...
- [KML Interactive Sampler](https://googlemaps.github.io/kml-samples/interactive/index.html): Lots of KML templates
- [Excel Powermap Plugin](http://geoawesomeness.com/geoawesomehowto-how-to-make-a-killer-map-using-excel-in-under-5-minutes-with-powermap-plugin/)
- [ArcGIS](https://www.esri.com/en-us/home): mapping & analysis software (proprietary, paid, 21-day trial)
- [QGIS](https://www.qgis.org/en/site/about/index.html): free & open-source alternative to ArcGis.

### Mindmaps & Network graphs
- [Visual Investigative Scenarios](https://vis.occrp.org/) (by OCCRP, online)
- [yEd Graph Editor](https://www.yworks.com/products/yed) (PC, Mac, Linux)
- [Gephi](https://gephi.org/)

### Timelines

- [TimelineJS](https://timeline.knightlab.com/)
- [Tik Tok](https://datanews.github.io/tik-tok/): Javascript tool to easily create simple, mobile-friendly, vertical timelines. Open-source.

## Weather
- [Wunderground History](https://www.wunderground.com/history/): weather history
- [Wolfram Alpha](wolframalpha.com): weather history. ("What was the weather in New York on January 1st 2017 ?")

## Websites

### Searches, info, related entities
- Advanced Google searches
 - [Google Search Operators](https://moz.com/learn/seo/search-operators) (moz.com)
 - [Mastering Google Search Operators in 67 steps](https://moz.com/blog/mastering-google-search-operators-in-67-steps) (moz.com)
 - [How to use Google dork for hacking](http://www.tekgyd.com/2015/07/how-to-use-google-dork-for-hacking.html) (tekgyd.com)
 - [Google Hacking Database](https://www.exploit-db.com/google-hacking-database/) (Exploit.db)
- whois (Registrar, owner info)
- [SpyOnWeb](http://spyonweb.com/): search by URL, IP address, analytics codes. API with free plan. See [this Belligcat how-to](https://www.bellingcat.com/resources/2017/07/31/automatically-discover-website-connections-tracking-codes/) for automation.
- [NerdyData Search](https://search.nerdydata.com/): search the source code of pages.
- [PublicWWW](https://publicwww.com/): search the source code of pages.
- [Unveiling hidden site connections with Google Analytics IDs](https://www.bellingcat.com/resources/how-tos/2015/07/23/unveiling-hidden-connections-with-google-analytics-ids/) (Bellingcat)

### Scraping
- [Scrape Interactive Geospatial Data](https://www.bellingcat.com/resources/how-tos/2018/09/05/scrape-interactive-geospatial-data/) (Bellingcat)

### Dark Web & Onion services
- [OnionScan](https://github.com/s-rah/onionscan)
 - AutomatingOSINT.com: DarkWeb OSINT with Python & OnionScan ([part1](http://www.automatingosint.com/blog/2016/07/dark-web-osint-with-python-and-onionscan-part-one/)/[part2](http://www.automatingosint.com/blog/2016/08/dark-web-osint-with-python-part-two-ssh-keys-and-shodan/)/[part3](http://www.automatingosint.com/blog/2016/08/dark-web-osint-with-python-part-three-visualization/))


## Whistleblowing software
- [GlobaLeaks](https://www.globaleaks.org/)
- [SecureDrop](https://securedrop.org)

## Misc
- [Shodan](https://www.shodan.io/): Internet of Things search engine
- [grayhatwarfare](https://buckets.grayhatwarfare.com/): Search open Amazon S3 buckets content.
- [awesome-selfhosted](https://github.com/Kickball/awesome-selfhosted): a list of Free Software network services and web applications which can be hosted locally




## License

This list is under the [Creative Commons Attribution-NonCommercial 4.0 International Public License](LICENSE) License.
