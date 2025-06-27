# Project Setup Instructions

Follow these steps to set up your environment and get started with the project.

---

## 1. Install Anaconda

Make sure [Anaconda](https://www.anaconda.com/) is installed on your machine.

- [Download Anaconda for macOS](https://www.anaconda.com/products/distribution#macos)
- [Download Anaconda for Windows](https://www.anaconda.com/products/distribution#windows)

Follow the installation instructions specific to your operating system.

---

## 2. Clone the Repository

Clone the repository containing the `environment.yml` file to your local machine:

```bash
git clone https://github.com/AmmarMohanna/EECE503P-798S.git
cd chapter_2_large_language_models/virtual_environment_setup

```
## 3. Create the Conda Environment

Open the terminal appropriate for your OS:

- Windows: Anaconda PowerShell Prompt
- macOS/Linux: Terminal

Create the environment using the YAML file:
```bash
conda env create -f environment.yml
```
### 4. Activate the Environment

Activate the newly created environment:

```bash
conda activate llms
```

### 5. Launch JupyterLab

Start JupyterLab from the terminal:

```bash
jupyter lab
```