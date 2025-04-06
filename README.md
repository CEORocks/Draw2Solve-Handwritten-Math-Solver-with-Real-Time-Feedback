# ✏️ Draw2Solve: Handwritten Math Solver with Real-Time Feedback

**Draw2Solve** is an intelligent, touch-friendly math canvas that turns your hand-drawn expressions into real-time answers. Powered by a multimodal language model and a lightweight GUI built with Python, this project brings natural math input to your desktop through freeform drawing and instant solution display.

Whether you're jotting down simple arithmetic or sketching more complex equations, **Draw2Solve** makes the process intuitive, visual, and seamless. Just write, press enter, and let AI do the rest.

---

## 🧩 Key Features

• Intuitive freehand drawing interface for writing math equations  
• Real-time solution placement next to drawn expressions  
• Minimalist black canvas with high-contrast white drawing  
• Built-in undo, clear, and calculate options for smooth interaction  
• Compact and responsive GUI using Tkinter and PIL  
• AI backend interprets drawn content and evaluates the equation

---

## ⚙️ Setup and Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Draw2Solve.git
cd Draw2Solve
```

2. Install the required Python packages:

```bash
pip install -r requirements.txt
```

3. Set up your OpenAI API key as an environment variable:

```bash
export OPENAI_API_KEY=your_api_key_here
```

---

## ▶️ How to Use

Run the app by executing the following command:

```bash
python main.py
```

### 🖥️ Interface Breakdown

• **Canvas** – Use your mouse or stylus to write equations  
• **Clear Button** – Wipes the canvas completely  
• **Undo (Ctrl/Cmd + Z)** – Removes your last stroke  
• **Calculate (Enter/Return)** – Triggers the AI to solve the equation  
• **Output** – Result is placed next to the equal sign in a highlighted color

### ✍️ Example Workflow

1. Draw `12 * 4 =` on the canvas  
2. Press **Enter** or click the **Calculate** button  
3. The app will append the answer (`48`) right after the equals sign  

> Note: The equal sign must appear as the last part of your written equation for the result to be correctly placed.

---

## 🔮 Planned Enhancements

• Smart equals sign detection using computer vision  
• Support for more complex multi-line equations  
• Equation history with export options  
• Additional language model support for offline use  

---

## 🤝 Contributing

Pull requests and feature suggestions are welcome. If you’d like to improve functionality, fix bugs, or propose interface upgrades, feel free to contribute.

---

## 📝 License

Licensed under the MIT License – use, modify, and distribute freely with credit.

---