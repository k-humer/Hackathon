# Анализ влияния товарного ассортимента на выручку ТТ ритейла

## Понятия.

**Товарная номенклатура** – группировка товара, согласно gr2.

**Товарная группа** – группировка товара, согласно gr.

**Эффективность продаж** – интегральный показатель, учитывающий все факторы, влияющие на продажи. Рассчитывается как отношение выручки к площади ТТ (руб/м2).

**Идентичные ТТ** – ТТ с близкими значениями эффективности продаж.

**Ранг(rank)** – ранг присваивается (ранжирование) согласно порядку, в котором элементы содержатся в структуре (таблице). Использован для сравнительного анализа.

**Плохая и хорошая ТТ** – ТТ, показывающая устойчивое снижение(плохая) или увеличение(хорошая) выручки за год, рассчитанной как среднее за несколько месяцев.

## Исходные данные.

1.  Никакой обработки данных не потребовалось.
2.  Удалены ТТ в количестве 6 из 84 представленных, отсутствующие хотя бы в одном наборе данных. Это никак не повлияло на результат исследования.

## Теоретическое обоснование.

1.  Чтобы избежать влияния флуктуаций хорошие и плохие ТТ выбраны по изменению средней выручки за апрель-май-июнь 2022 года к средней выручке за апрель-май-июнь 2021 года.
2.  Исхожу из того, что покупатель при выборе постоянного магазина для покупок, сравнивает наличие или отсутствие, не столько отдельного наименования товара, сколько набора корзины, который он привык брать. И если набор корзины перестанет его удовлетворять как по цене, так и по ассортименту, то он уйдёт в другой магазин. Отсюда влияние товарного ассортимента на продажи имеет затяжной характер и потому для сравнительного и статистического анализа по всем ТТ выбрал данные за май год к году.
3.  Сравнительный анализ плохих и хороших ТТ произведён за май месяц 2022 года.
4.  В исследовании использованы в основном сравнительные и статистические методы.

## Список хороших и плохих ТТ.

Список хороших ТТ в файле GOOD_tt.xlsx

Список плохих ТТ в файле BAD_tt.xlsx

## Визуализация ТТ

В файле effective_tt.html – ТТ раскрашены по эффективности, разделённые на три категории:

\- зелёные иконки, эффективность продаж ТТ более 110000 руб/м2,

\- оранжевые иконки, эффективность продаж ТТ 50000-110000 руб/м2,

\- красные иконки, эффективность продаж ТТ менее 50000 руб/м2.

В файле good\_bad\_tt.html – ТТ раскрашены по изменению выручки за год, разделённые на три категории:

\- зелёные иконки, увеличение выручки ТТ за год более 0%,

\- оранжевые иконки, снижение выручки ТТ за год до (-5)%,

\- красные иконки, снижение выручки ТТ за год от (-5)%.

## Товарная номенклатура за май 2021 и 2022 годов по всем ТТ

Приложение в файле compar\_analysis\_tn\_2021\_2022.xlsx.

Удалил из исследования пакеты.

В столбце **_revenue**,\*\* выручка по позиции товарной номенклатуры.

В столбце **_percent, %**, доля в общем объёме продаж.

Жёлтым цветом обозначены позиции товарной номенклатуры из товарной группы «Овощи. Фрукты. Грибы. Зелень», которые присутствуют в двух списках, зелёным цветом обозначены позиции, которые отсутствуют в списке за 2022 год.

Заметно, что за год предпочтения покупателей сдвинулись в сторону уменьшения покупок овощей, зелени и фруктов. Что может быть следствием снижения предлагаемого ассортимента, ухудшения качества предлагаемого товара или избыточного повышения цены.

## Сравнительный анализ между хорошими и плохими ТТ по товарной номенклатуре за май 2022 года.

Приложение в файле compar\_analysis\_tn\_bad\_good.xlsx.

Удалил из исследования пакеты.

Удалил товарную номенклатуру с продажами меньше 10000 рублей одновременно и в хороших, и в плохих ТТ.

Сравнение производилось методом ранжирования продаж по товарной номенклатуре (столбцы rank).

Никакой разницы в топе товарной группы и в топе товарной номенклатуры между хорошими и плохими ТТ не наблюдается.

Красным цветом, обозначены позиции товарной номенклатуры, которые торгуются в плохих ТТ хуже, чем в хороших.

Жёлтым цветом, обозначены позиции товарной номенклатуры, которые торгуются одинаково.

Зелёным цветом, обозначены позиции, которые торгуются в плохих ТТ лучше, чем в хороших ТТ.

Доля продаж красных позиций в плохих ТТ (36%) почти равна доле продаж в хороших ТТ (38%) и с лихвой компенсируются долей продаж зелёных позиций (40%). Другими словами, от перестановки мест слагаемых, сумма не меняется.

Отсюда вывод: в целом между хорошими и плохими ТТ ассортимент товарной номенклатуры не оказывает влияния на продажи.

## Выявленные особенности:<br>

1. Корреляция изменения товарного ассортимента с изменением выручки за год май к маю: 0.67<br>
2. Корреляция товарного ассортимента с выручкой за май 2021 года: 0.75<br>
3. Корреляция товарного ассортимента с выручкой за май 2022 года: 0.8<br>
4. Среднее изменение товарного ассортимента за год май к маю по всем ТТ показало увеличение: 7.32<br>
5. Среднее изменение выручки за год май к маю по всем ТТ показало снижение: -6.36<br>
6. Наблюдается снижение выручки за год май к маю при одновременном увеличении товарного ассортимента.<br>
7. За год предпочтения покупателей сдвинулись в сторону уменьшения покупок овощей и зелени.<br>
8. В плохих магазинах по сравнению с хорошими, товарный ассортимент не учитывает предпочтения покупателей как по количеству(3193 против 3702), так и по качеству - как пример, не хватает овощей и зелени.<br>
9. Статистическая проверка гипотезы показала, что товарный ассортимент по количеству не влияет на выручку, что подтверждается пунктом 6.<br>

## Общий вывод:

1.  Товарный ассортимент представлен достаточно широко и никак не влияет на выручку.
2.  Здесь тот случай, когда количество не перешло в качество. Товара представлено много, но не то что нужно покупателю. Явно, алгоритм подбора товарного ассортимента не в полной мере учитывает запросы покупателей, которые мало меняются со временем. Потому наблюдается отток покупателей.

## Предложения.

Так как значимых различий в товарном ассортименте плохих и хороших ТТ, влияющих на выручку не обнаружено, то остаётся повторить ассортимент 2021 года и:

1.  Расширить ассортимент в товарной группе «Овощи. Фрукты. Грибы. Зелень» в части товарной номенклатуры \- огурцы, фрукты, овощи, томаты, салаты, зелень.
2.  Повысить лояльность покупателей, применив бонусы и скидки к указанной товарной номенклатуре.

Данное предложение применимо ко всем ТТ, а не только к плохим.

## Выбор плохих ТТ для эксперимента.

Выберу идентичные ТТ из расчета, чтобы минимум и максимум интервала не отклонялись более 15% от среднего, для чего задам площадь ТТ в интервале 110 - 140 и эффективность в интервале 50000 – 70000. По этим условия нашлось 8 ТТ (файл experiment_tt.xlsx):

Сравнение результатов эксперимента необходимо провести с идентичными ТТ из ЮЗАО и СЗОА. Предложенная выборка по ЗАО недостаточна для этих целей.
