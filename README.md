# Information Visualization Redesign Project  
**Course Project for INFOSCI 301 – Data Visualization and Information Aesthetics**  
*Instructor: Prof. Luyao Zhang | Duke Kunshan University, Spring 2025*  

[![Project Poster](https://img.shields.io/badge/View_Full_Poster_PDF-%230077B5?style=for-the-badge&logo=adobe-acrobat-reader)](https://github.com/YifeiCathyYang/Redesign-Project/blob/main/InfoVis%20Redesign_Poster_Yifei%20Yang_Finalized.pdf)  


## 🎯 Goal  
This project aims to **redesign a global heat stress risk visualization** to improve clarity, interactivity, and ethical data representation. Key objectives include:  
- Enhancing visual encoding (color, size, labels) for better temperature trend visibility.  
- Integrating dynamic interaction (time slider, tooltips) to explore temporal climate patterns.  
- Addressing weaknesses in the original visualization, such as missing legends, opaque risk calculations, and static data representation.  


## 🛠️ Tools Used  
- **Python Libraries**: `Plotly` (for interactive maps and charts), `Pandas` (data processing).  
- **Platform**: Google Colab (cloud-based notebook environment).  
- **Data Source**: [Climate Change: Earth Surface Temperature Data](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data).  


## 📊 Data Visualization Theory  
The redesign is grounded in **Tamara Munzner's Visualization Framework** and **data governance principles**:  

### **Munzner's Key Principles**  
1. **Encoding Principles**:  
   - Color gradients and marker sizes encode temperature values intuitively.  
   - Geographic labels (e.g., US, China) highlight high-impact regions.  
2. **Task Abstraction**: Supports user goals like "discover trends" and "present insights."  
3. **Idiom Validation**: Improved usability through interactive elements (e.g., time slider).  
4. **Dynamic Data**: Replaced static maps with time-based interaction for evolving climate risk.  

### **Data Governance Frameworks**  
- **FAIR Principles**: Dataset transparency, accessibility, and reusability.  
- **OECD Guidelines**: Clear annotations ensure data traceability.  
- **DMBOK Standards**: Avoided misleading visuals through standardized encoding.  


## 📈 Results  
### Redesigned Visualizations  
1. **Interactive Global Temperature Map**  
   - **Features**: Time slider, tooltips, continent/country labels.  
   - **Improvements**:  
     - Intuitive color scale and size encoding for temperature trends.  
     - Highlighted key regions (e.g., China, US, India).  

2. **Global Surface Temperature Trends Over Time**  
   - **Features**: Animated line chart with temporal granularity.  
   - **Improvements**: Clear visualization of long-term warming patterns.  

3. **Temperature Variability Map (Mean vs. Max)**  
   - **Features**: Dual encoding for comparative analysis.  

### Key Advantages Over Original  
- ✅ **Enhanced Clarity**: Eliminated overplotting with spatial grouping.  
- ✅ **Dynamic Exploration**: Time slider enables tracking changes across decades.  
- ✅ **Ethical Transparency**: Cited data sources and methodology openly.  


## 🔍 Data & Code Availability Statement  
- **Dataset**: [Climate Change: Earth Surface Temperature Data](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data) (accessed April 2025).  
- **GitHub Repository**: [YifeiCathyYang/Redesign-Project](https://github.com/YifeiCathyYang/Redesign-Project)  
  - Includes all code (Google Colab notebooks) and design assets.  
- **License**: Open-source for academic and non-commercial use.  


**Contact**: Yifei Yang | [yy346@duke.edu](mailto:yy346@duke.edu)

**Acknowledgments**  
Special thanks to **Professor Luyao Zhang** for her insightful instruction throughout the INFOSCI 301 course. Her guidance was instrumental in shaping the direction of this project. I also wish to acknowledge **Dongping Liu** (Amazon Web Services) and **Dr. David Schaaf** (Saarland University) for their thoughtful insights, which contributed meaningfully to the redesign process. Appreciation is further extended to my classmates in INFOSCI 301 for their constructive feedback during peer reviews and workshops.  
