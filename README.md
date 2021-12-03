# CheOlga_minor_HW3
Ссылка на Colab
https://colab.research.google.com/drive/1fIBP2sr7HBk_ZvRzL4Sm75Lrylxh1u63?usp=sharing
# MultyQC
![image](https://user-images.githubusercontent.com/60808830/144602795-eff50c9b-7492-47f7-868c-782a82a4b365.png)
![image](https://user-images.githubusercontent.com/60808830/144602915-0debdbc8-6539-447d-9813-2b316ac34d26.png)
![image](https://user-images.githubusercontent.com/60808830/144602979-0461bf6b-9105-4f75-9604-9ded2cef5895.png)
![image](https://user-images.githubusercontent.com/60808830/144603011-b4914e7a-28ba-4e52-9aaa-b5763d65c359.png)
![image](https://user-images.githubusercontent.com/60808830/144603041-2a86edbe-6013-4e17-89e0-b3439374da9b.png)
![image](https://user-images.githubusercontent.com/60808830/144603166-99a80832-7075-43dd-ab3b-b6d598286ec4.png)
![image](https://user-images.githubusercontent.com/60808830/144603196-d9f8b643-0135-4b1e-bf65-84da48912644.png)
Учитывая количество уникально картированных чтений,а также информацию о числе чтений, соответствующих участкам генома, где не аннотировано ни одного гена и число чтений, принадлежащих чтений, рассчитываем число чтений, соответствующих хотя бы одному гену
![image](https://user-images.githubusercontent.com/60808830/144603763-b7107a2c-9d54-4c66-8102-f1e8d764c72f.png)
![image](https://user-images.githubusercontent.com/60808830/144604014-671f58c0-e210-4fec-aebb-bd5190deba6b.png)
![image](https://user-images.githubusercontent.com/60808830/144604161-18bacb30-a319-470c-9e00-6f0c4c8cac51.png)
# 2
Дифференциально эуспрессированные гены увеличивают экспрессию
![image](https://user-images.githubusercontent.com/60808830/144604680-ec556122-7a9c-4487-bb60-04a096ee5236.png)
Экспрессия генов отличается в разных группах
![image](https://user-images.githubusercontent.com/60808830/144604830-14278789-edb6-430b-9ca6-847a281abd3a.png)
Наиболе дифференциально экспрессированные гены
![image](https://user-images.githubusercontent.com/60808830/144604867-92e3be4c-361e-4f93-8650-c2042350aba6.png)
"Normalized counts" в контрольных и перепрограммированных образцах
.
import numpy as np
import pandas as pd
df1 = pd.read_csv('differentially_expressed_genes.txt', sep = '\t')
sorted_df1 = df1.sort_values(by='log2FoldChange', ascending=False)
sorted_df1.head
.
![image](https://user-images.githubusercontent.com/60808830/144607719-6f4388c4-ccf4-4604-8a77-fa7cb3e06880.png)
![image](https://user-images.githubusercontent.com/60808830/144607740-eb60bcfa-3ebe-4d93-bf3a-d049be42f515.png)
![image](https://user-images.githubusercontent.com/60808830/144607759-b818a6fa-1cfb-42cd-83b2-d3c2b1639835.png)
![image](https://user-images.githubusercontent.com/60808830/144607781-3e6e5993-fc19-4022-9b58-96be7a27f7dc.png)

