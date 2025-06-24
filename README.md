# Customer-Segmentation-Analysis-Using-Clustering-RFM
------------------------------------------------------------------------------------------------

## Objective

To segment customers into meaningful groups based on purchasing behavior and demographics using **Kmeans Clustering**, **Hierarchical Clustering** and **RFM (Recency, Frequency, Monetary) analysis** for better strategic decisions in marketing and customer relationship management.

## Key Steps
### 1. Data Preprocessing
- Loaded and validated data types.
- Handled categorical features: encoded `gender` and `preferred_category`.
- Checked for missing values and outliers.

### 2. Exploratory Data Analysis (EDA)
- **Univariate Analysis**:
  - Histograms and KDE plots for age, income, spending score, etc.
  - Pie charts for categorical features like gender and preferred category.
- **Bivariate Analysis**:
  - Boxplots, lineplots, and heatmaps to identify interactions and trends.

### 3. Correlation Analysis
- Visualized correlation matrix.
- Found weak correlation among variables, justifying clustering.

### 4. KMeans Clustering
- Applied KMeans on scaled features.
- Determined optimal clusters using **Elbow Method** and **Silhouette Score**.
- Segmented customers into **4 groups**.

### 5. Hierarchical Clustering
- Used **Agglomerative Clustering** and plotted **Dendrogram**.
- Formed **2 major clusters** for broad segmentation.

### 6. RFM Analysis
- Derived Recency, Frequency, and Monetary value.
- Created segments such as:
  - VIP Customers
  - Loyal Customers
  - At-Risk
  - Lost Customers
  - Need Attention

------------------------------------------------------------------------------------------------

## Key Insights

- High-income, low-tenure customers are potential premium targets.
- Long-term members showed declining purchase value—need re-engagement.
- Largest customer group falls in “Mid-Value” requiring attention.
- RFM and KMeans segments aligned well with business logic.

------------------------------------------------------------------------------------------------

## Customer Profiles

### From KMeans:
| Segment | Description |
|---------|-------------|
| 0       | Mid-income, moderate engagement |
| 1       | Older customers, mid-frequency, high last purchase |
| 2       | High income, low membership, moderate frequency |
| 3       | High frequency, loyal long-term members |

### From RFM:
- **VIP/Potential**: High frequency & spend — retain with exclusive perks.
- **Loyal Customers**: Consistently purchasing — engage with rewards.
- **Need Attention**: Moderate value — target with reminders.
- **At Risk**: Previously valuable — reactivation needed.
- **Lost**: Minimal activity — deprioritize.

---

## Recommendations

- Launch **Loyalty Programs** for Clusters 2 and 3.
- Design **Campaigns** for “At Risk” and “Need Attention” segments.
- Promote **premium products** to high-income new customers.
- Use segmentation labels to personalize marketing communications.
