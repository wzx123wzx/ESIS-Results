# folder struture

|-- dataset1

|--|-- DJI_0169.JPG-DJI_0172.JPG (subset of dataset)

|--|-- superpixel_10 # result of our method (N_s is set to 10)

|--|--|-- mosaic_fusion_dist -> our weighted blending result, corresponding to Eq. 8 and Fig. 3 (b) in the manuscript

|--|--|-- mosaic_graph_cut -> our superpixel level graph-cut result, corresponding to Fig. 4 (b) in the manuscript

|--|--|-- optimal_sp_segment -> show the optimal superpixel distribution, corresponding to Fig. 4 (a) in the manuscript

|--|--|-- superpixel_mosaic -> shown the superpixel segmentation on mosaic, corresponding to Fig. 3 (c) in the manuscript

|--|-- superpixel_100 # result of our method (N_s is set to 100)

...

|--|-- superpixel_1000 # result of our method (N_s is set to 1000)

...

|--|-- superpixel_10000 # result of our method (N_s is set to 10000)

...

|-- dataset2

...

|-- dataset3

...








