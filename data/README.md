**CONTENTS OF THE `data` FOLDER:**

**Note:** only the original CARMENES RV time series and the Machine Learning results are available in _GitHub_. The folders with their size shown in **bold text** are not directly available from _GitHub_. If interested in some specific data, please contact [ciro.emmanuel@dskyr.com](mailto:ciro.emmanuel@dskyr.com), indicating your affiliation and the purpose of use for the requested data.

**Files:**

- `README.md` (7 KB): this file.
- `FINAL_CARMENES_2Pulsators_Details.csv` (8 KB): the details (Carmencita parameters and more) from the $2$ CARMENES stars labelled as pulsators by the ML model.
- `CARMENES_5_Stars_Interest_PG.csv` (24 KB): the details (Carmencita parameters and more) from the $5$ CARMENES stars identified as interesting ones from the periodogram perspective.
- `Cesium_Corr_ML.csv` (240 KB): cross-correlation of _cesium_ features, for ML sample.
- `Cesium_Corr_S4.csv` (244 KB): cross-correlation of _cesium_ features, for S4 sample.
- `cesium_Features_by_Category.csv` (15 KB): a list of the extracted _cesium_ features, grouped by category.
- `RV_FINAL_ML_SyntheticDatasets_without_PG.csv` (544 KB): summary of the $1,000$ synthetic stars generated for S4 sample.
- `RV_ForPG_SyntheticDatasets_with_PG.csv` (1.4 MB): summary of the $300$ synthetic stars generated for the analysis of the impact of sampling and noise over the periodogram.
- `CARM_VIS_objects_with_PG_and_WF.csv` (1.5 MB): data of the $387$ CARMENES stars, including the periodogram results, and window functions calculations.
- `SELECTION_for_ML_CARM_VIS_objects_with_PG.csv` (872 KB): subset of the file `CARM_VIS_objects_with_PG_and_WF.csv`, with only the $233$ CARMENES stars selected for Machine Learning analysis.
- `SELECTION_for_PG_CARM_VIS_objects_with_PG.csv` (1.1 MB): subset of the file `CARM_VIS_objects_with_PG_and_WF.csv`, with only the $269$ CARMENES stars selected for periodogram analysis.
- `carmencita.readme.txt` (35 KB): description of the fields in the `carmencita.102.csv` file.
- `carmencita.102.csv` (2.1 MB): data for $2,212$ stars in Carmencita database.

**Compressed folders:**

- `CARM_VIS_RVs.zip` (3.8 MB): CARMENES RV time series
  - Includes both raw (`*.avcn.dat`) and processed (`*.avc.dat`) RV time series.

- `CARMENES_GTO_TESS_lc.zip` (**951 MB**): TESS photometric light curves available for some CARMENES stars.

- `CARM_VIS_RVs_PGs.zip` (**7.9 GB**): periodogram results (GLS) for CARMENES RV time series.
  - Includes the frequency periodogram result files (`*.dat`) and figures (subfolder `figures`).

- `CARM_VIS_TESS_PGs.zip` (**171 MB**): periodogram results (GLS) for TESS light curves.
  - Includes the frequency periodogram result files (`*.dat`) and figures (subfolder `figures`).

- `S1_ForPG_RVs_PGs.zip` (**77 MB**): periodogram results (GLS) for $S1_{p}$ sample (300 synthetic stars, perfectly sampled and noiseless).
  - Includes the frequency periodogram result files (`*.dat`) and figures (subfolder `figures`).

- `S2_ForPG_RVs_PGs.zip` (**107 MB**): periodogram results (GLS) for $S2_{p}$ sample (300 synthetic stars, perfectly sampled and with RV errors).
  - Includes the frequency periodogram result files (`*.dat`) and figures (subfolder `figures`).

- `S3_ForPG_RVs_PGs.zip` (**78 MB**): periodogram results (GLS) for $S3_{p}$ sample (300 synthetic stars, irregularly sampled and noiseless).
  - Includes the frequency periodogram result files (`*.dat`) and figures (subfolder `figures`).

- `S4_ForPG_RVs_PGs.zip` (**93 MB**): periodogram results (GLS) for $S4_{p}$ sample (300 synthetic stars, irregularly sampled and with RV errors).
  - Includes the frequency periodogram result files (`*.dat`) and figures (subfolder `figures`).

- `CARM_VIS_RVs_WinFunc_PGs.zip` (**3.1 GB**): periodogram results (GLS) for the Window Functions of CARMENES RV time series.
  - Includes the frequency periodogram result files (`*.dat`) and figures (subfolder `figures`).

- `CARM_VIS_TESS_WinFunc_PGs.zip` (**219 MB**): periodogram results (GLS) for the Window Functions of TESS light curves.
  - Includes the frequency periodogram result files (`*.dat`) and figures (subfolder `figures`).

- `STACKED_PG.zip` (24 MB): results of stacked periodograms obtained.
  - Includes two folders: one for CARMENES RV time series and another for TESS light curves. Both folder containd the stacked periodogram file (`*.dat`) and plot.

- `DIST_FILES.zip` (5.6 MB): files to generate the synthetic stars.
  - Contains the distributions of RV errors, sampling patterns, frequency, amplitude, reference epoch, phase and offset, for both the PG sample and ML sample.

- `SYNTH_RV_SAMPLES.zip` (**1.4 GB**): synthetic samples generated for simulated pulsating / non-pulsating stars:
  - Files:
    - `RV_FINAL_ML_SyntheticDataset.csv`: Summary of the $1,000$ synthetic stars created for ML analysis.
    - `RV_ForPG_SyntheticDatasets.csv`: Summary of the $300$ synthetic stars created for PG analysis.
    - `RV_ALTERNATIVE_S4B_Sample.csv`: Summary of the $37,280$ synthetic stars generated with an alternative approach, with a better coverage of the star pulsation parameters space.
  - Folders:
    - `S1/S2/S3/S4_FINAL_ts_files`: individual RV files of synthetic stars for samples $S1$, $S2$, $S3$ and $S4$ ($1,000 simulated stars, for ML analysis).
    - `S1/S2/S3/S4_ForPG_ts_files`: individual RV files of synthetic stars for samples $S1_{p}$, $S2_{p}$, $S3_{p}$ and $S4_{p}$ ($300 simulated stars, for PG analysis).
    - `S4B_ALTERNATIVE_ts_files`: $37,280$ simulated stars created with pulsation grids of: amplitude $A\in\;[0.1, 0.2, 0.4, 0.8, 1.6]\;m\;s^{-1}$; frequency $\nu\in\;[8.0, 16.0, 32.0, 64.0]\;d^{-1}$; phase $\delta\in\;[0.0, 0.25, 0.50, 0.75]$. In this case, only the S4 sample (noisy and with imperfect sampling) was created.

- `DATASETS_CESIUM.zip` (29 MB): files containing the cesium features extracted. It also includes the features of alternative synthetic sets of $37,280$ stars and $4000$ stars (under subfolder `1NN`).

- `DATASETS_ML.zip` (86 MB): contains all the tables of ML datasets, from the cesium features and transformed by the different steps of the ML process (imputing, scaling, etc.).

- `ML_MODELS.zip` (40 MB): contains all the steps and results of the ML model design, optimization, training and validation. There are three subfolders:
  - `ML_model_preselection`: contains the results of the ML model selection, from a pool of models of different families.
  - `ML_pipeline_steps`: contains the details and design (in `*.pickle` files) of all the ML pipeline steps.
  - `Results_decisionTree`: contains all the results obtained from the final model, the Decision Tree. The final model is stored in the `FINAL_Opt_DT_Classifier.pickle` file.

