# LAKAF-Tamarin-Model
## Introduction
This repository contains the tamarin model source code and the derived traces of the [LAKAF](https://doi.org/10.1016/j.sysarc.2021.102053) protocol.

## Layout
[LAKAF_Model.spthy](LAKAF_Model.spthy) contains the source code and security lemmas of the tamarin model.

[Traces](traces/) folder contains the derived traces of the security lemmas specified in the model.
 - lemma user_anonymity \([trace](traces/user_anonymity.png)\)
 - lemma k1_secrecy \([trace](traces/k1_secrecy.png)\)
 - lemma k3_secrecy \([trace](traces/k3_secrecy.png)\)
 - lemma sk_secrecy \([trace](traces/sk_secrecy.png)\)
 - lemma key_agreement_possible_check \([trace](traces/key_agreement_possible.png)\)
