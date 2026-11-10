# EV Adoption and Charging Infrastructure Gap Analysis in India

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aniketkoley-iisc/ev-gap-analysis-india-upm/blob/main/notebooks/ev-gap-analysis-india-upm.ipynb)

**Course:** Data Engineering at Scale (DSBA DA-231-O), IISc Bangalore
**Instructor:** Prof. Yogesh Simmhan
**Authors:**
* Track 1: Aniket Koley (aniketkoley@iisc.ac.in)
* Track 2: Dashrath Rajpurohit (dashrathraj1@iisc.ac.in)
* Track 3: Kumar Bhawenshu (kumarbhawes1@iisc.ac.in)
* Track 4: Chennuri Manikanta (manikantaku1@iisc.ac.in)

## Architecture Overview
End-to-end Medallion Lakehouse Pipeline (Bronze -> Silver -> Gold) integrating 1.59 GB Geofabrik OpenStreetMap PBF, Live Overpass API, E-Amrit registries, and Vahan RTO EV sales across Apache Spark 4.0.4, Uber H3 Spatial Indexing (Res-5 & Res-7), Pregel Highway Graph Analytics, Distributed Machine Learning (Spark ML RandomForest/GBT, TensorFlow MLP, Cross-Silo FedAvg), K=25 Optimal Siting Verification, Spark Scalability Benchmarking (0.25x to 4.00x Volume), Polyglot Persistence (SQLite RDBMS + NoSQL H3 KV + GeoJSON), and Windowed Streaming CEP.
