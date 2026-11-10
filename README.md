# EV Adoption & Charging Infrastructure Gap Analysis in India (UPM Lakehouse)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aniketkoley-iisc/ev-gap-analysis-india-upm/blob/main/notebooks/ev-gap-analysis-india-upm.ipynb)

**Course:** DSBA DA-231-O — Data Engineering at Scale (IISc Bangalore)  
**Instructor:** Prof. Yogesh Simmhan  

---

## Project Team & Equal Track Ownership

| Team Member | IISc Email | Primary Engineering Track & Notebook Cells |
| :--- | :--- | :--- |
| **Aniket Koley** | `aniketkoley@iisc.ac.in` | **Track 1 (Stages 1 & 2 — Cells 1 to 7):** Distributed Environment Setup, Medallion Lakehouse (`Bronze -> Silver -> Gold`), Live Geofabrik 1.59 GB OSM PBF & Multi-Repo Ingestion, Spark Pair RDD `reduceByKey` & Window 50m Spatial Deduplication (`739 -> 632` Silver stations) |
| **Dashrath Rajpurohit** | `dashrathraj1@iisc.ac.in` | **Track 2 (Stages 3 & 4 — Cells 8 to 9):** C++ `osmium-tool` National Highway Corridor Extraction (`18,136` OSM primitives), Multi-Resolution Uber H3 Hexagonal Spatial Indexing (`h3_res5` & `h3_res7`), Min-Max Normalization & Infrastructure Gap Index (`IGI`) |
| **Kumar Bhawenshu** | `kumarbhawes1@iisc.ac.in` | **Track 3 (Stages 5 & 6 — Cells 10 to 11):** Highway Network Graph Construction (`450` vertices, `2,244` edges), Pregel BSP Multi-Source Shortest Path & PageRank Centrality, Spark ML (`RF` & `GBT`) + TensorFlow + Cross-Silo FedAvg Demand Forecasting, Greedy Spatial De-Clustered Siting (`K = 1..100`, `>= 45 km` separation) & Before/After Graph Verification |
| **Chennuri Manikanta** | `manikantaku1@iisc.ac.in` | **Track 4 (Stages 7 & 8 — Cells 12 to 14):** Spark Scalability Benchmark (`0.25x` to `4.00x`, `records/sec` & `GB/sec`), Polyglot Persistence (`SQLite`, `NoSQL Document Store`, `GeoJSON`), Streaming CEP Telemetry, Interactive Folium Map (`MarkerCluster`, Live `K=1..100` Slicer, `15:1` IEA Benchmark Slicer) & Proposed New Station Success Rate Simulator |

---

## Live Execution on Google Colab

Click the **Open in Colab** badge above (or open [`notebooks/ev-gap-analysis-india-upm.ipynb`](notebooks/ev-gap-analysis-india-upm.ipynb)) to inspect all 14 compiled cells, statistical outputs, charts, and the interactive India map, or click **Runtime -> Run all** to execute the full pipeline live.

