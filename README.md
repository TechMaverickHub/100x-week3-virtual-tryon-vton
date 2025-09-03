# 100x Week 3 — Virtual Try-On (VTON) with ComfyUI

**Assignment (Medium Level):** Create a **Virtual Try-On Workflow** in ComfyUI where you provide a **model image** and a **garment image**, and generate a realistic output of the model wearing that clothing.  

This is where **AI meets fashion** — no fitting rooms, just prompt-powered design.  

---

## ✨ Workflow Overview
The workflow combines:
- **Masking** → Segments the person from the background.  
- **IPAdapter** → Transfers garment style and texture.  
- **Depth ControlNet** → Maintains realistic body structure, folds, and fit.  

The result: seamless, **AI-powered try-on images** that look natural and stylish.  

---

## 📂 Repo Layout
- `workflows/` → ComfyUI workflow JSON  
- `inputs/` → model + garment images  
- `outputs/` → generated try-on results  

---

## 🚀 How to Run
1. Open **ComfyUI**.  
2. Load `workflows/vton_workflow.json`.  
3. Place your **model image** and **garment image** inside `inputs/`.  
4. Run the workflow.  
5. View results in `outputs/`.  

---

## ✅ Checklist
- [ ] Workflow JSON  
- [ ] Sample model + garment images in `inputs/`  
- [ ] Generated try-on results in `outputs/`  

---

## 🎯 Learning Goals
- Understand **ComfyUI workflow chaining**.  
- Experiment with **IPAdapter + ControlNet fusion**.  
- Explore **practical fashion-tech applications** of GenAI.  

---

## 📜 License
MIT (repo). Generated images follow base model license.  
