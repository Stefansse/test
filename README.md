Стефан Стошевски 195085

2. Control Flow Graph

![cfg](https://github.com/Stefansse/SI_2023_lab2_195085/assets/117118626/f56c9a66-dcf1-4798-af72-a59047a05abd)

Цикломатска комплексност
Цикломатската комплексност изнесува 11. Истата ја добив според бројот на региони, како  и според формулата P + 1 kade П e бројот на предикатни јазли

Тест случаи според критериумот EveryBranch
1. user=null, се фрла exception
2. user=b1, username='', password=1#34567812, email='sfnn.?', existinguser=2, Постои ист user, емаил влегува во containts делот од if-от.
3. user=b2, username='niko', password=12345, Не постои ист user, password<=8 е во овој тест
4. user=b3, username = "sfkd", password = 1  3456, email = 'dadae', Не содржи . или @ во емаил, и password има празно место



![everybranch slika](https://github.com/Stefansse/SI_2023_lab2_195085/assets/117118626/bd6a1897-2ab9-407a-89aa-d8915614877a)





Тест случаи според Multiple Condition



  ![Multiplecondiitioncoverage](https://github.com/Stefansse/SI_2023_lab2_195085/assets/117118626/6c0d4d13-72bb-482c-b00e-72fc94a336b9)
