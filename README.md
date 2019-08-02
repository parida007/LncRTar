# LncRTar
A target prediction tool for long non coding RNA and messenger RNA.
Long noncoding RNAs (lncRNAs) are noncoding transcripts having length longer than 200 nucleotides. These molecules play a key role in various biological processes by regulating gene expression. Recently it has been demonstrated that lncRNAs can bind to proteins, DNA and even mRNAs. Such diversity in their binding capability necessitates understanding the binding mechanisms and rules exhibited by them.<br />
Till date several research groups have come up with many target prediction tools. However, the detailed mechanism of an lncRNA interacting with mRNA still remains to be understood. Multiple binding sites between the two RNAs (i.e. lncRNAs and mRNAs) remains to be the most critical factor decisive of an efficient interaction. Besides, tools predicting these interactions using machine learning algorithms do not predict the interaction score efficiently due to unavailability of enough negative datasets.<br />
LncrTar, is a target prediction tool, which overcomes the above mentioned hurdles and identifies the probable binding sites between lncRNA and mRNA along with determination of interaction energy. LncrTar comes up with two major findings. These calculations are done on the basis of the experimentally validated positive lncRNA-mRNA interaction information reported by *et.al. The feature set has been prepared from the sequence and binding information. Interaction confidence of the input sequence pair has been evaluated by 7 different machine learning models. The interaction confidence for input pair helps user to select the most putative interaction. The accessible segments between lncRNA and mRNA has been identified by using AccessE algorithm designed by us. The binding information among the accessible segments of lncRNA and its target can be visualized as well as downloaded.
