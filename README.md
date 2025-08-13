# 🧠 Interactive Transformer Architecture Tutorials

Learn transformer architecture concepts through hands-on visualizations and step-by-step mathematical analysis.

## 🚀 Live Demo

**[👉 View Interactive Tutorials](https://profitmonk.github.io/visual-ai-tutorials/)**

## 📚 Available Tutorials

### 🌀 RoPE: Rotary Position Embedding
**File:** `rope-tutorial.html`

Comprehensive guide to understanding how transformers encode position information through rotation:
- **Visual dimension pairing** with color-coded examples
- **Complete mathematical walkthrough** with cos/sin transformations  
- **Interactive examples** with up to 128D embeddings and 128 token contexts
- **Context extension challenges** and scaling analysis
- **Step-by-step RoPE application** with real token examples

**Key Concepts:** Position encoding, dimension pairs, rotation mathematics, context scaling

---

### 🎯 Q, K, V Matrix Dimensions  
**File:** `qkv-matrices.html`

Interactive exploration of attention mechanism matrix sizes and their relationship to model architecture:
- **Real model comparisons** (GPT-4, Claude Sonnet 4, Gemini, DeepSeek, LLaMA)
- **Matrix size calculations** showing how d and m affect memory/computation
- **Architecture analysis** with concrete memory requirements
- **Visual demonstrations** of parameter scaling

**Key Concepts:** Attention matrices, model dimensions, memory scaling, architecture comparison

---

### 📊 Context Length Impact: Training vs Inference
**File:** `context-length-impact.html`

Mathematical analysis of why models trained on long contexts excel at shorter sequences:
- **Fixed vs dynamic components** in transformer models
- **RoPE frequency analysis** - what changes and what doesn't
- **Performance metrics** with concrete speed/memory calculations
- **Step-by-step mathematical proofs** with real examples
- **Interactive comparisons** across different context lengths

**Key Concepts:** Context extension, performance analysis, RoPE frequencies, training vs inference

## 🏗️ Repository Structure

```
visual-ai-tutorials/
├── index.html                    # Landing page with tutorial links
├── rope-tutorial.html            # RoPE tutorial
├── qkv-matrices.html            # Q,K,V matrix tutorial  
├── context-length-impact.html   # Context length impact tutorial
└── README.md                    # This file
```

## 🎯 Target Audience

- **AI/ML Engineers** learning transformer internals
- **Researchers** studying attention mechanisms and position encoding
- **Students** in NLP/deep learning courses
- **Developers** working with LLMs who want to understand the underlying math
- **Anyone curious** about how modern AI models like GPT, Claude, and Gemini work

## ✨ Features

- **📱 Responsive Design** - Works on desktop, tablet, and mobile
- **🎨 Interactive Visualizations** - Real-time calculations and demonstrations
- **🔢 Mathematical Precision** - Step-by-step formulas with actual numbers
- **📊 Real Model Data** - Architecture specs from production models
- **🎛️ Configurable Examples** - Adjust parameters to see immediate effects
- **📚 Educational Focus** - Designed for learning, not just reference

## 🛠️ Technology Stack

- **Pure HTML/CSS/JavaScript** - No frameworks, works anywhere
- **Interactive calculations** - Real-time mathematical demonstrations
- **Responsive design** - Mobile-friendly layouts
- **GitHub Pages ready** - Deploy with zero configuration

## 🚀 Getting Started

### Option 1: View Online
Simply visit the [live demo](https://profitmonk.github.io/visual-ai-tutorials/) to access all tutorials immediately.

### Option 2: Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/profitmonk/visual-ai-tutorials.git
   cd visual-ai-tutorials
   ```

2. Open `index.html` in your browser or serve with a local server:
   ```bash
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

## 📖 Tutorial Highlights

### 🔥 What Makes These Tutorials Special

- **Real Architecture Data**: Actual specs from GPT-4, Claude Sonnet 4, Gemini 2.5 Pro
- **Interactive Math**: See formulas in action with adjustable parameters
- **Visual Learning**: Color-coded matrices, dimension pairing, rotation visualizations
- **Concrete Examples**: Real token sequences, actual memory calculations
- **Progressive Complexity**: Build understanding step-by-step

### 🎓 Learning Outcomes

After completing these tutorials, you'll understand:
- How RoPE encodes position through rotation mathematics
- Why attention matrices scale quadratically with sequence length  
- How model dimensions affect memory and computation requirements
- Why models trained on long contexts work better on short contexts
- The relationship between training and inference in transformer models

## 🤝 Contributing

Contributions are welcome! Whether it's:
- 🐛 Bug fixes
- ✨ New tutorial topics
- 📝 Documentation improvements
- 🎨 UI/UX enhancements
- 📊 Additional model architectures

Please feel free to open issues or submit pull requests.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Built with educational focus to demystify transformer architecture
- Inspired by the need for visual, interactive explanations of complex AI concepts
- Mathematical content based on original research papers and production model specifications

## 📞 Contact

- **GitHub Issues**: For bugs, feature requests, or questions
- **Discussions**: For general questions about transformer architecture
- **Pull Requests**: For contributions

---

**⭐ Star this repository if these tutorials helped you understand transformers better!**
