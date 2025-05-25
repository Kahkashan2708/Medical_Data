# Medical_Data (TF-IDF Visualization and Explanation)

This project contains a Jupyter Notebook that explains and visualizes the **TF-IDF (Term Frequency-Inverse Document Frequency)** algorithm using Python. It is ideal for students, researchers, and developers interested in natural language processing (NLP) and text mining.

---

## Files

- **Data_Visualised.ipynb**: The main Jupyter Notebook that:
  - Explains Term Frequency (TF), Inverse Document Frequency (IDF), and TF-IDF
  - Calculates TF-IDF manually and using `sklearn`
  - Visualizes word importance using bar charts

---

##  What is TF-IDF?

TF-IDF is a statistical measure used to evaluate how important a word is to a document in a collection or corpus. It is widely used in NLP tasks like:
- Text classification
- Search engines
- Document similarity
- Keyword extraction

\[
\text{TF-IDF}(t, d) = \text{TF}(t, d) \times \log\left(\frac{N}{1 + df(t)}\right)
\]

---

##  Requirements

Install the required Python libraries before running the notebook:

```bash
pip install numpy pandas matplotlib scikit-learn
