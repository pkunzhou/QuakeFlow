```
python download_waveform.py
python run_phasenet.py
python run_gamma.py
python convert_hypodd.py && bash run_hypodd_ct.sh
python cut_template.py && python run_cctorch.py
python convert_hypodd.py --dtcc && bash bash run_hypodd_cc.sh
python convert_growclust.py && bash run_growclust.sh
```