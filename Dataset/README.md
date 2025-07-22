## Dataset Description

The dataset used is based on the [Breast Cancer Wisconsin (Original) Data Set](https://archive.ics.uci.edu/dataset/15/breast+cancer+wisconsin+original)

Each row represents the analysis of a breast mass, with features extracted from a digitized image of a fine needle aspirate (FNA) of a breast mass. The dataset includes the following columns:

| Column Name                   | Description                                                                                    |
| ----------------------------- | ---------------------------------------------------------------------------------------------- |
| Sample Code Number          | ID number (not used in analysis).                                                              |
| Clump Thickness             | Assesses how closely grouped the cells are. Higher values may indicate malignancy.             |
| Uniformity of Cell Size     | Measures variation in cell size. Large variation may suggest cancer.                           |
| Uniformity of Cell Shape    | Measures variation in cell shape. Irregular shapes can be a sign of malignancy.                |
| Marginal Adhesion           | Evaluates how well cells adhere to each other. Poor adhesion is common in cancer cells.        |
| Single Epithelial Cell Size | Compares the size of epithelial cells to normal cells. Larger size may indicate abnormalities. |
| Bare Nuclei                 | Indicates presence of nuclei without cytoplasm. Often linked to malignancy.                    |
| Bland Chromatin             | Examines texture of the nucleus chromatin. Non-uniformity may indicate cancer.                 |
| Normal Nucleoli             | Measures size and quantity of nucleoli. Prominent nucleoli are often found in malignant cells. |
| Mitoses                     | Number of cell divisions. Higher mitotic activity is common in cancerous tissues.              |
| Class                       | Target variable: `2` = **Benign**, `4` = **Malignant**                                         |
