```bash
git clone https://github.com/chunyuan-w/pytorch.git
cd pytorch && chunyuan/llm_cpp_wrapper && python setup.py develop
pip install transformers==4.26.1
numactl -C 0-55 python run_dynamo_gptj.py
```
