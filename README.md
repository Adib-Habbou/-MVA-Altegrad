# MVA-Altegrad

## Introduction

This project delves into the intricate task of retrieving molecules, represented as graphs, using natural language queries. The challenge lies in integrating information encoded in text descriptions and molecular graphs. By developing a contrastive training pipeline employing distinct encoders specialized in handling textual data and graphical data, we are able to capture both nuances.

## Strategy

Leveraging Graph Attention Networks (GAT, GATv2 and SuperGAT) by using ensemble method, we showcase the adaptability of attention mechanisms in handling diverse graph structures. The proposed aggregation strategy, combining predictions from these models, enhances overall predictive performance. Despite all the above challenges, our approach demonstrates good final results by achieving a fair LRAP score at the end.

## Results

Final Rank on the public leaderboard : 8th

Final Score on the public leaderboard : 0.9387
