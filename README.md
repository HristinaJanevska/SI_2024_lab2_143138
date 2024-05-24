Hristina Janevska 143138

2. Control Flow Graph
![image](https://github.com/HristinaJanevska/SI_2024_lab2_143138/assets/46898770/67e02d42-1e96-47d6-ad23-61e1dc0d8ff1)
3.Цикломатската комплексност на овој код е 10. Истата ја добив со формулата E-N+2, каде Е ми го претставува број на ребра, N бројот на јазли, така што за овој код Е=37, N=29, па следува дека 27-19+2=10.
Бројот на региони е 10 значи толку е компелксноста и има толку неазвисни патеки во графот.
Друг начин е и преку предикатните јазли Р + 1. Број на предикатни јазли Р = 9 па оддтука следува 9 + 1 = 10.

4.Every Branch критериум
![image](https://github.com/HristinaJanevska/SI_2024_lab2_143138/assets/46898770/880f3b89-c089-43cc-b413-5dfac7897dee)

4,Multiple condition критериум
Можни комбинации за условот  
if (item.getPrice() > 300 && item.getDiscount() > 0 && item.getBarcode().charAt(0) == '0') се следните

![image](https://github.com/HristinaJanevska/SI_2024_lab2_143138/assets/46898770/39ca85b4-a59f-4d01-84d5-b3c64e804957)


![image](https://github.com/HristinaJanevska/SI_2024_lab2_143138/assets/46898770/541c5d6f-cd22-4869-874c-30fb1e74cdac)

Изразот ќе биде точен само во една ситуација односно кога сите три услови ќе бидат исполнети.Доколку еден од нив не е исполнет,не може да биде точен.
