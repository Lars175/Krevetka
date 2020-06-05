как ссылаться на проблемный [код](https://monosnap.com/file/L3g1D8RNo66IL8j1QifV5IzXHWA8kJ)

открыть файл на Github, выделить кусок кода, на который хотите сослаться, кликнуть на три точки и выбрать Copy permalink 
Есть такой оператор как (! )  Оператор логического отрицания; инвертирует значение булевой переменной.
12:14
Мы его добавляем в метод
12:14
public void increaseCurrentTemperature(){
    if (!isOn()) return;
    if (currentTemperature >= maxTemperature)
        return;
    currentTemperature++;
}
12:16
Это значить когда будет false  вызов след метода не выполняется, ну то есть выполняется со значением false
12:17
public void setOff() {
    AirConditioner conditioner = new AirConditioner();
    conditioner.setOn(false);
    conditioner.setCurrentTemperature(9);
    assertEquals(9, conditioner.getCurrentTemperature());
    assertEquals(false, conditioner.isOn());
}
12:18
только там у тебя нет вызова метода conditioner.decreaseCurrentTemperature(); или conditioner.increaseCurrentTemperature();





12:18
то есть выкл в состоянии повышение температуры и выкл в состоянии понижение температуры
12:19
андестенд ми?))
