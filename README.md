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
#Заокруглення кутів
1. Натискаємо Modify –> Fillet
2. Обираємо кути, які потрібно скруглити та виставляємо радіус скуглення d/2
 <img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/51baa7f5-735c-4dad-a0cb-c21236f43df4" />
3. Тепер ми отримали готову четвертину нашої деталі, далі ми перетворимо її у повноцінну
4. Натискаємо Create –> Mirror 
5. Виставлляємо переметри як на скріншоті
   <img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/526e64f9-a373-4294-bb06-59004fd23c4a" />
6. Натиснувши ОК отримуємо половину виконаного виробу
7. Повторяємо попередні кроки віддзерклюючи всю поточну деталь по внутрішній площині
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/5d7d4a51-1c78-4ea4-ac90-7f53f1aaa3db" />

#Додавання вдавленого тексту на виріб
1. Щоб додати текст потрібно обрати площину, та натиснути Create Sketch
2. Далі Create –> Text
   <img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/896090c4-4253-4be2-86da-89458c039f10" />
3. Виставляємо доданий текст за бажанням на деталі та натискаємо ОК
4. Потім вибираємо скетч з текстом та Create –> Extrude
5. В параметрах буде -4, щоб текст був наскрізним
   <img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/5aeec234-7635-42d6-a603-f55a5950547a" />
6. Далі я додав ще один надпис, але його товщина вдавлення становить -d/2, що дорівнює 2мм.
7. Виконавши такі ж самі маніпуляції ми отримаємо наступний виріб.
   <img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/0fe7fdc3-b8f7-468e-8a90-59cc85bc5c0b" />



