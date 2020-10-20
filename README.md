To learning
* !python /content/drive/My\ Drive/Colab\ Notebooks/audio-super-res-py3/src/run.py train --train /content/drive/My\ Drive/Colab\ Notebooks/audio-super-res-py3/data/vctk/speaker1/vctk-speaker1-train.h5 --val /content/drive/My\ Drive/Colab\ Notebooks/audio-super-res-py3/data/vctk/speaker1/vctk-speaker1-val.h5 -e 200 --batch-size 64 --lr 3e-4 --logname /content/drive/My\ Drive/Colab\ Notebooks/audio-super-res-py3/src/singlespeaker

To inference
* !python /content/drive/My\ Drive/Colab\ Notebooks/audio-super-res-py3/src/run.py eval --logname /content/drive/My\ Drive/Colab\ Notebooks/audio-super-res-py3/src/saveFile/model.ckpt-0000 --out-label singlespeaker-out --wav-file-list /content/drive/My\ Drive/Colab\ Notebooks/audio-super-res-py3/data/vctk/speaker1/speaker1-val-files.txt --r 4
