# **CODE ACKNOWLEDGEMENTS**

Functions/classes written by myself:<br />
VideoEncoder, printOut, train, test, evaluate, Model, get_Y_len

**LiveBot Github**<br />
https://github.com/lancopku/livebot/tree/master/codes<br />

Copied functions/classes: <br />
load_from_json, load_img, padding, recall, mean_rank, mean_reciprocal_rank, calc_hit_rank

Modified functions/classes: <br />
CustomDataset: changed imgs, vocab, rev_vocab, vocab_size to global <br />
CustomDataset init: modified to save each data components in different variables <br />
CustomDataset getitem: modified train/test/evaluate flag for different purposes <br />

**PyTorch Tutorial**<br />
https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html<br />
Based functions/classes: <br />
TextEncoder: referenced but rewrote for specific application <br />
CommentDecoder: referenced but rewrote for specific application <br />

**Batched Seq2Seq Github**<br />
https://github.com/spro/practical-pytorch/blob/master/seq2seq-translation/seq2seq-translation-batched.py <br />
Modified functions/classes: <br />
Attn: modified sizes to match application
