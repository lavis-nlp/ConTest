# ConTest
This repository provides evaluation code and link to our ConTest dataset.

Evaluation code and detailed instructions will be up soon, until then you can access the dataset via huggingface dataset library:

First install datasets library:
```python
pip install datasets
```

To access one of the versions of the dataset execute one of the following:
```python
from datasets import load_dataset
raw_dataset = load_dataset('jdepoix/junit_test_completion', 'raw')
tokenized_dataset = load_dataset('jdepoix/junit_test_completion', 'tokenized')
ast_dataset = load_dataset('jdepoix/junit_test_completion', 'ast_encoded')
ast_project_dataset = load_dataset('jdepoix/junit_test_completion', 'ast_encoded', split_type='project_based')
```

