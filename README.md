(
echo ## 📘 Word Embedding Similarity with GloVe
echo.
echo This project demonstrates how to use **pre-trained GloVe word embeddings** to compute **cosine similarity** between words. The goal is to find the top-N most similar words to a given query word.
echo.
echo ---
echo.
echo ### 📂 Files
echo.
echo - `main.ipynb`: Jupyter notebook with complete code and explanations.
echo - `requirements.txt`: List of Python dependencies.
echo - `README.md`: Project overview.
echo.
echo ---
echo.
echo ### 🚀 Features
echo.
echo - ✅ Real word vectors using **GloVe** (via `gensim`)
echo - ✅ Handles **out-of-vocabulary (OOV)** words gracefully
echo - ✅ Computes **cosine similarity** between words
echo - ✅ Returns top-N most similar words
echo - ✅ Clean and readable output formatting
echo - ✅ Ready to run in any environment
echo.
echo ---
echo.
echo ### 🛠️ Requirements
echo.
echo ^`bash
echo pip install -r requirements.txt
echo ^`
echo.
echo ---
echo.
echo ### 📌 How to Run
echo.
echo 1. Clone the repo
echo 2. Open `main.ipynb` in Jupyter Notebook or Colab
echo 3. Run all cells to test similarity across words like:
echo.
echo    ^`python
echo    query_word = "pear"
echo    ^`
echo.
echo ---
echo.
echo ### 🔄 Improvements Over Initial Version
echo.
echo ^| Area ^| Original Code ^| Final Version (Updated) ^|
echo ^|------^|-----------------^|---------------------------^|
echo ^| Embedding source ^| Manual dummy vectors ^| Real GloVe embeddings from `gensim.downloader` ^|
echo ^| Similarity metric ^| Cosine similarity ^| Same, but with better handling of zero vectors ^|
echo ^| OOV handling ^| Not addressed ^| ✅ Gracefully skipped with warning ^|
echo ^| Word self-comparison ^| Manually commented ^| ✅ Optionally included/excluded ^|
echo ^| Output formatting ^| Raw `print` ^| ✅ Clean, aligned output with 4-decimal precision ^|
echo ^| Parameterization ^| Hardcoded `"pear"` ^| ✅ Could be extended with `input()` or CLI param ^|
echo ^| Sorting ^| External sort key function ^| ✅ Simplified using lambda ^|
echo.
echo ---
echo.
echo ### ⚠️ Edge Cases Handled
echo.
echo - 🧩 Word not found in GloVe vocabulary
echo - 🧩 Zero vector edge case
echo - 🧩 Duplicate/self-comparison
echo - 🧩 Case sensitivity (words should be lowercase)
echo - 🧩 Tied scores handled via stable sort
echo.
echo ---
echo.
echo ### 📚 Example Output
echo.
echo ^`
echo Top 3 most similar words to 'pear':
echo 1. apple — Similarity: 0.9234
echo 2. grape — Similarity: 0.9121
echo 3. peach — Similarity: 0.9038
echo ^`
echo.
echo ---
echo.
echo ### ✍️ Author
echo.
echo Abhyuday Sultania
echo 📧 [Abhyuday767@gmail.com](mailto:Abhyuday767@gmail.com)
echo 💼 [LinkedIn](https://linkedin.com) ([https://www.linkedin.com/in/abhyuday-sultania-1a9245227/](https://www.linkedin.com/in/abhyuday-sultania-1a9245227/)) echo. ) > README.md
