*как ссылаться на проблемный [код](https://monosnap.com/file/L3g1D8RNo66IL8j1QifV5IzXHWA8kJ)

*открыть файл на Github, выделить кусок кода, на который хотите сослаться, кликнуть на три точки и выбрать Copy permalink 

*Есть такой оператор как (! )  Оператор логического отрицания; инвертирует значение булевой переменной.

*Мы его добавляем в метод

*public void increaseCurrentTemperature(){
    if (!isOn()) return;
    if (currentTemperature >= maxTemperature)
        return;
    currentTemperature++;
}

*Это значит когда будет false  вызов след метода не выполняется, ну то есть выполняется со значением false

public void setOff() {
    AirConditioner conditioner = new AirConditioner();
    conditioner.setOn(false);
    conditioner.setCurrentTemperature(9);
    assertEquals(9, conditioner.getCurrentTemperature());
    assertEquals(false, conditioner.isOn());
}


*только там у тебя нет вызова метода conditioner.decreaseCurrentTemperature(); или conditioner.increaseCurrentTemperature();

*то есть выкл в состоянии повышение температуры и выкл в состоянии понижение температуры

