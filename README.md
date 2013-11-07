Угадыватель карты
=================

Демонстратор фокуса из теории кодирования.

На столе стоит компьютер-фокусник (считаем, что без камеры, микрофона и сети). Обычная колода из 52 карт отправляется в аудиторию, откуда возвращаются 5 случайно выбранных карт. Лектор одну из этих карт кладёт на стол, а оставшиеся четыре называет помощнику, который, не зная карту со стола, последовательно вводит эти карты в комьютер. После этого на экране компьютера появляется изображение пятой карты.

Секрет в лекторе, который правильно выбирает одну из карт так, чтобы порядком четырёх других передать её значение.

0. Можно отсортировать все карты (договориться, что 2 < 3, пики < крести и т.д.). Этот порядок нам пригодится, чтобы уметь отсортировать любой набор карт (и потом строить любые перестановки этого набора). 

1. Из пяти карт хотя бы две имеют одинаковую масть. Поэтому загадывать надо именно одну из них. Соответственно, первая в нашей четвёрке карт прямо укажет на масть загаданной карты. 

2. Оставшиеся три карты можно расположить 3! = 6 разными способами. И нам этого хватает, чтобы закодировать достоинство пятой карты, поскольку на первом шаге из двух карт одинаковой масти мы выбрали не случайную, а ту, от которой до второй карты будет от 1 до 6 шагов (представьте себе круг из карт 2, 3, 4, 5, 6, 7, 8, 9, 10, В, Д, К, Т). 

Соответственно, компьютер, посмотрев на первую карту в переданном ему наборе, выясняет не только масть загаданной карты, но и номер, к которому надо прибавить число от 1 до 6, чтобы узнать достоинство искомой карты. А сам этот номер вычисляется мгновенно, так как совпадает с номером перестановки второй, третьей и четвёртой карты. 
