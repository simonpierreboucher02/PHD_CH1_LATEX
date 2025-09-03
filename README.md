# 📊 Has Financialization Changed the Impact of Macroeconomic Announcements?

<p align="center">
  <img src="https://img.shields.io/badge/PhD-Dissertation-blue?style=for-the-badge&logo=graduationcap" alt="PhD Dissertation"/>
  <img src="https://img.shields.io/badge/Chapter-1-green?style=for-the-badge" alt="Chapter 1"/>
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" alt="Status"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-LaTeX-008080?style=flat-square&logo=latex" alt="LaTeX"/>
  <img src="https://img.shields.io/badge/Data_Period-2007--2023-orange?style=flat-square&logo=calendar" alt="Data Period"/>
  <img src="https://img.shields.io/badge/Commodities-6_Futures-purple?style=flat-square&logo=trending-up" alt="Commodities"/>
  <img src="https://img.shields.io/badge/Analysis-High_Frequency-red?style=flat-square&logo=chart-line" alt="High Frequency"/>
</p>

<div align="center">

**👨‍🎓 Author:** Simon-Pierre Boucher  
**🏛️ Institution:** Université Laval, Quebec City, Canada  

</div>  

## Abstract

This study investigates, using high-frequency data, how financialization has changed the impact of macroeconomic announcements on commodity futures returns and volatility. We find that greater financialization dampens the impact of macroeconomic release surprises on commodity markets, as measured by price drift and volatility changes. Moreover, financial participants improve liquidity and price discovery, while reducing volatility. Since traditional market participants prefer stability, our results suggest a beneficial impact of financialization. When we disaggregate the results, we find that the beneficial effects of greater financial participation are linked to money managers rather than swap dealers.

## 🔬 Research Overview

### 🎯 Key Research Questions
- 📈 How has financialization affected commodity markets' response to macroeconomic announcements?
- 💡 Do financial participants improve or deteriorate price discovery in commodity markets?
- ⚖️ What are the differential effects of money managers versus swap dealers?

### 📊 Methodology

<p align="center">
  <img src="https://img.shields.io/badge/Time_Period-16.5_Years-blue?style=flat&logo=clock" alt="Time Period"/>
  <img src="https://img.shields.io/badge/Start_Date-Apr_2007-green?style=flat&logo=calendar" alt="Start Date"/>
  <img src="https://img.shields.io/badge/End_Date-Oct_2023-red?style=flat&logo=calendar" alt="End Date"/>
</p>

- **📅 Data Period:** April 2nd, 2007 to October 31st, 2023
- **🔍 Approach:** High-frequency intraday analysis following Andersen et al. (2007) and Kurov et al. (2019)
- **📦 Commodities:** Six major commodity futures contracts
- **📏 Financialization Measures:** Time-varying, commodity-specific indices based on speculation intensity and trade volume

### ✅ Key Findings
1. **💫 Information Diffusion:** Financialization contributes to better information diffusion and price discovery
2. **📉 Volatility Impact:** Financial participants generally reduce volatility in commodity markets
3. **🔄 Participant Differentiation:** Money managers reduce volatility and improve price discovery, while swap dealers increase volatility but still contribute to price discovery
4. **⚡ Market Efficiency:** Results suggest financialization benefits traditional commodity market participants

## 📁 Repository Structure

<p align="center">
  <img src="https://img.shields.io/badge/Files-20+-brightgreen?style=flat&logo=files" alt="Files"/>
  <img src="https://img.shields.io/badge/Sections-6-blue?style=flat&logo=list" alt="Sections"/>
  <img src="https://img.shields.io/badge/Figures-3-orange?style=flat&logo=image" alt="Figures"/>
  <img src="https://img.shields.io/badge/Appendices-3-purple?style=flat&logo=document" alt="Appendices"/>
</p>

### 📄 Main Files
- 📝 `chapitre1.tex` - Main LaTeX document
- 📚 `master.bib` - Bibliography file  
- 📊 `chapitre1.pdf` - Compiled PDF output

### 📋 Content Sections
- 🎯 `sections/01_introduction.tex` - Introduction and motivation
- 📖 `sections/02_literature_review.tex` - Literature review
- 📊 `sections/03_data.tex` - Data description and sources
- 🔬 `sections/04_methods.tex` - Econometric framework and methodology
- 📈 `sections/05_results.tex` - Empirical results and analysis
- 🎯 `sections/06_conclusion.tex` - Conclusions and implications

### 🛠️ Supporting Materials
- 📋 `tables.tex` - All tables and statistical results
- 🖼️ `figures.tex` - Figure references and captions
- 📎 `appendix_full.tex` - Complete additional results
- 🏦 `appendix_zlb.tex` - Zero Lower Bound period analysis
- 🦠 `appendix_covid.tex` - COVID-19 period robustness checks

### 📊 Figures
- 📈 `FIG_MSCT.pdf` - Market Sentiment and Commodity Trading visualization
- 📉 `FIG_NLS.pdf` - Non-Linear Specification results
- 🌊 `FIG_WT.pdf` - Wavelet Transform analysis

### 🎨 Style Files
- 💄 `aaai.sty` - LaTeX style package
- 📝 `aaai.bst` - Bibliography style

## 🛠️ Compilation Instructions

<p align="center">
  <img src="https://img.shields.io/badge/LaTeX-Required-red?style=flat&logo=latex" alt="LaTeX Required"/>
  <img src="https://img.shields.io/badge/BibTeX-Enabled-green?style=flat&logo=book" alt="BibTeX"/>
  <img src="https://img.shields.io/badge/Steps-4-blue?style=flat&logo=list-ol" alt="Steps"/>
</p>

### 📋 Prerequisites
- 📦 **LaTeX distribution:** TeX Live, MiKTeX, or MacTeX
- 🔧 **Required packages:** See preamble in `chapitre1.tex`

### ⚡ Compilation Steps
```bash
# Step 1: Initial compilation
pdflatex chapitre1.tex

# Step 2: Process bibliography
bibtex chapitre1

# Step 3: Second compilation (resolve citations)
pdflatex chapitre1.tex

# Step 4: Final compilation (resolve cross-references)
pdflatex chapitre1.tex
```

### 📤 Output
- 📊 **Final document:** `chapitre1.pdf`

## 🏆 Research Contributions

<p align="center">
  <img src="https://img.shields.io/badge/Innovation-4_Areas-gold?style=flat&logo=lightbulb" alt="Innovation"/>
  <img src="https://img.shields.io/badge/Methodology-Novel-success?style=flat&logo=search" alt="Methodology"/>
  <img src="https://img.shields.io/badge/Data-High_Frequency-info?style=flat&logo=database" alt="Data"/>
</p>

1. **🔬 Methodological Innovation:** Bridges financialization research with high-frequency macroeconomic announcements literature
2. **📊 Data Approach:** Uses high-frequency intraday data to overcome limitations of daily/weekly frequency studies  
3. **🔍 Disaggregated Analysis:** Separates effects of different financial market participants (money managers vs. swap dealers)
4. **⏱️ Time-Varying Measures:** Employs dynamic, commodity-specific financialization indices rather than simple pre/post-2004 splits

## 🏷️ Keywords

<div align="center">

![Commodities](https://img.shields.io/badge/Commodities-wheat?style=flat&logo=leaf&logoColor=white)
![Energy](https://img.shields.io/badge/Energy-yellow?style=flat&logo=zap&logoColor=black)
![Futures](https://img.shields.io/badge/Futures-orange?style=flat&logo=trending-up&logoColor=white)
![Information](https://img.shields.io/badge/Information_Diffusion-blue?style=flat&logo=rss&logoColor=white)
![Financialization](https://img.shields.io/badge/Financialization-green?style=flat&logo=dollar-sign&logoColor=white)
![High Frequency](https://img.shields.io/badge/High_Frequency-red?style=flat&logo=activity&logoColor=white)
![Speculation](https://img.shields.io/badge/Speculation-purple?style=flat&logo=chart-line&logoColor=white)
![Volatility](https://img.shields.io/badge/Volatility-darkred?style=flat&logo=bar-chart&logoColor=white)
![Macro](https://img.shields.io/badge/Macro_Announcements-teal?style=flat&logo=megaphone&logoColor=white)
![Events](https://img.shields.io/badge/Surprise_Events-pink?style=flat&logo=alert-triangle&logoColor=white)

</div>

## 🎓 Academic Context

<p align="center">
  <img src="https://img.shields.io/badge/Literature-4_Areas-academic?style=flat&logo=book-open" alt="Literature"/>
  <img src="https://img.shields.io/badge/Finance-Core-blue?style=flat&logo=university" alt="Finance"/>
  <img src="https://img.shields.io/badge/Microstructure-Advanced-green?style=flat&logo=microscope" alt="Microstructure"/>
</p>

This research contributes to several academic literatures:
- 📈 **Commodity Financialization:** Understanding how non-traditional investors affect commodity markets
- 🔬 **Market Microstructure:** High-frequency analysis of price discovery and volatility  
- 💡 **Information Processing:** How markets incorporate macroeconomic information
- 🌱 **Sustainable Finance:** Implications for green energy transition and renewable infrastructure

## 👥 Author Information

<div align="center">

### 👨‍🎓 Principal Author
**Simon-Pierre Boucher**  
PhD Candidate in Finance  
🏛️ Université Laval, Quebec City, QC, Canada  
📧 simon-pierre.boucher.1@ulaval.ca

<p align="center">
  <img src="https://img.shields.io/badge/Status-PhD_Candidate-blue?style=flat&logo=graduation-cap" alt="PhD Candidate"/>
  <img src="https://img.shields.io/badge/Field-Finance-green?style=flat&logo=chart-line" alt="Finance"/>
  <img src="https://img.shields.io/badge/Location-Quebec_City-red?style=flat&logo=map-pin" alt="Location"/>
</p>

### 🤝 Co-authors
- 👩‍🏫 **Marie-Hélène Gagnon** (Professor of Finance, Université Laval)
- 👨‍🏫 **Gabriel J. Power** (IG Wealth Management Chairholder, Université Laval)

</div>

## 📄 License

<p align="center">
  <img src="https://img.shields.io/badge/License-Academic_Use-lightgrey?style=flat&logo=creative-commons" alt="Academic Use"/>
  <img src="https://img.shields.io/badge/Purpose-Educational_Research-blue?style=flat&logo=book" alt="Educational Research"/>
</p>

This academic work is part of a PhD dissertation and is intended for educational and research purposes. Please cite appropriately if using any content from this repository.

---

<div align="center">
  
**📊 Research Excellence in Finance**

<img src="https://img.shields.io/badge/Last_Updated-September_2025-brightgreen?style=flat&logo=calendar" alt="Last Updated"/>
<img src="https://img.shields.io/badge/Made_with-❤️-red?style=flat" alt="Made with Love"/>

*Advancing understanding in commodity financialization*

</div>