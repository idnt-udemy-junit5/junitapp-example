# CHANGELOG
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## UNRELEASED

### ADDED
- **`#02` - JUnit5 // `#012` - Añadiendo la clase Banco y la relación con las cuentas**
  - The `Bank` class has been added.
  - The relationship of the `Bank` class with the `Account` class and the `Account` class with the `Bank` class has been established.
  - The method for transferring money between 2 accounts has been created.
  - The test has been created to test the method created in the class `Bank` in the class `AccountTest`.  
  

- **`#02` - JUnit5 // `#011` - Probando y afirmando excepciones con assertThrows en JUnit 5**
  - A new exception has been created (`NoEnoughtMoneyException`).
  - The `debit` method of the `Account` class has been updated to throw the `NoEnoughtMoneyException` exception when an attempt is made to subtract more money than the account balance.
  - A new test has been added to the `AccountTest` class to test the new functionality added to the `debit` method of the `Account` class.  
  

- **`#02` - JUnit5 // `#010` - TDD para debito y crédito**
  - _The tests to test the `debit` and `credit` methods in `Account` class have been created._
  - _The `debit` and `credit` methods have been created and implemented in `Account` class._
  

- **`#02` - JUnit5 // `#009` - Test Driven Development TDD con JUnit**
  - _A test has been created in the `AccountTest` class to explain how assertEquals works when a class has the `equals` method implemented and when it doesn't._  
  

- **`#02` - JUnit5 // `#008` - Escribiendo test para el saldo**
  - _A test ins `AccountTest` class has been created to test the `getBalance` method of the `Account` class._
  

- **`#02` - JUnit5 // `#007` - Escribiendo y ejecutando primeras pruebas unitarias con Assertions**
  - _A constructor with all arguments has been added to the `Account` class._
  - _The `person` property of the `Account` class has been renamed to `name`._
  - _A test class has been created for the `Account` class._
  - _A test has been created to test the `getName` method of the `Account` class._
    

- **`#02` - JUnit5 // `#006` - Creando y configurando el proyecto con JUnit 5**
  - _The project has been created._  
  - _`Junit5` and `Lombock` dependencies has been added to the pom file._
  - _The POJO `Account` has been created._
  