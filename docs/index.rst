.. FAIR Universe HEP Challenge documentation master file, created by
   sphinx-quickstart on Sat Jun  8 17:35:19 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to FAIR Universe HEP Challenge's documentation!
=======================================================
.. raw:: html

   <a href="https://fair-universe.lbl.gov/tutorials/Higgs_Uncertainty_Challenge-Codabench_Tutorial.pdf" class="button" style="display: inline-block; padding: 20px 40px; font-size: 18px; background-color: #4CAF50; color: white; text-align: center; text-decoration: none; border-radius: 5px;">
   Click Here For Tutorial Slides
   </a>

|

The Fair Universe project is organising the **HiggsML Uncertainty Challenge**, following on from the `HiggsML challenge on Kaggle <https://www.kaggle.com/c/higgs-boson>`_ in 2014, the context is the measurement of the Higgs Boson signal but in the presence of systematics unicertainities. Participants should design an advanced analysis technique that can not only measure the signal strength but also provide a confidence interval, from which correct coverage will be evaluated automatically from pseudo-experiments.

The confidence interval should include statistical and systematic uncertainties (concerning detector calibration, background levels, etc…). It is expected that analysis techniques that can control the impact of systematics will perform best, thereby pushing the field of uncertainty-aware AI techniques for HEP and beyond.

There are several information sources regarding the FAIR Universe - HiggsML Uncertainty Challenge:

* `Codabench <https://www.codabench.org/competitions/2977/>`_ : This serves as the platform to submit entries to the competition. It hosts the public training data `Click here to download the dataset (6.5GB) <https://www.codabench.org/datasets/download/b9e59d0a-4db3-4da4-b1f8-3f609d1835b2/>`_.

* `Tutorial Slides <https://fair-universe.lbl.gov/tutorials/Higgs_Uncertainty_Challenge-Codabench_Tutorial.pdf>`_ : These slides will help you register and submit a sample dummy submission.

* `Documentation <https://fair-universe.lbl.gov/docs/>`_ : This contains detailed information about the `science behind the challenge <https://fair-universe.lbl.gov/docs/pages/overview.html#problem-setting>`_, the `specifics of the data <https://fair-universe.lbl.gov/docs/pages/data.html>`_, and `documents the code <https://fair-universe.lbl.gov/docs/rst_source/modules.html>`_ used to facilitate the evaluation of the competition. It also describes the `evaluation metric <https://fair-universe.lbl.gov/docs/pages/evaluation.html>`_.

* `Github Repo <https://github.com/FAIR-Universe/HEP-Challenge/tree/master/>`_ : This hosts the code for testing submissions, as well as the `starting kit notebook <https://github.com/FAIR-Universe/HEP-Challenge/blob/master/StartingKit_HiggsML_Uncertainty_Challenge.ipynb>`_. The starting kit is also available on `Google Colab <https://colab.research.google.com/github/FAIR-Universe/HEP-Challenge/blob/master/StartingKit_HiggsML_Uncertainty_Challenge.ipynb>`_.

* `White Paper <https://fair-universe.lbl.gov/tutorials/Higgs_Uncertainty_Challenge_whitepaper.pdf>`_ : (coming soon): This serves as a full breakdown of the competition in detail.


|

.. toctree::
   :maxdepth: 1
   :caption: Pages:

   pages/Local_setup.md
   pages/overview.md
   pages/data.md
   pages/evaluation.md  

.. toctree::
   :maxdepth: 2
   :caption: Core Modules: 

   rst_source/ingestion_program
   rst_source/scoring_program
   rst_source/simple_one_syst_model
   rst_source/simple_stat_only_model

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
