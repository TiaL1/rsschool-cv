# **Valery Karnilayeu**

## **Contacts**

- **Location:** Gomel, Belarus
- **Phone:** +375 29 775-48-72
- **Email:** valerykarnilayeu@gmail.com
- **GitHub:** [TiaL1](https://github.com/TiaL1)

## **About Me**

## **Skills**

- HTML
- CSS
- JavaScript (Basic)
- Git

## **Code Example**

  `**const** calculator **=** {
    plus(firstNumber, secondNumber) {
    **return** firstNumber **+** secondNumber;
  },

  minus(firstNumber, secondNumber) {
    **return** firstNumber **-** secondNumber;
  },

  multyply(firstNumber, secondNumber) {
    **return** firstNumber ***** secondNumber;
  },

  division(firstNumber, secondNumber) {
    **return** firstNumber **/** secondNumber;
  },

  degree(firstNumber, secondNumber) {
    **let** total **=** 1;
    **while** (secondNumber) {
      total ***=** firstNumber;
      secondNumber**--**;
    }
    **return** total;
  },
};

**function** request() {
  **return** **+**prompt('Enter number', '0');
}

**function** main() {
  **let** flag **=** **true**;

  **while** (flag) {
    **const** operation **=** prompt('Enter operation: plus, minus, multyply, division, degree', 'exit').trim();

  **switch** (operation) {
      **case** 'plus': {
        alert(calculator.plus(request(), request()));
        **break**;
      }
    **case** 'minus': {
        alert(calculator.minus(request(), request()));
        **break**;
      }
    **case** 'multyply': {
        alert(calculator.multyply(request(), request()));
        **break**;
      }
    **case** 'division': {
        alert(calculator.division(request(), request()));
        **break**;
      }
    **case** 'degree': {
        alert(calculator.degree(request(), request()));
        **break**;
      }
    **case** 'exit':
    **case** **null**: {
        alert('Exit');
        flag **=** **false**;
        **break**;
      }
    **default**: {
        alert('Enter correct operation');
      }
    }
  }
}

main();`
## **Experience**
