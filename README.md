# MixRep: Hidden Representation Mixup for Low-Resource Speech Recognition

We include modified files in ESPnet for hidden representation mixup strategy. Look for comments with "mixup" words. 
We also include configurations file to the experiments we run in the paper, these are:

## WSJ Configurations (egs2/wsj/asr1/conf)

<b> baseline </b>: is22_baseline__wspecaug_noFM_run1.yaml

<b> mixup 0-th layer </b>: *is22_baseline_mixup0_wspecaug_noFM_tau0.15_mixcoeff2.0_run1.yaml*

<b> mixup 9-th layer </b>: *is22_baseline_mixup9_wspecaug_noFM_tau0.15_mixcoeff2.0_run1.yaml*

<b> mixup 0-th and 9-th layer </b>: *is22_baseline_mixup0,9_wspecaug_noFM_tau0.15_mixcoeff2.0_run1.yaml*

## SWBD Configurations (egs2/swbd/asr1/conf)

<b> For 40-hours subset </b>

<b> baseline </b>: *is22_noaug_4gpu_eighth_baseline_wspecaug_noFM_run0.yaml*

<b> mixup 0-th layer </b>: *is22_noaug_4gpu_eighth_mixup0_wspecaug_noFM_tau0.45_mixcoeff2.0_run0.yaml*

<b> mixup 0-th and 5-th layer </b>: *is22_noaug_4gpu_eighth_mixup0,5_wspecaug_noFM_tau0.45_mixcoeff2.0_run0.yaml*

<b> mixup 0-th and 9-th layer </b>: *is22_noaug_4gpu_eighth_mixup0,9_wspecaug_noFM_tau0.45_mixcoeff2.0_run0.yaml*

\*80-hours subset uses the same setup as 40-hours, except training data is larger
