# Napari 2D Colocalization Analysis

A Jupyter notebook for interactive 2D fluorescence microscopy image analysis using Napari.

The notebook provides an end-to-end workflow for quantitative colocalization analysis, allowing manual region selection, threshold optimisation, mask generation, and calculation of common colocalization metrics.

## Features

- Interactive image visualisation with Napari
- Manual ROI selection
- Adjustable intensity thresholding
- Background removal
- Binary mask generation
- Pearson correlation coefficient
- Manders overlap coefficients
- Positive pixel quantification
- Result export to CSV
- Publication-quality visualisations

## Requirements

The recommended environment can be created directly from the supplied Conda environment:

```bash
conda env create -f environment.yml
conda activate napari-colocalisation
```

## Main packages

- napari
- numpy
- pandas
- scikit-image
- scipy
- matplotlib
- magicgui

## Usage

1. Launch Jupyter Lab

```bash
jupyter lab
```

2. Open

```
napari_2d_colocalisation.ipynb
```

3. Load your microscopy images.

4. Adjust thresholds.

5. Draw ROIs in Napari.

6. Run the remaining cells to calculate colocalisation statistics.

## Outputs

The notebook generates:

- Pearson correlation coefficient
- Manders coefficients
- Positive pixel measurements
- Binary masks
- CSV summary tables

## Citation

If this notebook contributes to your work, please cite the repository.

## License

MIT License
