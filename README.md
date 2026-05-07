# BiSeDiff
BiSeDiff: Bidirectional Shift-Equivariant Diffusion for Boundary-Free Textile Texture Generation

## Challenges

Achieving seamless tiling is nontrivial. The model must ensure precise alignment at the boundaries while preserving consistency with the style and layout
of the input non-tileable exemplar. Existing methods face significant challenges with complex, seamless patterns, leading to: (i)inconsistent structure and (ii) discontinuous boundaries.

<img width="1620" height="493" alt="图1" src="https://github.com/user-attachments/assets/61a3852f-a353-4653-a179-403b71de257c" />
Fig. 1. Challenges in Texture Tiling. Given a non-tileable exemplar, existing methods struggle with inconsistent texture and discontinuous boundaries. Our method generates boundary-free images while faithfully preserving the input’s structure and style.

## The Overall Framework
<img width="1280" height="720" alt="Pipeline" src="https://github.com/user-attachments/assets/1bba582f-83dd-44ab-a5c5-cefec9060e24" />
Figure 1. Overview of the proposed BiSeDiff Framework. The key innovation is the Bidirectional Shift-Equivariance (BiSE) strategy for boundary-free
texture generation. This is supported by the Visual-Invariance Texture Alignment (ViTA) module, which integrates two synergistic components: Visual Feature
Alignment (VFA) for style consistency and Shift-Invariant Consistency (SIC) for structural coherence. Finally, the Tiled-Hann Decoding (THD) module enables
efficient generation of infinitely large, tileable patterns.

