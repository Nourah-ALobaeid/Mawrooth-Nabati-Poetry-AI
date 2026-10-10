# Mawrooth – Nabati Poetry AI

🏆 Winner of the **Idea Award** at Arabathon 2026 (عربثون)

**Mawrooth** is an AI system for explaining Saudi Nabati poetry using **ALLaM-7B** fine-tuned with **QLoRA**.

---

## 🔗 Links

- **Model:** [Hugging Face](https://huggingface.co/NorahAlobaied/Mawrooth-ALLaM-7B-LoRA)
- **Dataset:** [Hugging Face](https://huggingface.co/datasets/NorahAlobaied/Mawrooth-Nabati-Dataset)
- **Full Documentation:** [Hugging Face Model Card](https://huggingface.co/NorahAlobaied/Mawrooth-ALLaM-7B-LoRA)

---

## 📄 Project Materials

All project materials are available in the [`Project Info`](Project%20Info/) and [`demo`](demo/) folders:

- 📊 **Poster** (English)
- 📁 **Portfolio** (Arabic & English)
- 🖼 **Screenshot**
- 🎥 **Demo**

---

## 🎯 My Role

**Lead Developer & Project Lead** — Led end-to-end development: dataset curation (586 verses), Nabati dictionary (1,300+ terms), QLoRA training, Gradio interface, and Hugging Face deployment.

---

## 📊 Key Results

- Token Accuracy: **85.75%**
- Train Loss: 0.716 | Validation Loss: 0.711
- No overfitting
- 80 training steps | LoRA size: 65 MB

---

## 🛠️ Tech Stack

- **Base Model:** ALLaM-7B-Instruct-preview
- **Fine-tuning:** QLoRA (4-bit), PEFT
- **Interface:** Gradio
- **Deployment:** Hugging Face Hub
- **Language:** Arabic (Nabati dialect) + English (visual descriptions)

---

## 📚 About the Dictionary

The Nabati dictionary contains **More than 1,300 specialized terms**, including:
- Nabati vocabulary
- Star names
- Coffee tools
- Camel names
- Weather phenomena
- Geographic locations

Built through a structured process: reference lexicons, NLP root analysis, human verification, and contextual classification.

---

## 📜 Citation

```
@misc{mawrooth2026,
  title={Mawrooth: Arabic Nabati Poetry Explainer},
  author={Mawrooth Team},
  for={Arabthon 2026},
  year={2026},
  publisher={Hugging Face},
  howpublished={\url{https://huggingface.co/NorahAlobaied/Mawrooth-ALLaM-7B-LoRA}}
}
```

---

📧 Contact

For inquiries: nourahalobaeid@gmail.com

---

Made with ❤️ for Saudi heritage
