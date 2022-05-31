### Hi, my name is Juan Cruz 👋 📱

Welcome to personal repository.
I graduated as Image and Sound Designer at the University of Buenos Aires in 2019.
The pandemic was a turning point, with more free time I began to explore new paths.
In 2021 I decided to investigate the world of UX-UI Design, which then led me in early 2022 to study JavaScript and currently Swift, especially SwiftUI.


```swift

struct Card : Hashable{
    let income: Int
    let expense: Int
    var balance : Int {
        income - expense
    }
    
    let cardNumber : String
    let imageName : String
    var isSelected = false
    var backgroundColor : Color {
        isSelected ? Color.primaryCyan : Color.primaryYellow
        
    }
    var textColor : Color {
        isSelected ? .white : .black
    }
    
    var incomePercentage : Int {
        Int (Double(balance) / Double(income) * 100)
    }
}

```

<!--
**jcgomez14/jcgomez14** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
