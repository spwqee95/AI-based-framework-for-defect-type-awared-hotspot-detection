# Many-Layer Hotspot Detection by Layer-Attentioned Visual Question Answering

## Background:

Identifying hotspot patterns and correcting them as early as possible is crucial in ensuring yield and manufacturability in electronic design automation (EDA). Traditional hotspot detection methods often focus on individual layers or adjacent layers, overlooking the complex interactions between multiple layers in modern layouts.

<p align="center">
  <img src="fig/pattern_extraction.png" alt="Pattern Extraction">
</p>

## Approach:

We formulate the task of many-layer critical hotspot pattern extraction as a visual question answering (VQA) problem. Treating a many-layer layout pattern as an image and a defect type as a question, we designed a layer-attention deep learning VQA model tailored to this specific problem. This model assesses whether a pattern is critical to a queried defect type by incorporating visual question answering techniques.

<p align="center">
  <img src="fig/approach.png" alt="VQA Model" width="70%" height="70%">
</p>

## Key Features:

- **Deep Learning:** Harness the power of deep learning for analyzing complex layout patterns.
- **Computer Vision and NLP:** Integrate computer vision and NLP techniques to bridge the gap between visual patterns and textual queries.
- **Attention Mechanism:** Utilize a layer attention mechanism to dynamically highlight the importance of each layer in hotspot detection, enhancing model interpretability and performance.

<p align="center">
  <img src="fig/model.png" alt="Model" width="75%" height="75%">
</p>

## Results:

Experimental results showcase the superior question-answering ability of our proposed model. It surpasses existing methods on modern layouts with more than thirty layers, demonstrating its effectiveness in hotspot detection and defect type identification.

## Usage:

To replicate our experiments or apply our method to your own datasets, refer to the instructions provided in the `README.md` file and explore the provided codebase.

## Citation:

Y. -S. Chen and I. H. -R. Jiang, "Many-Layer Hotspot Detection by Layer-Attentioned Visual Question Answering," 2022 Design, Automation & Test in Europe Conference & Exhibition (DATE), Antwerp, Belgium, 2022, pp. 604-607, doi: 10.23919/DATE54114.2022.9774622.

## Keywords:

Deep Learning; Visual Question Answering; Natural Language Processing; Computer Vision; Attention Mechanism; Electronic Design Automation; VLSI Layout; Hotspot Detection

