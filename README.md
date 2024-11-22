# Adobe Revenue Analysis
This project examines Adobe's revenue trends between 2022 and 2024 to identify the products and geographic regions driving growth.

Founded in 1982 by John Warnock and Charles Geschke, Adobe specialises in software for content creation and publication, including graphics, photography, animation, video, and print. By focusing on Adobe's two primary subscription-based service categories—Digital Media (Creative Cloud, Document Cloud) and Digital Experience —this analysis pinpoints which offerings have contributed most to Adobe’s revenue. Additionally, the project explores regional revenue performance to uncover dominant markets like the Americas and their impact on Adobe's global strategy.

With these insights, Adobe can make data-driven decisions for marketing, sales, and pricing strategies as they plan for the upcoming fiscal year. By understanding product-level and regional revenue drivers, the company can allocate resources effectively, enhance market focus, and refine pricing models to sustain and accelerate growth.


## Data Creation and Structure

A self-made dataset was created by researching and compiling Adobe's financials from Adobe Investor Relations press releases. The practice my SQL skills and enable effective analysis, the dataset was structured into four tables: 

1. **Date Dimension Table**  
   - Contains sales dates for each starting week.  
   - Includes the quarter and fiscal year each date falls into.  

2. **Product Dimension Table**  
   - Features Adobe's parent products (**Digital Media** and **Digital Experience**).  
   - Breaks down into sub-products (e.g., **Creative Cloud** and **Document Cloud** under Digital Media).  

3. **Region Dimension Table**  
   - Lists geographic regions such as **Americas**, **EMEA**, and **Asia**.  

4. **Revenue Table**  
   - Stores revenue values for each product, region, and date combination.
     
  
<img width="955" alt="Screenshot 2024-11-22 at 19 17 19" src="https://github.com/user-attachments/assets/047922b0-08fc-4730-83c8-fb4966f01b7a">


  
## Insights Summary 

1. **Product-Level Revenue Growth:**
   
   -  Digital Media (DMe) has consistently driven more revenue growth compared to Digital Experience (DEx) over the analyzed period.
   -  Within Digital Media, Creative Cloud significantly outperforms Document Cloud, showing steady revenue growth and greater contribution to overall revenue.
   -  Year-over-year growth trends show sustained increases in Digital Media revenue, indicating that these products are core growth drivers.
     
3. **Regional Revenue Trends:**
   
   - The Americas generate significantly higher revenue than Asia and EMEA combined, maintaining a dominant position in Adobe’s geographic revenue distribution.
   - Asia and EMEA show slower revenue growth trends, highlighting potential opportunities for market expansion or targeted strategies to boost their performance.
     
5. **Year-over-Year Growth:**
   
   - Digital Media products exhibit stronger year-over-year growth compared to Digital Experience, with Creative Cloud showing the most pronounced increase.
   - Regional growth in the Americas is consistent, but Asia and EMEA display more modest increases, signaling potential areas to explore for scaling.
