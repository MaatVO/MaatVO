<h1 align="center">Hi, I'm Mattia 👋</h1>

<p align="center">
  <i>I studied philosophy and read Hume on why the future needn't resemble the past.<br>
  Now I get paid to bet that it will.</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/background-theoretical_philosophy-lightgrey" alt="background: theoretical philosophy">
  <img src="https://img.shields.io/badge/focus-time_series_forecasting-brightgreen" alt="focus: time series forecasting">
  <img src="https://img.shields.io/badge/slurm_job-PENDING-yellow" alt="slurm job: PENDING">
</p>

---

### `$ cat conf/human/mattia.yaml`

```yaml
# Hydra config. Instantiate with: python life.py +human=mattia
defaults:
  - background: theoretical_philosophy
  - education: msc_data_science
  - previously: it_business_analyst
  - override hydra/launcher: submitit_slurm   # everything ends up on HPC eventually
  - _self_

name: Mattia Varagnolo
role: data_scientist
employer: fbk/dsip            # Fondazione Bruno Kessler, Trento
specialization: time_series_forecasting
domains: [weather, climate, hydrology]
loss: mse                     # usually
seed: 42
```

### 🔮 Things I'm forecasting

| | Domain | What's going on |
|---|---|---|
| 🌊 | Hydrology | Water-level prediction and anomaly detection for a regional hydrological service, on live sensor data |
| 🌬️ | Numerical weather | Deep learning post-processing of forecast output |
| 🌩️ | Nowcasting | Short-range alerting for the regional weather service, with the FBK team |
| 🌍 | Climate | Generative models for downscaling, on large Zarr archives and many GPUs |
| 🌾 | Agriculture | Crop yield forecasting across several regions, PyTorch + Hydra |

And on the non-forecasting days: LLM systems, mostly RAG pipelines and evaluation. Someone has to write the grant applications.

### 🛠️ Open source

- **[MLCast](https://github.com/mlcast-community)**: contributor to the community framework for ML weather nowcasting, born in the EUMETNET E-AI programme
- **TSViz** 🚧: a time series visualization engine with weather modules and a core for classical ML on everyday time series

### 📦 `import`s

```python
import torch
import lightning as L
import hydra
import xarray as xr, zarr, dask, ray
import mlflow
from langgraph.graph import StateGraph   # for the non-forecasting days

# deployed via: Docker, Kubernetes, GCP, GitHub Actions
# trained on:   whatever Slurm gives me
```

### 🎓 Teaching

- Lecture on training deep learning models on HPC at FBK's AI for Weather and Climate School
- Team lead and mentor at WebValley, FBK's summer school for young data scientists

### 🎿 When the GPUs are busy

Skiing · motorcycle · games · still arguing about philosophy

### 📡 `ping`

[LinkedIn](https://www.linkedin.com/in/mattiavaragnolo) · [mattia.varagnolo@gmail.com](mailto:mattia.varagnolo@gmail.com)

<p align="center"><sub>Forecast for this README: 90% chance of being outdated by 2028.</sub></p>
