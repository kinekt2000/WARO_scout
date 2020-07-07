# Scout. WARO project
### group 8303
ETU 8303. Summer training practise, scout.  

---

### Team WARO
Grishin K.  
Zhurbin K.  
Kurlin N.  

### Building instructions
1. Скомпилировать программные модули  
2. Расположить папки saves и assets в директорию, откуда будет запущена программа  
3. Запустить программу. Точка входа - Application.class : main   

Для linux:
```
find -name "*.java" > sources
javac -d out @sources

cp assets out/assets
cp saves out/saves
cd out

java Application
```
Для Windows:
```
dir \s \B *.java > sources.txt
javac -d out @sources.txt

copy assets out\assets
copy saves out\saves
cd out

java Application
```

---

##### link to build  
tested on linux system
https://drive.google.com/drive/folders/1iCQLlTEN9N1xSARk43gAHejkjVudEfti?usp=sharing
