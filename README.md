# hse21_hw3
## Google Collab
[ссылка на 1 часть](https://colab.research.google.com/drive/1WIdlrOHgWDiiOR3yQSLzrB3sJNASLn6N?usp=sharing)

[ссылка на R анализ](https://colab.research.google.com/drive/1du72iSUwkuwGgHeks0FBlEmzgH3DzLAY?usp=sharing)
## MultiQC
**ID** | **Length** | **Failed (%)**
SRR3414629	| 65 | 18
SRR3414630	| 65 | 18
SRR3414631	| 65 | 18
SRR3414635	| 65 | 18
SRR3414636	| 65 | 18
SRR3414637	| 65 | 18

![image](https://user-images.githubusercontent.com/55647212/144171524-7f7a64cc-a1ea-4d87-ad66-e132355db81c.png)
![image](https://user-images.githubusercontent.com/55647212/144171624-1fa60142-bd0c-41ba-bdc6-7ee9f5add9ea.png)
![image](https://user-images.githubusercontent.com/55647212/144171722-28f16820-5cb4-4809-b23e-43e7d3b74456.png)
![image](https://user-images.githubusercontent.com/55647212/144171781-1b9122d4-fe2a-4a94-8805-7327f0b239a1.png)
![image](https://user-images.githubusercontent.com/55647212/144171853-e2d2972a-4630-495d-827a-473fe769882c.png)
![image](https://user-images.githubusercontent.com/55647212/144171913-1831bb5f-8a6f-4eba-a7cf-95ae04dbf28a.png)
![image](https://user-images.githubusercontent.com/55647212/144171990-ecab01ff-ddfc-491e-bce9-35e00e85a1e4.png)
![image](https://user-images.githubusercontent.com/55647212/144172060-9bfc84a4-15d7-4bb1-a144-5b4edc90a77d.png)
![image](https://user-images.githubusercontent.com/55647212/144172108-b6504f39-6e68-40fd-bae6-5562161bf890.png)
![image](https://user-images.githubusercontent.com/55647212/144172180-364465f3-a2b8-4588-8d4b-7b2c63e8553b.png)
## Statistics
**ID** | **Type** | **Reads N** | **Aligned reads** | **Aligned once** | **Reads per gene**
------------ | ------------- | ------------- | ------------- | ------------- | -------------
SRR3414629	| reprogramming	| 21106089	| 20510113 | 18375888 | 16049609
SRR3414630	| reprogramming	| 15244711	| 14832680 | 13186139 | 11465324
SRR3414631	| reprogramming	| 24244069	| 23547686 | 20928945 | 18408851
SRR3414635	| control	| 20956475 | 20395865 | 18428317 | 16275997
SRR3414636	| control	| 20307147 | 19757059 | 17825380 | 15757580
SRR3414637	| control	| 20385570 | 19847291 | 17844858 | 15736978
## DESeq2
MA-plot | Heatmap
:-------------------------:|:-------------------------:
<img width ="400" src="https://user-images.githubusercontent.com/55647212/144243687-859138ed-fe97-4c1f-a18f-01fe2d6a7ef9.png"> | <img width="400" alt="Screen Shot 2021-12-01 at 08 33 41" src="https://user-images.githubusercontent.com/55647212/144243725-5a06a6c6-a1a7-4996-9ec0-9697add7d40d.png">

### Гены, которые значимо поменяли свою экспрессию:
gene 15 | gene 10345
:-------------------------:|:-------------------------:
<img width ="400" src="https://user-images.githubusercontent.com/55647212/144247777-63f5dd89-6646-4a0a-9182-c6edff067030.png"> | <img width ="400" src="https://user-images.githubusercontent.com/55647212/144243790-84584add-bec2-42e2-aca4-6013b338af42.png">

gene 11567 | gene 12125
:-------------------------:|:-------------------------:
<img width ="400" src="https://user-images.githubusercontent.com/55647212/144247815-2164a96b-4faf-4973-9cb7-b69315c2af9a.png"> | <img width ="400" src="https://user-images.githubusercontent.com/55647212/144243817-1fffeb0d-42f0-42e9-9732-d874936ad610.png">
