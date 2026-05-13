- [^1]![[Pasted image 20260511193438.png]]
- [^2] ![[Pasted image 20260512211318.png]]
	- **TEAC и ORAC** ещё можно грубо сопоставлять, потому что оба выражены через **Trolox equivalents (TE)**, просто поделив второе на 100
	- values are comparable only approximately due to different antioxidant assays used
	- %% 
		```python
		import matplotlib.pyplot as plt
		
		# ====== ВСТАВЬ СВОИ ДАННЫЕ ======
		
		labels = [
		    "Amaranth",
		    "Buckwheat",
		    "Black quinoa",
		    "Red quinoa",
		    "Ermes rice",
		    "Nerone rice",
		    "Orange rice",
		    "Wild rice",
		    "Black rice",
		    "Violet rice",
		    "White sorghum",
		    "Red sorghum",
		    "Teff", 
		    "Black chickpea", 
		    "Adzuki bean",
		    "Black bean",
		    "Kidney bean",
		    "Red lentil"
		]
		
		values = [
		    1360.4,
		    8177.1,
		    3236.3,
		    2752.6,
		    1443.7,
		    7227.7,
		    2550.7,
		    3181.5,
		    3958.5,
		    11783.7,
		    2236.3,
		    4734.8,
		    2664.1,
		    1710.7,
		    2751.1,
		    4033.7,
		    3460.4,
		    1706.7
		]
		
		# Названия осей
		y_label = "ORAC (μmol TE/100 g)"
		
		# Подпись снизу
		caption = "Comparison of antioxidant capacity values measured\nusing the oxygen radical antioxidant capacity (ORAC)\nassay and expressed as Trolox equivalents (TE)."
		
		# ====== ПОСТРОЕНИЕ ГРАФИКА ======
		
		plt.figure(figsize=(10, 6))
		
		bars = plt.bar(labels, values)
		
		# Вертикальные подписи снизу
		plt.xticks(rotation=90)
		
		# Подписи осей
		plt.ylabel(y_label)
		
		# Шаг по оси Y = 2000
		max_value = max(values)
		plt.yticks(range(0, int(max_value) + 2001, 2000))
		
		# Сетка
		plt.grid(axis='y', linestyle='--', alpha=0.5)
		
		# Подпись под графиком
		plt.figtext(
		    0.5,
		    -0.08,
		    caption,
		    ha='center',
		    fontsize=11
		)
		
		plt.tight_layout()
		
		plt.show()
		```
		%%
- При приготовление крупы и бобовые теряют незначительное количество полифенолов[^3]
	- Кроме [[amaranth]], который теряет ~75%[^4]
- [^4] ![[Pasted image 20260512154845.png]]![[Pasted image 20260512154945.png]]

consequently, flours with a higher extraction rate are richer in polyphenols than refined flours[^5]

https://pubs.acs.org/doi/10.1021/jf990619o

[^1]: https://www.sciencedirect.com/science/article/pii/S0733521008001008
[^2]: https://www.sciencedirect.com/science/article/abs/pii/S0308814618313359
[^3]: https://pmc.ncbi.nlm.nih.gov/articles/PMC5615292/
[^4]: https://www.researchgate.net/publication/51987223_Total_phenolic_content_antioxidant_and_antidiabetic_properties_of_methanolic_extract_of_raw_and_traditionally_processed_Kenyan_indigenous_food_ingredients
[^5]: https://pmc.ncbi.nlm.nih.gov/articles/PMC5615292