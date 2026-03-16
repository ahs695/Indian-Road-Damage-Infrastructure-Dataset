Indian Road Damage & Infrastructure Dataset (IRDID)
Overview

The Indian Road Damage & Infrastructure Dataset (IRDID) is a curated computer vision dataset designed to capture common road damage and infrastructure issues in Indian road environments. While existing datasets such as the Road Damage Dataset (RDD) include images from multiple countries, including India, they do not fully capture the diversity and complexity of Indian road conditions. Indian roads often feature unmarked lanes, mixed road materials, informal infrastructure, heavy traffic interactions, and seasonal damage caused by monsoons.

This dataset aims to provide a structured and diverse collection of images representing typical road hazards in India to support research and development of computer vision models for road monitoring, infrastructure assessment, and smart city applications.

Dataset Classes

The dataset contains six classes of road damage and infrastructure conditions:

Potholes – Depressions or cavities formed in the road surface due to wear, erosion, or poor maintenance.

Cracks – Linear fractures on the road surface that indicate structural weakening.

Open Manholes – Uncovered or partially covered manholes that pose safety hazards.

Waterlogged Roads – Road sections submerged due to rainfall or drainage failure.

Broken Road Edges – Erosion or collapse along the edges or shoulders of the road.

Construction / Repair Zones – Road areas under repair or construction, including dug surfaces or temporary barriers.

Dataset Size

Total images: 1200

Images per class:

Class Images
Potholes 200
Cracks 200
Open Manholes 200
Waterlogged Roads 200
Broken Road Edges 200
Construction Zones 200
Dataset Split
Split Images
Train 840
Validation 180
Test 180

Split files are located in:

splits/train.txt
splits/val.txt
splits/test.txt
Folder Structure
Indian-Road-Damage-Infrastructure-Dataset/

images/
potholes/
cracks/
open_manholes/
waterlogged_road/
broken_edges/
construction_zones/

annotations/
labels.csv

metadata/
dataset_metadata.csv

splits/
train.txt
val.txt
test.txt

docs/
class_definitions.md

README.md
LICENSE
