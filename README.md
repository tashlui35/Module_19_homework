# Module_19_homework

This ledger allows the user who is using the application to find a fintech professional and pay them for their work. 

This had a few errors regarding gas price.

Initially I was getting an error on on the given code as it did not work having gas price as 0.

![Gass Error](Images/gas_error.png)

I then looked around on ganache and found the gas price was 20000000000.

![Gas Price](Images/gas_price.png)

I then tried using getGasPrice to use the number but got this error. 

![Get Gas Price Error](Images/get_gas_price_error.png)


After more researching I still couldn't get the getGasPrice to work so I ended up hard coding in the number after talking to the teachers.

Below shows screenshots from the working application:

Ganache account balance before transaction.
![Balance Before](Images/balance_before.png)


Ganache account balance after transaction.
![Balance After](Images/balance_after.png)


Inputs on sidebar of website
![Before Transaction](Images/before_trans.png)


Sidebar after transaction
![After Transaction](Images/after_trans.png)
