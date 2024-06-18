# Mutimodal embedding model
ImageBind and CLIP are two multimodal embedding models.

- ImageBlind repo: https://github.com/facebookresearch/ImageBind

- CLIP repo: https://github.com/openai/CLIP

The key idea behind ImageBind and CLIP is training an embedding model that can take various input types and map them into the same vector space.

- With CLIP, the inputs are images and text.

- With ImageBind, the inputs include depth, text, heat maps, audio, IMU data, and images/videos.

This concept is intriguing. The training process is similar to some face recognition models that embed various input types into a vector space and optimize their distances if they refer to the same entity, often using triplet loss or similar techniques. While the current impact might not be significant, this approach has potential. Such models can be used for multimodal LLM retrieval or as a backbone for training downstream tasks.

### My thoughts:

- Can humans understand a dog or a cat without sight? Yes, of course. Humans comprehend their environment using not just sight but also hearing, touch, and other senses.
- AI can become more human-like if it can fuse various senses for specific tasks.
- These two papers offer a potential method for sensor fusion, which could be beneficial for applications like self-driving cars or human-robot interactions—situations where more information than just images or text is needed.

