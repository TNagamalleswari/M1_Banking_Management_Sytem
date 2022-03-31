# TEST PLAN:

## Table no: High level test plan

| **Test ID** | **Description**                                              | **Exp I/P** | **Exp O/P** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  HLR1       |Creation of new account| Name:abc  Account Number:ab543211767 Initia Deposit:500|Congratulations... Your account has been created.|Congratulations... Your account has been created.|Requirement based |
|  HLR2       |Deposit Amount|100000 |Your current available bank balance is 20000000|Your current available bank balance is 200000|Requirement based|
|  HLR3       |withdraw Amount|35000| Sorry, You dont have enough money in your account| Sorry, You dont have enough money in your account| Requirement based  |
|  HHR4       |Entering Password| byavydset|Wrong Password|Wrong Password|Boundary based    |
|  HHR4       |Entering Password| ankitalnt|password match|password match|Boundary based    |

## Table no: Low level test plan

| **Test ID** | **Description**                                              | **Exp IN** | **Exp OUT** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  LLR1       |If user enters wrong Account Number. | ###########| Wrong account number...| Wrong account number...|Requirement based |
|  LLR2       |If wrong choice choosen| 7|Invalid choice|Exit|Scenario based    |


## USAGE UNITY TEST FRAMEWORK:
The Unity Test Framework (UTF) enables Unity users to test their code in both Edit Mode and Play Mode, and also on target platforms such as Standalone, Android, iOS, etc.
UTF uses a Unity integration of NUnit library, which is an open-source unit testing library for .Net languages.
It is possible to extend the Unity Test Framework (UTF) in many ways, for custom workflows for your projects and for other packages to build on top of UTF.


## Best Practices

 - [x] Checked all the possibilities of output
 - [x] Mentioned all the inputs for better understanding
 - [x] Presented in tabular form for easy understanding
 - [x] Both High level and low level Test plans are shown
