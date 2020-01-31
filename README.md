# no-gradient-predictions
This repository ensures predictions published by [no gradient](https://nogradient.com/2019/11/26/predictions-scorecard/) are stored as part of the [GitHub Archive Program](https://archiveprogram.github.com/) and also provides a history of provenance proofs using the Bitcoin blockchain.

File | SHA256 Hash | Proof of Existence | Bitcoin Transaction
--- | --- | --- | ---
[no-gradient-predictions.txt](https://github.com/octohub/no-gradient-predictions/blob/master/no-gradient-predictions.txt) | 089e6c5b0eec34984e4f48f9890fb198f5bf6719c526a22e2d685867ab18800b | [089e6...](https://proofofexistence.com/detail/089e6c5b0eec34984e4f48f9890fb198f5bf6719c526a22e2d685867ab18800b) | [1b711fecad99896de3f6ecfa6bad51fb81f8e8f74da5e1567bcfa6c61720425e](https://www.blockchain.com/btc/tx/1b711fecad99896de3f6ecfa6bad51fb81f8e8f74da5e1567bcfa6c61720425e)
[no-gradient-predictions-1.txt](https://github.com/octohub/no-gradient-predictions/blob/master/no-gradient-predictions-1.txt) | 53781be7da5d3f2a1f990a3627836f589c1e9264d405c1b8e85670ce0dd231a8 | [53781...](https://proofofexistence.com/detail/53781be7da5d3f2a1f990a3627836f589c1e9264d405c1b8e85670ce0dd231a8) | [5a29d5ec1911f98c5618b36702c0d2befc4f3bb15272ffeb16e8abd61905d94f](https://www.blockchain.com/btc/tx/5a29d5ec1911f98c5618b36702c0d2befc4f3bb15272ffeb16e8abd61905d94f)

### How to Verify Provenance
1. Download the predictions text file.
2. Calculate the SHA256 hash of the file. This can easily be done by uploading the file [here](https://md5file.com/calculator) or [here](https://emn178.github.io/online-tools/sha256_checksum.html).
3. Upload the file to [Proof of Existence](https://proofofexistence.com/) and verify it has successfully been notarized.
4. View the Bitcoin transaction on [blockchain.com](https://www.blockchain.com/). Verify the hash of the file is embedded at the end of the OP_RETURN value.
