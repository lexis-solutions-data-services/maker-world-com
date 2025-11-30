## 📊 Actor Stats

| Stat | Value |
|------|-------|
| **Version** | `0.0.2` |
| **Last Update** | Nov 30, 2025 |

---


# Maker World Scraper

![banner](https://i.ibb.co/jZTZFqfw/makerworld.png)

🔎 **What is the Maker World Scraper?**

The Maker World Scraper Actor is a web scraping tool designed to collect 3D model listings from Maker World, a popular platform for sharing and discovering 3D printable designs. Using advanced web scraping techniques, the actor extracts detailed model information including design metadata, creator profiles, and download statistics.

<p align="center">
  <img src="https://apify-image-uploads-prod.s3.us-east-1.amazonaws.com/DevbkY3adMTBuoECt-actor-kaWhk7mVwkunRR06b-cpArEe6XzQ-images-15.png" alt="MakerWorld.com Scraper" style="height: 60px; margin-right: 15px;" /><a href="https://apify.com/lexis-solutions/maker-world-com" target="_blank">
    <img src="https://img.shields.io/badge/Try%20it%20on-Apify-0066FF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDA4IiBoZWlnaHQ9IjQwOCIgdmlld0JveD0iMCAwIDQwOCA0MDgiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxnIGNsaXAtcGF0aD0idXJsKCNjbGlwMF8zNDFfNDE1NykiPgo8cGF0aCBkPSJNMjE4LjY5NSAxMDRIMzAwLjk3QzMwMi42NDMgMTA0IDMwNCAxMDUuMzU3IDMwNCAxMDcuMDNWMjMyLjc2NkMzMDQgMjM1Ljc3OCAzMDAuMDgzIDIzNi45NDUgMjk4LjQzNCAyMzQuNDI1TDIxNi4xNTkgMTA4LjY5QzIxNC44NDEgMTA2LjY3NCAyMTYuMjg3IDEwNCAyMTguNjk1IDEwNFoiIGZpbGw9IndoaXRlIi8+CjxwYXRoIGQ9Ik0xODkuMzA1IDEwNEgxMDcuMDNDMTA1LjM1NyAxMDQgMTA0IDEwNS4zNTcgMTA0IDEwNy4wM1YyMzIuNzY2QzEwNCAyMzUuNzc4IDEwNy45MTcgMjM2Ljk0NSAxMDkuNTY2IDIzNC40MjVMMTkxLjg0IDEwOC42OUMxOTMuMTU5IDEwNi42NzQgMTkxLjcxMyAxMDQgMTg5LjMwNSAxMDRaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMjAyLjU5MSAyMDQuNjY4TDEwOS4xMjcgMjk4LjgzNUMxMDcuMjI5IDMwMC43NDcgMTA4LjU4MyAzMDQgMTExLjI3OCAzMDRIMjk2LjhDMjk5LjQ4MyAzMDQgMzAwLjg0MiAzMDAuNzcgMjk4Ljk2NyAyOTguODUyTDIwNi45MDggMjA0LjY4NUMyMDUuNzI2IDIwMy40NzUgMjAzLjc4MiAyMDMuNDY4IDIwMi41OTEgMjA0LjY2OFoiIGZpbGw9IndoaXRlIi8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDBfMzQxXzQxNTciPgo8cmVjdCB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEwNCAxMDQpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==&logoColor=white" alt="Try it on Apify" style="border-radius: 12px; height: 60px;" />
  </a>
</p>


🧾 **What Data Can the Maker World Scraper Extract?**

The actor extracts the following comprehensive data from Maker World model pages:

- **Model Information:** Title, ID, Model ID, Creation Date, License Type
- **Design Creator:** Name, Avatar, Fan Count, Follow Count, Level, Certification Status
- **Model Statistics:** Download Count, Comment Count, Like/Dislike Status
- **Categories & Tags:** Primary categories and detailed tag lists
- **Model Properties:** Printability, Exclusivity, AI-Generated Content Status
- **Media:** Primary image URL and design details
- **URLs:** Direct links to model pages

💼 **What Use Cases Does the Maker World Scraper Actor Support?**

The Maker World Scraper Actor is perfect for:

- **3D Printing Communities:** Track trending designs and popular creators across the platform
- **Design Analysis:** Analyze design patterns, categories, and user preferences in the 3D printing space
- **Creator Intelligence:** Monitor top designers, their follower growth, and content performance
- **Market Research:** Understand trending topics, popular categories, and design preferences
- **Content Aggregation:** Build comprehensive databases of 3D printable models for research or commercial use
- **Competitive Analysis:** Track competitor designs and understand market positioning

📖 **How to Use the Maker World Scraper Actor**

1. **Create a Free Apify Account:** Sign up on the Apify platform
2. **Open the Maker World Scraper Actor:** Navigate to your actor's page
3. **Input Your Query:** Provide Maker World URLs (category pages, search pages, or detail pages).
4. **Start the Run:** Click "Start" to launch the scraping process
5. **Download Your Results:** Access the data in JSON, CSV, or via the Apify API

📥 **Input**

You can run the actor by providing a Maker World model URL. Example parameters:

```json
{
  "startUrls": [
    {
      "url": "https://makerworld.com/en/3d-models/901-3d-printer-accessories" // category page
    },
    {
      "url": "https://makerworld.com/en/search/models?keyword=halloween"  // search page
    },
    {
      "url": "https://makerworld.com/en/models/652863-the-forbidden-fruit#profileId-579671" // detail page
    }
  ],
  "maxItems": 5
}
```

📤 **Output**

The results are stored in the default dataset associated with the actor. Each model listing includes:

```json
{
  "url": "https://makerworld.com/en/models/1604781-desiccant-container-with-hygrometer#profileId-1692089",
  "title": "Desiccant Container with Hygrometer",
  "id": 1604781,
  "modelId": "US46884f49b9e1ad",
  "createdAt": "2025-07-14T08:57:53Z",
  "hasBacked": false,
  "hasCollect": false,
  "hasDislike": false,
  "hasLike": false,
  "downloadCount": 14,
  "isAIGC": false,
  "isAlreadyRedeemed": false,
  "isExclusive": true,
  "isFeaturedBoms": false,
  "isFeaturedCyberBrick": false,
  "isOfficial": false,
  "isPointRedeemable": false,
  "isPrintable": true,
  "isStaffPicked": false,
  "license": "Standard Digital File License",
  "commentCount": 0,
  "categories": ["3D Printer Accessories", "3D Printer"],
  "primaryImage": "https://makerworld.bblmw.com/makerworld/model/US46884f49b9e1ad/design/2025-07-14_ce645b8e4711d8.png",
  "designCreator": {
    "uid": 1388703163,
    "name": "JANBERRY DESIGN",
    "avatar": "https://public-cdn.bblmw.com/avatar/1388703163/2025-03-10_737153dbeed59.png",
    "fanCount": 5867,
    "followCount": 4,
    "isFollowed": false,
    "isBlacklist": false,
    "certificated": false,
    "handle": "user_1388703163",
    "level": 25,
    "gradeType": 4,
    "canBeSubscribed": true,
    "availableCreatorMembershipLevelCnt": 0,
    "gotoPersonalHomepage": true
  },
  "tags": [
    "desiccant",
    "desiccant accessories",
    "desiccant accessory",
    "desiccant container",
    "desiccant box",
    "Desiccant Case",
    "hygrometer",
    "thread",
    "spool",
    "BAMBU",
    "BAMBULAB",
    "bambu spool",
    "spool accesory",
    "spool accessories",
    "bambu spool accessory",
    "bambu filament",
    "dry",
    "dry box",
    "dry case",
    "dry container",
    "AMS",
    "printer",
    "printer accesories",
    "ps1",
    "A1",
    "X1",
    "shoe",
    "shoe dryer",
    "shoe drying",
    "drying"
  ]
}
```

## How Many Results Can I Scrape?

The actor is designed to scrape individual model pages efficiently. For bulk scraping, you can provide multiple URLs or integrate with search functionality to collect comprehensive datasets of Maker World models.

## Need to scrape more data from other platforms?

👉 Scrape Google ads with [Google Ads Scraper](https://apify.com/lexis-solutions/google-ads-scraper)

### FAQ

**Is Scraping Maker World Legal?**
The Maker World Scraper Actor only retrieves public data that is openly available on Maker World. We recommend reviewing Maker World's Terms of Service before running the actor.

**Who Should Use This Actor?**
This tool is ideal for 3D printing enthusiasts, designers, researchers, and businesses who need comprehensive data about 3D printable models and their creators.

**How Fast is the Scraper?**
Designed for efficiency, the actor includes built-in delays to prevent overloading target servers while maintaining quick data retrieval.

**Can I Scrape Multiple Models at Once?**
Yes, the actor can process multiple model URLs in a single run, making it efficient for bulk data collection.

👀 **p.s.**

Got feedback or need an extension?

Lexis Solutions is a [certified Apify Partner](https://apify.com/partners/find). We can help you with custom solutions or data extraction projects.

Contact us over [Email](mailto:scraping@lexis.solutions) or [LinkedIn](https://www.linkedin.com/company/lexis-solutions)

## Support Our Work 💝

If you're happy with our work and scrapers, you're welcome to leave us a company review [here](https://apify.com/partners/find/lexis-solutions/review) and leave a review for the scrapers you're subscribed to. It will take you less than a minute but it will mean a lot to us!
