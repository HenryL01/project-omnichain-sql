<h1>Project OmniChain: Global Logistics Optimizer</h1>

<h2>Executive Summary</h2>
<p>This project acts as an end-to-end supply chain diagnostic tool designed to uncover operational friction within a global e-commerce fulfillment network. By extracting and joining over 100,000 fragmented delivery and customer records, this analysis identifies regional shipping bottlenecks, calculates exact transit delays, and isolates profit erosion caused by disproportionate freight costs.</p>

<h2>Data Architecture (Raw Source Files)</h2>
<p>This analysis was built by extracting, cleaning, and joining the following normalized datasets:</p>
<ul>
    <li><code>olist_customers_dataset.csv</code></li>
    <li><code>olist_geolocation_dataset.csv</code></li>
    <li><code>olist_order_items_dataset.csv</code></li>
    <li><code>olist_order_payments_dataset.csv</code></li>
    <li><code>olist_order_reviews_dataset.csv</code></li>
    <li><code>olist_orders_dataset.csv</code></li>
    <li><code>olist_products_dataset.csv</code></li>
    <li><code>olist_sellers_dataset.csv</code></li>
    <li><code>product_category_name_translation.csv</code></li>
</ul>

<h2>The Business Problem</h2>
<p>Large-scale logistics networks frequently suffer from hidden inefficiencies. The objective of this project is to answer three core operational questions:</p>
<ul>
    <li><strong>Fulfillment Bottlenecks:</strong> What is the average delay between the "Order Placed" timestamp and the "Shipped" timestamp across different regions?</li>
    <li><strong>Customer Impact:</strong> Which geographic regions in Brazil experience the highest rate of late deliveries?</li>
    <li><strong>Profit Leakage:</strong> Which specific product categories suffer the worst profit margins when factoring in heavy freight costs?</li>
</ul>

<h2>Methodology & Tech Stack</h2>
<ul>
    <li><strong>Data Transformation (Backend):</strong> Used <strong>SQL</strong> to aggregate and clean the normalized relational database. Built complex <code>JOIN</code> queries to merge customer geolocation data with order fulfillment timestamps and payment/freight details.</li>
    <li><strong>Data Visualization (Frontend):</strong> Exported the aggregated master dataset into <strong>Tableau</strong> to build an interactive, executive-facing dashboard featuring geographic heatmaps and dynamic KPI trackers.</li>
</ul>

<hr>

<h2>About the Developer</h2>
<p>Developed by Xinyuan Liao[cite: 3], a student with a 3.98 GPA[cite: 4] currently transitioning to Industrial & Systems Engineering[cite: 2]. Driven by a passion for applying rigorous data science to large-scale business optimization[cite: 3], Xinyuan leverages hands-on experience as a Data Analytics Intern at Plus Therapeutics, Inc.[cite: 3, 4] and a technical background in Python and object-oriented programming[cite: 4] to build actionable enterprise data solutions.</p>
