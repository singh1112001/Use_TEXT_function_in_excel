# Use_TEXT_function_in_excel
in this I will showcase you how to extract date, time, hours of time, day of date , month of date and year of date using TEXT function in Excel.

## Need of TEXT function
Whenever we download a data based on time series, data contains timestamp which is combination of date and time i.e. 03-01-2015  01:00:00 , which is in this format. 
If we specifically want to analyze data based on hours, days or month, it becomes a bit complicated, unless we extract the hours, day or month. This can be easily done in pyhton notebooks, but it becomes a bit tricky when you are in excel, unless you know the beauty of TEXT() function. 

## Beauty of TEXT function

**TEXT()** function takes two argument, first is the location of data (value), other is in which format you want your data.
![image](https://github.com/singh1112001/Use_TEXT_function_in_excel/assets/88104229/459f0430-ac54-4ddd-926a-22b4c59553e4)

You can manipulate data and extract various information as string from given timestamp. <Br>
1. Extract Date from timestamp using TEXT()
   =Text(value, "DD/MM/YYYY") -> This will return the text in the form of DATE  <br><br>
![image](https://github.com/singh1112001/Use_TEXT_function_in_excel/assets/88104229/9886a30d-6ba5-4a94-afb7-a301b89d6499)

Result->
   ![image](https://github.com/singh1112001/Use_TEXT_function_in_excel/assets/88104229/8de2ca41-65b6-4e42-b041-768a10349eb4)


2. Extract Time from from timestamp using TEXT()
   =text(value,"H:MM") <br><br>
  ![image](https://github.com/singh1112001/Use_TEXT_function_in_excel/assets/88104229/8e134c28-8d7b-4c1c-a6a8-28bdaa5daa4d) <br>  
Result-> ![image](https://github.com/singh1112001/Use_TEXT_function_in_excel/assets/88104229/acfb669e-91b8-41a6-9145-e32d1bc2f31d) <br>

3. Extract Hour of time
   = text(value,"H")  <br>

![image](https://github.com/singh1112001/Use_TEXT_function_in_excel/assets/88104229/bd5288cc-67cd-4bc4-908e-8ecb23cf1091) <br>
Rsult -> ![image](https://github.com/singh1112001/Use_TEXT_function_in_excel/assets/88104229/0284cf34-d0e2-4b17-b63c-c51f6af7b173) <br>

4. Extract Day of Date
    = text(value,"DD")  <br>
    ![image](https://github.com/singh1112001/Use_TEXT_function_in_excel/assets/88104229/ca336d0d-bfea-4def-8732-9e004c34b1cf)
<br>
Result -> 
![image](https://github.com/singh1112001/Use_TEXT_function_in_excel/assets/88104229/8d01ba36-b1fe-45d1-a6f7-a32a5604cd1e)





   
