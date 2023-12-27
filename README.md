# mids-207-final-project-summer23-Nick-Frances-Jerry-Chi
DATASCI W207 Summer 2023 Final Project

This project aims to use ML techniques to distinguish emergency vehicles from regular road noise in order to improve traffic flow and reduce congestion

- There are 6 **main directories** & 6 <ins>sub directories</ins> in this repo containing the following:
    - **Data**
        - shap value plots of CNN
        - <ins>model_predictions</ins>
            - CSV containing predicted lables
        - <ins>original_data</ins>
            - CSVs containing features extracted by original research team
        - <ins>processed_data</ins>
            - CSVs containing re-extracted/corrected features
        - <ins>spectrograms</ins>
            - <ins>ambulance</ins>
                - ambulance recording spectrograms
            - <ins>road</ins>
                - road noise recording spectrograms
    - **EDA**
        - notebooks for exploring the extracted features as well as the actual underlying audio files
    - **MISC**
        - old code used in dev
    - **Models**
        - notebooks containing each of the models fit
    - **Preprocessing**
        - notebooks used to re-extract feature CSVs and spectrogram images
    - **Slides_and_Feedback**
        - baseline slides, baseline feedback & final presentation slides

Note: the audio files are too large to host in github and thus are not present here. Throughout this project, each member referenced the audio files locally. The data was obtained from https://www.nature.com/articles/s41597-022-01727-2#Sec6. Please refer there for access to the underlying wav files
