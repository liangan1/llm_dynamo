```bash
git clone https://github.com/liangan1/pytorch.git
cd pytorch && git checkout gh/XiaobingSuper/80/head && python setup.py develop
pip install transformers==4.26.1
numactl -C 0-55 python run_dynamo_gptj.py
```
