# CircuitEncoder
A Self-Supervised, Pre-Trained, and Cross-Stage-Aligned Circuit Encoder Provides a Foundation for Various Design Tasks (ASP-DAC'25) [[paper]](https://dl.acm.org/doi/abs/10.1145/3658617.3697597)

The latest and full version of CircuitEncoder has been updated to
- A multimodal RTL encoder: CircuitFusion (ICLR'25) 
    - CircuitFusion: Multimodal Circuit Representation Learning for Agile Chip Design
    - CircuitFusion fuses RTL-stage code, graph, and summary into a unified register-level embedding, supporting various design quality prediction tasks.
    - [[Paper]](https://openreview.net/forum?id=rbnf7oe6JQ) 
    - [[Code]](https://github.com/hkust-zhiyao/CircuitFusion)
- A multimodal netlist encoder: NetTAG (DAC'25) 
    - NetTAG: A Multimodal RTL-and-Layout-Aligned Netlist Foundation Model via Text-Attributed Graph
    - NetTAG formulates netlists as text-attributed graphs, with gates annotated by symbolic logic expressions and physical characteristics as text attributes.  Its multimodal architecture combines an LLM-based text encoder for gate semantics and a graph transformer for global structure, supporting both netlist-stage design quality prediction and functional reasoning tasks.
    - [[Paper]]() 
    - [[Code]](https://github.com/hkust-zhiyao/NetTAG)