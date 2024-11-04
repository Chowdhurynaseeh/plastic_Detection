


# Plastic Detection in River

Plastic pollution in marine environments is a global threat, endangering marine species, human health, food security, and coastal tourism. Annually, more than 350 million tons of plastic are produced, with over 15 million tons ending up in the world's oceans. As plastic degrades into micro-plastics over time, both macro and microplastics have severe environmental impacts. Rivers serve as the primary source of plastic in oceans, with more than 80% of river plastic originating from just 1000 rivers globally. Organizations such as The Ocean Cleanup are investing resources to address ocean plastic pollution by focusing on cleaning rivers.

![image](https://github.com/user-attachments/assets/286513d1-713c-454e-b5e9-9d72f432be91)

## Introduction

This project presents a Streamlit app capable of detecting plastic presence in rivers using Deep Learning techniques like Object Detection, employing state-of-the-art models such as "You Only Look Once (YOLO)". The app utilizes the YOLOv8m Pre-trained Object Detection model, trained on a custom dataset containing photos of rivers potentially contaminated with waste. The waste items in the dataset are annotated through bounding boxes and categorized into four groups: Plastic Bags, Plastic Bottles, Other Plastic Waste, and No Plastic Waste. It is noteworthy that some photos may not contain any waste.

## Dataset

The dataset is provided in the file `convert_to_yolo.py`, which facilitates the download and conversion of datasets into a YOLO-usable format. Alternatively, you can download the dataset from [here](https://huggingface.co/datasets/Kili/plastic_in_river). The dataset is split into **`train`** and **`validation`** sets, comprising **3407** and **425** images, respectively. After conversion to YOLO Format, the downloaded dataset structure is as follows:


## Preview
![screenshot](https://github.com/Chowdhurynaseeh/plastic_Detection/blob/main/Screenshots/Example-screenshot.png)

## Contributing

Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.
