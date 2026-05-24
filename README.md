# telecom-analysis

**OBJETIVE:**
Identify usage patterns, detect atypical behaviors, and understand which customer segments exhibit differentiated needs, in order to optimize the commercial offer and improve the user experience.

**Databases used**

plans.csv: Current plans (price, included minutes, included GB, cost per extra).
users_latam.csv: Customer information: age, city, registration date, plan subscribed to.
usage.csv: Actual usage details: calls (duration) and messages (length).

**Stages completed**
- Integrate and clean databases from three different sources.
- Apply validation techniques, standardize data types, and detect inconsistent values.
- Build a statistical profile of usage (calls and messages) by customer and demographic segment.
- Detect outliers and atypical behavior using statistical and visual methods.
- Create customer segments based on age, country, and usage behavior.
- Visualize differences between segments and extract relevant business insights.

**How to reproduce the analysis**

1. Open `notebooks/telecom-analysis.ipynb`
2. Run the cells in order
3. The notebook automatically loads the dataset from `/data/` or a public link (as appropriate)
