# Image-Captioner 
🚀 *Turning pictures into words, one caption at a time!*  
This project showcases an **Image Captioning System** that combines the power of **ResNet50** 
for image feature extraction and an **LSTM-based decoder** to generate captions.   
Trained on the **Flickr8k dataset**, it crafts meaningful, grammatically correct descriptions of images and even supports custom inputs for real-time captioning.

## Snorkelling Adventure!🌊
**Here’s me, going snorkeling for the first time ever! 🐠**    
<img width="400" alt="Picture 2" src="https://github.com/user-attachments/assets/60b72091-775f-4d5a-a747-66fadaed4335">

**💬 And here’s what my Image Captioner thought of it!**  
<img width="526" alt="Screenshot 2024-12-09 at 3 14 47 PM" src="https://github.com/user-attachments/assets/85f9b7d8-74aa-40ad-912b-f712a91af37c">  
***Happy Indeed!*** ✨
## Features  
✨ ResNet50 + LSTM Combo: Extracts image features and generates descriptive captions.  
✨ Custom Image Support: Upload your own images and get captions instantly.  
✨ Grammatically Fluent: Produces captions that are coherent and human-like.  
## How it works  
1. Feature Extraction:  
Uses **ResNet50** (pre-trained on ImageNet) to pull out the best features from your images.
2. Caption Generation:  
Feeds those features to an **LSTM-based decoder**, which crafts the perfect caption for your image.
## Academic Insights  
### Model Performance:  
While the model produces grammatically correct captions, its ability to identify specific objects can be influenced by dataset bias. For example, it occasionally misidentifies objects, such as labeling a cat as a dog.
### Limitations:  
The Flickr8k dataset is relatively small, limiting the model's ability to generalize to diverse scenarios.  
### Future Directions:  
Train on larger datasets like MS COCO for improved diversity.  
Explore Transformer-based decoders for more context-aware captioning.  
Incorporate techniques like data augmentation and contrastive learning to mitigate bias.  
## Final Report  
📄 The detailed final report for this project, which includes methodology, 
analysis, and findings, has been uploaded as a PDF file in this repository. 
Refer to it for in-depth insights into the model's design and performance evaluation.  
## Conclusion  
This project demonstrates the potential of deep learning in bridging the gap between vision and language. 
While the model generates coherent and grammatically correct captions, its limitations, such as dataset bias and misidentifications, 
highlight opportunities for improvement. With future enhancements like training on larger datasets and adopting advanced architectures, 
this system can evolve into a more robust and accurate image captioning solution.  
🤖 Built with TensorFlow and Passion for AI.      
🎓 *Developed as part of an academic project to explore the synergy between vision and language.*


