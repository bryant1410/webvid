# WebVid Dataset
### [Project Page](https://www.robots.ox.ac.uk/~vgg/research/frozen-in-time/) |  [Dataset Page](https://m-bain.github.io/webvid-dataset/)  |   [Demo (Live Search)](http://meru.robots.ox.ac.uk/frozen-in-time/)

Large-scale text-video dataset, **containing 10 million video-text pairs** scraped from the web. This dataset was used for large-scale pretraining to achieve state-of-the-art end-to-end retrieval in our frozen-in-time work: the code of which can be found [here](https://github.com/m-bain/frozen-in-time)

2.5M Subset

- [train](http://www.robots.ox.ac.uk/~maxbain/webvid/results_2M_train.csv) (640MB)

`wget http://www.robots.ox.ac.uk/~maxbain/webvid/results_2M_train.csv`


- [val](http://www.robots.ox.ac.uk/~maxbain/webvid/results_2M_val.csv) (1.3MB)

`wget http://www.robots.ox.ac.uk/~maxbain/webvid/results_2M_val.csv`


10M

- (Coming Soon)


## Disclaimer

We note that data sourced from the web may be prone to biases and may contain graphic content. Please be careful of unintended societal, gender, racial and other biases when training or deploying models trained on this data.

## Cite

If you use this dataset in your research, please cite:


[Frozen in Time: A Joint Video and Image Encoder for End-to-End Retrieval](https://arxiv.org/abs/2104.00650)

Max Bain, Arsha Nagrani, Gül Varol, Andrew Zisserman.
```bibtex
@misc{bain2021frozen,
      title={Frozen in Time: A Joint Video and Image Encoder for End-to-End Retrieval}, 
      author={Max Bain and Arsha Nagrani and Gül Varol and Andrew Zisserman},
      year={2021},
      eprint={2104.00650},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```


## FAQs

**Q1**: Can you provide the original videos for download?

**A1**: Since we do not own the videos in the dataset, we cannot legally provide them to you. The video owner(s) can choose to delete it at anytime, in which case the video will no longer be available in the dataset. Due to this, unfortunately, some videos in the dataset will be lost over time, and we are unable to help with this issue. However, the sources are official and we expect the large majority of videos to be available for the forseeable future.
###

**Q2**: Is it normal that a subset of videos cannot be retrieved from the provided URLs?

**A2**: Yes. See Q1.

###

**Q3**: Can you provide download scripts in this repository?

**A3**: No, contact me privately if you need advice on how to download.

###

**Q4**: I noticed there are watermarks on the videos, how will this affect training?

**A4**: We found we were still able to achieve top performance (with the watermarks) on downstream text-to-video retrieval, both for finetuning and zero-shot settings. We expect similar results on other video language tasks but didn't test these in the paper. If you do use this dataset for other video-language tasks, we'd be interested to hear how it goes.

## Contact Us

If you have a question not provided in the FAQs above, please create an issue in this repository. 

If you would like to share feedback or report concerns, please email me at maxbain@robots.ox.ac.uk
