# Створення деталі "Сніжинка" для лазерного різака
1.Завантажити Fusion 360 та отримати студентську версію звернувшись в підтримку  
2.Перейти на порожню вкладку натиснувши "Untitled"
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/61f98604-81ab-459e-8a8d-fa254074c904" />
3. Натиснути Create Sketch
<img width="1920" height="1032" alt="create_sketch" src="https://github.com/user-attachments/assets/07bdb9f3-efab-4f74-8066-6e13030823ce" />
4. Обираємо площину для скетча, для зручності було обрано xOy
<img width="1920" height="1032" alt="select_plane" src="https://github.com/user-attachments/assets/469cec42-7804-41d6-930a-2040f5a82166" />
5. Вносимо параметри для зручності роботи з скетчом
<img width="1920" height="1032" alt="change_paramteres" src="https://github.com/user-attachments/assets/9e4f9730-d5cc-4820-866c-9e4c4956d452" />
6.Вводимо параметри які були задані за умовою у розділ User Parameters
<img width="1202" height="482" alt="params_values" src="https://github.com/user-attachments/assets/f027718f-c904-42bf-ab6a-f43bd57b4855" />
7. Обираємо інструмент Create Line, та створюємо границі для нашого скетча
8. Будуємо лінію вгору довжиною L/2
9. Будуємо лінію вправо довжиною d/2
10. Будуємо лінію вгору довжиною L/2
11.Будуємо лінію вправо довжиною L - d/2
12.Будуємо лінію вниз довжиною L - d/2
13.Будуємо лінію вліво довжиною L/2
14.Будуємо лінію вниз довжиною d/2
15.Будуємо лінію вліво довжиною L/2

У результаті отримуємо скетч, який зображений на скріншоті
<img width="1920" height="1032" alt="ready_sketch" src="https://github.com/user-attachments/assets/26ae6c38-e9f0-489b-b048-e08127f94054" />
Натискаємо Finish sketch

#Перетворюємо скетч у фігуру
1. Виділяємо скетч ЛКМ
2. Create –> Extrude
3. В поле distance вводимо d
4. Після цього отримуємо об'ємну фігуру
   <img width="1920" height="1032" alt="3d_obj" src="https://github.com/user-attachments/assets/64a65710-be03-459f-acf0-ce7c6073fb91" />
5. Натискаємо Create –> Mirror 
6. Виставлляємо переметри
   Object Type: Bodies
7. Натиснувши ОК отримуємо половину виконаного виробу
8. Повторяємо попередні кроки віддзерклюючи всю поточну деталь по внутрішній площині

# Скруглення кутів
