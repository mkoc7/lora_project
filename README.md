# LoRA ile LLM İnce Ayarlama Projesi

Bu repository (kod deposu), büyük dil modellerini (LLM - Large Language Model) LoRA (Low-Rank Adaptation) tekniğini kullanarak verimli bir şekilde ince ayarlamak için gerekli kodları içerir.

## 🚀 Özellikler

- [LLaMA-2 7B](https://huggingface.co/meta-llama/Llama-2-7b-hf) modelini LoRA ile ince ayarlama
- Düşük bellek kullanımı sayesinde tüketici sınıfı GPU'larda çalışabilme
- Özel veri setleriyle hızlı adaptasyon

## 📋 Gereksinimler

- Python 3.8+
- PyTorch 2.0+
- Transformers 4.30+
- PEFT 0.4+
- Datasets 2.12+

## 🔧 Kurulum

```bash
# Sanal ortam oluşturun (isteğe bağlı)
python -m venv venv
source venv/bin/activate  # Linux/Mac
# veya
venv\Scripts\activate  # Windows

# Gerekli paketleri yükleyin
pip install torch transformers peft datasets
