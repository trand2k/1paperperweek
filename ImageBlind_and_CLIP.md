# Mutimodal embedding model
ImageBlind and CLIP is 2 multimodal embedding model

ImageBlind repo: https://github.com/facebookresearch/ImageBind

CLIP repo: https://github.com/openai/CLIP

Key-idea of ImageBlind and CLIP is trainning an embedding model can take various input type in to same vector space. 

With CLIP , it is image and text

With ImageBlind, It is Depth, text, heat-map, audio, IMU , image/video

This idea is interesting, trainning process have same idea with some face reg model. embedding various input type into an vector space, try to optimize distance of them if it mentioned to same thing. Using tripet loss or sth like that .... 

Maybe, It's not so much effect now, but i thought it is protential way, this kind of model can use for muti-modal LLM retrieval, or use as an backbone for tranning some down-stream task. 

My thought:
- i have big question, can human feeling about a dog, a cat without sight ? Yes, of course, human understand evironment not base on only sight, hearing or tactile. 
- AI can be more likely human if can fusion any sence for another specific task
- 2 paper give protential way for fusion sensor, it helpful for self-driving car or human-robot ,.... some applicaion need more information than just image or text,... 


