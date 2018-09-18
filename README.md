# tcga_visualization

Project that allows to visualize benchmarking results from the TCGA community in a *'D3.js'* chart.

The sample [data](https://github.com/inab/tcga_visualization/tree/master/data) used in this visualizer has been derived from the materials of next manuscript:

[Comprehensive Characterization of Cancer Driver Genes and Mutations](https://www.cell.com/cell/fulltext/S0092-8674%2818%2930237-X?code=cell-site), Bailey et al, 2018, Cell

[![doi:10.1016/j.cell.2018.02.060](https://img.shields.io/badge/doi-10.1016%2Fj.cell.2018.02.060-green.svg)](https://doi.org/10.1016/j.cell.2018.02.060)

# How to use

Requirements:

-npm
-http server

Clone the repo to your document root :
```
git clone https://github.com/inab/tcga_visualization.git
```

Install dependencies from package.json :
```
npm install 
```

Compile with webpack and visualize sample results in your localhost :
```
./node_modules/.bin/webpack-cli src/app.js --output=build/build.js -d -w
```
