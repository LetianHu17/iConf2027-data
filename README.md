# iConf2027-data
# Dataset for *Hedgehogs or Foxes? Early-Career Semantic Trajectories of Highly Accomplished Scientists*

This repository stores the original data for the paper *Hedgehogs or Foxes? Early-Career Semantic Trajectories of Highly Accomplished Scientists*.

## Dataset Description
This repository contains a publication-level semantic trajectory dataset for 103 highly accomplished scientists who received major scientific awards, including the Nobel Prize, Fields Medal, and ACM A.M. Turing Award. Laureates were matched to OpenAlex author profiles, and their publications were represented using title-and-abstract embeddings.

For each publication, the dataset reports three semantic trajectory measures: Semantic Expansion, Research Coherence, and Semantic Alignment. These measures capture how a scientist’s new work moves away from prior work, how concentrated their accumulated research is, and how strongly new work remains directionally aligned with previous research.

The dataset file is `awardee_semantic_trajectories.parquet` and includes author identifiers, award history, publication years, paper identifiers, and semantic trajectory measures.
