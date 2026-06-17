# NatDisasterRank

This project takes an aerial image of a disaster-affected area and divides it into 12 grid sections. Each grid is then ranked from 1 to 12 based on urgency, helping first responders identify which areas may need aid the most.

To build the image-based scoring system, I trained and evaluated both a CNN-based model and a Vision Transformer model on a combined dataset of approximately 15,000 disaster and non-disaster images. The data was split into 70% training, 15% validation, and 15% testing. Both models achieved strong performance across the evaluation metrics, and the results, graphs, and code are included below.