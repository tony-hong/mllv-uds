# Seminar: Machine Learning for Language and Vision

## News

If you are interested, please send [Xudong Hong](mailto:xhong@coli.uni-saarland.de) an email to register for this seminar. 

## Introduction

Welcome to our seminar on "Machine Learning for Language and Vision." We are excited to delve into the fascinating intersection of these two domains and explore how recent advancements have significantly impacted both research and practical applications. This seminar aims to provide you with a comprehensive understanding of state-of-the-art techniques, covering topics such as pre-training for images and videos, multitask learning, parameter efficiency, generative models, and reinforcement learning.

We will discuss groundbreaking research papers that have contributed to the current landscape of machine learning for language and vision. These papers showcase various techniques, including bootstrapping language-image pre-training, learning transferable visual models from natural language supervision, and neural script knowledge through vision, language, and sound. We will also explore the unification of vision-and-language tasks via text generation, multimodal multitask learning with unified transformers, and parameter-efficient transfer learning approaches. Moreover, we will investigate generative models, such as high-resolution image synthesis with latent diffusion models and the latest GPT model, GPT-4. Finally, we will examine reinforcement learning's role in visual storytelling.

By the end of this seminar, you will have a solid grasp of the latest developments in machine learning for language and vision, as well as an understanding of how these techniques can be applied to a variety of tasks and domains. We hope that this seminar will inspire you to explore further research and practical applications in this exciting interdisciplinary field.

## Topics

We will discuss the following topics:

### Pre-training - Image

- Li, J., Li, D., Xiong, C. and Hoi, S., 2022, June. [Blip: Bootstrapping language-image pre-training for unified vision-language understanding and generation](https://arxiv.org/abs/2201.12086). In *International Conference on Machine Learning* (pp. 12888-12900). PMLR.
- Radford, A., Kim, J.W., Hallacy, C., Ramesh, A., Goh, G., Agarwal, S., Sastry, G., Askell, A., Mishkin, P., Clark, J. and Krueger, G., 2021, July. [Learning transferable visual models from natural language supervision](http://proceedings.mlr.press/v139/radford21a). In International conference on machine learning (pp. 8748-8763). PMLR.

### Pre-training - Video

- Zellers, R., Lu, J., Lu, X., Yu, Y., Zhao, Y., Salehi, M., Kusupati, A., Hessel, J., Farhadi, A. and Choi, Y., 2022. [Merlot reserve: Neural script knowledge through vision and language and sound](http://openaccess.thecvf.com/content/CVPR2022/html/Zellers_MERLOT_Reserve_Neural_Script_Knowledge_Through_Vision_and_Language_and_CVPR_2022_paper.html). In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition* (pp. 16375-16387).
- Zellers, R., Lu, X., Hessel, J., Yu, Y., Park, J.S., Cao, J., Farhadi, A. and Choi, Y., 2021. [Merlot: Multimodal neural script knowledge models](https://proceedings.neurips.cc/paper/2021/hash/c6d4eb15f1e84a36eff58eca3627c82e-Abstract.html). *Advances in Neural Information Processing Systems*, *34*, pp.23634-23651.

### Multitask Learning

- Cho, J., Lei, J., Tan, H. & Bansal, M.. (2021). [Unifying Vision-and-Language Tasks via Text Generation](https://proceedings.mlr.press/v139/cho21a.html). *Proceedings of the 38th International Conference on Machine Learning*, in *Proceedings of Machine Learning Research* 139:1931-1942
- Hu, R. and Singh, A., 2021. [Unit: Multimodal multitask learning with a unified transformer](https://openaccess.thecvf.com/content/ICCV2021/html/Hu_UniT_Multimodal_Multitask_Learning_With_a_Unified_Transformer_ICCV_2021_paper.html?ref=https://githubhelp.com). In Proceedings of the IEEE/CVF International Conference on Computer Vision (pp. 1439-1449).

### Parameter Efficiency - Prompt Tuning

- Tsimpoukelli, M., Menick, J.L., Cabi, S., Eslami, S.M., Vinyals, O. and Hill, F., 2021. [Multimodal few-shot learning with frozen language models](https://proceedings.neurips.cc/paper/2021/hash/01b7575c38dac42f3cfb7d500438b875-Abstract.html). Advances in Neural Information Processing Systems, 34, pp.200-212.
- Yu, Y., Chung, J., Yun, H., Kim, J. and Kim, G., 2021. [Transitional adaptation of pretrained models for visual storytelling](https://openaccess.thecvf.com/content/CVPR2021/html/Yu_Transitional_Adaptation_of_Pretrained_Models_for_Visual_Storytelling_CVPR_2021_paper.html). In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (pp. 12658-12668).

### Parameter Efficiency - Adapters

- Sung, Y.L., Cho, J. and Bansal, M., 2022. [Vl-adapter: Parameter-efficient transfer learning for vision-and-language tasks](https://openaccess.thecvf.com/content/CVPR2022/html/Sung_VL-Adapter_Parameter-Efficient_Transfer_Learning_for_Vision-and-Language_Tasks_CVPR_2022_paper.html). In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (pp. 5227-5237).
- Sung, Y.L., Cho, J. and Bansal, M., 2022. [LST: Ladder Side-Tuning for Parameter and Memory Efficient Transfer Learning](https://openreview.net/forum?id=isPnnaTZaP5). In *Advances in Neural Information Processing Systems 2022*.

### Parameter Efficiency - Prefix-Tuning

- Zhang, Z., Guo, W., Meng, X., Wang, Y., Wang, Y., Jiang, X., Liu, Q. and Yang, Z., 2022. [Hyperpelt: Unified parameter-efficient language model tuning for both language and vision-and-language tasks](https://arxiv.org/abs/2203.03878). arXiv preprint arXiv:2203.03878.

### Generative Model - Diffusion

- Rombach, R., Blattmann, A., Lorenz, D., Esser, P. and Ommer, B., 2022. [High-resolution image synthesis with latent diffusion models.](https://openaccess.thecvf.com/content/CVPR2022/html/Rombach_High-Resolution_Image_Synthesis_With_Latent_Diffusion_Models_CVPR_2022_paper.html) In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition* (pp. 10684-10695).

### Generative Model - GPT

- OpenAI, 2023. GPT-4. Available at: [https://openai.com/research/gpt-4](https://openai.com/research/gpt-4). March 14, 2023.
    - (Optional) OpenAI (2023). [GPT-4 Technical Report](https://arxiv.org/abs/2303.08774). ArXiv, abs/2303.08774.
- Wu, C., Yin, S., Qi, W., Wang, X., Tang, Z. and Duan, N., 2023. [Visual 
chatgpt: Talking, drawing and editing with visual foundation models](https://arxiv.org/abs/2303.04671). *arXiv preprint arXiv:2303.04671.*

### Reinforcement Learning

- Hu, J., Cheng, Y., Gan, Z., Liu, J., Gao, J. and Neubig, G., 2020, April. [What makes a good story? designing composite rewards for visual storytelling](https://ojs.aaai.org/index.php/AAAI/article/view/6305). In Proceedings of the AAAI Conference on Artificial Intelligence (Vol. 34, No. 05, pp. 7969-7976).

If you know about an interesting paper, you can also propose it in the registration email. 

## Contact

If you have any questions or concerns, please contact us via email. We look forward to seeing you at the discussion!

**Xudong Hong**: xhong@coli.uni-saarland.de

**Ruitao Feng**: fruitao@coli.uni-saarland.de

## (The following is under construction. Please stay tuned. )

## Discussion Format

We will have a group discussion on each paper, where participants can share their thoughts and insights on the research. The discussion will be led by a moderator who will facilitate the conversation and keep the discussion on topic.

## Date and Time

The date and time for the discussion will be determined soon. Please stay tuned for updates.

## Requirement
Students should have a basic understanding of natural language processing and computer vision concepts. Additionally, they should be familiar with deep learning models and have some experience in programming with Python. Students are expected to actively engage in discussions and critically analyze the papers presented during the seminar. They are also encouraged to share their own insights and perspectives on the topics covered.
