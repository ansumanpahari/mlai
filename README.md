# Machine Learning and Artificial Intelligence
**Assignment 5.1: Will the Customer Accept the Coupon?**

The project is to find out the customer who are most likely to accept the coupon. The analysis focus more on the postive side than on the negative side. It has two parts. First part is based on the assignment and 2nd part is based on indepedent investigation.
## Findings Based on Assignment
   **Here is list of potential candiates who are most likely to accept the coupon**
   - Who went to the Bar 3 or less has higher acceptance rate. Rate is almost `80%`.
   - Who are went to Bar once and 25 years or more has higher acceptance rate. Rate is almost `70%`.
   - Who went to the Bar once and had passengers other than kid has higher acceptance rate. Rate is almost `96%`. 
## Findings Based on Indepenet Investigation
On 2nd part I focused on the gender, age, income, CarryAway and martialStatus to analysis who are more likely to accept the coupon.

### Here is list of potential candiates who are most likely to accept the coupon

**Compare Male vs Female - Who took CarryAway 4 or more**
    
    - Male has higher rate of acceptance. Almost 10% higher in the category of 4 or more CarryAway.
    
**Compare Male vs Female - Income less than 50K**
    
    - Male has higher rate of acceptance. But the difference is not that significant in this catefory.
    
**Male vs Female - Based on Age**
    
    - Male wins in `below21`, `21`, `26`, `36`, `46`
    - Female wins in `31`, `41` and `50plus`

**Male vs Female - Based on visiting Bar number of times**
    
    - Male wins in `1~3`, `4~8` and `gt8`
    - Female wins in `never` and `less1`
  
**Marital Status - Based on CarryAway number of times**
    
    - Married partner wins in `1~3`, `14~8`
    - Single wins in `less1` and `gt8`

## File Structure
- data folder - Contains data (csv) file
- images folder - Contains images
- pre-process Jupyter file - Wanted to split the project in multiple files. Pre-porcess is where initial analysis is done. It mainly used for understanding the data.
- prompt Jupyter file - The main juypter file. Contains code.