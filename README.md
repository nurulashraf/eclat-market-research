
# ECLAT Market Research

ECLAT Market Research is a data-driven project that explores customer purchase patterns using association rule mining techniques — specifically the ECLAT algorithm. This project analyzes market basket data to identify frequent itemsets and meaningful relationships between products, offering insights for strategic decision-making in retail and e-commerce.

---

## Features

- Performs market basket analysis using the **ECLAT (Equivalence Class Clustering and bottom-up Lattice Traversal)** algorithm.
- Visualizes frequent itemsets and their supports using interactive plots.
- Allows customization of support thresholds.
- Exports insights for use in marketing and inventory planning.

---

## Project Structure

- **`notebooks/`**: Jupyter notebooks for data analysis, feature engineering, and model building.
- **`requirements.txt`**: List of required Python packages
- **`LICENSE`**: MIT License file
- **`README.md`**: Project overview and usage instructions.

---

## Tools & Libraries

- Python 3.x
- Pandas
- pyECLAT
- Jupyter Notebook

---

## How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/nurulashraf/eclat-market-research.git
   cd eclat-market-research
   ````

2. **Install dependencies:**

   Create a virtual environment (optional but recommended), then install:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook:**

   Open `notebooks/eclat_market_research.ipynb` in Jupyter Notebook or Jupyter Lab to explore and analyze the data.

4. **Modify support threshold:**

   You can adjust the minimum support value in the code to explore different itemsets.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

