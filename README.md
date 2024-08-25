The code implements program- ASSEMBLY LANGUAGE STATEMENTS on MIPS-32 architecture and verifies the operation of processor model .

The statements includes the simple exapmle : ADD three numbers 10,20 and 25 stored in processor registers -  

So this includes three steps :
1. Initialize register R1 with 10 .
2. Initialize register R2 with 20 .
3. Initialize register R3 with 25 .
4. Add three numbers and store the sum in R4.

Assembly language program for this specific exapmle :
 
        
    ADDI R1,R0,10  
 
    ADDI R2,R0,20
    
    ADDI R3,R0,25
    
    ADD R4,R1,R2
    
    ADD R5,R4,R3
    
    HLT `
 
Further this language will get convert to machine language in form of instruction array and this instruction is accessed from memory and will run over the 32bit MIPS model .

To avoid DATA HAZARD we have considered dummy instructions in between and those will be ensuring to pass one clock so that before WRITING BACK the previous stage may not access the data from same previously used address.



  
 
