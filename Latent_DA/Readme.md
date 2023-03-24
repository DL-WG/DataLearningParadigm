In this code, we introduce the Generalised Latent Assimilation (GLA) approach which can be used in Machine learning surrogate modelling for dynamical systems The reportory including python scripts for reduced-order-modelling (POD, 1D CAE and POD AE), LSTM surrogate modelling (inside the latent space with preprocessing) and GLA (with non-linear high dimensional transformation operators).

If you are interested in applying GLA for a inverse problem with an initial guess, please refer to the file GLA_simple_ex.py in the GLA repotory. The ROM_LSTM_GLA.py contains the implementation of GLA with a reduced-order surrogate model (with either POD or POD AE + LSTM).

Due to the large volume, we provide only 5 time steps of oil concentration data (The CFD data for one simulation (Um = 0.52)) in the two-phase flow application. To read and reshape openfoam data, please refer to the python script load_data.py in ROM repotory. The full CFD dataset is available upon reasonalble request to sibo.cheng@imperial.ac.uk

citation:

@article{cheng2023generalised,
  title={Generalised latent assimilation in heterogeneous reduced spaces with machine learning surrogate models},
  author={Cheng, Sibo and Chen, Jianhua and Anastasiou, Charitos and Angeli, Panagiota and Matar, Omar K and Guo, Yi-Ke and Pain, Christopher C and Arcucci, Rossella},
  journal={Journal of Scientific Computing},
  volume={94},
  number={1},
  pages={11},
  year={2023},
  publisher={Springer}
}

@article{cheng2022data,
  title={Data-driven surrogate model with latent data assimilation: Application to wildfire forecasting},
  author={Cheng, Sibo and Prentice, I Colin and Huang, Yuhan and Jin, Yufang and Guo, Yi-Ke and Arcucci, Rossella},
  journal={Journal of Computational Physics},
  volume={464},
  pages={111302},
  year={2022},
  publisher={Elsevier}
}

@article{zhuang2022ensemble,
  title={Ensemble latent assimilation with deep learning surrogate model: application to drop interaction in a microfluidics device},
  author={Zhuang, Yilin and Cheng, Sibo and Kovalchuk, Nina and Simmons, Mark and Matar, Omar K and Guo, Yi-Ke and Arcucci, Rossella},
  journal={Lab on a Chip},
  volume={22},
  number={17},
  pages={3187--3202},
  year={2022},
  publisher={Royal Society of Chemistry}
}
