- 👋 Hi, I’m @hyunwook-seo
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
hyunwook-seo/hyunwook-seo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

//두 수의 차

import Foundation

func solution(_ num1:Int, _ num2:Int) -> Int {
    return num1 - num2
}

//숫자 비교하기

import Foundation

func solution(_ num1:Int, _ num2:Int) -> Int {
    var result: Int
    if num1 == num2 {
        result = 1
    } else {
        result = -1
    }
    return result
}
