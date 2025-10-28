# Rock Paper Scissors Game 🎮

A simple command-line Rock Paper Scissors game built with Python. Challenge the computer and test your luck!

## 🎯 Features

- Interactive command-line interface
- Play against computer AI
- Continuous gameplay with replay option
- Clear win/lose/draw logic
- Simple and intuitive controls

<div align="center">

### Don't want to clone? No problem! Run it instantly:

[![Open in Codespaces](https://img.shields.io/badge/Open%20in-Codespaces-green?style=for-the-badge&logo=github)](https://codespaces.new/sridharchinthaparthi/rock-paper-scissors)

**Perfect for:**
- 📱 Mobile browsing - Test from your phone!
- ⚡ Quick exploration - No setup required
- 🧪 Experimentation - Fork and modify

</div>

## 📋 Prerequisites

- Python 3.10 installed on your system

## 🔧 Installation

1. Clone the repository:
```bash
git clone https://github.com/sridahrchinthaparthi/rock-paper-scissors.git
```

2. Navigate to the project directory:
```bash
cd rock-paper-scissors
```

3. Run the game:
```bash
python rock_paper_scissor.py
```

## 🎮 How to Play

1. Run the program
2. Choose your move:
   - 1 -- Rock
   - 2 -- Paper
   - 3 -- Scissor
3. The computer will randomly select its move
4. The winner is determined by classic rules:
   - Rock crushes Scissors
   - Scissors cuts Paper
   - Paper covers Rock
5. Choose to play again or exit

## 📝 Game Rules

- **Rock** beats **Scissors**
- **Scissors** beats **Paper**
- **Paper** beats **Rock**
- Same choices result in a **Draw**

## 💻 Code Example

```python
import random

l=['Rock','Paper','Scissor']

while True:
    r=random.randint(0,2)
    for i in range(0,len(l)):
        print(i+1,'--',l[i])

    ch=int(input('Enter your choice: '))
    print('you: ',l[ch-1])
    print('Computer: ',l[r])

    if l[ch-1]==l[r]:
        print('It\'s a Draw')
    elif l[ch-1]=='Scissor' and l[r]=='Paper':
        print('Wow nice you won ..!!')
    elif l[ch-1]=='Paper' and l[r]=='Rock':
        print('You won very nice...')
    elif l[ch-1]=='Rock' and l[r]=='Scissor':
        print('Yow won ....great...!!')
    else:
        print('Computer WINS...You lost....')
    
    a=input('Do you want to Play again?? (y/n): ')
    if a.lower()=='y':
        continue
    else:
        print('Thank you for playing.....')
        break
```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/sridahrchinthaparthi/rock-paper-scissors/issues).

## 📧 Contact

**Sridhar Chinthaparthi**
- Email: sridhar.chinthaparthi@gmail.com
- GitHub: [@sridharchinthaparthi](https://github.com/sridharchinthaparthi)

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

## ⭐ Show your support

Give a ⭐️ if you enjoyed this project!

---


**Happy Gaming! 🎲**

