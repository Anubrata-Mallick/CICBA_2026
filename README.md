<div align="center">

<big><big><b>🧠 A Decision Support System for AI Content Detection</b></big></big>

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="850">

</div>

<!-- 🌐 RESEARCH PAPER --> 
## <img src="https://user-images.githubusercontent.com/74038190/216656949-4d98aa51-a60a-4dd1-b531-1b5745e18002.gif" width="50"> Research Paper

### **Publishing Soon at CICBA-2026**

📄 **Paper:** `Coming Soon`

🌐 **Conference:** [CICBA-2026](https://www.cicba.in/)

> The paper link will be added here once officially published.

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif">


<!-- Demo -->
## <img src="https://user-images.githubusercontent.com/74038190/216654095-6f6772e4-e433-4bba-9164-1ca6f463ac3f.gif" width="50"> Demo

<p align="center">
  <img src="./assets/demo.gif" alt="Demo" width="800">
</p>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif">


<!-- 🌐 Overall Arch --> 

## 🏗️ Overall Architecture

<img src="./assets/arch.png" alt="Overall Architecture" width="850">

The system processes a PDF through separate **text and image analysis pipelines**, followed by an adaptive late-fusion layer to generate an overall AI probability score.

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif">


<!-- 🌐 Text Analysis --> 
## 📝 Text Analysis

<img src="./assets/Textarch.png" alt="Text Analysis Architecture" width="850">

The text module combines:

- **TF-IDF + Logistic Regression**
- **TF-IDF + Multinomial Naive Bayes**
- **Stylometric Features + Random Forest**
- **Neural Network Meta-Learner**

### 📊 Text Module Performance

**99.10% Accuracy | 99.97% AUROC**

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif">


<!-- 🌐 PDF BIFUECATION --> 
## 🖼️ PDF Bifurcation

The PDF processor separates the document into:

**Text → Text Detection Module**

**Images → Image Detection Module**

### 🔗 PDF Processor

[PDF Processor Repository](https://github.com/Anubrata-Mallick/PDF_PROCESSOR)

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif">


<!-- 🌐 Score --> 
## ⚡ AI Score Fusion

<img src="./assets/FusionFormula1.png" alt="Fusion Formula" width="800">

<img src="./assets/FusionFormula2.png" alt="Fusion Formula" width="800">

The text and image predictions are combined using an **adaptive late-fusion strategy** to produce the final document-level AI score.

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif">


<!-- 🌐 Test Result --> 
## 🧪 Test Results

<img src="./assets/Test.png" alt="Test Results" width="850">

The system was evaluated on adversarial cases, mixed text-image documents, and real academic project reports.

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="50">

<!-- 🌐 My contri --> 
<div align="center">

# <img src="https://user-images.githubusercontent.com/74038190/216658117-5a5c9ab7-7319-4ffa-9e64-79d6bf0fb8d1.gif"> My Contribution

### 🚀 Engineering the Pipeline from Architecture to Validation

<p>
  <em>
    My work focused on designing, developing, integrating, and validating
    <br>
    the core AI pipeline behind the project.
  </em>
</p>

</div>

<br>

---

### 🏗️ 01 · System Architecture

> Designed the **overall architecture** for efficient AI-based tracking while optimizing the system for operation within a constrained space.

---

### 📄 02 · PDF Bifurcation Pipeline

> Developed the **PDF bifurcation pipeline** to intelligently separate **text and images** from PDF documents, creating structured inputs for downstream AI processing.

---

### 🧠 03 · Ensemble AI Architecture

> Designed an **ensemble architecture** integrated with a **neural-network decision head** for robust text detection and intelligent model-level decision making.

---

### 🎯 04 · AI Score Fusion

> Developed the **fusion formula** responsible for generating the overall **AI score prediction**, together with its corresponding probability.

---

### 🧪 05 · Testing & Edge Cases

> Designed and conducted **comprehensive testing** of the fused model, systematically evaluating performance across different scenarios, edge cases, and failure conditions.


<img src="https://user-images.githubusercontent.com/74038190/212744287-14f66c13-5458-40dc-9244-8ff533fc8f4a.gif" width="950">
<!-- 🌐 Shout out --> 
<div align="center">

# <img src="https://user-images.githubusercontent.com/74038190/214644145-264f4759-7633-441e-9d67-d8dda9d50d26.gif" width="80"> Shoutouts <img src="https://user-images.githubusercontent.com/74038190/214644145-264f4759-7633-441e-9d67-d8dda9d50d26.gif" width="80">
🤝 The People Behind the Journey

<p> <em> People I had the pleasure of working with throughout the entire journey — <br> from the initial idea 💡 to the final publication 🚀 </em> </p>

<br>

<table align="center"> <tr> <td align="center" width="50%"> <h3>🌟 Shreya Dhar</h3> <p> <strong>Team Member</strong> </p> <a href="https://www.linkedin.com/in/shreya-dhar-4b3b66292/"> <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"> </a> </td> <td align="center" width="50%"> <h3>🌟 Kartick Kumar Shaw</h3> <p> <strong>Team Member</strong> </p> <a href="https://www.linkedin.com/in/kartick-kumar-shaw-229861299/"> <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"> </a> </td> </tr> <tr> <td align="center" width="50%"> <h3>🌟 Karma Tashi Gyatsho Bhutiya</h3> <p> <strong>Team Member</strong> </p> <a href="https://www.linkedin.com/in/karma-tashi-gyatsho10/"> <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"> </a> </td> <td align="center" width="50%"> <h3>🧭 Indrajit Bhattacharya</h3> <p> <strong>Mentor</strong> </p> <a href="https://www.linkedin.com/in/indrajit-bhattacharya-53132a14/"> <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"> </a> </td> </tr> </table>
---

<p align="center">

⭐ **If you find the project interesting, consider starring the repository!**

</p>
