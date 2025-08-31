# GPT-2 Mechanistic Interpretability Research Platform

![Platform Screenshot](https://user-images.githubusercontent.com/176001/ai_research_screenshot.png) <!-- You can add a real screenshot here -->

> **Explore and visualize how GPT-2 understands language, discovers circuits, and processes information—right in your browser.**

---

## 🚀 Overview

This project is an **interactive research platform** designed for advanced mechanistic interpretability studies of GPT-2 transformer models. Inspired by methods from Anthropic, OpenAI, and leading interpretability research, it enables hands-on experiments in:

- **Activation patching**
- **Causal tracing**
- **Sparse Autoencoder (SAE) analysis**
- **Gradient attribution**
- **Neuron ablation**
- **Circuit discovery**

All in an accessible, web-based interface—no Python or backend required!

---

## 🧑‍🔬 Features

- **Model Loading**: Simulates GPT-2 Small, Medium, and Large variants
- **Experiment Modes**: Switch between activation patching, circuit discovery, attribution, ablation, and more
- **Visualization**: Interactive heatmaps, attention patterns, circuit graphs, and feature plots using Plotly.js
- **Parameter Control**: Set layer/head/position ranges, thresholds, and experiment configurations
- **Research Presets**: One-click loading of classic interpretability experiments (pronoun resolution, factual recall, etc.)
- **Advanced Tools**: Path patching, causal interventions, feature visualization, linear probe studies
- **Export/Import**: Save your research results for further analysis

---

## 🖥️ Getting Started

1. **Clone this repo** (or simply download `gpt2_brain_mapper.html`)
2. **Open `gpt2_brain_mapper.html` in your browser** (Chrome/Firefox recommended)
3. **Start experimenting!**

No installation, no dependencies—everything runs client-side.

---

## 🔬 Example Use Cases

- **Activation Patching**: Discover which layers/heads/neurons are causally important for a given prediction
- **Attention Analysis**: Visualize and interpret attention patterns for your input
- **Circuit Discovery**: Map out functional subcircuits for factual recall, coreference, or reasoning
- **Ablation Studies**: See how knocking out certain neurons or heads impacts model behavior
- **Feature Probing**: Explore discovered features with autoencoders and linear probes

---

## 📸 Screenshots

<!-- Replace with actual screenshots -->
![Activation Patching Demo](https://user-images.githubusercontent.com/176001/ai_research_patch_demo.png)
![Circuit Visualization](https://user-images.githubusercontent.com/176001/ai_research_circuit_demo.png)

---

## 🧑‍💻 Technologies Used

- **HTML/CSS/JS** (single file, easy to extend)
- **[TensorFlow.js](https://www.tensorflow.org/js)** (for neural simulation)
- **[Plotly.js](https://plotly.com/javascript/)** (interactive visualizations)
- **[Math.js](https://mathjs.org/)**, **Lodash** (utility libraries)

---

## 📝 Acknowledgments

- Techniques inspired by [Anthropic's interpretability research](https://transformer-circuits.pub/) and [OpenAI's work](https://openai.com/research/)
- UI/UX modeled after leading labs' interpretability dashboards
- Thanks to the transformer interpretability community for ideas and datasets

---

## 🤝 Contributing

Pull requests, feature suggestions, and bug reports are welcome!  
Feel free to fork and extend the platform for your own research needs.

---

## 📄 License

MIT License

---

## 🌐 Resources

- [Transformer Circuits Thread](https://transformer-circuits.pub/)
- [OpenAI Mechanistic Interpretability](https://openai.com/research/)
- [Neel Nanda’s Interpretability Blog](https://www.neelnanda.io/mechanistic-interpretability)

---

**Happy interpreting!** 🧠✨
