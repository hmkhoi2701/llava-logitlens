# LLaVA Interpretability

Logit Lens from the paper, [Towards Interpreting Visual Information Processing in Vision-Language Models](https://arxiv.org/abs/2410.07149).

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/clemneo/llava-interp
   cd llava-interp


2. Install required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
* `create_logit_lens.py` Run the model and create interative logit lens HTMLs for a set of images.
* Paste the HTML content on a dedicated website, say [https://www.codechef.com/html-online-compiler](https://www.codechef.com/html-online-compiler) and try the interactive results.

## Citation
```
@misc{neo2024interpretingvisualinformationprocessing,
      title={Towards Interpreting Visual Information Processing in Vision-Language Models}, 
      author={Clement Neo and Luke Ong and Philip Torr and Mor Geva and David Krueger and Fazl Barez},
      year={2024},
      eprint={2410.07149},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2410.07149}, 
}
```
