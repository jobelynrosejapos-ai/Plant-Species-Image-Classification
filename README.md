# Plant-Species-Image-Classification
Laboratory Work 2-A Activity — Plant Species Image Classification  Using Teachable Machine

Plant Species Image Classification Using Teachable Machine

A. Project Overview This project presents an image classification model developed to recognize 20 distinct plant species. Utilizing a dataset of 5000 images, the model was trained to differentiate among various plant morphological features, including structural characteristics, leaf patterns, and color variations. The system is intended to support gardeners and botany students in the efficient identification of common ornamental and wild plant species.

#B

## 🌿 Plant Species Gallery

| Common Name | Scientific Name | Description | Image |
|-------------|-----------------|-------------|-------|
| Dragon Plant | *Dracaena* | Sturdy woody stems with rosettes of sword-shaped leaves | <img width="200" src="https://github.com/user-attachments/assets/9a51cc61-addd-48f6-b3f7-7fa87ecbf2a6" /> |
| ZZ Plant | *Zamioculcas zamiifolia* | Hardy, drought-tolerant, evergreen perennial native to Eastern Africa, known for its glossy, dark green, pinnately compound leaves | <img width="200" src="https://github.com/user-attachments/assets/bce62d3d-fc6b-4ece-b457-052f51b89ae4" /> |
| Silver Inch Plant | *Tradescantia zebrina* | Silvery-white stripes on top of olive-green/purple leaves and deep magenta undersides | <img width="200" src="https://github.com/user-attachments/assets/c1e78549-63b4-4eac-b8d4-795f1f9ebe74" /> |
| Watermelon Peperomia | *Peperomia argyreia* | Silvery-green stripes resembling a watermelon rind | <img width="200" src="https://github.com/user-attachments/assets/04061f53-1397-4c50-8a3f-2956f6f13a21" /> |
| Purple Passion Plant | *Gynura aurantiaca* | Lavender-white petals and a fringed, wavy crown of deep purple/white filaments | <img width="200" src="https://github.com/user-attachments/assets/c9c77fb9-b67c-4eb1-9d8f-df0cb6a046bd" /> |
| String of Hearts | *Ceropegia woodii* | Heart-shaped leaves and long, cascading purple stems | <img width="200" src="https://github.com/user-attachments/assets/1d70d5e4-7118-4fbc-a075-772dcfaa5928" /> |
| Spider Plant | *Chlorophytum comosum* | Narrow, arching, variegated (white/green) or solid green strap-shaped leaves | <img width="200" src="https://github.com/user-attachments/assets/0c96f546-83b0-46db-b9a8-9f6e05289a1a" /> |
| Prayer Plant | *Maranta leuconeura* | Velvety, patterned leaves in shades of green, cream, and red, requiring high humidity, indirect light, and consistent moisture to thrive | <img width="200" src="https://github.com/user-attachments/assets/1c867357-bcf8-4c51-9b1d-77bb261f4680" /> |
| Plumosus Asparagus Fern | *Asparagus setaceus* | An elegant, fast-growing evergreen with delicate, feathery, needle-like foliage that mimics true ferns | <img width="200" src="https://github.com/user-attachments/assets/19561c5e-0d8d-447a-b022-b405544de4d4" /> |
| Heartleaf Philodendron | *Philodendron hederaceum* | Heart-shaped leaves variegated with lime green, yellow, and dark green stripes | <img width="200" src="https://github.com/user-attachments/assets/895c511c-ea67-4b3d-a981-1cad052a700c" /> |
| Philodendron Selloum | *Thaumatophyllum bipinnatifidum* | Deeply lobed, glossy dark green leaves, growing up to 10–15 feet tall and wide | <img width="200" src="https://github.com/user-attachments/assets/92cb9287-6ce2-4fee-8a5a-31a470b26bc1" /> |
| Peace Lily | *Spathiphyllum* | Glossy green leaves and iconic white flowers | <img width="200" src="https://github.com/user-attachments/assets/f4d2f550-4dfe-4dfe-84a7-2ac3d7d16f8c" /> |
| Dieffenbachia | *Dieffenbachia seguine* | Thick stems and large, oblong, variegated leaves featuring cream, yellow, or white patterns on a green base | <img width="200" src="https://github.com/user-attachments/assets/b80067f2-8bf9-47b2-a766-19293d5fd3f6" /> |
| Laurentii Sansevieria | *Dracaena trifasciata* | Succulent with stiff, sword-shaped leaves featuring dark green mottled centers and striking creamy-yellow margins | <img width="200" src="https://github.com/user-attachments/assets/646e4456-f566-4e94-9324-319283981f02" /> |
| Haworthia | *Haworthia Duval* | Perennial succulents native to South Africa, typically reaching 3–5 inches in height and width | <img width="200" src="https://github.com/user-attachments/assets/8911fa2d-c7df-4860-9f33-28eb9a8e30b5" /> |
| Money Tree | *Pachira aquatica* | Braided trunk, glossy green leaves, and symbolic ability to bring good luck, prosperity, and wealth | <img width="200" src="https://github.com/user-attachments/assets/de409b21-a53d-407b-bb1a-d7e0ee582874" /> |
| Jade Plant | *Crassula ovata* | Evergreen succulent featuring thick, woody stems and glossy, fleshy green leaves often tinged with red margins | <img width="200" src="https://github.com/user-attachments/assets/0beb877a-3e3d-43cf-9ca4-231fd6d9a40e" /> |
| Burro's Tail | *Sedum morganianum* | Long, thick stems densely packed with plump, pale blue-green to gray-green leaves that resemble a braided donkey tail | <img width="200" src="https://github.com/user-attachments/assets/d374835b-25a6-42d7-bfb0-b5fb10ec7d9f" /> |
| Chinese Money Plant | *Pilea peperomioides* | Coin-shaped, glossy dark green leaves that grow on long petioles | <img width="200" src="https://github.com/user-attachments/assets/08671a84-7d71-4de3-9d2f-36439180dbab" /> |
| Boston Fern | *Nephrolepis exaltata* | Lush, arching, sword-shaped fronds and cascading growth | <img width="200" src="https://github.com/user-attachments/assets/d484b5ea-4051-452d-aa06-dc5078fab6b4" /> |
