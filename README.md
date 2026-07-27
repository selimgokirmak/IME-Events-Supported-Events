## 🤖 [IME Events Exhibitor List Scraper](https://apify.com/skython/ime-events-exhibitor-list-scraper)

Simple web scraper for extracting exhibitor data from trade show exhibitor lists provided by **IME Events**. Easily scrape company profiles including **company details, websites, social media links, product categories, and more**. 

Ideal for **B2B lead generation, market research, event networking, and competitive analysis**. Supports multiple **IME Events** exhibition websites with a consistent HTML structure.

> [Apify](https://apify.com/) is a cloud platform and marketplace for web scraping and automation tools.

---

## Contents

- [Features](#features)

- [Use Cases](#use-cases)

- [Supported Website Structure](#supported-website-structure)

- [Supported IME Events Exhibitions (Exhibitor Lists)](#supported-ime-events-exhibitions-exhibitor-lists)

- [Testing Exhibitor List URLs](#testing-exhibitor-list-urls-for-free)

- [Exhibitor List Scraper - All-In-One Version](#exhibitor-list-scraper---all-in-one-version)

- [Data Fields](#data-fields)

- [Example Output](#example-output)

- [My Other Exhibitor List Scrapers](#my-other-exhibitor-list-scrapers)

---

## Features

- Scrape all exhibitor profiles from supported IME Events event websites

- Extract detailed data from every exhibitor profile page

- Company primary information (address, website)

- Social media links (LinkedIn, Facebook, Instagram, Twitter)

- Two output formats (Single-Row & Multi-Row)

- Multi-Row format for Excel-friendly product category filtering

- Export to JSON, CSV, and Excel

---

## Use Cases

- **B2B Lead Generation:** Build targeted contact lists for marketing and sales outreach. 

- **Market Research:** Analyze exhibitors by product categories, brands, and sectors.  

- **Event Networking:** Familiarize yourself with exhibitors before attending trade fairs.  

- **Competitive Analysis:** Track competitor participation and product focus areas.

---

## Supported Website Structure

- This scraper is designed to extract data from exhibitor directories with the same HTML structure as the supported IME Events exhibitor lists below.

- Take a look at some of the event websites from the below list. Your event website URL might be in that list.

- If you are not sure about if this actor is capable of scraping your event URL, test it with [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor.

---

## Supported IME Events Exhibitions (Exhibitor Lists)

> The following partial list includes IME Events exhibitor directory URLs that have been tested so far. Other IME Events events or different events with the same website structure may also be supported.

> Some event URLs may have been updated or canceled entirely; please check them before using.

- [Adhesives And Bonding Expo 2026 Exhibitor List – adhesivesandbondingexpo.com](https://www.adhesivesandbondingexpo.com/exhibitor-list/)

- [Adhesives And Bonding Expo Europe 2026 Exhibitor List – adhesivesandbondingexpo-europe.com](https://www.adhesivesandbondingexpo-europe.com/exhibitor-list/)

- [Ceramics Expo 2026 Exhibitor List – ceramicsexpousa.com](https://www.ceramicsexpousa.com/exhibitor-list/)

- [Foam Expo Europe 2026 Exhibitor List – foam-expo-europe.com](https://www.foam-expo-europe.com/exhibitor-list/)

- [Foam Expo North America 2026 Exhibitor List – foam-expo.com](https://www.foam-expo.com/exhibitor-list/)

- [Space Tech Expo Europe 2026 Exhibitor List – spacetechexpo-europe.com](https://www.spacetechexpo-europe.com/exhibitor-list/)

- [Space Tech Expo USA 2026 Exhibitor List – spacetechexpo.com](https://www.spacetechexpo.com/exhibitor-list/)

- [Thermal Management Expo 2026 Exhibitor List – thermalmanagementexpo.com](https://www.thermalmanagementexpo.com/exhibitor-list/)

- [Thermal Management Expo Europe 2026 Exhibitor List – thermalmanagementexpo-europe.com](https://www.thermalmanagementexpo-europe.com/exhibitor-list/)

---

## Testing Exhibitor List URLs for FREE

- Since I have multiple exhibitor list scraper actors for different types of trade event websites, it might be hard to find the correct actor for your exhibitor list URL.

- Use [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor to test your exhibitor list URLs **for FREE** and see which scraper can process them.

---

## Exhibitor List Scraper - All-In-One Version

- I also provide an **All-In-One** version that combines **my 30+ exhibitor list scrapers** into a single actor.

- Instead of searching for the correct scraper for each event URL, simply provide the event URL and the actor automatically selects the appropriate scraper.

- ➡️ [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

---

## Data Fields

<table>
  <thead>
    <tr>
    <th><span style="font-size:14px;">Company</span></th>
    <th><span style="font-size:14px;">Social</span></th>
    <th><span style="font-size:14px;">Additional</span></th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td>Profile URL</td>
            <td>LinkedIn</td>
            <td>Hall Stands</td>
        </tr>
        <tr>
            <td>Company Name</td>
            <td>Facebook</td>
            <td>Product Categories</td>
        </tr>
        <tr>
            <td>Address</td>
            <td>Instagram</td>
            <td>Description</td>
        </tr>
        <tr>
            <td>Website</td>
            <td>Twitter / X</td>
            <td></td>
        </tr>
    </tbody>
</table>

---

## Example Output

```json
{
  "___exhibitor_profile_url": "https://www.adhesivesandbondingexpo-europe.com/exhibitor-list/exhibitor?boothid=a3RUK0000003P9x2AE",
  "__company_name": "Bestfoam SRL",
  "_company_address": "305100 Buzias, Buzias, Timis, 305100, Romania",
  "_company_country": "Romania",
  "_company_website": "http://www.bestfoam.ro",
  "_hall_stands": "210",
  "_social_url_linkedin": "https://www.linkedin.com/in/bestfoam-romania-088164238/",
  "_social_url_facebook": "https://www.facebook.com/bestfoamsrl",
  "_social_url_youtube": "https://www.youtube.com/@Bestfoam",
  "description": "Bestfoam is a European manufacturer of industrial knives and distributor of specialized...",
  "expo_type": "fme",
  "product_categories": [
    "Chemical Raw Materials",
    "Cutting Machines",
    "Machine Distributor"
  ]
}
```

---

## My Other Exhibitor List Scrapers

- [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

- [Koelnmesse Exhibitor List Scraper](https://apify.com/skython/koelnmesse-exhibitor-list-scraper)

- [Messe Frankfurt Exhibitor List Scraper](https://apify.com/skython/messe-frankfurt-exhibitor-list-scraper)

- [Map Your Show Exhibitor List Scraper](https://apify.com/skython/map-your-show-exhibitor-list-scraper)

- [Messe Düsseldorf Exhibitor List Scraper](https://apify.com/skython/messe-duesseldorf-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper](https://apify.com/skython/xporience-exhibitor-list-scraper)

- [Reed Expo Exhibitor List Scraper](https://apify.com/skython/reed-expo-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper V2](https://apify.com/skython/xporience-exhibitor-list-scraper-2)

- [Nürnberg Messe Exhibitor List Scraper](https://apify.com/skython/nuernberg-messe-exhibitor-list-scraper)

- [GSMA MWC Exhibitor List Scraper](https://apify.com/skython/gsma-mwc-exhibitor-list-scraper)

- [Messe Berlin Exhibitor List Scraper](https://apify.com/skython/messe-berlin-exhibitor-list-scraper)

- [AFAG Messe Exhibitor List Scraper](https://apify.com/skython/afag-messe-exhibitor-list-scraper)

- [Messe Stuttgart Exhibitor List Scraper](https://apify.com/skython/messe-stuttgart-exhibitor-list-scraper)

- [Messe Essen Exhibitor List Scraper](https://apify.com/skython/messe-essen-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper](https://apify.com/skython/informa-markets-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper V2](https://apify.com/skython/informa-markets-exhibitor-list-scraper-2)

- [Ungerboeck Exhibitor List Scraper](https://apify.com/skython/ungerboeck-exhibitor-list-scraper)

- [A2Z Events Exhibitor List Scraper](https://apify.com/skython/a2z-events-exhibitor-list-scraper)

- [Deutsche Messe Exhibitor List Scraper](https://apify.com/skython/deutsche-messe-exhibitor-list-scraper)

- [Newfront Exhibitor List Scraper](https://apify.com/skython/newfront-exhibitor-list-scraper)

- [Goeshow Exhibitor List Scraper](https://apify.com/skython/goeshow-exhibitor-list-scraper)

- [EasyFairs Exhibitor List Scraper](https://apify.com/skython/easyfairs-exhibitor-list-scraper)

- [IEG Expo Exhibitor List Scraper](https://apify.com/skython/ieg-expo-exhibitor-list-scraper)

- [The Smarter E Exhibitor List Scraper](https://apify.com/skython/the-smarter-e-exhibitor-list-scraper)

- [Schall Messen Exhibitor List Scraper](https://apify.com/skython/schall-messen-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper V2](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper-2)

- [Comexposium Exhibitor List Scraper](https://apify.com/skython/comexposium-exhibitor-list-scraper)

- [ANDMORE Exhibitor List Scraper](https://apify.com/skython/andmore-exhibitor-list-scraper)

- [Comexposium Exhibitor List Scraper V2](https://apify.com/skython/comexposium-exhibitor-list-scraper-2)

- [Informa Markets Exhibitor List Scraper V3](https://apify.com/skython/informa-markets-exhibitor-list-scraper-3)