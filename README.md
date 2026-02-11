
# 🌿 Plant-Species-Image-Classification

## A. Project Overview

This project focuses on building an image classification model for commonly used **Philippine medicinal plants**. The dataset consists of plant images collected from online sources and organized into 20 different plant species classes.

The purpose of this project is to train a machine learning model capable of accurately identifying medicinal plants based on visual features such as leaf shape, color, texture, and structure. This project demonstrates the application of image classification techniques in agriculture, healthcare, and educational contexts.

---

## B. Plant Species

Below are the 20 medicinal plant species included in the dataset. Each class contains representative images used for training and evaluation.

### 1. Oregano
![Oregano](images/oregano.jpg)
- **Scientific Name:** *Plectranthus amboinicus*
- **Description:** A medicinal herb commonly used in the Philippines to treat coughs, colds, and respiratory conditions.

### 2. Peppermint
![Peppermint](images/peppermint.jpg)
- **Scientific Name:** *Mentha × piperita*
- **Description:** An aromatic plant used for digestion relief and as a natural remedy for headaches.

### 3. Clove
![Clove](images/clove.jpg)
- **Scientific Name:** *Syzygium aromaticum*
- **Description:** A flowering plant whose dried flower buds are used for pain relief and oral health.

### 4. Hilbas
![Hilbas](images/hilbas.jpg)
- **Scientific Name:** *Artemisia vulgaris*
- **Description:** Traditionally used to reduce inflammation and treat digestive issues.

### 5. Mango Leaves
![Mango Leaves](images/mango_leaves.jpg)
- **Scientific Name:** *Mangifera indica*
- **Description:** Leaves are used in traditional medicine for diabetes and respiratory problems.

### 6. Pandan
![Pandan](images/pandan.jpg)
- **Scientific Name:** *Pandanus amaryllifolius*
- **Description:** Known for its fragrance and medicinal properties for pain and headaches.

### 7. Aloe Vera
![Aloe Vera](images/aloe_vera.jpg)
- **Scientific Name:** *Aloe vera*
- **Description:** Widely used for skin treatment, burns, and wound healing.

### 8. Anise
![Anise](images/anise.jpg)
- **Scientific Name:** *Pimpinella anisum*
- **Description:** Used to aid digestion and relieve bloating.

### 9. Calamansi
![Calamansi](images/calamansi.jpg)
- **Scientific Name:** *Citrus microcarpa*
- **Description:** A native citrus fruit used for immunity and respiratory relief.

### 10. Ampalaya
![Ampalaya](images/ampalaya.jpg)
- **Scientific Name:** *Momordica charantia*
- **Description:** Known for helping regulate blood sugar levels.

### 11. Guyabano Leaves
![Guyabano Leaves](images/guyabano_leaves.jpg)
- **Scientific Name:** *Annona muricata*
- **Description:** Traditionally used to boost immunity and promote relaxation.

### 12. Banana Leaves
![Banana Leaves](images/banana_leaves.jpg)
- **Scientific Name:** *Musa spp.*
- **Description:** Used in traditional medicine and food preparation.

### 13. Santol Leaves
![Santol Leaves](images/santol_leaves.jpg)
- **Scientific Name:** *Sandoricum koetjape*
- **Description:** Leaves are used for digestive and anti-inflammatory remedies.

### 14. Guava Leaves
![Guava Leaves](images/guava_leaves.jpg)
- **Scientific Name:** *Psidium guajava*
- **Description:** Commonly used for treating diarrhea and wound cleansing.

### 15. Ipil-Ipil Leaves
![Ipil-Ipil Leaves](images/ipil_ipil_leaves.jpg)
- **Scientific Name:** *Leucaena leucocephala*
- **Description:** Used for antibacterial and anti-inflammatory purposes.

### 16. Kangkong
![Kangkong](images/kangkong.jpg)
- **Scientific Name:** *Ipomoea aquatica*
- **Description:** A leafy vegetable with nutritional and medicinal value.

### 17. Alugbati
![Alugbati](images/alugbati.jpg)
- **Scientific Name:** *Basella alba*
- **Description:** Used for digestive health and skin conditions.

### 18. Lemongrass
![Lemongrass](images/lemongrass.jpg)
- **Scientific Name:** *Cymbopogon citratus*
- **Description:** Known for its antibacterial and calming properties.

### 19. Malunggay
![Malunggay](images/malunggay.jpg)
- **Scientific Name:** *Moringa oleifera*
- **Description:** Highly nutritious plant used to boost immunity.

### 20. Ginseng
![Ginseng](images/ginseng.jpg)
- **Scientific Name:** *Panax ginseng*
- **Description:** Used to increase energy and improve overall health.

---

## C. Model Training Details

The image classification model was trained using the following parameters:

- **Epochs:** 40  
- **Batch Size:** 32  
- **Learning Rate:** 0.001  
- **Number of Images per Class:** Approximately 300 images per plant species  

These parameters were selected to balance learning efficiency, model accuracy, and prevention of overfitting.

---

## D. Model Evaluation

The model’s performance was evaluated using standard classification metrics.

### Evaluation Outputs:
- **Confusion Matrix**
- **Accuracy per Class**
- **Overall Model Accuracy**

### Screenshots:
![Confusion Matrix](results/confusion_matrix.png)

![Accuracy per Class](results/accuracy_per_class.png)

![Overall Accuracy](results/overall_accuracy.png)

---

## 📌 Conclusion

The trained model demonstrates effective classification of Philippine medicinal plants and can serve as a foundation for future applications such as mobile plant identification systems and educational tools.
