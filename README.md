# instagram_filter_real_ai
Repo for the paper about "Instagram-like filters for AI-generated and real photos".


## preparation
Go to the evaluation folder and run `./download.sh`, which will download and extract all images (real and AI generated)

## requirements

* python3 and jupyter notebook, the code is only tested under ubuntu 24.04
* uv for clip embeddings

The code for the embedding extraction is taken from my repository for [CLIPSE](https://github.com/stg7/clipse) and added in the subfolder (`embeddings`) for completeness.
The image feature tool is taken from my repo [sophoappeal_image_features_tool](https://github.com/Telecommunication-Telemedia-Assessment/sophoappeal_image_features_tool) with added files for uv to be used.


## acknowledgments :book:
If you use this software in your research, please include a link to the repository and reference the following paper:

```bibtex
@article{goering2026insta,
  author       = {Göring, Steve and Rao, Rakesh},
  date         = {2026},
  note         = {in review},
  title        = {Instagram-like filters for AI-generated and real photos},
}
```

If you like the software that I develop and contribute, you can [donate me a :coffee:](https://ko-fi.com/binarys3v3n).
 
Because :coffee: is a fundamental source for energy and motivation :smile:.


## license

[MIT License](LICENSE)

