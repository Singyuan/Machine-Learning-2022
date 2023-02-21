# HW 7 -  Question Answering
**Just run jupyter notebook on Colab pro+.**
## The method I used to pass the strong baselines includes

1. Use model 'hfl/chinese-macbert-large'
2. decrease doc_stride
3. Change learning rate [website](https://huggingface.co/transformers/v2.0.0/_modules/transformers/optimization.html)
4. apply random select preprocessing [website](https://zhuanlan.zhihu.com/p/398953990)
5. apply postprocessing [website](https://huggingface.co/course/chapter6/3)
6. Use gradient accumulation [website](https://cowarder.site/2019/10/29/Gradient-Accumulation)