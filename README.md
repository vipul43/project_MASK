# project_MASK
- Description: neural net to classify images of people with mask
- Team: Vinay Kumar Pulavarti(111801034@smail.iitpkd.ac.in),
        Gurunadh Pachappagari(111801029@smail.iitpkd.ac.in),
        Sai Vipul Mohan Veludandi(111801045@smail.iitpkd.ac.in)
- Idea:
    - Preprocessing Model(opencv):
        - Input: Images containing multiple people with mask or without mask
        - Output: Bounding co-ordinates of faces of people
    - Main Model(Deep Learning Model):
        - Dataset: [face-mask-12k-images-dataset](https://www.kaggle.com/ashishjangra27/face-mask-12k-images-dataset) 
        - Input: Images containing single person with or without mask 
        - Output: Labels corresponding to with mask or without mask images