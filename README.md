# RTP Payload Format for Visual Volumetric Video-based Coding (V3C)

This repository is used for discussion and development of a personal draft for V3C RTP payload format (draft-ilola-avtcore-rtp-v3c). The current version of the draft can be found in [IETF Datatracker](https://datatracker.ietf.org/doc/draft-ilola-avtcore-rtp-v3c/).

## Copy of abstract

This memo describes an RTP payload format for visual volumetric video-based coding (V3C) as defined in [ISO/IEC 23090-5](https://www.iso.org/standard/73025.html). A V3C bitstream is composed of V3C units that contain V3C video sub-bitstreams, V3C atlas sub-bitstreams, or a V3C parameter set. The RTP payload format for V3C video sub-bitstreams is defined by appropriate Internet Standards for the applicable video codec. The RTP payload format for V3C atlas sub-bitstreams is described by this memo. The RTP payload format allows for packetization of one or more V3C Network Abstraction Layer (NAL) units in a RTP packet payload as well as fragmentation of a V3C NAL unit into multiple RTP packets. The memo also describes the mechanisms for grouping RTP streams of V3C component sub-bitstreams, providing a complete solution for streaming V3C bitstream. 

## Building the draft

The draft can be built into .txt or .xml versions using [kramdown-rfc](https://github.com/cabo/kramdown-rfc). Please see details about kramdown-rfc usage from the related github project. 

Alteratively, [IETF conversion tool](https://author-tools.ietf.org/) may be used without installing additional software packages.

## Contributing

All material in this repository is considered as contributions to the IETF Standards Process and the applicaple policies shall apply. 