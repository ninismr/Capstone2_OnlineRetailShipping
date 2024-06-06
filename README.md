# Online Retail Shipping: Delivery Performance Analysis 
Capstone Project Module 2 - DTIDS Purwadhika (Mulya Fajar Ningsih Alwi)

In this project, I will position myself as a data analyst in a company. Based on the data obtained, I will formulate a series of questions according to the business needs and potential issues faced by the company. I will answer the questions posed by the company, create narratives and visualizations, and present insights from the analysis that stakeholders can use to make business decisions.

- [Tableau Dashboard Link (Click Here!)](https://public.tableau.com/views/Capstone2_OnlineRetailShipping-Mulya/Dashboard1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)
- [Tableau Story Link (Click Here!)](https://public.tableau.com/views/Capstone2_OnlineRetailShipping-Mulya/Story1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

## Business Background
The company specializes in the e-commerce sale of electronic goods. Known for a wide range of quality products at competitive prices, it serves customers across various regions. To ensure efficient delivery, the company manages its own warehouses and handles shipping directly, using land, sea, and air transportation.

Despite these efforts, the company has been facing shipment delays, affecting customer satisfaction. Recognizing the critical importance of timely delivery, the company aims to analyze the factors that influence shipping delays to make informed business decisions. This will help improve shipping performance and enhance the overall customer experience.

## Business Problem Statement
The company is facing challenges with delayed shipments and needs to understand the underlying reasons behind these delays. By identifying which shipments are delayed and analyzing their characteristics, the company aims to enhance its shipping process. This will enable the company to improve operational efficiency, reduce delays, and ultimately provide better service to its customers.

As a data analyst, our goal is to answer these critical questions:

1. What are the key factors contributing to shipping delays?
2. How can we optimize the shipping process to reduce delays?

By addressing these questions, we can provide actionable insights that will help the company enhance its shipping operations and meet customer expectations more effectively.

## Conclusion
1. **Delivery Status Overview:**
   - Most deliveries are late, making up about 60% of all shipments. This shows that there is a big problem with delays in delivering products.

2. **Key Factors in Shipping Delays:**
   - **Product Weight and Discount:**
      - We found two main things that affect delays: how much discount we offer on products and how heavy the products are.
      - If we offer big discounts, there is a higher chance of delays. On the other hand, heavier products are less likely to be late. Therefore,  if it is a lighter product, there is a higher chance of it being delayed.
      - Lighter products usually get bigger discounts, and they are more likely to be late. But heavier products, which usually get smaller discounts, are usually on time.

3. **Other Influencing Factors:**
   - **Warehouse Block and Shipping Mode:**
     - Many products are piling up in Warehouse Block E, and the shipment mode is heavily dominated by ship mode. This accumulation in a single warehouse block and reliance on just one shipment method may contribute to delivery delays. However, we cannot rely on this factor because there is no accurate data on how products are distributed across warehouses and shipment modes. Since the count of products in Block E is exactly twice of the other blocks, there is a possibility that one block is missing in the dataset. 
   - **Customer Calls and Prior Purchases:**
     - Some other factors like how many times a customer has bought from us before and how often customers call about their orders also matter, but they do not have a big impact on delays.
   - **Product Cost:**
     - Higher-cost products are slightly less prone to delays, but this also do not have a big impact on delays.

5. **Key Factors Assumptions:**

   - **Product Weight:** Lighter products might be more prone to getting lost, misplaced, or damaged, leading to delays. They might also be less of a priority for shipping staff compared to heavier, bulkier items that are easier to manage and track.
   - **Product Discount:** Higher discount products could be part of clearance sales or promotional offers, making them less profitable for the company. As a result, these items might not be prioritized for quick delivery. Additionally, higher discount products might be in higher demand, leading to inventory management issues and delays in shipping.

## Actionable Recommendation
1. **Limit Products in Light Weight Segment:** To increase on-time delivery rates, consider limiting the number of products in the light weight segment (products below 1839.5 grams). By focusing on heavier products, which have shown to be less likely to experience delays, the company can improve overall delivery performance.

2. **Adjust Discount Strategies:** Offer lower discounts on products to potentially reduce delays in delivery. Lower discounts not only correlate with better on-time delivery rates but also contribute to cost savings for the company. By optimizing discount strategies, the company can maintain profitability while improving delivery performance.

3. **Distribute Products Across Warehouses:** Instead of concentrating products in a single warehouse block, distribute them evenly across multiple blocks. This helps reduce crowdedness and blockages in the shipping process, leading to smoother operations and potentially faster deliveries.

4. **Diversify Shipment Modes:** Explore diversifying shipment modes beyond just relying on one dominant mode, such as the ship mode. By incorporating alternative modes like flights or road transport, the company can introduce flexibility and efficiency into the shipping process, reducing overall delivery times.

5. **Monitor Customer Calls:** Although customer calls show a weak correlation with delivery delays, it is still essential to monitor customer inquiries and feedback regarding shipment statuses. Addressing customer concerns promptly can help improve satisfaction and mitigate potential delays.
