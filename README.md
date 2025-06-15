# ANI_Pipeline
Análisis de identidad de nucleótidos (Python)

Este pipeline permite descargar genomas completos desde RefSeq, descomprimirlos, y calcular matrices ANI usando skani y fastANI.

## Requisitos

- Conda instalado
- Git

## Instalación

```bash
git clone https://github.com/tu_usuario/ANI_pipeline.git
cd ANI_pipeline
conda env create -f environment.yml
conda activate ani_env
jupyter notebook ANI_pipeline.ipynb

##Uso

- Ejecuta el notebook.
- Ingresa el taxID del organismo.
- El pipeline descargará los genomas, los descomprimirá y calculará ANI.
- Los resultados estarán en skani_output.tsv y fastani_output.tsv.
