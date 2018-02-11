# FPGA-project
ATM cum Banking server simulation implemented on Xilinx zynq 7000

Project members:
Patrick George
Prabhjot Singh
S.M.M.Sharief



In this project,we have implemented a Banking server and ATM using
an FPGA and Verilog.Users are given an option to choose Banking
server or ATM using a user input.

The context:

● There are a total of four accounts.Each account can store a
maximum of Rs.10000 and each can only be accessed by
entering the correct 4 pin password.

In the Banking side,we have the following functionalities:

● User can add or remove an account.
● Money can be deposited in a particular account the user
chooses.
● Pin of an account can be changed to a user given value.
● An account which was blocked due to wrong pin attempts in the
ATM can be unblocked in the BANK.

ATM side:

● Entered PIN will be verified before granting access to the
account for the withdrawal of money.
● Two options are given in the ATM side:Check balance or
withdraw money.
● The balance will be displayed with the help of 4 seven segment
displays.
● Money can be withdrawn in steps-the given denominations are
Rs.1000,Rs.500,Rs.100,Rs.50.
● More than 3 wrong PIN attempts after choosing an account will
result in the account getting blocked,which in turn can only be
unblocked in the banking side.
