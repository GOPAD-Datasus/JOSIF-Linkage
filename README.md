# JOSIF Record Linkage

## Paper

>This repository is based on our paper:  
**Proposal For Linkage Between Health Information Systems SIM And SINASC**  
Authors: Morsoleto, R. et al.  
Presented and accepted at: [JOSIF](https://josif.ifsuldeminas.edu.br/ojs/index.php/anais/index) 2024.

## Installation & Usage

> [!IMPORTANT]  
> The files ``DN.parquet.gzip`` and ``DO.parquet.gzip`` weren't included in this repository due to their size. Both will need to be manually loaded on to the ``data/input`` folder. 

Poetry was used for dependency management. To download it, visit: [python-poetry.org](https://python-poetry.org/).

Activate a virtual environment and execute:

```bash
poetry install
# Or
pip install .
```

```bash
python main.py
```

## License
[LGNU](LICENSE) | © GOPAD 2025
