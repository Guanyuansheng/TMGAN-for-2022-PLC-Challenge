# TMGAN-for-2022-PLC-Challenge

we propose a novel packet loss concealment model based on temporal memory generative adversarial network (TMGAN). Taking a nested-UNet and the temporal
feature-wise linear modulation as the backbone, the proposed generator can aggregate local and global features by leveraging the memory function in LSTMs, thus reducing the effect
of buffer size on the reconstruction quality. Furthermore, we design the multi-stage vector quantizers with a gating mechanism to cope with burst losses. In the gated vector quantizers,
the encoding learning can autonomously avoid missing the large regions and the decoding reconstruction incorporates the codebook and quantization features of the previous frames, which
allows for the high-quality recovery during longer burst losses. Experimental results demonstrate the effectiveness of each temporal memory module, and show the competitive performance
of the proposed method in terms of speech quality, intelligibility and PLCMOS for different burst loss lengths.

