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

The Fair Universe project is organising the **HiggsML Uncertainty Challenge**, The context is the measurement of the Higgs Boson signal like in `HiggsML challenge on Kaggle <https://www.kaggle.com/c/higgs-boson>`_ in 2014, Participants should design an advanced analysis technique that can not only measure the signal strength but also provide a confidence interval, from which correct coverage will be evaluated automatically from pseudo-experiments.

The confidence interval should include statistical and systematic uncertainties (concerning detector calibration, background levels, etc…). It is expected that advanced analysis techniques that can control the impact of systematics will perform best, thereby pushing the field of uncertainty-aware AI techniques for HEP and beyond.

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
