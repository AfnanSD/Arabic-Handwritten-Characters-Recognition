# Arabic-Handwritten-Characters-Recognition

A ViTB16 feature extractor computer vision model to classify hand written Arabic letters

- dataset used: [Arabic Handwritten Characters Dataset](https://www.kaggle.com/datasets/mloey1/ahcd1/data)
  - 16,800 characters written by 60 participants
  - The age range is between 19 to 40 years
  - 90% of participants are right-hand
- picked model: [ViTB16](https://pytorch.org/vision/main/models/generated/torchvision.models.vit_b_16.html) (The model picked based on the highest accuracy reached, which can be seen in the experiements section)
- deployed at HuggingFace and can be tried [here](https://huggingface.co/spaces/AfnanSD/Arabic-Handwritten-Characters-Recognition)
