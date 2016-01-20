JCalendarWidget is a highly customizable, multi lingual Calendar component for graphically picking a date.It renders a calendar including the days of the week, the weeks of the year, and the days of the month. It can be easily used in GUI builders.

Checkout [Swing Components](https://code.google.com/p/swing-components/) for more swing controls

**Screenshots**

![http://2.bp.blogspot.com/-lUTsmIWOtnA/Tay3O7nsp5I/AAAAAAAAAOs/nacWZMtjFT8/s1600/_2011-04-04_00-12-29.png](http://2.bp.blogspot.com/-lUTsmIWOtnA/Tay3O7nsp5I/AAAAAAAAAOs/nacWZMtjFT8/s1600/_2011-04-04_00-12-29.png)

![http://4.bp.blogspot.com/-vp-8Fqmp45o/Tay3PFRJjRI/AAAAAAAAAO0/FCHIAq0DUJU/s1600/_2011-04-04_00-30-07.png](http://4.bp.blogspot.com/-vp-8Fqmp45o/Tay3PFRJjRI/AAAAAAAAAO0/FCHIAq0DUJU/s1600/_2011-04-04_00-30-07.png)

![http://2.bp.blogspot.com/-RfmmqiGAs-o/Tay3OrRtJmI/AAAAAAAAAOc/pT7-0QyCnpM/s1600/_2011-04-02_01-45-58.png](http://2.bp.blogspot.com/-RfmmqiGAs-o/Tay3OrRtJmI/AAAAAAAAAOc/pT7-0QyCnpM/s1600/_2011-04-02_01-45-58.png)

![http://2.bp.blogspot.com/-IM3wNRzGHIo/Tay3O_3U5dI/AAAAAAAAAOk/KR6RQ3t5PzQ/s1600/_2011-04-02_01-46-42.png](http://2.bp.blogspot.com/-IM3wNRzGHIo/Tay3O_3U5dI/AAAAAAAAAOk/KR6RQ3t5PzQ/s1600/_2011-04-02_01-46-42.png)

http://3.bp.blogspot.com/-wFsmI9kUFio/Tay5P43OrtI/AAAAAAAAAO8/F2Xav-MM2UA/s1600/datepicker.PNG

**Usage**

Add the bean to your pallete and drag the bean onto your form and customize it.If not using a GUI builder(but why????)

```
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