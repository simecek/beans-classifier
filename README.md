# Bean leaf classifier (Streamlit)

A small Streamlit app: upload a photo of a bean leaf and a fine-tuned ConvNeXt model predicts one of three categories (angular leaf spot, bean rust, healthy).

- Dataset: [AI-Lab-Makerere/beans](https://huggingface.co/datasets/AI-Lab-Makerere/beans)
- Model: [simecek/beans-classifier](https://huggingface.co/simecek/beans-classifier), trained with fastai in Google Colab; the app downloads `model.pkl` from there

Run locally:

```bash
pip install -r requirements.txt
streamlit run app.py
```

A temporary test of the deployment for the Data Science Practicum 2026 (Masaryk University).
