CellMarkerFinder

CellMarkerFinder is a lightweight Python notebook tool for exploring cell-type marker genes by species using a searchable marker library.

This tool allows users to quickly retrieve marker genes associated with specific cell types in Human or Mouse from a curated dataset derived from the CellMarker database.

The goal of this project is to provide a simple interface for researchers to browse and extract marker genes efficiently for downstream biological analysis such as single-cell RNA-seq, spatial biology, and multiplex imaging.

Data Source

The marker dataset used in this project originates from the CellMarker database.

CellMarker is a manually curated database of experimentally supported cell markers across tissues in human and mouse.

Official database website:

http://117.50.127.228/CellMarker/

The database compiles marker information from thousands of published studies and provides marker genes associated with many different cell types across tissues.

Citation

If you use the CellMarker database, please cite:

Hu C, Li T, Xu Y, et al.
CellMarker 2.0: an updated database of manually curated cell markers in human/mouse and web tools based on scRNA-seq data.
Nucleic Acids Research. 2023.

About This Tool

This repository provides a simple search interface built in Python using Jupyter Notebook that allows users to:

browse cell types using a scrollable dropdown list

filter cell types using a search box

select species (Human or Mouse)

retrieve alphabetically sorted marker genes

The tool is designed to make marker retrieval fast and convenient when preparing gene lists for biological analysis.

Features

Scrollable list of cell types

Search box to filter cell names

Species selection (Human / Mouse)

Returns marker gene lists

Genes are sorted alphabetically for easy copying

Lightweight interface using Python and ipywidgets

Example Workflow

Select a cell type from the dropdown list

If the desired cell type is not visible, type a keyword in the search box to filter the list

Select the species

Click Find genes

Example:

Cell type: macrophage
Species: Human

Output:

CD14
CD163
CD68
CSF1R
MARCO
MSR1


Author

Long Nguyen
Master's Student
Institute of Biotechnology
National Taiwan University (NTU)

This tool was developed as a small research utility to simplify exploration of cell-type marker genes derived from the CellMarker database.

Disclaimer

This project is an independent research utility and is not affiliated with the official CellMarker database developers.

All credit for the marker data belongs to the CellMarker database authors.
