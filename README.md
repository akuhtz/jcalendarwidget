# JCalendarWidget
Automatically exported from code.google.com/p/jcalendarwidget

JCalendarWidget is a highly customizable, multi lingual Calendar component for graphically picking a date.It renders a calendar including the days of the week, the weeks of the year, and the days of the month and can be easily used in GUI builders.

###Screenshots:

###Usage:
Add the bean to your pallete and drag the bean onto your form and customize it.
If not using a GUI builder(but why? try NetBeans)

```java
//instantiate the JCalendarWidget
JCalendarWidget widget = new JCalendarWidget();
// JDatePicker has overloaded constructor to specify the dateFormat
//will use DateFormat.LONG as default
JDatePicker picker = new JDatePicker();
//customize the widget
widget.setHolidayForeground(Color.RED);
widget.setHighlightHoliday(true);
widget.setDatesFromPreviousAndNextMonthShown(true);
 
//add the widget to datepicker
picker.setCalendarWidet(picker);
```

