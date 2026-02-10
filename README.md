<h1>Behavioral Churn Radar</h1>
<h4>The Behavioral Churn Radar Dashboard is an end-to-end analytics solution designed to analyze subscription churn by combining user behavior, operational friction, and payment stability. The dashboard enables both high-leve monitoring and deep-dive analysis to help identify not only how much churn is occurring, but why it happens and which users are most at risk.</h4>

<h3>Purpose:</h3>
<h4>The primary goal of this dashboard is to move beyond reactive churn reporting and support proactive retention decision-making. It helps stakeholders understand overall subscription health, quantify revenue exposure, detect early churn risk signals, and priotize retenion efforts before customer loss occurs.</h4>

<h3>Tech Stack:</h3>
<h4>
  <ul>
    <li>Power BI: Data modeling, DAX calculations, and interactive dashboard design</li>
    <li>DAX: CHurn metrics, risk scoring, and derived logic</li>
    <li>Excel: Source data preparation and structuring</li>
</ul></h4>

<h3>Data Source:</h3>
<h4>This project uses a synthetic subscription dataset designed to simulate real-world SaaS churn scenarios. The data includes multiple fact tables representing different dimensions of customer interaction:
<ul>
  <li>Subscriptions – User plans, churn status, and revenue</li>
  <li>User Activity – Daily engagement metrics such as sessions, features used, and time spent</li>
  <li>Support Tickets – Customer support interactions and resolution times</li>
  <li>Payments – Payment outcomes indicating billing stability</li>
</ul>
The dataset was manually created for learning and portfolio demonstration purposes and does not contain any real customer information.</h4>

<h3>Features & Highlights</h3>
<h4>Two-Level Dashboard Structure<br><br>
<img src="https://github.com/IshitaSinha2002/Behavioral-Churn-Radar-Dashboard/blob/main/Main%20Page%20SS.png" alt=""><br><br>
Page 1: Subscription Intelligence<br><br>
<img src="https://github.com/IshitaSinha2002/Behavioral-Churn-Radar-Dashboard/blob/main/Churn%20Risk%20Deep%20Dive%20SS.png" alt=""><br><br>
This page provides a high-level overview of subscription health and churn performance. It includes key summary metrics such as Total Active Users, Total Churned Users, Churn Rate, and Revenue at Risk to quickly assess business impact. Trend and distribution visuals such as Churn Trend over Time, Churn by Subscription Plan, Payment Outcome Distribution, and Support Ticket Types help identify patterns across time, pricing tiers, billing stability, and customer support interactions. <br><br>
Page 2: Churn Risk Deep Dive<br><br>
<img src="https://github.com/IshitaSinha2002/Behavioral-Churn-Radar-Dashboard/blob/main/Churn%20Risk%20Deep%20Dive%20SS.png" alt=""><br><br>
This page focuses on identifying and explaining future churn risk among active users. It highlights High-Risk Active Users and associated Revenue at Risk, along with operational and behavioral indicators driving that risk. Visuals such as Payment Stability Trend and Support Ticket Types for High-Risk Users surface friction and billing issues, while engagement-focused metrics including Average Sessions, Feature Usage Depth, Average Time Spent, and Average Resolution Time explain how declining usage and service experience contribute to churn risk.
</h4>
