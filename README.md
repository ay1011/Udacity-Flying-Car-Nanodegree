# Udacity Flying Car Nanodegree

[![Udacity - Fly Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](https://www.udacity.com/course/flying-car-nanodegree--nd787)



## Projects


### 1. Backyard Flyer
**Description:** Set up a state machine using event-driven programming to make [udacidrone](https://github.com/udacity/udacidrone) fly autonomously in a square shape.

**Code**: [backyard_flyer.py](/FCND-Backyard-Flyer/backyard_flyer.py)

**Result**:

![backyard flyer](/gif/backyard_flyer.gif)

## Environment Setup
1. Download and install [miniconda3](https://conda.io/miniconda.html).
2. Clone the repository and then navigate to `FCND-Term1-Starter-Kit` submodule:
```bash
git clone https://github.com/udacity/FCND-Backyard-Flyer.git
cd FCND-Term1-Starter-Kit
```
3. Create the miniconda environment:
```bash
conda env create -f environment.yml
```
4. Verify the fcnd environment:
```bahs
conda info --envs
```
5. Clean up downloaded packages:
```bash
conda clean -tp
```
6. Activate `fcnd` conda environment:
```bash
activate fcnd
```
