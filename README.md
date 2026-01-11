# Neural-Machine-Translation-for-Indian-Languages-Report
Built an end-to-end English→Hindi and English→Bengali NMT system using ~150k parallel sentence pairs, covering data cleaning, vocabulary design, training, and evaluation.
Implemented and benchmarked Seq2Seq (GRU/LSTM), Attention-based models, and Transformer architectures, analyzing stability and generalization on medium-scale datasets.
Systematically evaluated tokenization strategies (word-level, Word2Vec, BPE) and identified subword fragmentation as a key failure mode for Hindi/Bengali scripts.
Designed a reduced (“Half”) Transformer with word-level vocabulary, achieving the best and most stable performance (0.32–0.35 score) while avoiding BPE-induced alignment errors.
Applied beam search decoding, mixed-precision training, and regularization techniques, selecting the final model based on accuracy–stability trade-offs rather than model size.
