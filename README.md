# Отчёт о тестировании бонусной системы "Precision"

## Краткое описание

02.05.2020 г. было проведено тестирование бонусной системы "Precision". 
На тестирование потрачено 30 мин.

"Precision" описывает процесс получения бонусов клиентами.

В качестве входных данных описано часть кода:

```public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```
В результате тестирования итоговое значение равно 0.8999999999999999. Данный результат не соответствует действительности.

## Описание тестов
Проведено функциональное тестирование части кода

## Результаты
1. При запуске, итоговое значение равно 0.8999999999999999. Результат неверный.
2. В результате тестирования выявлены следующие дефекты: [См. ссылку](https://github.com/TanyaKomyakova/Precision/issues/1)

## Общие рекомендации

При написании кода, необходимо использовать те типы переменных диапозон которых подходит для получения верного результата.


