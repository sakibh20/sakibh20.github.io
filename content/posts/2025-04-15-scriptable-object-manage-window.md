---
template: SinglePost
title: Scriptable Object Manage Window
status: Published
date: 2025-04-15
featuredImage: https://ucarecdn.com/3631fe18-ea18-41f5-a3ed-119386495008/
excerpt: Unity Custom Editor Window for ScriptableObject Serialization &
  Addressables Integration
categories:
  - category: Tools
---
# Unity Custom Editor Window for ScriptableObject Serialization & Addressables Integration

This repository presents a **custom-built Editor Window** designed to automate and simplify the management of complex **ScriptableObject** data structures in Unity. This tool supports full **JSON serialization and deserialization**, and integrates seamlessly with Unity's **Addressables system** — all from a user-friendly, tabbed editor interface.

## ✨ Key Features

- 🧭 **Multi-tabbed Custom Editor Window** for a clean and modular interface.
- 📝 **Export ScriptableObjects to JSON**, with full support for:
  - ✅ Nested classes
  - ✅ Enums
  - ✅ Polymorphic data structures and inheritance
- 📦 **Regenerate ScriptableObjects from JSON**, preserving:
  - Data integrity
  - Field types
  - Nested structures
- 🧠 **Accurate type mapping** based on base and derived classes.

---

## 📦 Addressables Integration

This tool goes a step further by automating asset setup for Unity’s **Addressable Asset System**:

- 📁 All generated assets are added to the **correct Addressable Groups**.
- 🏷️ Assets are tagged with **appropriate Addressable labels** based on their type/configuration.
- 📤 Ready for remote content updates, builds, and clean runtime use — no manual setup required.

---

## 🧠 Why It Matters

Managing complex data-driven systems in Unity often leads to repetitive tasks, error-prone manual setups, and bloated inspectors. This Editor Window:

- Automates asset generation from config files
- Supports **version control-friendly JSON** structures
- Enforces clean data pipelines for modular systems

Ideal for games with **procedural content, large item databases, or layered gameplay mechanics** powered by ScriptableObjects.

---

## 📹 Demo Video & GitHub Link


[![Github Repo](https://ucarecdn.com/f9451599-8419-47d2-b35f-ed3ecc76e923/-/preview/280x80/)](https://github.com/sakibh20/custom-editor-window-sv)

<iframe width="560" height="315" src="https://www.youtube.com/embed/worTyFjI8Jg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## 🔧 Built With

- Unity Editor API (CustomWindow, EditorGUILayout, Tabs)
- Newtonsoft JSON (or Unity's JsonUtility)
- ScriptableObject architecture with inheritance and polymorphism
- Addressables API (`AddressableAssetSettings`, `AssetLabelReference`, etc.)

---

## 📂 Project Status

This tool was developed and deployed as part of a real-world game development pipeline, dramatically improving productivity for large content teams.

---