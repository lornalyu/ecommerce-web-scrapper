# Web Scapper for Etsy

## Disclaimer
This e-commerce website Scraper is provided as-is for informational purposes only. Users are responsible for ensuring their use of the scraper complies with Etsy's Terms of Service, particularly regarding data scraping and API use. This project's maintainers do not endorse or condone the use of this tool for any activities that violate Etsy's conditions.

## Introduction
In this project, I did web scrapping to collect valuable data from Etsy, one of the most famous global online platforms for the sale and purchase of goods. Etsy is a live creative goods marketplace, including unique handmade things, vintage, and a high lot amount of craftwork items. With millions of buyers and sellers from around the world, there's a virtual treasure trove of unique items covering almost every known interest and passion. Their website helps humanity connect to sustainability with the promotion of small business and artisans and has really put them on the map for where to head when looking for something with personal flair.

This project aimed to extract detailed information about products listed under the "jewelry" category on Etsy. The extraction aimed at a wide range of key attributes, such as product names, original prices, current prices, discount rates, ratings, numbers of reviews, availability of free shipments, and product URLs. These characteristics would display the overall outlook of the product offerings, and at the same time, it allows doing detail analysis of the pricing strategies, customer satisfaction (as per the ratings and the count of reviews), and the prevalence of incentives, including the offer for free shipping.

![image](https://github.com/lornalyu/ecommerce-web-scrapper/assets/157392307/8feb3f62-0f6b-4a64-8a83-30bdc5ecb9c3)

<img width="1725" alt="image" src="https://github.com/lornalyu/ecommerce-web-scrapper/assets/157392307/460deda7-5479-403c-b7e6-ab4566ee5b6e">

## Sample for the scrapped file
<img width="1323" alt="image" src="https://github.com/lornalyu/ecommerce-web-scrapper/assets/157392307/5eb76762-825a-4e28-9bac-da0cff090d59">

## Insight from the dataset
In a meticulous examination of Etsy's bustling "jewelry" category, our project illuminates the nuanced marketplace dynamics, spotlighting pricing strategies, customer satisfaction metrics, and the strategic use of incentives. Here's what we've uncovered:

**There is a Striking Embrace of Discounts**. Among the myriad of listings analyzed, a significant portion leverages discounts, with an average discount rate revealing a marketplace in keen competition. This penchant for price adjustments not only illustrates the sellers' agility in attracting buyers but also reflects a broader strategy to stand out in an ocean of unique offerings. 

**Stellar ratings do not automatically translate to higher review volumes**. Delving deeper into customer feedback, we found that high ratings are a common thread, with most products boasting an impressive average rating. Yet, the correlation between high ratings and review counts is less direct than one might assume, indicating that stellar ratings do not automatically translate to higher review volumes. And it suggests that exceptional quality and unique product offerings are paramount in securing customer satisfaction.

**Free shipping does not significantly sway customer ratings.** A considerable number of listings offer free shipping, a tactic commonly employed to entice buyers. However, our analysis reveals that while prevalent, free shipping does not significantly sway customer ratings. 

**There are Diverse Tactics in a Creative Marketplace**. Our project not only peels back the layers of Etsy's "jewelry" category to reveal the pricing and marketing strategies at play but also highlights the marketplace's vibrant spirit of creativity and individuality. Sellers navigate the competitive landscape with a blend of tactical pricing, quality offerings, and targeted incentives, all while maintaining the unique charm that sets Etsy apart.

This exploration into Etsy's "jewelry" category not only demystifies the current state of affairs but also celebrates the marketplace's commitment to fostering a diverse and dynamic platform where creativity, craftsmanship, and customer satisfaction intertwine.

The dataset underpinning this analysis was meticulously curated from Etsy's "jewelry" category, leveraging web scraping techniques to extract detailed product information. 

## **Collection Date and Scope**
Data was collected on **March 17**, reflecting a snapshot of the marketplace at that time. To manage the scope of the project and ensure depth of analysis, the collection focused exclusively on the first page of listings within the "jewelry" category. This approach provided a representative sample of the current offerings and trends.

#### **Variables**
'Names', 'Original Prices', 'Current Prices', 'Discounts', 'Ratings', 'Review Counts', 'Free Shipping', 'URLs'
