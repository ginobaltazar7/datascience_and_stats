# Awesome Data Science and Statistics with Python

> A curated list of awesome resources for practicing data science using Python, including not only libraries, but also links to tutorials, code snippets, blog posts and talks.  
#### Core
[pandas](https://pandas.pydata.org/) - Data structures built on top of [numpy](https://www.numpy.org/).  
[scikit-learn](https://scikit-learn.org/stable/) - Core ML library.  
[matplotlib](https://matplotlib.org/) - Plotting library.  
[seaborn](https://seaborn.pydata.org/) - Data visualization library based on matplotlib.  
[datatile](https://github.com/polyaxon/datatile) - Basic statistics using `DataFrameSummary(df).summary()`.  
[pandas_profiling](https://github.com/pandas-profiling/pandas-profiling) - Descriptive statistics using `ProfileReport`.  
[sklearn_pandas](https://github.com/scikit-learn-contrib/sklearn-pandas) - Helpful `DataFrameMapper` class.  
[missingno](https://github.com/ResidentMario/missingno) - Missing data visualization.  
[rainbow-csv](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv) - Plugin to display .csv files with nice colors.  

#### Environment and Jupyter
[General Jupyter Tricks](https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/)  
Fixing environment: [link](https://jakevdp.github.io/blog/2017/12/05/installing-python-packages-from-jupyter/)  
Python debugger (pdb) - [blog post](https://www.blog.pythonlibrary.org/2018/10/17/jupyter-notebook-debugging/), [video](https://www.youtube.com/watch?v=Z0ssNAbe81M&t=1h44m15s), [cheatsheet](https://nblock.org/2011/11/15/pdb-cheatsheet/)  
[cookiecutter-data-science](https://github.com/drivendata/cookiecutter-data-science) - Project template for data science projects.  
[nteract](https://nteract.io/) - Open Jupyter Notebooks with doubleclick.  
[papermill](https://github.com/nteract/papermill) - Parameterize and execute Jupyter notebooks, [tutorial](https://pbpython.com/papermil-rclone-report-1.html).  
[nbdime](https://github.com/jupyter/nbdime) - Diff two notebook files, Alternative GitHub App: [ReviewNB](https://www.reviewnb.com/).  
[RISE](https://github.com/damianavila/RISE) - Turn Jupyter notebooks into presentations.  
[qgrid](https://github.com/quantopian/qgrid) - Pandas `DataFrame` sorting.  
[pivottablejs](https://github.com/nicolaskruchten/jupyter_pivottablejs) - Drag n drop Pivot Tables and Charts for jupyter notebooks.  
[itables](https://github.com/mwouts/itables) - Interactive tables in Jupyter.  
[jupyter-datatables](https://github.com/CermakM/jupyter-datatables) - Interactive tables in Jupyter.  
[debugger](https://blog.jupyter.org/a-visual-debugger-for-jupyter-914e61716559) - Visual debugger for Jupyter.  
[nbcommands](https://github.com/vinayak-mehta/nbcommands) - View and search notebooks from terminal.  
[handcalcs](https://github.com/connorferster/handcalcs) - More convenient way of writing mathematical equations in Jupyter.  
[notebooker](https://github.com/man-group/notebooker) - Productionize and schedule Jupyter Notebooks.  
[bamboolib](https://github.com/tkrabel/bamboolib) - Intuitive GUI for tables.  
[voila](https://github.com/QuantStack/voila) - Turn Jupyter notebooks into standalone web applications.  
[voila-gridstack](https://github.com/voila-dashboards/voila-gridstack) - Voila grid layout.  

#### Pandas Tricks, Alternatives and Additions
[Pandas Tricks](https://towardsdatascience.com/5-lesser-known-pandas-tricks-e8ab1dd21431)  
[Using df.pipe() (video)](https://www.youtube.com/watch?v=yXGCKqo5cEY)  
[pandasvault](https://github.com/firmai/pandasvault) - Large collection of pandas tricks.  
[modin](https://github.com/modin-project/modin) - Parallelization library for faster pandas `DataFrame`.  
[vaex](https://github.com/vaexio/vaex) - Out-of-Core DataFrames.  
[pandarallel](https://github.com/nalepae/pandarallel) - Parallelize pandas operations.  
[xarray](https://github.com/pydata/xarray/) - Extends pandas to n-dimensional arrays.  
[swifter](https://github.com/jmcarpenter2/swifter) - Apply any function to a pandas dataframe faster.   
[pandas_flavor](https://github.com/Zsailer/pandas_flavor) - Write custom accessors like `.str` and `.dt`.   
[pandas-log](https://github.com/eyaltrabelsi/pandas-log) - Find business logic issues and performance issues in pandas.  
[pandapy](https://github.com/firmai/pandapy) - Additional features for pandas.  
[lux](https://github.com/lux-org/lux) - Dataframe visualization within Jupyter.  
[dtale](https://github.com/man-group/dtale) - View and analyze Pandas data structures, integrating with Jupyter.  
[polars](https://github.com/pola-rs/polars) - Multi-threaded alternative to pandas.  

#### Scikit-Learn Alternatives
[scikit-learn-intelex](https://github.com/intel/scikit-learn-intelex) - Intel extension for scikit-learn for speed.  

#### Helpful
[drawdata](https://github.com/koaning/drawdata) - Quickly draw some points and export them as csv, [website](https://drawdata.xyz/).  
[tqdm](https://github.com/tqdm/tqdm) - Progress bars for for-loops. Also supports [pandas apply()](https://stackoverflow.com/a/34365537/1820480).  
[icecream](https://github.com/gruns/icecream) - Simple debugging output.  
[loguru](https://github.com/Delgan/loguru) - Python logging.  
[pyprojroot](https://github.com/chendaniely/pyprojroot) - Helpful `here()` command from R.  
[intake](https://github.com/intake/intake) - Loading datasets made easier, [talk](https://www.youtube.com/watch?v=s7Ww5-vD2Os&t=33m40s).   

#### Extraction
[textract](https://github.com/deanmalmgren/textract) - Extract text from any document.  
[camelot](https://github.com/socialcopsdev/camelot) - Extract text from PDF.  

#### Big Data
[spark](https://docs.databricks.com/spark/latest/dataframes-datasets/introduction-to-dataframes-python.html#work-with-dataframes) - `DataFrame` for big data, [cheatsheet](https://gist.github.com/crawles/b47e23da8218af0b9bd9d47f5242d189), [tutorial](https://github.com/ericxiao251/spark-syntax).  
[sparkit-learn](https://github.com/lensacom/sparkit-learn), [spark-deep-learning](https://github.com/databricks/spark-deep-learning) - ML frameworks for spark.  
[koalas](https://github.com/databricks/koalas) - Pandas API on Apache Spark.  
[dask](https://github.com/dask/dask), [dask-ml](http://ml.dask.org/) - Pandas `DataFrame` for big data and machine learning library, [resources](https://matthewrocklin.com/blog//work/2018/07/17/dask-dev), [talk1](https://www.youtube.com/watch?v=ccfsbuqsjgI), [talk2](https://www.youtube.com/watch?v=RA_2qdipVng), [notebooks](https://github.com/dask/dask-ec2/tree/master/notebooks), [videos](https://www.youtube.com/user/mdrocklin).  
[dask-gateway](https://github.com/jcrist/dask-gateway) - Managing dask clusters.  
[turicreate](https://github.com/apple/turicreate) - Helpful `SFrame` class for out-of-memory dataframes.  
[h2o](https://github.com/h2oai/h2o-3) - Helpful `H2OFrame` class for out-of-memory dataframes.  
[datatable](https://github.com/h2oai/datatable) - Data Table for big data support.  
[cuDF](https://github.com/rapidsai/cudf) - GPU DataFrame Library, [Intro](https://www.youtube.com/watch?v=6XzS5XcpicM&t=2m50s).  
[ray](https://github.com/ray-project/ray/) - Flexible, high-performance distributed execution framework.  
[mars](https://github.com/mars-project/mars) - Tensor-based unified framework for large-scale data computation.  
[bottleneck](https://github.com/kwgoodman/bottleneck) - Fast NumPy array functions written in C.   
[bolz](https://github.com/Blosc/bcolz) - A columnar data container that can be compressed.  
[cupy](https://github.com/cupy/cupy) - NumPy-like API accelerated with CUDA.  
[petastorm](https://github.com/uber/petastorm) - Data access library for parquet files by Uber.  
[zarr](https://github.com/zarr-developers/zarr-python) - Distributed numpy arrays.  
[NVTabular](https://github.com/NVIDIA/NVTabular) - Feature engineering and preprocessing library for tabular data by nvidia.  

#### Distributed Systems
[nextflow](https://github.com/nextflow-io/nextflow) - Run scripts and workflow graphs in Docker image using Google Life Sciences, AWS Batch and others.  
[dsub](https://github.com/DataBiosphere/dsub) - Run batch computing tasks in Docker image in the Google Cloud.  

#### Command line tools, CSV
[ni](https://github.com/spencertipping/ni) - Command line tool for big data.  
[xsv](https://github.com/BurntSushi/xsv) - Command line tool for indexing, slicing, analyzing, splitting and joining CSV files.  
[csvkit](https://csvkit.readthedocs.io/en/1.0.3/) - Another command line tool for CSV files.  
[csvsort](https://pypi.org/project/csvsort/) - Sort large csv files.  
[tsv-utils](https://github.com/eBay/tsv-utils) - Tools for working with CSV files by ebay.  
[cheat](https://github.com/cheat/cheat) - Make cheatsheets for command line commands.  

#### Classical Statistics

##### Statistical Tests and Packages
[Modes, Medians and Means: A Unifying Perspective](https://www.johnmyleswhite.com/notebook/2013/03/22/modes-medians-and-means-an-unifying-perspective/)   
[Using Norms to Understand Linear Regression](https://www.johnmyleswhite.com/notebook/2013/03/22/using-norms-to-understand-linear-regression/)   
[Verifying the Assumptions of Linear Models](https://github.com/erykml/medium_articles/blob/master/Statistics/linear_regression_assumptions.ipynb)  
[Mediation and Moderation Intro](https://ademos.people.uic.edu/Chapter14.html)  
[statsmodels](https://www.statsmodels.org/stable/index.html) - Statistical tests.  
[linearmodels](https://github.com/bashtage/linearmodels) - Instrumental variable and panel data models.  
[pingouin](https://github.com/raphaelvallat/pingouin) - Statistical tests. [Pairwise correlation between columns of pandas DataFrame](https://pingouin-stats.org/generated/pingouin.pairwise_corr.html)   
[scipy.stats](https://docs.scipy.org/doc/scipy/reference/stats.html#statistical-tests) - Statistical tests.  
[scikit-posthocs](https://github.com/maximtrp/scikit-posthocs) - Statistical post-hoc tests for pairwise multiple comparisons.   
Bland-Altman Plot [1](https://pingouin-stats.org/generated/pingouin.plot_blandaltman.html), [2](http://www.statsmodels.org/dev/generated/statsmodels.graphics.agreement.mean_diff_plot.html) - Plot for agreement between two methods of measurement.  
[ANOVA](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.f_oneway.html), Tutorials: [One-way](https://pythonfordatascience.org/anova-python/), [Two-way](https://pythonfordatascience.org/anova-2-way-n-way/), [Type 1,2,3 explained](https://mcfromnz.wordpress.com/2011/03/02/anova-type-iiiiii-ss-explained/).  

##### Comparing Two Populations
[torch-two-sample](https://github.com/josipd/torch-two-sample) - Friedman-Rafsky Test: Compare two population based on a multivariate generalization of the Runstest. [Explanation](https://www.real-statistics.com/multivariate-statistics/multivariate-normal-distribution/friedman-rafsky-test/), [Application](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5014134/)  

##### Process Improvement / Factorial Experiments
[Factorial Design](https://opentext.wsu.edu/carriecuttler/chapter/9-1-setting-up-a-factorial-experiment/) - Modeling factor or feature interaction effects using a factorial design table   
[Process Improvement](https://www.itl.nist.gov/div898/handbook/pri/pri.htm) Basic concepts, terminology, underlying the proper statistical design of experiments   
[Yates Algorithm](https://www.itl.nist.gov/div898/handbook/eda/section3/eda35i.htm) - Estimate Factor Effects in a 2-Level Factorial Design, see also this link to [Stanford Lecture](https://artowen.su.domains/courses/363/Lecture_02_08.pdf)

##### Interim Analyses / Sequential Analysis / Stopping
[Sequential Analysis](https://en.wikipedia.org/wiki/Sequential_analysis) - Wikipedia.  
[Treatment Effects Monitoring](https://online.stat.psu.edu/stat509/node/75/) - Design and Analysis of Clinical Trials PennState.  
[sequential](https://cran.r-project.org/web/packages/Sequential/Sequential.pdf) - Exact Sequential Analysis for Poisson and Binomial Data (R package).  
[confseq](https://github.com/gostevehoward/confseq) - Uniform boundaries, confidence sequences, and always-valid p-values.  

##### Visualizations
[Dependent Propabilities](https://static.laszlokorte.de/stochastic/)  
[Null Hypothesis Significance Testing (NHST) and Sample Size Calculation](https://rpsychologist.com/d3/NHST/)  
[Correlation](https://rpsychologist.com/d3/correlation/)  
[Cohen's d](https://rpsychologist.com/d3/cohend/)  
[Confidence Interval](https://rpsychologist.com/d3/CI/)  
[Equivalence, non-inferiority and superiority testing](https://rpsychologist.com/d3/equivalence/)  
[Bayesian two-sample t test](https://rpsychologist.com/d3/bayes/)  
[Distribution of p-values when comparing two groups](https://rpsychologist.com/d3/pdist/)  
[Understanding the t-distribution and its normal approximation](https://rpsychologist.com/d3/tdist/)  

##### Talks
[Inverse Propensity Weighting](https://www.youtube.com/watch?v=SUq0shKLPPs)  
[Dealing with Selection Bias By Propensity Based Feature Selection](https://www.youtube.com/watch?reload=9&v=3ZWCKr0vDtc)  

##### Texts
[Montgomery et al. - How conditioning on post-treatment variables can ruin your experiment and what to do about it](https://cpb-us-e1.wpmucdn.com/sites.dartmouth.edu/dist/5/2293/files/2021/03/post-treatment-bias.pdf)  
[Greenland - Statistical tests, P values, confidence intervals, and power: a guide to misinterpretations](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4877414/)  
[Blume - Second-generation p-values: Improved rigor, reproducibility, & transparency in statistical analyses](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0188299)  
[Lindeløv - Common statistical tests are linear models](https://lindeloev.github.io/tests-as-linear/)    
[Chatruc - The Central Limit Theorem and its misuse](https://lambdaclass.com/data_etudes/central_limit_theorem_misuse/)  
[Al-Saleh - Properties of the Standard Deviation that are Rarely Mentioned in Classrooms](http://www.stat.tugraz.at/AJS/ausg093/093Al-Saleh.pdf)   
[Wainer - The Most Dangerous Equation](http://www-stat.wharton.upenn.edu/~hwainer/Readings/Most%20Dangerous%20eqn.pdf)   
[Gigerenzer - The Bias Bias in Behavioral Economics](https://www.nowpublishers.com/article/Details/RBE-0092)  
[Cook - Estimating the chances of something that hasn’t happened yet](https://www.johndcook.com/blog/2010/03/30/statistical-rule-of-three/)  

#### Epidemiology
[R Epidemics Consortium](https://www.repidemicsconsortium.org/projects/) - Large tool suite for working with epidemiological data (R packages). [Github](https://github.com/reconhub)   
[incidence2](https://github.com/reconhub/incidence2) - Computation, handling, visualisation and simple modelling of incidence (R package).  
[EpiEstim](https://github.com/mrc-ide/EpiEstim) - Estimate time varying instantaneous reproduction number R during epidemics (R package) [paper](https://academic.oup.com/aje/article/178/9/1505/89262).  
[researchpy](https://github.com/researchpy/researchpy) - Helpful `summary_cont()` function for summary statistics (Table 1).  
[zEpid](https://github.com/pzivich/zEpid) - Epidemiology analysis package, [Tutorial](https://github.com/pzivich/Python-for-Epidemiologists).  

#### Exploration and Cleaning
[Checklist](https://github.com/r0f1/ml_checklist).  
[pandasgui](https://github.com/adamerose/pandasgui) - GUI for viewing, plotting and analyzing Pandas DataFrames.  
[janitor](https://pyjanitor.readthedocs.io/) - Clean messy column names.  
[impyute](https://github.com/eltonlaw/impyute) - Imputations.  
[fancyimpute](https://github.com/iskandr/fancyimpute) - Matrix completion and imputation algorithms.  
[imbalanced-learn](https://github.com/scikit-learn-contrib/imbalanced-learn) - Resampling for imbalanced datasets.  
[tspreprocess](https://github.com/MaxBenChrist/tspreprocess) - Time series preprocessing: Denoising, Compression, Resampling.  
[Kaggler](https://github.com/jeongyoonlee/Kaggler) - Utility functions (`OneHotEncoder(min_obs=100)`)  
[pyupset](https://github.com/ImSoErgodic/py-upset) - Visualizing intersecting sets.  
[pyemd](https://github.com/wmayner/pyemd) - Earth Mover's Distance / Wasserstein distance, similarity between histograms. [OpenCV implementation](https://docs.opencv.org/3.4/d6/dc7/group__imgproc__hist.html), [POT implementation](https://pythonot.github.io/auto_examples/plot_OT_2D_samples.html)   
[littleballoffur](https://github.com/benedekrozemberczki/littleballoffur) - Sampling from graphs.  

#### Noisy Labels
[cleanlab](https://github.com/cleanlab/cleanlab) - Machine learning with noisy labels, finding mislabeled data, and uncertainty quantification. Also see awesome list below.  
[doubtlab](https://github.com/koaning/doubtlab) - Find bad or noisy labels.

#### Train / Test Split
[iterative-stratification](https://github.com/trent-b/iterative-stratification) - Stratification of multilabel data.  

#### Feature Engineering
[Talk](https://www.youtube.com/watch?v=68ABAU_V8qI)  
[sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html) - Pipeline, [examples](https://github.com/jem1031/pandas-pipelines-custom-transformers).  
[pdpipe](https://github.com/shaypal5/pdpipe) - Pipelines for DataFrames.  
[scikit-lego](https://github.com/koaning/scikit-lego) - Custom transformers for pipelines.  
[skoot](https://github.com/tgsmith61591/skoot) - Pipeline helper functions.  
[categorical-encoding](https://github.com/scikit-learn-contrib/categorical-encoding) - Categorical encoding of variables, [vtreat (R package)](https://cran.r-project.org/web/packages/vtreat/vignettes/vtreat.html).  
[dirty_cat](https://github.com/dirty-cat/dirty_cat) - Encoding dirty categorical variables.  
[patsy](https://github.com/pydata/patsy/) - R-like syntax for statistical models.  
[mlxtend](https://rasbt.github.io/mlxtend/user_guide/feature_extraction/LinearDiscriminantAnalysis/) - LDA.  
[featuretools](https://github.com/Featuretools/featuretools) - Automated feature engineering, [example](https://github.com/WillKoehrsen/automated-feature-engineering/blob/master/walk_through/Automated_Feature_Engineering.ipynb).  
[tsfresh](https://github.com/blue-yonder/tsfresh) - Time series feature engineering.  
[pypeln](https://github.com/cgarciae/pypeln) - Concurrent data pipelines.  
[feature_engine](https://github.com/solegalli/feature_engine) - Encoders, transformers, etc.  
[NVTabular](https://github.com/NVIDIA/NVTabular) - Feature engineering and preprocessing library for tabular data by nvidia.  

#### Image Cleanup
[Fiji](https://fiji.sc/) - General purpose tool. Image viewer and image processing package.  
[napari](https://github.com/napari/napari) - Multi-dimensional image viewer.  
[fiftyone](https://github.com/voxel51/fiftyone) - Viewer and tool for building high-quality datasets and computer vision models.  
[DivNoising](https://github.com/juglab/DivNoising) - Unsupervised denoising method.  
[aydin](https://github.com/royerlab/aydin) - Image denoising.  
[unprocessing](https://github.com/timothybrooks/unprocessing) - Image denoising by reverting the image processing pipeline.  

#### Microscopy / Segmentation
[Awesome Cytodata](https://github.com/cytodata/awesome-cytodata)  
[BD Spectrum Viewer](https://www.bdbiosciences.com/en-us/resources/bd-spectrum-viewer) - Calculate spectral overlap, bleed through for fluorescence microscopy dyes.  
[Tree of Microscopy](https://biomag-lab.github.io/microscopy-tree/) - Review of cell segmentation algorithms, [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0962892421002518).  
[cellpose](https://github.com/mouseland/cellpose) - Cell segmentation. [Paper](https://www.biorxiv.org/content/10.1101/2020.02.02.931238v1), [Dataset](https://www.cellpose.org/dataset).  
[MedMNIST](https://github.com/MedMNIST/MedMNIST) - Datasets for 2D and 3D Biomedical Image Classification.  
[skimage](https://scikit-image.org/docs/dev/api/skimage.exposure.html#skimage.exposure.equalize_adapthist) - Illumination correction (CLAHE).  
[cidre](https://github.com/smithk/cidre) - Illumination correction method for optical microscopy.  
[BaSiC](https://github.com/marrlab/BaSiC) - Background and Shading Correction of Optical Microscopy Images.  
[ashlar](https://github.com/labsyspharm/ashlar) - Whole-slide microscopy image stitching and registration.  
[CSBDeep](https://github.com/CSBDeep/CSBDeep) - Image denoising, restoration and object detection, [Project page](https://csbdeep.bioimagecomputing.com/tools/).  
[mcmicro](https://github.com/labsyspharm/mcmicro) - Multiple-choice microscopy pipeline, [Paper](https://www.nature.com/articles/s41592-021-01308-y).  
[UnMicst](https://github.com/HMS-IDAC/UnMicst) - Identifying Cells and Segmenting Tissue.  
[stardist](https://github.com/stardist/stardist) - Object Detection with Star-convex Shapes.  
[nnUnet](https://github.com/MIC-DKFZ/nnUNet) - 3D biomedical image segmentation.  
[atomai](https://github.com/pycroscopy/atomai) - Deep and Machine Learning for Microscopy.  


#### Feature Engineering Images
[skimage](https://scikit-image.org/docs/dev/api/skimage.measure.html#skimage.measure.regionprops) - Regionprops: area, eccentricity, extent.  
[mahotas](https://github.com/luispedro/mahotas) - Zernike, Haralick, LBP, and TAS features.  
[pyradiomics](https://github.com/AIM-Harvard/pyradiomics) - Radiomics features from medical imaging.  
[pyefd](https://github.com/hbldh/pyefd) - Elliptical feature descriptor, approximating a contour with a Fourier series.  

#### Feature Selection
[Overview Paper](https://www.sciencedirect.com/science/article/pii/S016794731930194X), [Talk](https://www.youtube.com/watch?v=JsArBz46_3s), [Repo](https://github.com/Yimeng-Zhang/feature-engineering-and-feature-selection)    
Blog post series - [1](http://blog.datadive.net/selecting-good-features-part-i-univariate-selection/), [2](http://blog.datadive.net/selecting-good-features-part-ii-linear-models-and-regularization/), [3](http://blog.datadive.net/selecting-good-features-part-iii-random-forests/), [4](http://blog.datadive.net/selecting-good-features-part-iv-stability-selection-rfe-and-everything-side-by-side/)  
Tutorials - [1](https://www.kaggle.com/residentmario/automated-feature-selection-with-sklearn), [2](https://machinelearningmastery.com/feature-selection-machine-learning-python/)  
[sklearn](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.feature_selection) - Feature selection.  
[eli5](https://eli5.readthedocs.io/en/latest/blackbox/permutation_importance.html#feature-selection) - Feature selection using permutation importance.  
[scikit-feature](https://github.com/jundongl/scikit-feature) - Feature selection algorithms.  
[stability-selection](https://github.com/scikit-learn-contrib/stability-selection) - Stability selection.  
[scikit-rebate](https://github.com/EpistasisLab/scikit-rebate) - Relief-based feature selection algorithms.  
[scikit-genetic](https://github.com/manuel-calzolari/sklearn-genetic) - Genetic feature selection.  
[boruta_py](https://github.com/scikit-learn-contrib/boruta_py) - Feature selection, [explaination](https://stats.stackexchange.com/questions/264360/boruta-all-relevant-feature-selection-vs-random-forest-variables-of-importanc/264467), [example](https://www.kaggle.com/tilii7/boruta-feature-elimination).  
[Boruta-Shap](https://github.com/Ekeany/Boruta-Shap) - Boruta feature selection algorithm + shapley values.  
[linselect](https://github.com/efavdb/linselect) - Feature selection package.  
[mlxtend](https://rasbt.github.io/mlxtend/user_guide/feature_selection/ExhaustiveFeatureSelector/) - Exhaustive feature selection.     
[BoostARoota](https://github.com/chasedehan/BoostARoota) - Xgboost feature selection algorithm.  
[INVASE](https://github.com/jsyoon0823/INVASE) - Instance-wise Variable Selection using Neural Networks.  
[SubTab](https://github.com/AstraZeneca/SubTab) - Subsetting Features of Tabular Data for Self-Supervised Representation Learning, AstraZeneca.  
[mrmr](https://github.com/smazzanti/mrmr) - Maximum Relevance and Minimum Redundancy Feature Selection, [Website](http://home.penglab.com/proj/mRMR/).  
[arfs](https://github.com/ThomasBury/arfs) - All Relevant Feature Selection.  
[VSURF](https://github.com/robingenuer/VSURF) - Variable Selection Using Random Forests (R package) [doc](https://www.rdocumentation.org/packages/VSURF/versions/1.1.0/topics/VSURF).  


#### Subset Selection
[apricot](https://github.com/jmschrei/apricot) - Selecting subsets of data sets to train machine learning models quickly.  

#### Dimensionality Reduction / Representation Learning

##### Selection
Check also the Clustering section and self-supervised learning section for ideas!  
[Review](https://members.loria.fr/moberger/Enseignement/AVR/Exposes/TR_Dimensiereductie.pdf)  
  
PCA - [link](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html)    
Autoencoder - [link](https://blog.keras.io/building-autoencoders-in-keras.html)  
Isomaps - [link](https://scikit-learn.org/stable/modules/generated/sklearn.manifold.Isomap.html#sklearn.manifold.Isomap)    
LLE - [link](https://scikit-learn.org/stable/modules/generated/sklearn.manifold.LocallyLinearEmbedding.html)  
Force-directed graph drawing - [link](https://scanpy.readthedocs.io/en/stable/api/scanpy.tl.draw_graph.html#scanpy.tl.draw_graph)    
MDS - [link](https://scikit-learn.org/stable/modules/generated/sklearn.manifold.MDS.html)  
Diffusion Maps - [link](https://scanpy.readthedocs.io/en/stable/api/scanpy.tl.diffmap.html)  
t-SNE - [link](https://scikit-learn.org/stable/modules/generated/sklearn.manifold.TSNE.html#sklearn.manifold.TSNE)    
NeRV - [link](https://github.com/ziyuang/pynerv), [paper](https://www.jmlr.org/papers/volume11/venna10a/venna10a.pdf)  
MDR - [link](https://github.com/EpistasisLab/scikit-mdr)  
UMAP - [link](https://github.com/lmcinnes/umap)  
Random Projection - [link](https://scikit-learn.org/stable/modules/random_projection.html)  
Ivis - [link](https://github.com/beringresearch/ivis)   
SimCLR - [link](https://github.com/lightly-ai/lightly)  

##### Neural-network based
[esvit](https://github.com/microsoft/esvit) - Vision Transformers for Representation Learning (Microsoft).  
[MCML](https://github.com/pachterlab/MCML) - Semi-supervised dimensionality reduction of Multi-Class, Multi-Label data (sequencing data) [paper](https://www.biorxiv.org/content/10.1101/2021.08.25.457696v1).  

##### Packages
[Talk](https://www.youtube.com/watch?v=9iol3Lk6kyU), [tsne intro](https://distill.pub/2016/misread-tsne/). 
[sklearn.manifold](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.manifold) and [sklearn.decomposition](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.decomposition) - PCA, t-SNE, MDS, Isomaps and others.  
[sklearn.random_projection](https://scikit-learn.org/stable/modules/random_projection.html) - Johnson-Lindenstrauss lemma, Gaussian random projection, Sparse random projection.  
[prince](https://github.com/MaxHalford/prince) - Dimensionality reduction, factor analysis (PCA, MCA, CA, FAMD).  
Faster t-SNE implementations: [lvdmaaten](https://lvdmaaten.github.io/tsne/), [MulticoreTSNE](https://github.com/DmitryUlyanov/Multicore-TSNE), [FIt-SNE](https://github.com/KlugerLab/FIt-SNE)
[umap](https://github.com/lmcinnes/umap) - Uniform Manifold Approximation and Projection, [talk](https://www.youtube.com/watch?v=nq6iPZVUxZU), [explorer](https://github.com/GrantCuster/umap-explorer), [explanation](https://pair-code.github.io/understanding-umap/), [parallel version](https://docs.rapids.ai/api/cuml/stable/api.html).  
[sleepwalk](https://github.com/anders-biostat/sleepwalk/) - Explore embeddings, interactive visualization (R package).  
[somoclu](https://github.com/peterwittek/somoclu) - Self-organizing map.  
[scikit-tda](https://github.com/scikit-tda/scikit-tda) - Topological Data Analysis, [paper](https://www.nature.com/articles/srep01236), [talk](https://www.youtube.com/watch?v=F2t_ytTLrQ4), [talk](https://www.youtube.com/watch?v=AWoeBzJd7uQ), [paper](https://www.uncg.edu/mat/faculty/cdsmyth/topological-approaches-skin.pdf).  
[giotto-tda](https://github.com/giotto-ai/giotto-tda) - Topological Data Analysis.  
[ivis](https://github.com/beringresearch/ivis) - Dimensionality reduction using Siamese Networks.  
[trimap](https://github.com/eamid/trimap) - Dimensionality reduction using triplets.  
[scanpy](https://github.com/theislab/scanpy) - [Force-directed graph drawing](https://scanpy.readthedocs.io/en/stable/api/scanpy.tl.draw_graph.html#scanpy.tl.draw_graph), [Diffusion Maps](https://scanpy.readthedocs.io/en/stable/api/scanpy.tl.diffmap.html).  
[direpack](https://github.com/SvenSerneels/direpack) - Projection pursuit, Sufficient dimension reduction, Robust M-estimators.  
[DBS](https://cran.r-project.org/web/packages/DatabionicSwarm/vignettes/DatabionicSwarm.html) - DatabionicSwarm (R package).  
[contrastive](https://github.com/abidlabs/contrastive) - Contrastive PCA.  
[scPCA](https://github.com/PhilBoileau/scPCA) - Sparse contrastive PCA (R package).  
[tmap](https://github.com/reymond-group/tmap) - Visualization library for large, high-dimensional data sets.  

#### Training-related
[iterative-stratification](https://github.com/trent-b/iterative-stratification) - Cross validators with stratification for multilabel data.   
[livelossplot](https://github.com/stared/livelossplot) - Live training loss plot in Jupyter Notebook.   

#### Visualization
[All charts](https://datavizproject.com/), [Austrian monuments](https://github.com/njanakiev/austrian-monuments-visualization).  
[Better heatmaps and correlation plots](https://towardsdatascience.com/better-heatmaps-and-correlation-matrix-plots-in-python-41445d0f2bec).  
[Example notebooks for interactive visualizations](https://github.com/nicolaskruchten/pydata_global_2021/tree/main)(Plotly,Seaborn, Holoviz, Altair)  
[cufflinks](https://github.com/santosjorge/cufflinks) - Dynamic visualization library, wrapper for [plotly](https://plot.ly/), [medium](https://towardsdatascience.com/the-next-level-of-data-visualization-in-python-dd6e99039d5e), [example](https://github.com/WillKoehrsen/Data-Analysis/blob/master/plotly/Plotly%20Whirlwind%20Introduction.ipynb).  
[physt](https://github.com/janpipek/physt) - Better histograms, [talk](https://www.youtube.com/watch?v=ZG-wH3-Up9Y), [notebook](https://nbviewer.jupyter.org/github/janpipek/pydata2018-berlin/blob/master/notebooks/talk.ipynb).  
[fast-histogram](https://github.com/astrofrog/fast-histogram) - Fast histograms.  
[matplotlib_venn](https://github.com/konstantint/matplotlib-venn) - Venn diagrams, [alternative](https://github.com/penrose/penrose).  
[joypy](https://github.com/sbebo/joypy) - Draw stacked density plots (=ridge plots), [Ridge plots in seaborn](https://seaborn.pydata.org/examples/kde_ridgeplot.html).  
[mosaic plots](https://www.statsmodels.org/dev/generated/statsmodels.graphics.mosaicplot.mosaic.html) - Categorical variable visualization, [example](https://sukhbinder.wordpress.com/2018/09/18/mosaic-plot-in-python/).  
[scikit-plot](https://github.com/reiinakano/scikit-plot) - ROC curves and other visualizations for ML models.  
[yellowbrick](https://github.com/DistrictDataLabs/yellowbrick) - Visualizations for ML models (similar to scikit-plot).  
[bokeh](https://bokeh.pydata.org/en/latest/) - Interactive visualization library, [Examples](https://bokeh.pydata.org/en/latest/docs/user_guide/server.html), [Examples](https://github.com/WillKoehrsen/Bokeh-Python-Visualization).  
[lets-plot](https://github.com/JetBrains/lets-plot/blob/master/README_PYTHON.md) - Plotting library.  
[animatplot](https://github.com/t-makaro/animatplot) - Animate plots build on matplotlib.  
[plotnine](https://github.com/has2k1/plotnine) - ggplot for Python.  
[altair](https://altair-viz.github.io/) - Declarative statistical visualization library.  
[bqplot](https://github.com/bloomberg/bqplot) - Plotting library for IPython/Jupyter Notebooks.  
[hvplot](https://github.com/pyviz/hvplot) - High-level plotting library built on top of [holoviews](http://holoviews.org/).  
[dtreeviz](https://github.com/parrt/dtreeviz) - Decision tree visualization and model interpretation.  
[chartify](https://github.com/spotify/chartify/) - Generate charts.  
[VivaGraphJS](https://github.com/anvaka/VivaGraphJS) - Graph visualization (JS package).  
[pm](https://github.com/anvaka/pm) - Navigatable 3D graph visualization (JS package), [example](https://w2v-vis-dot-hcg-team-di.appspot.com/#/galaxy/word2vec?cx=5698&cy=-5135&cz=5923&lx=0.1127&ly=0.3238&lz=-0.1680&lw=0.9242&ml=150&s=1.75&l=1&v=hc).  
[python-ternary](https://github.com/marcharper/python-ternary) - Triangle plots.  
[falcon](https://github.com/uwdata/falcon) - Interactive visualizations for big data.  
[hiplot](https://github.com/facebookresearch/hiplot) - High dimensional Interactive Plotting.  
[visdom](https://github.com/fossasia/visdom) - Live Visualizations.  
[mpl-scatter-density](https://github.com/astrofrog/mpl-scatter-density) - Scatter density plots. Alternative to 2d-histograms.   
[ComplexHeatmap](https://github.com/jokergoo/ComplexHeatmap) - Complex heatmaps for multidimensional genomic data (R package).  
[largeVis](https://github.com/elbamos/largeVis) - Visualize embeddings (t-SNE etc.) (R package).  

#### Colors
[palettable](https://github.com/jiffyclub/palettable) - Color palettes from [colorbrewer2](https://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3).  
[colorcet](https://github.com/holoviz/colorcet) - Collection of perceptually uniform colormaps.  

#### Dashboards
[superset](https://github.com/apache/superset) - Dashboarding solution by Apache.  
[streamlit](https://github.com/streamlit/streamlit) - Dashboarding solution. [Resources](https://github.com/marcskovmadsen/awesome-streamlit), [Gallery](https://awesome-streamlit.org/) [Components](https://www.streamlit.io/components), [bokeh-events](https://github.com/ash2shukla/streamlit-bokeh-events).  
[dash](https://dash.plot.ly/gallery) - Dashboarding solution by plot.ly. [Resources](https://github.com/ucg8j/awesome-dash).  
[visdom](https://github.com/facebookresearch/visdom) - Dashboarding library by facebook.  
[panel](https://panel.pyviz.org/index.html) - Dashboarding solution.  
[altair example](https://github.com/xhochy/altair-vue-vega-example) - [Video](https://www.youtube.com/watch?v=4L568emKOvs).  
[voila](https://github.com/QuantStack/voila) - Turn Jupyter notebooks into standalone web applications.  
[voila-gridstack](https://github.com/voila-dashboards/voila-gridstack) - Voila grid layout.  

#### UI
[gradio](https://github.com/gradio-app/gradio) - Create UIs for your machine learning model.  

#### Survey Tools
[samplics](https://github.com/samplics-org/samplics) - Sampling techniques for complex survey designs.  

#### Geographical Tools
[folium](https://github.com/python-visualization/folium) - Plot geographical maps using the Leaflet.js library, [jupyter plugin](https://github.com/jupyter-widgets/ipyleaflet).  
[gmaps](https://github.com/pbugnion/gmaps) - Google Maps for Jupyter notebooks.  
[stadiamaps](https://stadiamaps.com/) - Plot geographical maps.  
[datashader](https://github.com/bokeh/datashader) - Draw millions of points on a map.  
[sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.BallTree.html) - BallTree, [Example](https://tech.minodes.com/experiments-with-in-memory-spatial-radius-queries-in-python-e40c9e66cf63).  
[pynndescent](https://github.com/lmcinnes/pynndescent) - Nearest neighbor descent for approximate nearest neighbors.  
[geocoder](https://github.com/DenisCarriere/geocoder) - Geocoding of addresses, IP addresses.  
Conversion of different geo formats: [talk](https://www.youtube.com/watch?v=eHRggqAvczE), [repo](https://github.com/dillongardner/PyDataSpatialAnalysis)  
[geopandas](https://github.com/geopandas/geopandas) - Tools for geographic data  
Low Level Geospatial Tools (GEOS, GDAL/OGR, PROJ.4)  
Vector Data (Shapely, Fiona, Pyproj)  
Raster Data (Rasterio)  
Plotting (Descartes, Catropy)  
Predict economic indicators from Open Street Map [ipynb](https://github.com/njanakiev/osm-predict-economic-measurements/blob/master/osm-predict-economic-indicators.ipynb).  
[PySal](https://github.com/pysal/pysal) - Python Spatial Analysis Library.  
[geography](https://github.com/ushahidi/geograpy) - Extract countries, regions and cities from a URL or text.  
[cartogram](https://go-cart.io/cartogram) - Distorted maps based on population.  

#### Recommender Systems
Examples: [1](https://lazyprogrammer.me/tutorial-on-collaborative-filtering-and-matrix-factorization-in-python/), [2](https://medium.com/@james_aka_yale/the-4-recommendation-engines-that-can-predict-your-movie-tastes-bbec857b8223), [2-ipynb](https://github.com/khanhnamle1994/movielens/blob/master/Content_Based_and_Collaborative_Filtering_Models.ipynb), [3](https://www.kaggle.com/morrisb/how-to-recommend-anything-deep-recommender).  
[surprise](https://github.com/NicolasHug/Surprise) - Recommender, [talk](https://www.youtube.com/watch?v=d7iIb_XVkZs).  
[turicreate](https://github.com/apple/turicreate) - Recommender.  
[implicit](https://github.com/benfred/implicit) - Fast Collaborative Filtering for Implicit Feedback Datasets.  
[spotlight](https://github.com/maciejkula/spotlight) - Deep recommender models using PyTorch.  
[lightfm](https://github.com/lyst/lightfm) - Recommendation algorithms for both implicit and explicit feedback.  
[funk-svd](https://github.com/gbolmier/funk-svd) - Fast SVD.  
[pywFM](https://github.com/jfloff/pywFM) - Factorization.  

#### Decision Tree Models
[Intro to Decision Trees and Random Forests](https://victorzhou.com/blog/intro-to-random-forests/), Intro to Gradient Boosting [1](https://explained.ai/gradient-boosting/), [2](https://www.gormanalysis.com/blog/gradient-boosting-explained/), [Decision Tree Visualization](https://explained.ai/decision-tree-viz/index.html)    
[lightgbm](https://github.com/Microsoft/LightGBM) - Gradient boosting (GBDT, GBRT, GBM or MART) framework based on decision tree algorithms, [doc](https://sites.google.com/view/lauraepp/parameters).  
[xgboost](https://github.com/dmlc/xgboost) - Gradient boosting (GBDT, GBRT or GBM) library, [doc](https://sites.google.com/view/lauraepp/parameters), Methods for CIs: [link1](https://stats.stackexchange.com/questions/255783/confidence-interval-for-xgb-forecast), [link2](https://towardsdatascience.com/regression-prediction-intervals-with-xgboost-428e0a018b), [Frank Kane's short but good intro](https://www.youtube.com/watch?v=OQKQHNCVf5k).  
[catboost](https://github.com/catboost/catboost) - Gradient boosting.  
[h2o](https://github.com/h2oai/h2o-3) -  Gradient boosting and general machine learning framework.  
[snapml](https://www.zurich.ibm.com/snapml/) - Gradient boosting and general machine learning framework by IBM, for CPU and GPU. [PyPI](https://pypi.org/project/snapml/)    
[pycaret](https://github.com/pycaret/pycaret) - Wrapper for xgboost, lightgbm, catboost etc.  
[thundergbm](https://github.com/Xtra-Computing/thundergbm) - GBDTs and Random Forest.  
[h2o](https://github.com/h2oai/h2o-3) - Gradient boosting.  
[forestci](https://github.com/scikit-learn-contrib/forest-confidence-interval) - Confidence intervals for random forests.  
[scikit-garden](https://github.com/scikit-garden/scikit-garden) - Quantile Regression.  
[grf](https://github.com/grf-labs/grf) - Generalized random forest.  
[dtreeviz](https://github.com/parrt/dtreeviz) - Decision tree visualization and model interpretation.  
[Nuance](https://github.com/SauceCat/Nuance) - Decision tree visualization.  
[rfpimp](https://github.com/parrt/random-forest-importances) - Feature Importance for RandomForests using Permuation Importance.  
Why the default feature importance for random forests is wrong: [link](http://explained.ai/rf-importance/index.html)  
[treeinterpreter](https://github.com/andosa/treeinterpreter) - Interpreting scikit-learn's decision tree and random forest predictions.  
[bartpy](https://github.com/JakeColtman/bartpy) - Bayesian Additive Regression Trees.  
[infiniteboost](https://github.com/arogozhnikov/infiniteboost) - Combination of RFs and GBDTs.  
[merf](https://github.com/manifoldai/merf) - Mixed Effects Random Forest for Clustering, [video](https://www.youtube.com/watch?v=gWj4ZwB7f3o)  
[rrcf](https://github.com/kLabUM/rrcf) - Robust Random Cut Forest algorithm for anomaly detection on streams.  
[groot](https://github.com/tudelft-cda-lab/GROOT) - Robust decision trees.  
[linear-tree](https://github.com/cerlymarco/linear-tree) - Trees with linear models at the leaves.  

#### Natural Language Processing (NLP) / Text Processing
[talk](https://www.youtube.com/watch?v=6zm9NC9uRkk)-[nb](https://nbviewer.jupyter.org/github/skipgram/modern-nlp-in-python/blob/master/executable/Modern_NLP_in_Python.ipynb), [nb2](https://ahmedbesbes.com/how-to-mine-newsfeed-data-and-extract-interactive-insights-in-python.html), [talk](https://www.youtube.com/watch?time_continue=2&v=sI7VpFNiy_I).  
[Text classification Intro](https://mlwhiz.com/blog/2018/12/17/text_classification/), [Preprocessing blog post](https://mlwhiz.com/blog/2019/01/17/deeplearning_nlp_preprocess/).  
[gensim](https://radimrehurek.com/gensim/) - NLP, doc2vec, word2vec, text processing, topic modelling (LSA, LDA), [Example](https://markroxor.github.io/gensim/static/notebooks/gensim_news_classification.html), [Coherence Model](https://radimrehurek.com/gensim/models/coherencemodel.html) for evaluation.  
Embeddings - [GloVe](https://nlp.stanford.edu/projects/glove/) ([[1](https://www.kaggle.com/jhoward/improved-lstm-baseline-glove-dropout)], [[2](https://www.kaggle.com/sbongo/do-pretrained-embeddings-give-you-the-extra-edge)]), [StarSpace](https://github.com/facebookresearch/StarSpace), [wikipedia2vec](https://wikipedia2vec.github.io/wikipedia2vec/pretrained/), [visualization](https://projector.tensorflow.org/).  
[magnitude](https://github.com/plasticityai/magnitude) - Vector embedding utility package.  
[pyldavis](https://github.com/bmabey/pyLDAvis) - Visualization for topic modelling.  
[spaCy](https://spacy.io/) - NLP.  
[NTLK](https://www.nltk.org/) - NLP, helpful `KMeansClusterer` with `cosine_distance`.  
[pytext](https://github.com/facebookresearch/PyText) - NLP from Facebook.  
[fastText](https://github.com/facebookresearch/fastText) - Efficient text classification and representation learning.  
[annoy](https://github.com/spotify/annoy) - Approximate nearest neighbor search.  
[faiss](https://github.com/facebookresearch/faiss) - Approximate nearest neighbor search.  
[pysparnn](https://github.com/facebookresearch/pysparnn) - Approximate nearest neighbor search.  
[infomap](https://github.com/mapequation/infomap) - Cluster (word-)vectors to find topics, [example](https://github.com/mapequation/infomap/blob/master/examples/python/infomap-examples.ipynb).  
[datasketch](https://github.com/ekzhu/datasketch) - Probabilistic data structures for large data (MinHash, HyperLogLog).  
[flair](https://github.com/zalandoresearch/flair) - NLP Framework by Zalando.  
[stanfordnlp](https://github.com/stanfordnlp/stanfordnlp) - NLP Library.  
[Chatistics](https://github.com/MasterScrat/Chatistics) - Turn Messenger, Hangouts, WhatsApp and Telegram chat logs into DataFrames.  
[textvec](https://github.com/textvec/textvec) - Supervised text vectorization tool.  
[textdistance](https://github.com/life4/textdistance) - Collection for comparing distances between two or more sequences.  

##### Papers
[Search Engine Correlation](https://arxiv.org/pdf/1107.2691.pdf)  

#### Biology / Bioinformatics

##### Sequencing
[cellxgene](https://github.com/chanzuckerberg/cellxgene) - Interactive explorer for single-cell transcriptomics data.  
[scanpy](https://github.com/theislab/scanpy) - Analyze single-cell gene expression data, [tutorial](https://github.com/theislab/single-cell-tutorial).  
[janggu](https://github.com/BIMSBbioinfo/janggu) - Deep Learning for Genomics.  
[gdsctools](https://github.com/CancerRxGene/gdsctools) - Drug responses in the context of the Genomics of Drug Sensitivity in Cancer project, ANOVA, IC50, MoBEM, [doc](https://gdsctools.readthedocs.io/en/master/).  

##### Image-related
See also Microscopy Section above.  
[Overview over cell segmentation algorithms](https://biomag-lab.github.io/microscopy-tree/)  
[python_for_microscopists](https://github.com/bnsreenu/python_for_microscopists) - Notebooks and associated [youtube channel](https://www.youtube.com/channel/UC34rW-HtPJulxr5wp2Xa04w/videos) for a variety of image processing tasks.  
[mahotas](http://luispedro.org/software/mahotas/) - Image processing (Bioinformatics), [example](https://github.com/luispedro/python-image-tutorial/blob/master/Segmenting%20cell%20images%20(fluorescent%20microscopy).ipynb).   
[imagepy](https://github.com/Image-Py/imagepy) - Software package for bioimage analysis.  
[scimap](https://github.com/labsyspharm/scimap) - Spatial Single-Cell Analysis Toolkit.  
[CellProfiler](https://github.com/CellProfiler/CellProfiler) - Biological image analysis.   
[imglyb](https://github.com/imglib/imglyb) - Viewer for large images, [talk](https://www.youtube.com/watch?v=Ddo5z5qGMb8), [slides](https://github.com/hanslovsky/scipy-2019/blob/master/scipy-2019-imglyb.pdf).  
[microscopium](https://github.com/microscopium/microscopium) - Unsupervised clustering of images + viewer, [talk](https://www.youtube.com/watch?v=ytEQl9xs8FQ).  
[cytokit](https://github.com/hammerlab/cytokit) - Analyzing properties of cells in fluorescent microscopy datasets.  
[ZeroCostDL4Mic](https://github.com/HenriquesLab/ZeroCostDL4Mic/wiki) - Deep-Learning in Microscopy.  

##### Drug discovery
[TDC](https://github.com/mims-harvard/TDC/tree/main) - Drug Discovery and Development.  
[DeepPurpose](https://github.com/kexinhuang12345/DeepPurpose) - Deep Learning Based Molecular Modeling and Prediction Toolkit.  

##### Courses
[mit6874](https://mit6874.github.io/) - Computational Systems Biology: Deep Learning in the Life Sciences.  

#### Image Processing
[Talk](https://www.youtube.com/watch?v=Y5GJmnIhvFk)  
[cv2](https://github.com/skvark/opencv-python) - OpenCV, classical algorithms: [Gaussian Filter](https://docs.opencv.org/3.1.0/d4/d13/tutorial_py_filtering.html), [Morphological Transformations](https://docs.opencv.org/3.0-beta/doc/py_tutorials/py_imgproc/py_morphological_ops/py_morphological_ops.html).  
[scikit-image](https://github.com/scikit-image/scikit-image) - Image processing.  
[CORAL](https://github.com/VisionLearningGroup/CORAL) - Correlation Alignment for Domain Adaptation.  

#### Neural Networks
[Convolutional Neural Networks for Visual Recognition](https://cs231n.github.io/) - Stanford CS class.  
[ConvNet Shape Calculator](https://madebyollin.github.io/convnet-calculator/) - Calculate output dimensions of Conv2D layer.  
[Great Gradient Descent Article](https://towardsdatascience.com/10-gradient-descent-optimisation-algorithms-86989510b5e9)  
[Intro to semi-supervised learning](https://lilianweng.github.io/lil-log/2021/12/05/semi-supervised-learning.html)  

##### Tutorials & Viewer
fast.ai course - [Lessons 1-7](https://course.fast.ai/videos/?lesson=1), [Lessons 8-14](http://course18.fast.ai/lessons/lessons2.html)  
[Tensorflow without a PhD](https://github.com/GoogleCloudPlatform/tensorflow-without-a-phd) - Neural Network course by Google.  
Feature Visualization: [Blog](https://distill.pub/2017/feature-visualization/), [PPT](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture12.pdf)  
[Tensorflow Playground](https://playground.tensorflow.org/)  
[Visualization of optimization algorithms](https://vis.ensmallen.org/), [Another visualization](https://github.com/jettify/pytorch-optimizer)    
[cutouts-explorer](https://github.com/mgckind/cutouts-explorer) - Image Viewer.  

##### Image Related
[imgaug](https://github.com/aleju/imgaug) - More sophisticated image preprocessing.  
[Augmentor](https://github.com/mdbloice/Augmentor) - Image augmentation library.  
[keras preprocessing](https://keras.io/preprocessing/image/) - Preprocess images.  
[albumentations](https://github.com/albu/albumentations) - Wrapper around imgaug and other libraries.  
[augmix](https://github.com/google-research/augmix) - Image augmentation from Google.  
[kornia](https://github.com/kornia/kornia) - Image augmentation, feature extraction and loss functions.  
[augly](https://github.com/facebookresearch/AugLy) - Image, audio, text, video augmentation from Facebook.  

##### Lossfunction Related
[SegLoss](https://github.com/JunMa11/SegLoss) - List of loss functions for medical image segmentation.  

##### Activation Functions
[rational_activations](https://github.com/ml-research/rational_activations) - Rational activation functions.  

##### Text Related
[ktext](https://github.com/hamelsmu/ktext) - Utilities for pre-processing text for deep learning in Keras.   
[textgenrnn](https://github.com/minimaxir/textgenrnn) - Ready-to-use LSTM for text generation.  
[ctrl](https://github.com/salesforce/ctrl) - Text generation.  

##### Libs General
[keras](https://keras.io/) - Neural Networks on top of [tensorflow](https://www.tensorflow.org/), [examples](https://gist.github.com/candlewill/552fa102352ccce42fd829ae26277d24).  
[keras-contrib](https://github.com/keras-team/keras-contrib) - Keras community contributions.  
[keras-tuner](https://github.com/keras-team/keras-tuner) - Hyperparameter tuning for Keras.  
[hyperas](https://github.com/maxpumperla/hyperas) - Keras + Hyperopt: Convenient hyperparameter optimization wrapper.  
[elephas](https://github.com/maxpumperla/elephas) - Distributed Deep learning with Keras & Spark.  
[tflearn](https://github.com/tflearn/tflearn) - Neural Networks on top of tensorflow.  
[tensorlayer](https://github.com/tensorlayer/tensorlayer) - Neural Networks on top of tensorflow, [tricks](https://github.com/wagamamaz/tensorlayer-tricks).  
[tensorforce](https://github.com/reinforceio/tensorforce) - Tensorflow for applied reinforcement learning.  
[autokeras](https://github.com/jhfjhfj1/autokeras) - AutoML for deep learning.  
[PlotNeuralNet](https://github.com/HarisIqbal88/PlotNeuralNet) - Plot neural networks.  
[lucid](https://github.com/tensorflow/lucid) - Neural network interpretability, [Activation Maps](https://openai.com/blog/introducing-activation-atlases/).  
[tcav](https://github.com/tensorflow/tcav) - Interpretability method.  
[AdaBound](https://github.com/Luolc/AdaBound) - Optimizer that trains as fast as Adam and as good as SGD, [alt](https://github.com/titu1994/keras-adabound).  
[foolbox](https://github.com/bethgelab/foolbox) - Adversarial examples that fool neural networks.  
[hiddenlayer](https://github.com/waleedka/hiddenlayer) - Training metrics.  
[imgclsmob](https://github.com/osmr/imgclsmob) - Pretrained models.  
[netron](https://github.com/lutzroeder/netron) - Visualizer for deep learning and machine learning models.  
[ffcv](https://github.com/libffcv/ffcv) - Fast dataloder.  

##### Libs Pytorch
[Good Pytorch Introduction](https://cs230.stanford.edu/blog/pytorch/)  
  
[skorch](https://github.com/dnouri/skorch) - Scikit-learn compatible neural network library that wraps pytorch, [talk](https://www.youtube.com/watch?v=0J7FaLk0bmQ), [slides](https://github.com/thomasjpfan/skorch_talk).  
[fastai](https://github.com/fastai/fastai) - Neural Networks in pytorch.  
[timm](https://github.com/rwightman/pytorch-image-models) - Pytorch image models.  
[ignite](https://github.com/pytorch/ignite) - Highlevel library for pytorch.  
[torchcv](https://github.com/donnyyou/torchcv) - Deep Learning in Computer Vision.  
[pytorch-optimizer](https://github.com/jettify/pytorch-optimizer) - Collection of optimizers for pytorch.  
[pytorch-lightning](https://github.com/PyTorchLightning/PyTorch-lightning) - Wrapper around PyTorch.  
[lightly](https://github.com/lightly-ai/lightly) - MoCo, SimCLR, SimSiam, Barlow Twins, BYOL, NNCLR.  
[MONAI](https://github.com/project-monai/monai) - Deep learning in healthcare imaging.  
[kornia](https://github.com/kornia/kornia) - Image transformations, epipolar geometry, depth estimation.  

##### Distributed Libs
[flexflow](https://github.com/flexflow/FlexFlow) - Distributed TensorFlow Keras and PyTorch.  

##### Architecture Visualization
[Awesome List](https://github.com/ashishpatel26/Tools-to-Design-or-Visualize-Architecture-of-Neural-Network)  
[netron](https://github.com/lutzroeder/netron) - Viewer for neural networks.  

##### Object detection / Instance Segmentation
[Good Yolo Explanation](https://jonathan-hui.medium.com/real-time-object-detection-with-yolo-yolov2-28b1b93e2088)  
[segmentation_models](https://github.com/qubvel/segmentation_models) - Segmentation models with pretrained backbones: Unet, FPN, Linknet, PSPNet.  
[yolact](https://github.com/dbolya/yolact) - Fully convolutional model for real-time instance segmentation.  
[EfficientDet Pytorch](https://github.com/toandaominh1997/EfficientDet.Pytorch), [EfficientDet Keras](https://github.com/xuannianz/EfficientDet) - Scalable and Efficient Object Detection.  
[detectron2](https://github.com/facebookresearch/detectron2) - Object Detection (Mask R-CNN) by Facebook.  
[simpledet](https://github.com/TuSimple/simpledet) - Object Detection and Instance Recognition.  
[CenterNet](https://github.com/xingyizhou/CenterNet) - Object detection.  
[FCOS](https://github.com/tianzhi0549/FCOS) - Fully Convolutional One-Stage Object Detection.  
[norfair](https://github.com/tryolabs/norfair) - Real-time 2D object tracking.  
[Detic](https://github.com/facebookresearch/Detic) -  Detector with image classes that can use image-level labels (facebookresearch).  

##### Image Annotation
[cvat](https://github.com/openvinotoolkit/cvat) - Image annotation tool.  
[pigeon](https://github.com/agermanidis/pigeon) - Create annotations from within a Jupyter notebook.  

##### Image Classification
[nfnets](https://github.com/ypeleg/nfnets-keras) - Neural network.   
[efficientnet](https://github.com/lukemelas/EfficientNet-PyTorch) - Neural network.   
[pycls](https://github.com/facebookresearch/pycls) - Pytorch image classification networks: ResNet, ResNeXt, EfficientNet, and RegNet (by Facebook).  

##### Applications and Snippets
[SPADE](https://github.com/nvlabs/spade) - Semantic Image Synthesis.  
[Entity Embeddings of Categorical Variables](https://arxiv.org/abs/1604.06737), [code](https://github.com/entron/entity-embedding-rossmann), [kaggle](https://www.kaggle.com/aquatic/entity-embedding-neural-net/code)  
[Image Super-Resolution](https://github.com/idealo/image-super-resolution) - Super-scaling using a Residual Dense Network.  
Cell Segmentation - [Talk](https://www.youtube.com/watch?v=dVFZpodqJiI), Blog Posts: [1](https://www.thomasjpfan.com/2018/07/nuclei-image-segmentation-tutorial/), [2](https://www.thomasjpfan.com/2017/08/hassle-free-unets/)  
[deeplearning-models](https://github.com/rasbt/deeplearning-models) - Deep learning models.  

##### Variational Autoencoders (VAEs)
[Variational Autoencoder Explanation Video](https://www.youtube.com/watch?v=9zKuYvjFFS8)  
[disentanglement_lib](https://github.com/google-research/disentanglement_lib) - BetaVAE, FactorVAE, BetaTCVAE, DIP-VAE.  
[ladder-vae-pytorch](https://github.com/addtt/ladder-vae-pytorch) - Ladder Variational Autoencoders (LVAE).  

##### Generative Adversarial Networks (GANs)
[Awesome GAN Applications](https://github.com/nashory/gans-awesome-applications)  
[The GAN Zoo](https://github.com/hindupuravinash/the-gan-zoo) - List of Generative Adversarial Networks.  
[CycleGAN and Pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix) - Various image-to-image tasks.  
[Tensorflow GAN implementations](https://github.com/hwalsuklee/tensorflow-generative-model-collections)  
[Pytorch GAN implementations](https://github.com/znxlwm/pytorch-generative-model-collections)  
[Pytorch GAN implementations](https://github.com/eriklindernoren/PyTorch-GAN#adversarial-autoencoder)  
[StudioGAN](https://github.com/POSTECH-CVLab/PyTorch-StudioGAN) - Pytorch GAN implementations.  

##### Transformers
[SegFormer](https://github.com/NVlabs/SegFormer) - Simple and Efficient Design for Semantic Segmentation with Transformers.  
[esvit](https://github.com/microsoft/esvit) - Efficient self-supervised Vision Transformers.  
[Meta's Xformers](https://github.com/facebookresearch/xformers) - by [abstracting GPU kernels](https://devblog.pytorchlightning.ai/part-i-simplifying-transformer-research-with-xformers-lightning-a715737b8ad4), [read Google's paper](https://arxiv.org/pdf/2009.06732.pdf), [ this intro](https://medium.com/inside-machine-learning/what-is-a-transformer-d07dd1fbec04) and [HarvardNLP's model arch](http://nlp.seas.harvard.edu/2018/04/03/attention.html).  

##### Graph-Based Neural Networks
[How to do Deep Learning on Graphs with Graph Convolutional Networks](https://towardsdatascience.com/how-to-do-deep-learning-on-graphs-with-graph-convolutional-networks-7d2250723780)  
[Introduction To Graph Convolutional Networks](http://tkipf.github.io/graph-convolutional-networks/)  
[An attempt at demystifying graph deep learning](https://ericmjl.github.io/essays-on-data-science/machine-learning/graph-nets/)  
[ogb](https://ogb.stanford.edu/) - Open Graph Benchmark, Benchmark datasets.  
[networkx](https://github.com/networkx/networkx) - Graph library.  
[cugraph](https://github.com/rapidsai/cugraph) - RAPIDS, Graph library on the GPU.  
[pytorch-geometric](https://github.com/rusty1s/pytorch_geometric) - Various methods for deep learning on graphs.  
[dgl](https://github.com/dmlc/dgl) - Deep Graph Library.  
[graph_nets](https://github.com/deepmind/graph_nets) - Build graph networks in Tensorflow, by deepmind.  

##### Other neural network and deep learning frameworks
[caffe](https://github.com/BVLC/caffe) - Deep learning framework, [pretrained models](https://github.com/BVLC/caffe/wiki/Model-Zoo).  
[mxnet](https://github.com/apache/incubator-mxnet) - Deep learning framework, [book](https://d2l.ai/index.html).  

#### Model conversion
[hummingbird](https://github.com/microsoft/hummingbird) - Compile trained ML models into tensor computations (by Microsoft).  

#### GPU
[cuML](https://github.com/rapidsai/cuml) - RAPIDS, Run traditional tabular ML tasks on GPUs, [Intro](https://www.youtube.com/watch?v=6XzS5XcpicM&t=2m50s).  
[thundergbm](https://github.com/Xtra-Computing/thundergbm) - GBDTs and Random Forest.  
[thundersvm](https://github.com/Xtra-Computing/thundersvm) - Support Vector Machines.  
Legate Numpy - Distributed Numpy array multiple using GPUs by Nvidia (not released yet) [video](https://www.youtube.com/watch?v=Jxxs_moibog).  

#### Regression
Understanding SVM Regression: [slides](https://cs.adelaide.edu.au/~chhshen/teaching/ML_SVR.pdf), [forum](https://www.quora.com/How-does-support-vector-regression-work), [paper](http://alex.smola.org/papers/2003/SmoSch03b.pdf)  

[pyearth](https://github.com/scikit-learn-contrib/py-earth) - Multivariate Adaptive Regression Splines (MARS), [tutorial](https://uc-r.github.io/mars).  
[pygam](https://github.com/dswah/pyGAM) - Generalized Additive Models (GAMs), [Explanation](https://multithreaded.stitchfix.com/blog/2015/07/30/gam/).  
[GLRM](https://github.com/madeleineudell/LowRankModels.jl) - Generalized Low Rank Models.  
[tweedie](https://xgboost.readthedocs.io/en/latest/parameter.html#parameters-for-tweedie-regression-objective-reg-tweedie) - Specialized distribution for zero inflated targets, [Talk](https://www.youtube.com/watch?v=-o0lpHBq85I).  
[MAPIE](https://github.com/scikit-learn-contrib/MAPIE) - Estimating prediction intervals.  

#### Polynomials
[orthopy](https://github.com/nschloe/orthopy) - Orthogonal polynomials in all shapes and sizes.  

#### Classification
[Talk](https://www.youtube.com/watch?v=DkLPYccEJ8Y), [Notebook](https://github.com/ianozsvald/data_science_delivered/blob/master/ml_creating_correct_capable_classifiers.ipynb)  
[Blog post: Probability Scoring](https://machinelearningmastery.com/how-to-score-probability-predictions-in-python/)  
[All classification metrics](http://rali.iro.umontreal.ca/rali/sites/default/files/publis/SokolovaLapalme-JIPM09.pdf)  
[DESlib](https://github.com/scikit-learn-contrib/DESlib) - Dynamic classifier and ensemble selection.  
[human-learn](https://github.com/koaning/human-learn) - Create and tune classifier based on your rule set.  

#### Metric Learning
[Contrastive Representation Learning](https://lilianweng.github.io/lil-log/2021/05/31/contrastive-representation-learning.html)  
  
[metric-learn](https://github.com/scikit-learn-contrib/metric-learn) - Supervised and weakly-supervised metric learning algorithms.  
[pytorch-metric-learning](https://github.com/KevinMusgrave/pytorch-metric-learning) - Pytorch metric learning.  
[deep_metric_learning](https://github.com/ronekko/deep_metric_learning) - Methods for deep metric learning.  
[ivis](https://bering-ivis.readthedocs.io/en/latest/supervised.html) - Metric learning using siamese neural networks.  
[tensorflow similarity](https://github.com/tensorflow/similarity) - Metric learning.  

#### Distance Functions
[scipy.spatial](https://docs.scipy.org/doc/scipy/reference/spatial.distance.html) - All kinds of distance metrics.  
[pyemd](https://github.com/wmayner/pyemd) - Earth Mover's Distance / Wasserstein distance, similarity between histograms. [OpenCV implementation](https://docs.opencv.org/3.4/d6/dc7/group__imgproc__hist.html), [POT implementation](https://pythonot.github.io/auto_examples/plot_OT_2D_samples.html)   
[dcor](https://github.com/vnmabus/dcor)  - Distance correlation and related Energy statistics.  
[GeomLoss](https://www.kernel-operations.io/geomloss/) - Kernel norms, Hausdorff divergences, Debiased Sinkhorn divergences (=approximation of Wasserstein distance).  

#### Self-supervised Learning
[lightly](https://github.com/lightly-ai/lightly) - MoCo, SimCLR, SimSiam, Barlow Twins, BYOL, NNCLR.  
[vissl](https://github.com/facebookresearch/vissl) - Self-Supervised Learning with PyTorch: RotNet, Jigsaw, NPID, ClusterFit, PIRL, SimCLR, MoCo, DeepCluster, SwAV.  

#### Clustering
[Overview of clustering algorithms applied image data (= Deep Clustering)](https://deepnotes.io/deep-clustering).  
[Clustering with Deep Learning: Taxonomy and New Methods](https://arxiv.org/pdf/1801.07648.pdf).  
[Hierarchical Cluster Analysis (R Tutorial)](https://uc-r.github.io/hc_clustering) - Dendrogram, Tanglegram  
[hdbscan](https://github.com/scikit-learn-contrib/hdbscan) - Clustering algorithm, [talk](https://www.youtube.com/watch?v=dGsxd67IFiU), [blog](https://towardsdatascience.com/understanding-hdbscan-and-density-based-clustering-121dbee1320e).  
[pyclustering](https://github.com/annoviko/pyclustering) - All sorts of clustering algorithms.  
[FCPS](https://github.com/Mthrun/FCPS) -  Fundamental Clustering Problems Suite (R package).  
[GaussianMixture](https://scikit-learn.org/stable/modules/generated/sklearn.mixture.GaussianMixture.html) - Generalized k-means clustering using a mixture of Gaussian distributions, [video](https://www.youtube.com/watch?v=aICqoAG5BXQ).  
[nmslib](https://github.com/nmslib/nmslib) - Similarity search library and toolkit for evaluation of k-NN methods.  
[buckshotpp](https://github.com/zjohn77/buckshotpp) - Outlier-resistant and scalable clustering algorithm.  
[merf](https://github.com/manifoldai/merf) - Mixed Effects Random Forest for Clustering, [video](https://www.youtube.com/watch?v=gWj4ZwB7f3o)  
[tree-SNE](https://github.com/isaacrob/treesne) - Hierarchical clustering algorithm based on t-SNE.  
[MiniSom](https://github.com/JustGlowing/minisom) - Pure Python implementation of the Self Organizing Maps.  
[distribution_clustering](https://github.com/EricElmoznino/distribution_clustering), [paper](https://arxiv.org/abs/1804.02624), [related paper](https://arxiv.org/abs/2003.07770), [alt](https://github.com/r0f1/distribution_clustering).  
[phenograph](https://github.com/dpeerlab/phenograph) - Clustering by community detection.  
[FastPG](https://github.com/sararselitsky/FastPG) - Clustering of single cell data (RNA). Improvement of phenograph, [Paper](https://www.researchgate.net/publication/342339899_FastPG_Fast_clustering_of_millions_of_single_cells).  
[HypHC](https://github.com/HazyResearch/HypHC) - Hyperbolic Hierarchical Clustering.  
[BanditPAM](https://github.com/ThrunGroup/BanditPAM) - Improved k-Medoids Clustering.  
[dendextend](https://github.com/talgalili/dendextend) - Comparing dendrograms (R package).  
[DeepDPM](https://github.com/BGU-CS-VIL/DeepDPM) - Deep Clustering With An Unknown Number of Clusters.  

##### Clustering Evaluation
[Wagner, Wagner - Comparing Clusterings - An Overview](https://publikationen.bibliothek.kit.edu/1000011477/812079)
* [Adjusted Rand Index](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.adjusted_rand_score.html)
* [Normalized Mutual Information](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.normalized_mutual_info_score.html)
* [Adjusted Mutual Information](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.adjusted_mutual_info_score.html)
* [Fowlkes-Mallows Score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.fowlkes_mallows_score.html)
* [Silhouette Coefficient](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.silhouette_score.html)
* [Variation of Information](https://gist.github.com/jwcarr/626cbc80e0006b526688), [Julia](https://clusteringjl.readthedocs.io/en/latest/varinfo.html)
* [Pair Confusion Matrix](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.cluster.pair_confusion_matrix.html)
* [Consensus Score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.consensus_score.html) - The similarity of two sets of biclusters.

[Assessing the quality of a clustering (video)](https://www.youtube.com/watch?v=Mf6MqIS2ql4)   
[fpc](https://cran.r-project.org/web/packages/fpc/index.html) - Various methods for clustering and cluster validation (R package).  
* Minimum distance between any two clusters
* Distance between centroids
* p-separation index: Like minimum distance. Look at the average distance to nearest point in different cluster for p=10% "border" points in any cluster. Measuring density, measuring mountains vs valleys
* Estimate density by weighted count of close points 

Other measures:
* Within-cluster average distance
* Mean of within-cluster average distance over nearest-cluster average distance (silhouette score)
* Within-cluster similarity measure to normal/uniform
* Within-cluster (squared) distance to centroid (this is the k-Means loss function)
* Correlation coefficient between distance we originally had to the distance the are induced by the clustering (Huberts Gamma)
* Entropy of cluster sizes
* Average largest within-cluster gap
* Variation of clusterings on bootstrapped data

#### Multi-label classification
[scikit-multilearn](https://github.com/scikit-multilearn/scikit-multilearn) - Multi-label classification, [talk](https://www.youtube.com/watch?v=m-tAASQA7XQ&t=18m57s).  

#### Signal Processing and Filtering
[Stanford Lecture Series on Fourier Transformation](https://see.stanford.edu/Course/EE261), [Youtube](https://www.youtube.com/watch?v=gZNm7L96pfY&list=PLB24BC7956EE040CD&index=1), [Lecture Notes](https://see.stanford.edu/materials/lsoftaee261/book-fall-07.pdf).  
[The Scientist & Engineer's Guide to Digital Signal Processing (1999)](https://www.analog.com/en/education/education-library/scientist_engineers_guide.html).  
[Kalman Filter article](https://www.bzarg.com/p/how-a-kalman-filter-works-in-pictures).  
[Kalman Filter book](https://github.com/rlabbe/Kalman-and-Bayesian-Filters-in-Python) - Focuses on intuition using Jupyter Notebooks. Includes Baysian and various Kalman filters.  
[Interactive Tool](https://fiiir.com/) for FIR and IIR filters, [Examples](https://plot.ly/python/fft-filters/).  
[filterpy](https://github.com/rlabbe/filterpy) - Kalman filtering and optimal estimation library.  

#### Geometry
[geomstats](https://github.com/geomstats/geomstats) - Computations and statistics on manifolds with geometric structures.  

#### Time Series
[statsmodels](https://www.statsmodels.org/dev/tsa.html) - Time series analysis, [seasonal decompose](https://www.statsmodels.org/dev/generated/statsmodels.tsa.seasonal.seasonal_decompose.html) [example](https://gist.github.com/balzer82/5cec6ad7adc1b550e7ee), [SARIMA](https://www.statsmodels.org/dev/generated/statsmodels.tsa.statespace.sarimax.SARIMAX.html), [granger causality](http://www.statsmodels.org/dev/generated/statsmodels.tsa.stattools.grangercausalitytests.html).  
[kats](https://github.com/facebookresearch/kats) - Time series prediction library by Facebook.  
[prophet](https://github.com/facebook/prophet) - Time series prediction library by Facebook.  
[neural_prophet](https://github.com/ourownstory/neural_prophet) - Time series prediction built on Pytorch.  
[pyramid](https://github.com/tgsmith61591/pyramid), [pmdarima](https://github.com/tgsmith61591/pmdarima) - Wrapper for (Auto-) ARIMA.  
[modeltime](https://cran.r-project.org/web/packages/modeltime/index.html) - Time series forecasting framework (R package).  
[pyflux](https://github.com/RJT1990/pyflux) - Time series prediction algorithms (ARIMA, GARCH, GAS, Bayesian).  
[atspy](https://github.com/firmai/atspy) - Automated Time Series Models.  
[pm-prophet](https://github.com/luke14free/pm-prophet) - Time series prediction and decomposition library.  
[htsprophet](https://github.com/CollinRooney12/htsprophet) - Hierarchical Time Series Forecasting using Prophet.  
[nupic](https://github.com/numenta/nupic) - Hierarchical Temporal Memory (HTM) for Time Series Prediction and Anomaly Detection.  
[tensorflow](https://github.com/tensorflow/tensorflow/) - LSTM and others, examples: [link](
https://machinelearningmastery.com/time-series-forecasting-long-short-term-memory-network-python/
), [link](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/contrib/timeseries), [link](https://github.com/hzy46/TensorFlow-Time-Series-Examples), [Explain LSTM](https://github.com/slundberg/shap/blob/master/notebooks/deep_explainer/Keras%20LSTM%20for%20IMDB%20Sentiment%20Classification.ipynb), seq2seq: [1](https://machinelearningmastery.com/how-to-develop-lstm-models-for-multi-step-time-series-forecasting-of-household-power-consumption/), [2](https://github.com/guillaume-chevalier/seq2seq-signal-prediction), [3](https://github.com/JEddy92/TimeSeries_Seq2Seq/blob/master/notebooks/TS_Seq2Seq_Intro.ipynb), [4](https://github.com/LukeTonin/keras-seq-2-seq-signal-prediction)  
[tspreprocess](https://github.com/MaxBenChrist/tspreprocess) - Preprocessing: Denoising, Compression, Resampling.  
[tsfresh](https://github.com/blue-yonder/tsfresh) - Time series feature engineering.  
[tsfel](https://github.com/fraunhoferportugal/tsfel) - Time series feature extraction.  
[thunder](https://github.com/thunder-project/thunder) - Data structures and algorithms for loading, processing, and analyzing time series data.  
[gatspy](https://www.astroml.org/gatspy/) - General tools for Astronomical Time Series, [talk](https://www.youtube.com/watch?v=E4NMZyfao2c).  
[gendis](https://github.com/IBCNServices/GENDIS) - shapelets, [example](https://github.com/IBCNServices/GENDIS/blob/master/gendis/example.ipynb).  
[tslearn](https://github.com/rtavenar/tslearn) - Time series clustering and classification, `TimeSeriesKMeans`, `TimeSeriesKMeans`.  
[pastas](https://pastas.readthedocs.io/en/latest/examples.html) - Simulation of time series.  
[fastdtw](https://github.com/slaypni/fastdtw) - Dynamic Time Warp Distance.  
[fable](https://www.rdocumentation.org/packages/fable/versions/0.0.0.9000) - Time Series Forecasting (R package).  
[pydlm](https://github.com/wwrechard/pydlm) - Bayesian time series modeling ([R package](https://cran.r-project.org/web/packages/bsts/index.html), [Blog post](http://www.unofficialgoogledatascience.com/2017/07/fitting-bayesian-structural-time-series.html))  
[PyAF](https://github.com/antoinecarme/pyaf) - Automatic Time Series Forecasting.  
[luminol](https://github.com/linkedin/luminol) - Anomaly Detection and Correlation library from Linkedin.  
[matrixprofile-ts](https://github.com/target/matrixprofile-ts) - Detecting patterns and anomalies, [website](https://www.cs.ucr.edu/~eamonn/MatrixProfile.html), [ppt](https://www.cs.ucr.edu/~eamonn/Matrix_Profile_Tutorial_Part1.pdf), [alternative](https://github.com/matrix-profile-foundation/mass-ts).  
[stumpy](https://github.com/TDAmeritrade/stumpy) - Another matrix profile library.  
[obspy](https://github.com/obspy/obspy) - Seismology package. Useful `classic_sta_lta` function.  
[RobustSTL](https://github.com/LeeDoYup/RobustSTL) - Robust Seasonal-Trend Decomposition.  
[seglearn](https://github.com/dmbee/seglearn) - Time Series library.  
[pyts](https://github.com/johannfaouzi/pyts) - Time series transformation and classification, [Imaging time series](https://pyts.readthedocs.io/en/latest/auto_examples/index.html#imaging-time-series).  
Turn time series into images and use Neural Nets: [example](https://gist.github.com/oguiza/c9c373aec07b96047d1ba484f23b7b47), [example](https://github.com/kiss90/time-series-classification).  
[sktime](https://github.com/alan-turing-institute/sktime), [sktime-dl](https://github.com/uea-machine-learning/sktime-dl) - Toolbox for (deep) learning with time series.   
[adtk](https://github.com/arundo/adtk) - Time Series Anomaly Detection.  
[rocket](https://github.com/angus924/rocket) - Time Series classification using random convolutional kernels.  
[luminaire](https://github.com/zillow/luminaire) - Anomaly Detection for time series.  
[etna](https://github.com/tinkoff-ai/etna) - Time Series library.  
[Chaos Genius](https://github.com/chaos-genius/chaos_genius) - ML powered analytics engine for outlier/anomaly detection and root cause analysis.  

##### Time Series Evaluation
[TimeSeriesSplit](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.TimeSeriesSplit.html) - Sklearn time series split.  
[tscv](https://github.com/WenjieZ/TSCV) - Evaluation with gap.  

#### Financial Data and Trading
Tutorial on using cvxpy: [1](https://calmcode.io/cvxpy-one/the-stigler-diet.html), [2](https://calmcode.io/cvxpy-two/introduction.html)  
[pandas-datareader](https://pandas-datareader.readthedocs.io/en/latest/whatsnew.html) - Read stock data.  
[yfinance](https://github.com/ranaroussi/yfinance) - Read stock data from Yahoo Finance.  
[findatapy](https://github.com/cuemacro/findatapy) - Read stock data from various sources.  
[ta](https://github.com/bukosabino/ta) - Technical analysis library.  
[backtrader](https://github.com/mementum/backtrader) - Backtesting for trading strategies.  
[surpriver](https://github.com/tradytics/surpriver) - Find high moving stocks before they move using anomaly detection and machine learning.  
[ffn](https://github.com/pmorissette/ffn) - Financial functions.  
[bt](https://github.com/pmorissette/bt) - Backtesting algorithms.  
[alpaca-trade-api-python](https://github.com/alpacahq/alpaca-trade-api-python) - Commission-free trading through API.  
[eiten](https://github.com/tradytics/eiten) - Eigen portfolios, minimum variance portfolios and other algorithmic investing strategies.  
[tf-quant-finance](https://github.com/google/tf-quant-finance) - Quantitative finance tools in tensorflow, by Google.  
[quantstats](https://github.com/ranaroussi/quantstats) - Portfolio management.  
[Riskfolio-Lib](https://github.com/dcajasn/Riskfolio-Lib) - Portfolio optimization and strategic asset allocation.  
[OpenBBTerminal](https://github.com/OpenBB-finance/OpenBBTerminal) - Terminal.  

##### Quantopian Stack
[pyfolio](https://github.com/quantopian/pyfolio) - Portfolio and risk analytics.  
[zipline](https://github.com/quantopian/zipline) - Algorithmic trading.  
[alphalens](https://github.com/quantopian/alphalens) - Performance analysis of predictive stock factors.  
[empyrical](https://github.com/quantopian/empyrical) - Financial risk metrics.  
[trading_calendars](https://github.com/quantopian/trading_calendars) - Calendars for various securities exchanges.  

#### Survival Analysis
[Time-dependent Cox Model in R](https://stats.stackexchange.com/questions/101353/cox-regression-with-time-varying-covariates).  
[lifelines](https://lifelines.readthedocs.io/en/latest/) - Survival analysis, Cox PH Regression, [talk](https://www.youtube.com/watch?v=aKZQUaNHYb0), [talk2](https://www.youtube.com/watch?v=fli-yE5grtY).  
[scikit-survival](https://github.com/sebp/scikit-survival) - Survival analysis.  
[xgboost](https://github.com/dmlc/xgboost) - `"objective": "survival:cox"` [NHANES example](https://slundberg.github.io/shap/notebooks/NHANES%20I%20Survival%20Model.html)  
[survivalstan](https://github.com/hammerlab/survivalstan) - Survival analysis, [intro](http://www.hammerlab.org/2017/06/26/introducing-survivalstan/).  
[convoys](https://github.com/better/convoys) - Analyze time lagged conversions.  
RandomSurvivalForests (R packages: randomForestSRC, ggRandomForests).  
[pysurvival](https://github.com/square/pysurvival) - Survival analysis.  
[DeepSurvivalMachines](https://github.com/autonlab/DeepSurvivalMachines) - Fully Parametric Survival Regression.  

#### Outlier Detection & Anomaly Detection
[sklearn](https://scikit-learn.org/stable/modules/outlier_detection.html) - Isolation Forest and others.  
[pyod](https://pyod.readthedocs.io/en/latest/pyod.html) - Outlier Detection / Anomaly Detection.  
[eif](https://github.com/sahandha/eif) - Extended Isolation Forest.  
[AnomalyDetection](https://github.com/twitter/AnomalyDetection) - Anomaly detection (R package).  
[luminol](https://github.com/linkedin/luminol) - Anomaly Detection and Correlation library from Linkedin.  
Distances for comparing histograms and detecting outliers - [Talk](https://www.youtube.com/watch?v=U7xdiGc7IRU): [Kolmogorov-Smirnov](https://docs.scipy.org/doc/scipy-0.14.0/reference/generated/scipy.stats.ks_2samp.html), [Wasserstein](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.wasserstein_distance.html), [Energy Distance (Cramer)](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.energy_distance.html), [Kullback-Leibler divergence](https://scipy.github.io/devdocs/generated/scipy.stats.entropy.html).  
[banpei](https://github.com/tsurubee/banpei) - Anomaly detection library based on singular spectrum transformation.  
[telemanom](https://github.com/khundman/telemanom) - Detect anomalies in multivariate time series data using LSTMs.  
[luminaire](https://github.com/zillow/luminaire) - Anomaly Detection for time series.  

#### Ranking
[lightning](https://github.com/scikit-learn-contrib/lightning) - Large-scale linear classification, regression and ranking.  

#### Scoring
[SLIM](https://github.com/ustunb/slim-python) - Scoring systems for classification, Supersparse linear integer models.  

#### Causal Inference
[Statistical Rethinking](https://github.com/rmcelreath/stat_rethinking_2022) - Video Lecture Series, Bayesian Statistics, Causal Models, [R](https://bookdown.org/content/4857/), [python](https://github.com/pymc-devs/resources/tree/master/Rethinking_2), [numpyro1](https://github.com/asuagar/statrethink-course-numpyro-2019), [numpyro2](https://fehiepsi.github.io/rethinking-numpyro/), [tensorflow-probability](https://github.com/ksachdeva/rethinking-tensorflow-probability).  
[Python Causality Handbook](https://github.com/matheusfacure/python-causality-handbook)  
[dowhy](https://github.com/Microsoft/dowhy) - Estimate causal effects.  
[CausalImpact](https://github.com/tcassou/causal_impact) - Causal Impact Analysis ([R package](https://google.github.io/CausalImpact/CausalImpact.html)).  
[causallib](https://github.com/IBM/causallib) - Modular causal inference analysis and model evaluations by IBM, [examples](https://github.com/IBM/causallib/tree/master/examples).  
[causalml](https://github.com/uber/causalml) - Causal inference by Uber.  
[upliftml](https://github.com/bookingcom/upliftml) - Causal inference by Booking.com.  
[EconML](https://github.com/microsoft/EconML) - Heterogeneous Treatment Effects Estimation by Microsoft.  
[causality](https://github.com/akelleh/causality) - Causal analysis using observational datasets.  

##### Neuroscience
[Nengo](https://github.com/nengo/nengo) - Library for creating and simulating large-scale brain models.  
[Nitime](https://github.com/nipy/nitime) - Timeseries analysis for neuroscience data.  
[Nilearn](https://github.com/nilearn/nilearn) - Module for performing statistical learning/machine learning on NeuroImaging data.  
[DIPY](https://github.com/nipy/dipy) - Toolbox for analysis of MR diffusion imaging.  
[MNE-Python](https://github.com/mne-tools/mne-python) - Community-driven software for processing time-resolved neural signals including electroencephalography (EEG) and magnetoencephalography (MEG).  
[NiBabel](https://github.com/nipy/nibabel) - Provides read and write access to some common medical and neuroimaging file formats.  
[PsychoPy](https://github.com/psychopy/psychopy) - Package for running psychology and neuroscience experiments. It allows for creating psychology stimuli in Python.  
[NuPic](https://github.com/numenta/nupic) - Numenta Platform for Intelligent Computing is an implementation of Hierarchical Temporal Memory (HTM), a theory of intelligence based strictly on the neuroscience of the neocortex.  
[Brian2](https://github.com/brian-team/brian2) - Free, open source simulator for spiking neural networks.  
[expyriment](https://github.com/expyriment/expyriment) - Platform-independent lightweight Python library for designing and conducting timing-critical behavioural and neuroimaging experiments.  
[BindsNET](https://github.com/Hananel-Hazan/bindsnet) - Package for simulating spiking neural networks for reinforcement & machine learning.  
[SpikeInterface](https://github.com/SpikeInterface/spikeinterface) - Framework designed to unify spike-sorting technologies.  
[More here>>](https://github.com/analyticalmonk/awesome-neuroscience)  - Credit to Akash Tandon

##### Papers
[Bours - Confounding](https://edisciplinas.usp.br/pluginfile.php/5625667/mod_resource/content/3/Nontechnicalexplanation-counterfactualdefinition-confounding.pdf)  
[Bours - Effect Modification and Interaction](https://www.sciencedirect.com/science/article/pii/S0895435621000330)  

#### Probabilistic Modeling and Bayes
[Intro](https://erikbern.com/2018/10/08/the-hackers-guide-to-uncertainty-estimates.html), [Guide](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers)  
[PyMC3](https://docs.pymc.io/) - Bayesian modelling, [intro](https://docs.pymc.io/notebooks/getting_started)  
[numpyro](https://github.com/pyro-ppl/numpyro) - Probabilistic programming with numpy, built on [pyro](https://github.com/pyro-ppl/pyro).  
[pomegranate](https://github.com/jmschrei/pomegranate) - Probabilistic modelling, [talk](https://www.youtube.com/watch?v=dE5j6NW-Kzg).  
[pmlearn](https://github.com/pymc-learn/pymc-learn) - Probabilistic machine learning.  
[arviz](https://github.com/arviz-devs/arviz) - Exploratory analysis of Bayesian models.  
[zhusuan](https://github.com/thu-ml/zhusuan) - Bayesian deep learning, generative models.  
[edward](https://github.com/blei-lab/edward) - Probabilistic modeling, inference, and criticism, [Mixture Density Networks (MNDs)](http://edwardlib.org/tutorials/mixture-density-network), [MDN Explanation](https://towardsdatascience.com/a-hitchhikers-guide-to-mixture-density-networks-76b435826cca).  
[Pyro](https://github.com/pyro-ppl/pyro) - Deep Universal Probabilistic Programming.  
[tensorflow probability](https://github.com/tensorflow/probability) - Deep learning and probabilistic modelling, [talk1](https://www.youtube.com/watch?v=KJxmC5GCWe4), [notebook talk1](https://github.com/AlxndrMlk/PyDataGlobal2021/blob/main/00_PyData_Global_2021_nb_full.ipynb), [talk2](https://www.youtube.com/watch?v=BrwKURU-wpk), [example](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Chapter1_Introduction/Ch1_Introduction_TFP.ipynb).  
[bambi](https://github.com/bambinos/bambi) - High-level Bayesian model-building interface on top of PyMC3.  
[neural-tangents](https://github.com/google/neural-tangents) - Infinite Neural Networks.  
[bnlearn](https://github.com/erdogant/bnlearn) - Bayesian networks, parameter learning, inference and sampling methods.  

#### Gaussian Processes
[Visualization](http://www.infinitecuriosity.org/vizgp/), [Article](https://distill.pub/2019/visual-exploration-gaussian-processes/)  
[GPyOpt](https://github.com/SheffieldML/GPyOpt) - Gaussian process optimization.   
[GPflow](https://github.com/GPflow/GPflow) - Gaussian processes (Tensorflow).  
[gpytorch](https://gpytorch.ai/) - Gaussian processes (Pytorch).  

#### Stacking Models and Ensembles
[Model Stacking Blog Post](http://blog.kaggle.com/2017/06/15/stacking-made-easy-an-introduction-to-stacknet-by-competitions-grandmaster-marios-michailidis-kazanova/)  
[mlxtend](https://github.com/rasbt/mlxtend) - `EnsembleVoteClassifier`, `StackingRegressor`, `StackingCVRegressor` for model stacking.  
[vecstack](https://github.com/vecxoz/vecstack) - Stacking ML models.  
[StackNet](https://github.com/kaz-Anova/StackNet) - Stacking ML models.  
[mlens](https://github.com/flennerhag/mlens) - Ensemble learning.  
[combo](https://github.com/yzhao062/combo) - Combining ML models (stacking, ensembling).  

#### Model Evaluation
[pycm](https://github.com/sepandhaghighi/pycm) - Multi-class confusion matrix.  
[pandas_ml](https://github.com/pandas-ml/pandas-ml) - Confusion matrix.  
Plotting learning curve: [link](http://www.ritchieng.com/machinelearning-learning-curve/).  
[yellowbrick](http://www.scikit-yb.org/en/latest/api/model_selection/learning_curve.html) - Learning curve.  
[pyroc](https://github.com/noudald/pyroc) - Receiver Operating Characteristic (ROC) curves.  

#### Model Uncertainty
[uncertainty-toolbox](https://github.com/uncertainty-toolbox/uncertainty-toolbox) - Predictive uncertainty quantification, calibration, metrics, and visualization.  

#### Interpretable Classifiers and Regressors
[skope-rules](https://github.com/scikit-learn-contrib/skope-rules) - Interpretable classifier, IF-THEN rules.  
[sklearn-expertsys](https://github.com/tmadl/sklearn-expertsys) - Interpretable classifiers, Bayesian Rule List classifier.  

#### Model Explanation, Interpretability, Feature Importance
[Book](https://christophm.github.io/interpretable-ml-book/agnostic.html), [Examples](https://github.com/jphall663/interpretable_machine_learning_with_python)  
[shap](https://github.com/slundberg/shap) - Explain predictions of machine learning models, [talk](https://www.youtube.com/watch?v=C80SQe16Rao), [Good Shap intro](https://www.aidancooper.co.uk/a-non-technical-guide-to-interpreting-shap-analyses/).  
[treeinterpreter](https://github.com/andosa/treeinterpreter) - Interpreting scikit-learn's decision tree and random forest predictions.  
[lime](https://github.com/marcotcr/lime) - Explaining the predictions of any machine learning classifier, [talk](https://www.youtube.com/watch?v=C80SQe16Rao), [Warning (Myth 7)](https://crazyoscarchang.github.io/2019/02/16/seven-myths-in-machine-learning-research/).  
[lime_xgboost](https://github.com/jphall663/lime_xgboost) - Create LIMEs for XGBoost.  
[eli5](https://github.com/TeamHG-Memex/eli5) - Inspecting machine learning classifiers and explaining their predictions.  
[lofo-importance](https://github.com/aerdem4/lofo-importance) - Leave One Feature Out Importance, [talk](https://www.youtube.com/watch?v=zqsQ2ojj7sE), examples: [1](https://www.kaggle.com/divrikwicky/pf-f-lofo-importance-on-adversarial-validation), [2](https://www.kaggle.com/divrikwicky/lofo-importance), [3](https://www.kaggle.com/divrikwicky/santanderctp-lofo-feature-importance).  
[pybreakdown](https://github.com/MI2DataLab/pyBreakDown) - Generate feature contribution plots.  
[pycebox](https://github.com/AustinRochford/PyCEbox) - Individual Conditional Expectation Plot Toolbox.  
[pdpbox](https://github.com/SauceCat/PDPbox) - Partial dependence plot toolbox, [example](https://www.kaggle.com/dansbecker/partial-plots).  
[partial_dependence](https://github.com/nyuvis/partial_dependence) - Visualize and cluster partial dependence.  
[skater](https://github.com/datascienceinc/Skater) - Unified framework to enable model interpretation.  
[anchor](https://github.com/marcotcr/anchor) - High-Precision Model-Agnostic Explanations for classifiers.  
[l2x](https://github.com/Jianbo-Lab/L2X) - Instancewise feature selection as methodology for model interpretation.  
[contrastive_explanation](https://github.com/MarcelRobeer/ContrastiveExplanation) - Contrastive explanations.  
[DrWhy](https://github.com/ModelOriented/DrWhy) - Collection of tools for explainable AI.  
[lucid](https://github.com/tensorflow/lucid) - Neural network interpretability.  
[xai](https://github.com/EthicalML/XAI) - An eXplainability toolbox for machine learning.  
[innvestigate](https://github.com/albermax/innvestigate) - A toolbox to investigate neural network predictions.  
[dalex](https://github.com/pbiecek/DALEX) - Explanations for ML models (R package).  
[interpretml](https://github.com/interpretml/interpret) - Fit interpretable models, explain models.  
[shapash](https://github.com/MAIF/shapash) - Model interpretability.  
[imodels](https://github.com/csinva/imodels) - Interpretable ML package.  

#### Automated Machine Learning
[AdaNet](https://github.com/tensorflow/adanet) - Automated machine learning based on tensorflow.  
[tpot](https://github.com/EpistasisLab/tpot) - Automated machine learning tool, optimizes machine learning pipelines.  
[auto_ml](https://github.com/ClimbsRocks/auto_ml) - Automated machine learning for analytics & production.  
[autokeras](https://github.com/jhfjhfj1/autokeras) - AutoML for deep learning.  
[nni](https://github.com/Microsoft/nni) - Toolkit for neural architecture search and hyper-parameter tuning by Microsoft.  
[automl-gs](https://github.com/minimaxir/automl-gs) - Automated machine learning.  
[mljar](https://github.com/mljar/mljar-supervised) - Automated machine learning.  
[automl_zero](https://github.com/google-research/google-research/tree/master/automl_zero) - Automatically discover computer programs that can solve machine learning tasks from Google.  
[AlphaPy](https://github.com/ScottfreeLLC/AlphaPy) - Automated Machine Learning using scikit-learn xgboost, LightGBM and others.  

#### Graph Representation Learning
[Karate Club](https://github.com/benedekrozemberczki/karateclub) - Unsupervised learning on graphs.   
[Pytorch Geometric](https://github.com/rusty1s/pytorch_geometric) - Graph representation learning with PyTorch.   
[DLG](https://github.com/dmlc/dgl) - Graph representation learning with TensorFlow.   

#### Convex optimization
[cvxpy](https://github.com/cvxgrp/cvxpy) - Modeling language for convex optimization problems. Tutorial: [1](https://calmcode.io/cvxpy-one/the-stigler-diet.html), [2](https://calmcode.io/cvxpy-two/introduction.html)  

#### Evolutionary Algorithms & Optimization
[deap](https://github.com/DEAP/deap) - Evolutionary computation framework (Genetic Algorithm, Evolution strategies).  
[evol](https://github.com/godatadriven/evol) - DSL for composable evolutionary algorithms, [talk](https://www.youtube.com/watch?v=68ABAU_V8qI&t=11m49s).  
[platypus](https://github.com/Project-Platypus/Platypus) - Multiobjective optimization.  
[autograd](https://github.com/HIPS/autograd) - Efficiently computes derivatives of numpy code.  
[nevergrad](https://github.com/facebookresearch/nevergrad) - Derivation-free optimization.  
[gplearn](https://gplearn.readthedocs.io/en/stable/) - Sklearn-like interface for genetic programming.  
[blackbox](https://github.com/paulknysh/blackbox) - Optimization of expensive black-box functions.  
Optometrist algorithm - [paper](https://www.nature.com/articles/s41598-017-06645-7).  
[DeepSwarm](https://github.com/Pattio/DeepSwarm) - Neural architecture search.  

#### Hyperparameter Tuning
[sklearn](https://scikit-learn.org/stable/index.html) - [GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html), [RandomizedSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.RandomizedSearchCV.html).  
[sklearn-deap](https://github.com/rsteca/sklearn-deap) - Hyperparameter search using genetic algorithms.  
[hyperopt](https://github.com/hyperopt/hyperopt) - Hyperparameter optimization.  
[hyperopt-sklearn](https://github.com/hyperopt/hyperopt-sklearn) - Hyperopt + sklearn.  
[optuna](https://github.com/pfnet/optuna) - Hyperparamter optimization, [Talk](https://www.youtube.com/watch?v=tcrcLRopTX0).  
[skopt](https://scikit-optimize.github.io/) - `BayesSearchCV` for Hyperparameter search.  
[tune](https://ray.readthedocs.io/en/latest/tune.html) - Hyperparameter search with a focus on deep learning and deep reinforcement learning.  
[hypergraph](https://github.com/aljabr0/hypergraph) - Global optimization methods and hyperparameter optimization.  
[bbopt](https://github.com/evhub/bbopt) - Black box hyperparameter optimization.  
[dragonfly](https://github.com/dragonfly/dragonfly) - Scalable Bayesian optimisation.  
[botorch](https://github.com/pytorch/botorch) - Bayesian optimization in PyTorch.  
[ax](https://github.com/facebook/Ax) - Adaptive Experimentation Platform by Facebook.  

#### Incremental Learning, Online Learning
sklearn - [PassiveAggressiveClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.PassiveAggressiveClassifier.html), [PassiveAggressiveRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.PassiveAggressiveRegressor.html).  
[river](https://github.com/online-ml/river) - Online machine learning.  
[Kaggler](https://github.com/jeongyoonlee/Kaggler) - Online Learning algorithms.  
[onelearn](https://github.com/onelearn/onelearn) - Online Random Forests.  

#### Active Learning
[Talk](https://www.youtube.com/watch?v=0efyjq5rWS4)  
[modAL](https://github.com/modAL-python/modAL) - Active learning framework.  

#### Reinforcement Learning
[YouTube](https://www.youtube.com/playlist?list=PL7-jPKtc4r78-wCZcQn5IqyuWhBZ8fOxT), [YouTube](https://www.youtube.com/playlist?list=PLqYmG7hTraZDNJre23vqCGIVpfZ_K2RZs)  
Intro to Monte Carlo Tree Search (MCTS) - [1](https://jeffbradberry.com/posts/2015/09/intro-to-monte-carlo-tree-search/), [2](http://mcts.ai/about/index.html), [3](https://medium.com/@quasimik/monte-carlo-tree-search-applied-to-letterpress-34f41c86e238)  
AlphaZero methodology - [1](https://github.com/AppliedDataSciencePartners/DeepReinforcementLearning), [2](https://web.stanford.edu/~surag/posts/alphazero.html), [3](https://github.com/suragnair/alpha-zero-general), [Cheat Sheet](https://medium.com/applied-data-science/alphago-zero-explained-in-one-diagram-365f5abf67e0)  
[RLLib](https://ray.readthedocs.io/en/latest/rllib.html) - Library for reinforcement learning.  
[Horizon](https://github.com/facebookresearch/Horizon/) - Facebook RL framework.  

#### Deployment and Lifecycle Management

##### Workflow Scheduling and Orchestration
[airflow](https://github.com/apache/airflow) - Schedule and monitor workflows.  
[prefect](https://github.com/PrefectHQ/prefect) - Python specific workflow scheduling.  
[dagster](https://github.com/dagster-io/dagster) - Development, production and observation of data assets.  
[ploomber](https://github.com/ploomber/ploomber) - Workflow orchestration.  
[kestra](https://github.com/kestra-io/kestra) - Workflow orchestration.  

##### Containerization and Docker
[Reduce size of docker images (video)](https://www.youtube.com/watch?v=Z1Al4I4Os_A)  
[Optimize Docker Image Size](https://www.augmentedmind.de/2022/02/06/optimize-docker-image-size/)  
[cog](https://github.com/replicate/cog) - Facilitates building Docker images.  

##### Dependency Management
[dephell](https://github.com/dephell/dephell) - Dependency management.  
[poetry](https://github.com/python-poetry/poetry) - Dependency management.  
[pyup](https://github.com/pyupio/pyup) - Dependency management.  
[pypi-timemachine](https://github.com/astrofrog/pypi-timemachine) - Install packages with pip as if you were in the past.  

##### Data Versioning and Pipelines
[dvc](https://github.com/iterative/dvc) - Version control for large files.  
[hangar](https://github.com/tensorwerk/hangar-py) - Version control for tensor data.  
[kedro](https://github.com/quantumblacklabs/kedro) - Build data pipelines.  
[feast](https://github.com/feast-dev/feast) - Feature store. [Video](https://www.youtube.com/watch?v=_omcXenypmo).  

##### Data Science Related
[m2cgen](https://github.com/BayesWitnesses/m2cgen) - Transpile trained ML models into other languages.  
[sklearn-porter](https://github.com/nok/sklearn-porter) - Transpile trained scikit-learn estimators to C, Java, JavaScript and others.  
[mlflow](https://mlflow.org/) - Manage the machine learning lifecycle, including experimentation, reproducibility and deployment.  
[modelchimp](https://github.com/ModelChimp/modelchimp) - Experiment Tracking.  
[skll](https://github.com/EducationalTestingService/skll) - Command-line utilities to make it easier to run machine learning experiments.  
[BentoML](https://github.com/bentoml/BentoML) - Package and deploy machine learning models for serving in production.  
[dagster](https://github.com/dagster-io/dagster) - Tool with focus on dependency graphs.  
[knockknock](https://github.com/huggingface/knockknock) - Be notified when your training ends.  
[metaflow](https://github.com/Netflix/metaflow) - Lifecycle Management Tool by Netflix.  
[cortex](https://github.com/cortexlabs/cortex) - Deploy machine learning models.  
[Neptune](https://neptune.ai) - Experiment tracking and model registry.  
[clearml](https://github.com/allegroai/clearml) - Experiment Manager, MLOps and Data-Management.  
[polyaxon](https://github.com/polyaxon/polyaxon) - MLOps.  

#### Math and Background
[All kinds of math and statistics resources](https://realnotcomplex.com/)  
Gilbert Strang - [Linear Algebra](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/index.htm)  
Gilbert Strang - [Matrix Methods in Data Analysis, Signal Processing, and Machine Learning
](https://ocw.mit.edu/courses/mathematics/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/)  

#### Other
[daft](https://github.com/dfm/daft) - Render probabilistic graphical models using matplotlib.  
[unyt](https://github.com/yt-project/unyt) - Working with units.  
[scrapy](https://github.com/scrapy/scrapy) - Web scraping library.  
[VowpalWabbit](https://github.com/VowpalWabbit/vowpal_wabbit) - ML Toolkit from Microsoft.  
[Python Record Linkage Toolkit](https://github.com/J535D165/recordlinkage) - link records in or between data sources. 

#### General Python Programming
[more_itertools](https://more-itertools.readthedocs.io/en/latest/) - Extension of itertools.  
[funcy](https://github.com/Suor/funcy) - Fancy and practical functional tools.  
[dateparser](https://dateparser.readthedocs.io/en/latest/) - A better date parser.  
[jellyfish](https://github.com/jamesturk/jellyfish) - Approximate string matching.   
[coloredlogs](https://github.com/xolox/python-coloredlogs) - Colored logging output.    

#### Resources
[Distill.pub](https://distill.pub/) - Blog.   
[Machine Learning Videos](https://github.com/dustinvtran/ml-videos)  
[Data Science Notebooks](https://github.com/donnemartin/data-science-ipython-notebooks)  
[Recommender Systems (Microsoft)](https://github.com/Microsoft/Recommenders)  
[Datascience Cheatsheets](https://github.com/FavioVazquez/ds-cheatsheets)   

##### Guidelines 
[datasharing](https://github.com/jtleek/datasharing) - Guide to data sharing.  

##### Books
[Chan - Introduction to Probability for Data Science](https://probability4datascience.com/index.html)  
[Colonescu - Principles of Econometrics with R](https://bookdown.org/ccolonescu/RPoE4/)  

##### Other Awesome Lists
[Awesome Adversarial Machine Learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning)    
[Awesome AI Booksmarks](https://github.com/goodrahstar/my-awesome-AI-bookmarks)    
[Awesome AI on Kubernetes](https://github.com/CognonicLabs/awesome-AI-kubernetes)    
[Awesome Big Data](https://github.com/onurakpolat/awesome-bigdata)    
[Awesome Business Machine Learning](https://github.com/firmai/business-machine-learning)    
[Awesome Causality](https://github.com/rguo12/awesome-causality-algorithms)    
[Awesome Community Detection](https://github.com/benedekrozemberczki/awesome-community-detection)    
[Awesome CSV](https://github.com/secretGeek/AwesomeCSV)  
[Awesome Cytodata](https://github.com/cytodata/awesome-cytodata)  
[Awesome Data Science with Ruby](https://github.com/arbox/data-science-with-ruby)   
[Awesome Dash](https://github.com/ucg8j/awesome-dash)   
[Awesome Decision Trees](https://github.com/benedekrozemberczki/awesome-decision-tree-papers)    
[Awesome Deep Learning](https://github.com/ChristosChristofidis/awesome-deep-learning)   
[Awesome ETL](https://github.com/pawl/awesome-etl)   
[Awesome Financial Machine Learning](https://github.com/firmai/financial-machine-learning)   
[Awesome Fraud Detection](https://github.com/benedekrozemberczki/awesome-fraud-detection-papers)   
[Awesome GAN Applications](https://github.com/nashory/gans-awesome-applications)   
[Awesome Graph Classification](https://github.com/benedekrozemberczki/awesome-graph-classification)   
[Awesome Industry Machine Learning](https://github.com/firmai/industry-machine-learning)  
[Awesome Gradient Boosting](https://github.com/benedekrozemberczki/awesome-gradient-boosting-papers)   
[Awesome Learning with Label Noise](https://github.com/subeeshvasu/Awesome-Learning-with-Label-Noise)  
[Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning#python)    
[Awesome Machine Learning Books](http://matpalm.com/blog/cool_machine_learning_books/)  
[Awesome Machine Learning Interpretability](https://github.com/jphall663/awesome-machine-learning-interpretability)     
[Awesome Machine Learning Operations](https://github.com/EthicalML/awesome-machine-learning-operations)   
[Awesome Metric Learning](https://github.com/kdhht2334/Survey_of_Deep_Metric_Learning)  
[Awesome Monte Carlo Tree Search](https://github.com/benedekrozemberczki/awesome-monte-carlo-tree-search-papers)   
[Awesome Neural Network Visualization](https://github.com/ashishpatel26/Tools-to-Design-or-Visualize-Architecture-of-Neural-Network)  
[Awesome Online Machine Learning](https://github.com/MaxHalford/awesome-online-machine-learning)  
[Awesome Pipeline](https://github.com/pditommaso/awesome-pipeline)  
[Awesome Public APIs](https://github.com/public-apis/public-apis)  
[Awesome Python](https://github.com/vinta/awesome-python)   
[Awesome Python Data Science](https://github.com/krzjoa/awesome-python-datascience)   
[Awesome Python Data Science](https://github.com/thomasjpfan/awesome-python-data-science)  
[Awesome Python Data Science](https://github.com/amitness/toolbox)  
[Awesome Pytorch](https://github.com/bharathgs/Awesome-pytorch-list)  
[Awesome Quantitative Finance](https://github.com/wilsonfreitas/awesome-quant)  
[Awesome Recommender Systems](https://github.com/grahamjenson/list_of_recommender_systems)  
[Awesome Semantic Segmentation](https://github.com/mrgloom/awesome-semantic-segmentation)  
[Awesome Sentence Embedding](https://github.com/Separius/awesome-sentence-embedding)  
[Awesome Time Series](https://github.com/MaxBenChrist/awesome_time_series_in_python)  
[Awesome Time Series Anomaly Detection](https://github.com/rob-med/awesome-TS-anomaly-detection)  
[Awesome Visual Attentions](https://github.com/MenghaoGuo/Awesome-Vision-Attentions)  
[Awesome Visual Transformer](https://github.com/dk-liang/Awesome-Visual-Transformer)  

#### Lectures
[NYU Deep Learning SP21](https://www.youtube.com/playlist?list=PLLHTzKZzVU9e6xUfG10TkTWApKSZCzuBI) - Youtube Playlist.   

#### Misc
[Color codes](https://github.com/d3/d3-3.x-api-reference/blob/master/Ordinal-Scales.md#categorical-colors)  
[Frequency codes for time series](https://pandas.pydata.org/pandas-docs/stable/timeseries.html#offset-aliases)  
[Date parsing codes](https://docs.python.org/3/library/datetime.html#strftime-and-strptime-behavior)  
[Feature Calculators tsfresh](https://github.com/blue-yonder/tsfresh/blob/master/tsfresh/feature_extraction/feature_calculators.py)  

## Contributing  
Do you know a package that should be on this list? Did you spot a package that is no longer maintained and should be removed from this list? Then feel free to read the [contribution guidelines](CONTRIBUTING.md) and submit your pull request or create a new issue.  

## Credits
Thanks to [Florian Rohrer](https://github.com/r0f1). 

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
