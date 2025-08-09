# StartUp_Funding
Tkinter-based app to upload, clean, analyze, and visualize startup funding datasets with Pandas, Seaborn, and Matplotlib insights.
Here’s a clear description you can use for your Tkinter-based **Startup Funding Analysis** project:

### **Key Features:**

1. **Upload Dataset**

   * Load CSV datasets from Kaggle or any other source.
   * Displays original and cleaned column names, data types, and sample rows in the GUI text area.

2. **Show Cleaning Steps**

   * Identifies issues in the dataset such as:

     * Columns with spaces or irregular names
     * Missing values in key fields
     * Invalid dates or non-numeric funding amounts
   * Displays a cleaning report before processing.

3. **Clean Data**

   * Standardizes column names (lowercase, underscore format)
   * Handles missing values with defaults like `"Unknown"` or `0`
   * Converts dates into a proper datetime format
   * Cleans numeric funding amounts (removes commas, converts to integers)

4. **Analyze Data**

   * Generates **text-based insights** directly in the GUI:

     * Funding trends over the years
     * Top sectors, cities, startups, investors
     * Investment type distribution

5. **Visualize Insights**

   * Creates **interactive charts** using Seaborn & Matplotlib:

     * Funding trends over time
     * Top sectors, cities, startups
     * Most active investors
     * Investment type distribution

6. **Recommendations**

   * Provides strategic insights based on data patterns
   * Suggests focus areas like top-performing cities, investors, and sectors

### **Technologies Used:**

* **Tkinter** – GUI interface
* **Pandas** – Data manipulation and cleaning
* **Seaborn & Matplotlib** – Data visualization
* **CSV Dataset** – Startup funding data (Kaggle dataset recommended)

### **Use Case:**

* For **startup analysts**, **investors**, and **data enthusiasts** who want to explore funding patterns
* Ideal for **academic projects**, **portfolio building**, and **data science learning**

