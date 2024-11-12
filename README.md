# Amazon-ML-Challenge-2024
Build an AI system that  extracts the entities such as iterm_weight,item_width,voltaage from images.

This capability is crucial in fields like healthcare, e-commerce where precise product information and many products lack detailed textual descriptions, making it essential to obtain key details directly from images.     

These images provide important information such as weight, volume,voltage, wattage, dimensions,  
and many more, which are critical for digital stores.

Approach:

-Fine-tuned PaliGemma Vision model on 5,000 product images using LoRA (Low-Rank Adaptation)
 technique for efficient finetuning.  
-Achieved 0.70 F1 score through fine-tuning, compared to base model’s 0.59.  

Technical Stack:  
- **Transformers Library**: Hugging Face Transformers    
- **Model Fine-tuning**: PEFT (Parameter-Efficient Fine-Tuning)   
- **Model Quantization**: BitsandBytes   
- **Data Processing**: Pandas, NumPy  
- **Image Processing**: PIL (Pillow)  
- **Model Training**: Hugging Face Trainer  
- **Experiment Tracking**: Weights & Biases (W&B)     


