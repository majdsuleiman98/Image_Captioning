<p align="justify">
### Image Captioning Project

In this project, I explored various deep learning architectures to address the image captioning problem, achieving promising results across different models.

### 1.1. Architecture: Encoder-Decoder
The Encoder-Decoder architecture, often referred to as the "Inject" model, is a foundational approach for image captioning. It directly connects the Image Feature Encoder to the Sequence Decoder, followed by a Sentence Generator. In this method, image features are first encoded, and this encoded information is then utilized to generate descriptive sentences.

### 1.2. Architecture: Multi-Modal
The Multi-Modal architecture presents an alternative to the Inject approach and has demonstrated superior performance in image captioning tasks. In this model, the Image Encoder and Sequence Decoder operate independently. The Image Encoder processes only the visual data, while the Sequence Decoder handles the text sequence generation. By keeping the processing of images and text separate, the architecture enhances the quality of the generated captions.
- The CNN network exclusively processes the image.
- The LSTM network operates solely on the sequence generated so far.

### 1.3. Architecture: Transformer with Encoder-Decoder
In the realm of image captioning, the Transformer-based Encoder-Decoder architecture has become a prominent choice, particularly for its use of Attention mechanisms. This approach diverges from traditional Recurrent Networks by employing Transformers, which excel in capturing contextual relationships within data. By focusing on objects in the image and their spatial relationships, this architecture produces accurate and contextually rich descriptions. Vision Transformer (VIT) can also be integrated instead of a traditional CNN to further enhance performance.

### 1.4. Architecture: Attention with Encoder-Decoder
The "Attention with Encoder-Decoder" architecture has gained significant traction in Natural Language Processing (NLP) due to its ability to improve performance through Attention mechanisms. In this architecture, as each word in the caption is generated, the Attention model focuses on the most relevant parts of the image corresponding to that word. This targeted focus allows the model to produce more precise and contextually appropriate captions, making it a powerful approach for image captioning tasks.
</p>
