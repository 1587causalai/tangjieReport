{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {
    "Collapsed": "false"
   },
   "source": [
    "# 项目概览\n",
    "\n",
    "这是一个信息因果模型(ICM)的报告准备项目。我期望在这个项目中，把信息因果模型的理论构架阐述清楚 (某种意义下 VAE， Bayesian network, RNN 等都是 ICM 的特例)。\n",
    "我尽量避免直接写公式给新接触的人看，多数时候公式可能把创造的动机给掩盖掉，同时让问题是否能 tractable 变得不那么清晰。我想说清楚的是信息因果模型的动机和背后的问题。"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {
    "Collapsed": "false"
   },
   "source": [
    "几个问题需要回答：\n",
    "\n",
    "- 当前因果理论研究的故事，包括\n",
    "    - 为什么要研究因果？\n",
    "    - 历史上有哪些人做了哪些研究？\n",
    "    - 当前因果问题的进展如何？\n",
    "    - 重点突出遇到了有环因果问题，为什么必须解决它？\n",
    "    \n",
    "- 提出我们解决问题的思路 --- Causality as information transfer\n",
    "    - 是什么启发了把信息传递当成因果？Causality for machine learning\n",
    "    - 当前有哪些工作，他们是如何做的？哲学上，causality free will and neuroscience\n",
    "    - 我们的具体做法(Info Causal Models)是什么样子的？为什么这么做？使用 predictive coding, pyro models with gates.\n",
    "    - 有了 ICM 之后，三级因果思维对应的因果语义是什么样子？\n",
    "    \n",
    "- 使用例子来说明我们的模型 ICM\n",
    "    - 简单两个节点的模型，包括单向边，一个简单闭环。\n",
    "    - 对比其他的因果模型，prons and cons.\n",
    "    - 因果语义"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {
    "Collapsed": "false"
   },
   "source": [
    "## About Causal AI"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {
    "Collapsed": "false"
   },
   "source": [
    "Causal AI 是具备因果推理能力，旨在通过小图灵测试的 AI 系统。\n",
    "\n",
    "Judea Pearl 是 Causal AI 的奠基人，Bernhard Scholkopf 推进了 Causality for Machine Learning，Yoshua Bengio 提出了 System 2 deep learning 作为 Causal AI 的一个范式。沉醉于 life and Intelligence 之美，尤其是人类社会系统的群体智能。众多工具中（包括数学，计算机，物理，复杂系统等等），偏好用信息论视角研究如何教会机器因果思维，希望创造具备 free will 的 AI，使之成为我们的良师益友，一起探索解密生命和智能的终极奥秘。\n",
    "\n",
    "https://github.com/CausalAI/AboutCausalAI\n",
    "\n",
    "\n",
    "+++++++++++++ Mini Turing Test +++++++++++++++\n",
    "\n",
    "> How can machines represent causal knowledge in a way that would enable them to access the necessary information swiftly, answer questions correctly, and do it with ease, as a human can? "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {
    "Collapsed": "false"
   },
   "source": []
  },
  {
   "cell_type": "markdown",
   "metadata": {
    "Collapsed": "false"
   },
   "source": []
  },
  {
   "cell_type": "markdown",
   "metadata": {
    "Collapsed": "false"
   },
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "Collapsed": "false"
   },
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.4"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
