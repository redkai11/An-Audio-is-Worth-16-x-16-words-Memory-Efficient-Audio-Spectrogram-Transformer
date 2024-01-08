# Memory-Efficient-Audio-Melspectrogram-Tranformer-Model

This repository contains the implementation for Memory Efficient Audio Melspectrogram Tranformer Model (MEAMTM) which utilizes nnAudio and the Audio Spectrogram Transformer to offer a memory-efficient solution for audio classification. With this model, you can directly feed audio waveforms without the need to convert them into spectrograms separately, saving both storage and memory.

# Features
* Memory Efficiency: The model eliminates the need for intermediate spectrogram conversion, reducing memory requirements and improving efficiency.
* Ease of Use: Simplified audio processing pipeline by directly handling audio waveforms.
* nnAudio Integration: Utilizes the nnAudio library for efficient audio processing and feature extraction
* Audio Spectrogram Transformer: Leverages the capabilities of the Audio Spectrogram Transformer for effective feature extraction from audio spectrograms/Melspectrograms.

# References

@ARTICLE{9174990, author={K. W. {Cheuk} and H. {Anderson} and K. {Agres} and D. {Herremans}}, journal={IEEE Access}, title={nnAudio: An on-the-Fly GPU Audio to Spectrogram Conversion Toolbox Using 1D Convolutional Neural Networks}, year={2020}, volume={8}, number={}, pages={161981-162003}, doi={10.1109/ACCESS.2020.3019084}}

@article{dosovitskiy2020vit,
  title={An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale},
  author={Dosovitskiy, Alexey and Beyer, Lucas and Kolesnikov, Alexander and Weissenborn, Dirk and Zhai, Xiaohua and Unterthiner, Thomas and  Dehghani, Mostafa and Minderer, Matthias and Heigold, Georg and Gelly, Sylvain and Uszkoreit, Jakob and Houlsby, Neil},
  journal={ICLR},
  year={2021}
}

@ARTICLE{gong_psla, 
    author={Gong, Yuan and Chung, Yu-An and Glass, James},  
    journal={IEEE/ACM Transactions on Audio, Speech, and Language Processing},   
    title={PSLA: Improving Audio Tagging with Pretraining, Sampling, Labeling, and Aggregation},   
    year={2021}, 
    doi={10.1109/TASLP.2021.3120633}
}
