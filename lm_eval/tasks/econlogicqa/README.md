# EconLogicQA

### Paper

Title: `EconLogicQA: A Question-Answering Benchmark for Evaluating Large Language Models in Economic Sequential Reasoning`

Abstract: https://arxiv.org/abs/2405.07938

EconLogicQA is a dataset designed to evaluate and benchmark various LLMs in sequential reasoning capabilities 
through sorting questions derived from economics news.

Homepage: https://huggingface.co/datasets/yinzhu-quan/econ_logic_qa


### Citation

```
@misc{quan2024econlogicqa,
      title={EconLogicQA: A Question-Answering Benchmark for Evaluating Large Language Models in Economic Sequential Reasoning}, 
      author={Yinzhu Quan and Zefang Liu},
      year={2024},
      eprint={2405.07938},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```

### Tasks

* `econ_logic_qa_generative`: EconLogicQA text generation task 


### Checklist

For adding novel benchmarks/datasets to the library:
* [x] Is the task an existing benchmark in the literature?
  * [x] Have you referenced the original paper that introduced the task?
  * [x] If yes, does the original paper provide a reference implementation? If so, have you checked against the reference implementation and documented how to run such a test?


If other tasks on this dataset are already supported:
* [ ] Is the "Main" variant of this task clearly denoted?
* [ ] Have you provided a short sentence in a README on what each new variant adds / evaluates?
* [ ] Have you noted which, if any, published evaluation setups are matched by this variant?
