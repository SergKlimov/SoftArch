# SoftArch
Software Architecture Dev

Проектируемая система предназначена для автоматизации просцесса наполнения электронной библиотеки (ЭБ) контентом.
В разрабатываемой системе подразумевается наличие трех ролей пользователей: автор, проверяющий, администратор.
Автор заходит в систему и загружает в нее электронный документ для передачи его в ЭБ. Также автор вносит всю необходимую информацию о предоставляемом документе.
Затем, когда в систему заходит проверябщий, ему выдается сообщение о поступивших документах для обработки. Проверяющий загружает документ и вручную просматривает наличие в нем различного рода ошибок, после успешной проверки самого документа, проверяются дополнительная информация о нем, введенные автором при подаче заявки. При наличии ошибок заявка отклоняется, автору высылается уведомление о найденных ошибках и необходима повторная отправка документа для предоставления его в ЭБ.
При удачной проверке у администратора отображается уведомление о необходимости добавления документа в систему.
Разрабатываемая сиситема должна реализовывать следующие функции:
- поддержка различных типов пользователей (автор, проверяющий документа, ответственный за добавление документа в электронный каталог и бд (администратор))
- прием документов для последующей их обработки от автора
- обработка дополнительной информации о документе, вводимой автором документа в интерфейсе системы
- возможность подтверждения корректности документа от проверяющего
- добавление сведений о документе в бд и представление его в электронном каталоге от лица администратора
 
#Диаграмма прецедентов#
![template](https://github.com/SergKlimov/SoftArch/blob/master/Use%20case%20diag.png?raw=true)

#Варианты использования#
![template](http://www.interface.ru/ca/vvu1.gif)
#Диаграмма классов#
![template](http://www.interface.ru/ca/vvu1.gif)
