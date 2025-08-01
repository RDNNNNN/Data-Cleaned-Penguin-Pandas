# 項目：視覺化帕默群島企鵝資料

### 分析目標

本資料分析報告的目的是對帕默群島上企鵝樣本的相關指標進行視覺化，從而探索和分析物種、性別、所在島嶼等因素，與企鵝的身體屬性，包括體重、嘴峰長度和深度、鰭的長度之間的關係

### 簡介

原始資料 `Penguins.csv` 包括 334 個收集自南極洲帕爾默群島的 3 個島嶼上的企鵝樣本，以及企鵝相關屬性資料，包括種類名、所在島、嘴峰長度、嘴峰深度、鰭長度、體重、性別

`Penguins.csv`每列的意思如下：
- species：企鵝的種類
- island：企鵝所在島
- culmen_length_mm：企鵝嘴峰的長度（單位為毫米）
- culmen_depth_mm：企鵝嘴峰的深度（單位為毫米）
- flipper_length_mm：企鵝鰭的長度（單位為毫米）
- body_mass_g：企鵝體重（單位為克）
- sex：企鵝性別

### 企鵝種類

![Penguins](image/penguins.png)

### 企鵝島嶼

![Islands](image/islands.png)

### 企鵝性別

![Sex](image/sex.png)

### 不同島嶼企鵝種類

![Penguins Islands](image/penguins_islands.png)

### 不同島嶼企鵝性別

![Islands Sex](image/islands_sex.png)

### 企鵝間的關聯性

![Pairplot Penguins](image/pairplot_penguins.png)

### 企鵝種類間的差異

![Pairplot Species](image/pairplot_species.png)

### 企鵝種類間的差異(線性回歸線)

![Pairplot Species Line](image/pairplot_species_line.png)

### 企鵝性別的差異

![Pairplot Sex](image/pairplot_sex.png)