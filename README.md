# Biology-Viewer

BiologyViewer is a compact 3D biology structure viewer built with Python, Pygame, and OpenGL.

It displays real-source-backed biological structures including:

- Proteins from RCSB PDB
- Human organs from BodyParts3D meshes
- Molecules from PubChem 3D
- Nucleic acids such as DNA and RNA from RCSB PDB

## Features

- Clean 3D rendering with compact framing
- Category-based visual identity
- CLI-style startup banner
- Protein secondary-structure coloring
- Ball-and-stick molecule rendering
- Source-backed anatomy mesh rendering
- Cached downloads for faster reuse

## Supported Categories

- Protein
- Molecule
- Nucleic Acid
- Human Organ

## Example Items

- `hemoglobin`
- `actin`
- `glucose`
- `atp`
- `dna_double_helix`
- `trna_rna`
- `liver`
- `lungs`
- `stomach`

## Requirements

Install the required Python packages before running:

```bash
pip install pygame PyOpenGL biopython numpy
