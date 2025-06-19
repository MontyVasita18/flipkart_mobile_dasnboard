# flipkart_mobile_dasnboard

---

## Power BI Dashboard Summary – Flipkart Mobiles Dataset

### Objective:

To visualize mobile phone data from Flipkart and answer key business questions using Power BI.

---

### 1. Price Range Segmentation

* A DAX column named `Price Segment` was created based on the `Selling Price`.

* Categories defined:

  * Low: Less than ₹10,000
  * Mid: ₹10,000 – ₹19,999
  * Upper Mid: ₹20,000 – ₹39,999
  * Premium: ₹40,000 and above

* **Visual Used**: Donut Chart

* **Purpose**: Shows the distribution of mobile phones across price categories.

---

### 2. Top Brands by Number of Models

* **Visual Used**: Bar Chart
* **Metric**: Count of unique models for each brand
* **Purpose**: Highlights which brand offers the most product models in the market.

---

### 3. Brands Covering All Price Segments

* **Visual Used**: Stacked Column Chart
* **Axis**: Brand
* **Legend**: Price Segment
* **Purpose**: Identifies brands that offer phones in low, mid, and premium price segments.

---

### 4. Common Specifications

* **RAM and Storage**: Displayed using bar charts
* **Ratings**: Shown through a bar or line chart representing average rating by brand
* **Purpose**: Reveals most popular configurations and the brands with the highest customer ratings.

---

### 5. Discount and Offers

* **Visual Used**: Scatter Plot
* **Fields**: Selling Price vs. Discount
* **Purpose**: Identifies the models with highest discounts and pricing patterns.

---

### Key DAX Formulas Used:

* `Price Segment`: Categorizes phones based on their selling price
* `Model Count`: Counts distinct phone models for each brand
* `Top Discounted`: Ranks phones based on highest discount values

---
