# Investment Research Portfolio

Welcome to the **Investment Research Portfolio** project! This repository showcases the research and analysis of my personal investments, focusing on long-term value investing strategies. The goal is to document the investment process, share insights, and track the performance of a concentrated portfolio.

## Table of Contents

- [Introduction](#introduction)
- [Investment Philosophy](#investment-philosophy)
- [Templates](#templates)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction

This project contains comprehensive research reports and analyses of selected stocks in my investment portfolio. Each report is crafted using LaTeX templates designed for both in-depth analysis and initial stock screening. The repository serves as a record of my investment decisions and a tool for continuous learning and improvement.

## Investment Philosophy

My investment approach is grounded in **long-term value investing**, focusing on:

- Identifying companies with **strong fundamentals** and sustainable competitive advantages.
- Conducting thorough **intrinsic valuation** to find undervalued stocks.
- Maintaining a **concentrated portfolio** to capitalize on high-conviction ideas.
- Emphasizing **risk management** by understanding potential downsides.


## Categories
- Slow Growers: Quite flat earnigns generous and regular divident, dividend safety low payou is less risky than high. (both div and stock), Usually not a BUY if there is no perspective to turn around or new exciting thing. Apple recently
- Stalwarts: grow faster than slow growers 6-12 percent growth, no real miracles here, spike in price are a sell won't justify earnings growth. Can be owned as they are a good protection in a recession, check previous. Make 30-50% then sell.
- Fast Growers: Life changers 20-25% per year not higher, higher are hyped stocks which are very risky and have competition. if grows slows down market with go south, finances have to be very good with substantial profits. At some point they will stop growing its important to think about that check room for growth. Proven expansion in more than one city or country. PE below growth rate. Rare companies.
- Cyclicals: They follow the economy, suffer when economy is bad 50% down or more if at wrong part of the cycle. Timing is everything look at inventories. Stock declines at peak earning when people expect a recession, worst slum better recovery. Upturn easier to predict than downturn usually those are the airlines car manifacturers chemicals ect...
- Turnarounds: close to bankrupcy there is fear for it but when the fear eases the stock explodes everything is rerated. Understand if issues are big as perceived or not. And can the company survive a raid from creditors, how can it turn around? Restructuring is not good. Effects of cutting costs?
- Asset Plays: A company sitting on something valuable that the market is overlooking or it hasn't yet started to print cash. The asset can be cash real estate een accounting losses inventory number of users ect... Know the asset be patient, look at debt and management.


## Templates

This repository also includes LaTeX templates designed for investment research:

- **Comprehensive Analysis Template**: For detailed research and valuation of individual stocks.
- **Initial Research Template**: For quick assessment of stocks during the screening process.

Templates are located in the `templates` directory:

- [Comprehensive Analysis Template](templates/comprehensive_analysis_template.tex)
- [Initial Research Template](templates/initial_research_template.tex)

## Usage

### Viewing Reports

Compiled PDF reports are available in the `reports` directory. To view a report, its only the templates and the main portfolio outlook:

1. Navigate to the `reports` folder.
2. Open the desired PDF file (e.g., `amazon_analysis.pdf`).

### Compiling LaTeX Documents

If you wish to compile the LaTeX documents yourself:

1. Ensure you have a LaTeX distribution installed (e.g., TeX Live, MiKTeX).
2. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/investment-research-portfolio.git
   ```

3. Navigate to the report or template directory:

   ```bash
   cd investment-research-portfolio/reports
   ```

4. Compile the `.tex` file using `pdflatex`:

   ```bash
   pdflatex amazon_analysis.tex
   ```

5. If the document includes references, run `bibtex`:

   ```bash
   bibtex amazon_analysis.aux
   pdflatex amazon_analysis.tex
   pdflatex amazon_analysis.tex
   ```

### Customizing Templates

To use the templates for your own research:

1. Copy the desired template from the `templates` directory.
2. Rename it appropriately.
3. Fill in the sections with your research data.

## Contributing

Feedback, suggestions, and contributions are welcome! If you have insights or improvements:

- **Fork** the repository.
- **Create** a new branch for your changes.
- **Submit** a pull request for review.

Alternatively, you can open an [issue](https://github.com/yourusername/investment-research-portfolio/issues) for any questions or suggestions.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code and templates, but please provide appropriate attribution.

---

**Disclaimer**: The information contained in this repository is for educational and informational purposes only. It reflects personal research and opinions and should not be considered financial advice. Investors should conduct their own due diligence and consult with a licensed financial advisor before making any investment decisions.
