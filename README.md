Выполнил: Шмаль Константин Иванович ИЭ-25

<div align="center">
  
  # 1. Установка виртуальной машины:
  <p> o	Создал новую виртуальную машину, выделив для нее 4 ГБ ОЗУ и 20 ГБ жесткого диска. </p>
  <img width="70%" height="70%" alt="image" src="https://github.com/IKOCTR/Labs_OC_and_Webs/blob/main/Lab1_1.png" />
  
  # 2. Установка Debian:
  <p> o	Скачал ISO-образ Debian и установил его на виртуальную машину. </p>
  <p> o	Настроил основные параметры </p>
  <img width="70%" height="70%" alt="image" src="https://github.com/IKOCTR/Labs_OC_and_Webs/blob/main/Lab1_2.png" />
  
  # 3.	Обновление системы:
  <p> o	Настроил подключение к интернету через NAT и Bridged. </p>
  <img width="70%" height="70%" alt="image" src="https://github.com/IKOCTR/Labs_OC_and_Webs/blob/main/Lab1_5.png" />
  <img width="70%" height="70%" alt="image" src="https://github.com/IKOCTR/Labs_OC_and_Webs/blob/main/Lab1_6.png" />
  
  <p> o	Выполнил обновление системы, используя sudo apt-get update и sudo apt-get upgrade. </p>
  <img width="70%" height="70%" alt="image" src="https://github.com/IKOCTR/Labs_OC_and_Webs/blob/main/Lab1_3.png" />
  <img width="70%" height="70%" alt="image" src="https://github.com/IKOCTR/Labs_OC_and_Webs/blob/main/Lab1_4.png" />
  
  # 4. Настройка SSH:
  <p> o	Установил и настроил SSH-сервер. </p>
  <p>Установка SSH пакетов (-y : Согласие на все вопросы)</p>
  <img width="70%" height="70%" alt="image" src="https://github.com/IKOCTR/Labs_OC_and_Webs/blob/main/Lab1_7.png" />
  <p>Установил службу SSH в авто-загрузку</p>
  <p> (--now : включить службу сейчас без перезагрузки) </p>
  <p> (systemctl enable : авто-загрузка служб)</p>
  <img width="70%" height="70%" alt="image" src="https://github.com/IKOCTR/Labs_OC_and_Webs/blob/main/Lab1_8.png" />
  <p> o Подключился по SSH с основного ПК к ВМ </p>
  <p>По паролю:</p>
  <img width="70%" height="70%" alt="image" src="https://github.com/IKOCTR/Labs_OC_and_Webs/blob/main/Lab1_9.png" />
  <p>По ключу:</p>
  <p>Создал ключ SSH по типу шифрования : ed25519</p>
  <img width="70%" height="70%" alt="image" src="https://github.com/IKOCTR/Labs_OC_and_Webs/blob/main/Lab1_10.png" />
  <p>Создал директорию .shh для ключа (проверил что дир. создалась корректно)</p>
  <img width="70%" height="70%" alt="image" src="https://github.com/IKOCTR/Labs_OC_and_Webs/blob/main/Lab1_11.png" />
  <p>В файл с ключом, записал ключ-pub (замок) из хоста (который создал пару шагов назад)</p>
  <p>Установил права доступа к .shh директории и файлу с ключом-pub (для корректной работы)</p>
  <p>700 и 600 ?</p>
  <p>1-ая цифра: Владелец файла</p>
  <p>2-ая цифра: Группа в которую входит владелец файла</p>
  <p>3-ая цифра: Остальные пользователи</p>
  <img width="70%" height="70%" alt="image" src="https://github.com/IKOCTR/Labs_OC_and_Webs/blob/main/Lab1_12.png" />
  <img width="70%" height="70%" alt="image" src="https://github.com/IKOCTR/Labs_OC_and_Webs/blob/main/Lab1_13.png" />
</div>
