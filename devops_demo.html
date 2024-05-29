<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Calculator</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
        .calculator {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .display {
            width: 100%;
            height: 40px;
            margin-bottom: 10px;
            text-align: right;
            padding: 10px;
            font-size: 1.5em;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .buttons {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 10px;
        }
        .button {
            padding: 20px;
            font-size: 1.5em;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            background-color: #f0f0f0;
        }
        .button.operation {
            background-color: #f9a825;
            color: white;
        }
        .button.equal {
            grid-column: span 4;
            background-color: #4caf50;
            color: white;
        }
    </style>
</head>
<body>
    <div class="calculator">
        <input type="text" class="display" id="display" disabled>
        <div class="buttons">
            <button class="button" onclick="appendNumber(7)">7</button>
            <button class="button" onclick="appendNumber(8)">8</button>
            <button class="button" onclick="appendNumber(9)">9</button>
            <button class="button operation" onclick="setOperation('+')">+</button>
            <button class="button" onclick="appendNumber(4)">4</button>
            <button class="button" onclick="appendNumber(5)">5</button>
            <button class="button" onclick="appendNumber(6)">6</button>
            <button class="button operation" onclick="setOperation('-')">-</button>
            <button class="button" onclick="appendNumber(1)">1</button>
            <button class="button" onclick="appendNumber(2)">2</button>
            <button class="button" onclick="appendNumber(3)">3</button>
            <button class="button operation" onclick="setOperation('*')">*</button>
            <button class="button" onclick="appendNumber(0)">0</button>
            <button class="button" onclick="clearDisplay()">C</button>
            <button class="button" onclick="calculate()">=</button>
            <button class="button operation" onclick="setOperation('/')">/</button>
        </div>
    </div>

</body>
</html>
<script>
  let display = document.getElementById('display');
let currentOperation = null;
let firstOperand = null;
let secondOperand = false;

function appendNumber(number) {
    if (display.value === "0" || secondOperand) {
        display.value = number;
        secondOperand = false;
    } else {
        display.value += number;
    }
}

function setOperation(operation) {
    if (currentOperation !== null) {
        calculate();
    }
    firstOperand = parseFloat(display.value);
    currentOperation = operation;
    secondOperand = true;
}

function calculate() {
    if (currentOperation === null) return;
    let secondOperandValue = parseFloat(display.value);
    let result;
    switch (currentOperation) {
        case '+':
            result = firstOperand + secondOperandValue;
            break;
        case '-':
            result = firstOperand - secondOperandValue;
            break;
        case '*':
            result = firstOperand * secondOperandValue;
            break;
        case '/':
            result = firstOperand / secondOperandValue;
            break;
    }
    display.value = result;
    currentOperation = null;
    firstOperand = null;
}

function clearDisplay() {
    display.value = '';
    currentOperation = null;
    firstOperand = null;
}

</script>
