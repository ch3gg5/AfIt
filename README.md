# 🧠 AfIt: Open-Source AI-Powered Nutrition & Wellness Tracker

> **Gains start in the kitchen. AI helps you track it all.**

AfIt is a **privacy-first, open-source health and nutrition tracker** that combines **manual logging**, **AI assistance**, **wearable integration**, and **body metrics estimation** into one powerful app.

Whether you're tracking macros, managing hydration, or improving body composition, **AfIt gives you the tools — without selling your data**.

See [PRIVACY.md](PRIVACY.md), to learn more.

---

## Why AfIt?

- ✅ No paywalls, ads, or subscriptions  
- ✅ Privacy-respecting — no data sold or shared  
- ✅ AI-powered insights built-in  
- ✅ Fully open source — new code under **Apache 2.0**  

---

## 🌟 Roadmap

| Feature | Status | Description |
|--------|--------|-------------|
| ✅ Manual Macro Tracking | Done | Track calories, protein, carbs, fats manually. Built-in support for common foods and portion sizes |
| 💧 Personalized Water Tracking | In-Progress | Auto-calculate daily water goals based on weight, activity level, and climate. Log intake via manual entry or quick buttons |
| 📸 Food Label OCR Scanner | Planned | Scan packaged food labels with your camera and auto-extract macros using OCR and AI parsing |
| 🤖 AI Assistant Integration | Planned | Get smart suggestions, meal ideas, and macro balancing tips powered by local or cloud-based AI models (ChatGPT, Llama, Ollama) |
| 🔄 Wearable Sync (Google Fit / Apple Health) | Planned | Sync steps, heart rate, sleep, and workout data to dynamically adjust calorie targets |
| 🧬 Body Metrics Estimator | Planned | Estimate body fat % using wearable data + personal inputs (e.g., BMI, U.S. Navy method) |
| 🎨 Full UI/UX Redesign | Planned | A clean, intuitive interface inspired by Notion and Apple Health — minimalistic, modular, and user-first |

For full roadmap, see [ROADMAP.md](ROADMAP.md)

---

## 🚀 Getting Started

### Prerequisites
- Flutter SDK installed
- Git
- Optional: Python (for training models or local AI)

### Installation

```bash
git clone https://github.com/your-username/afit.git  
cd afit
flutter pub get
flutter run
```

> For detailed setup instructions, see [CONTRIBUTING.md](CONTRIBUTING.md)

---

## 🤝 Contributing

We welcome contributions from everyone — developers, designers, data scientists, nutritionists, and testers!

To contribute:
1. Fork the repo
2. Create a feature branch (`git checkout -b feature/new-screen`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-screen`)
5. Open a pull request

For more info, check out our [Contributing Guide](CONTRIBUTING.md)

---

## 📄 License

This project builds on the GPLv3-licensed [Energize](https://codeberg.org/epinez/Energize/src/commit/763dc8f7b5abe5a772846ca30941e34145a00c7f) codebase, which remains under its original license.

All **new code** in this project is licensed under **[Apache License 2.0](LICENSE)** — allowing broad reuse while giving proper credit and protecting contributors.

See:
- [LICENSE](LICENSE) – Apache 2.0 (new code)
- [GPLv3](GPLv3) – Original Energize license

---

## ❤️ Show Your Support

If you like what we're building:

- ⭐ Star the repo
- Share it with friends
- Contribute code or design
- Suggest features or improvements

Together, we can build the most **intelligent, ethical, and user-owned nutrition tracker** out there.

### Contributors & Advisors

- [Energize](https://codeberg.org/epinez/Energize/src/commit/763dc8f7b5abe5a772846ca30941e34145a00c7f) - Provided AfIt's foundation 
- [Qwen/QwQ Team]https://qwenlm.github.io/about/) - Provided early vision framing, roadmap strategy, UI/UX guidance, and technical planning.
