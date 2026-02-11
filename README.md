
# 🌿 Plant-Species-Image-Classification

## A. Project Overview

This project focuses on building an image classification model for commonly used **Philippine medicinal plants**. The dataset consists of plant images collected from online sources and organized into 20 different plant species classes.

The purpose of this project is to train a machine learning model capable of accurately identifying medicinal plants based on visual features such as leaf shape, color, texture, and structure. This project demonstrates the application of image classification techniques in agriculture, healthcare, and educational contexts.

---

## B. Plant Species

Below are the 20 medicinal plant species included in the dataset. Each class contains representative images used for training and evaluation.

### 1. Oregano
![Oregano](https://i.herbalreality.com/wp-content/uploads/2023/10/18162340/Oregano-Origanum-vulgare-1300x975.jpeg)
- **Scientific Name:** *Plectranthus amboinicus*
- **Description:** A medicinal herb commonly used in the Philippines to treat coughs, colds, and respiratory conditions.

### 2. Peppermint
![Peppermint](https://cdn.mos.cms.futurecdn.net/TBk4mufJgZZ4jSbW4K6Raj-1280-80.jpg.webp)
- **Scientific Name:** *Mentha × piperita*
- **Description:** An aromatic plant used for digestion relief and as a natural remedy for headaches.

### 3. Clove
![Clove](https://cdn.mos.cms.futurecdn.net/dD52bNpiVsDi4fPkGFB6bL-1236-80.jpg.webp)
- **Scientific Name:** *Syzygium aromaticum*
- **Description:** A flowering plant whose dried flower buds are used for pain relief and oral health.

### 4. Hilbas
![Hilbas](https://imgs.search.brave.com/LJOSvl42g6sFhRY23xnUU5aw9Syqg36coOdAJZN6OvU/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9zZWVk/dmlsbGV1c2EuY29t/L2Nkbi9zaG9wL2Zp/bGVzL3NodXR0ZXJz/dG9ja18yMzE2MTI4/ODc3c20uanBnP3Y9/MTczMjY0OTkxMCZ3/aWR0aD0xNDQ1)
- **Scientific Name:** *Artemisia vulgaris*
- **Description:** Traditionally used to reduce inflammation and treat digestive issues.

### 5. Mango Leaves
![Mango Leaves](https://m.media-amazon.com/images/I/61VHiFHiEmL._AC_SL400_.jpg)
- **Scientific Name:** *Mangifera indica*
- **Description:** Leaves are used in traditional medicine for diabetes and respiratory problems.

### 6. Pandan
![Pandan](https://www.vietworldkitchen.com/wp-content/uploads/2008/10/pandan-1.jpg)
- **Scientific Name:** *Pandanus amaryllifolius*
- **Description:** Known for its fragrance and medicinal properties for pain and headaches.

### 7. Aloe Vera
![Aloe Vera](https://cdn.britannica.com/73/177473-050-7B7C6918/aloe-vera-plant.jpg)
- **Scientific Name:** *Aloe vera*
- **Description:** Widely used for skin treatment, burns, and wound healing.

### 8. Anise
![Anise](https://cdn.mos.cms.futurecdn.net/dVWrYx3S2bjo2keSZBvPCS-1200-80.jpg)
- **Scientific Name:** *Pimpinella anisum*
- **Description:** Used to aid digestion and relieve bloating.

### 9. Calamansi
![Calamansi](https://bacolodpages.com/sites/default/files/styles/480x480/public/products/Calamansi2.jpg.webp?itok=CQf0A-L1)
- **Scientific Name:** *Citrus microcarpa*
- **Description:** A native citrus fruit used for immunity and respiratory relief.

### 10. Ampalaya
![Ampalaya](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSQOzlPtQSuW-vxUmjYn-0tls4c4OFCmpceoA&s)
- **Scientific Name:** *Momordica charantia*
- **Description:** Known for helping regulate blood sugar levels.

### 11. Guyabano Leaves
![Guyabano Leaves](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcREjnmCsGII0GSi8ICzJ1M1JWvY1MGSj1lveg&s)
- **Scientific Name:** *Annona muricata*
- **Description:** Traditionally used to boost immunity and promote relaxation.

### 12. Banana Leaves
![Banana Leaves](https://animals.sandiegozoo.org/sites/default/files/2017-02/banana_leaves.jpg)
- **Scientific Name:** *Musa spp.*
- **Description:** Used in traditional medicine and food preparation.

### 13. Santol Leaves
![Santol Leaves](images/plants/santol.jpg)
- **Scientific Name:** *Sandoricum koetjape*
- **Description:** Leaves are used for digestive and anti-inflammatory remedies.

### 14. Guava Leaves
![Guava Leaves](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTqXXjhdYPiPsGApkknz1JQp9NMOA7ONXDJQg&s)
- **Scientific Name:** *Psidium guajava*
- **Description:** Commonly used for treating diarrhea and wound cleansing.

### 15. Ipil-Ipil Leaves
![Ipil-Ipil Leaves](https://img.freepik.com/premium-photo/leucaena-leucocephala-herbal-ipil-ipil-leaf-space_63726-1776.jpg)
- **Scientific Name:** *Leucaena leucocephala*
- **Description:** Used for antibacterial and anti-inflammatory purposes.

### 16. Kangkong
![Kangkong](https://yummykitchentv.com/wp-content/uploads/2023/04/WATER-SPINACH_RESIZED1-1024x768.jpg)
- **Scientific Name:** *Ipomoea aquatica*
- **Description:** A leafy vegetable with nutritional and medicinal value.

### 17. Alugbati
![Alugbati](https://img.lazcdn.com/g/p/e39c07ed7cee17234500d5c24d7a49e8.jpg_720x720q80.jpg)
- **Scientific Name:** *Basella alba*
- **Description:** Used for digestive health and skin conditions.

### 18. Lemongrass
![Lemongrass](https://upload.wikimedia.org/wikipedia/commons/b/bd/YosriNov04Pokok_Serai.JPG)
- **Scientific Name:** *Cymbopogon citratus*
- **Description:** Known for its antibacterial and calming properties.

### 19. Malunggay
![Malunggay](images/plants/malunggay.jpg)
- **Scientific Name:** *Moringa oleifera*
- **Description:** Highly nutritious plant used to boost immunity.

### 20. Ginseng
![Ginseng](https://www.news-medical.net/image-handler/picture/2019/5/shutterstock_734716603.jpg)
- **Scientific Name:** *Panax ginseng*
- **Description:** Used to increase energy and improve overall health.

---

## C. Model Training Details

The image classification model was trained using the following parameters:

- **Epochs:** 40  
- **Batch Size:** 32  
- **Learning Rate:** 0.001  
- **Number of Images per Class:** Approximately 250 images per plant species  

These parameters were selected to balance learning efficiency, model accuracy, and prevention of overfitting.

---

## D. Model Evaluation

The model’s performance was evaluated using standard classification metrics.

### Evaluation Outputs:
- **Confusion Matrix**
- **Accuracy per Class**
- **Overall Model Accuracy**


## E. Model Testing

To verify the real-world performance of the trained model, testing was conducted using unseen images through the **Preview** section of the application. These test images were not included in the training or validation datasets.

Below are 10 sample screenshots showing the model’s predictions during testing. Each screenshot demonstrates the model’s ability to classify different plant species based on visual input.

### Testing Screenshots

![Test 1](images/plants/01.png)
![Test 2](images/plants/02.png)
![Test 3](images/plants/03.png)
![Test 4](images/plants/04.png)
![Test 5](images/plants/05.png)
![Test 6](images/plants/06.png)
![Test 7](images/plants/07.png)
![Test 8](images/plants/08.png)
![Test 9](images/plants/09.png)
![Test 10](images/plants/10.png)


These testing results indicate that the model can correctly identify medicinal plant species with a high level of accuracy, demonstrating its effectiveness for practical and educational use.


### Screenshots:
![Confusion Matrix](images/plants/confusion.png)

![Accuracy per Class](images/plants/accuracy.png)

---

## Conclusion

The trained model demonstrates effective classification of Philippine medicinal plants and can serve as a foundation for future applications such as mobile plant identification systems and educational tools.
