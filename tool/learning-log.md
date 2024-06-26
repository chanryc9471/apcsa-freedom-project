# Tool Learning Log 

Tool: **Flutter**

Project: **Cookbook App**

---

10/27/23: [Intro & Setup](https://youtu.be/1ukSR1GRtMU?si=T5thSLF81Ldu1RCD)
* Git: https://git-scm.com/downloads
* Flutter: https://docs.flutter.dev/get-started/install
* VS Code: https://code.visualstudio.com/download

* I originally wanted to do Swift, but I saw Flutter and how it was cross-platform so I liked that better
   * https://www.youtube.com/watch?v=HJDCXdhQaP0&t=8s
     * I liked Xcode better
     * functions looked more cleaner and easier to use 

---

10/29/23: [Dart Primer](https://youtu.be/FLQ-Vhw1NYQ?si=tkzexejwfiK54_x8)
* Dart Playground: https://dartpad.dev/
   * went on it to test out all the variables, similar to what I learned in Java thus far
__Basics__
* instead of `boolean` (Java), it's `bool`
* variables are similar to Java
* `dynamic` can be used
* use `let` if the value won't be changed
**PAUSED AT 15:47 IN VIDEO**

---

10/30/23: 
* continued with the [Dart Primer](https://youtu.be/FLQ-Vhw1NYQ?si=tkzexejwfiK54_x8) video
<img width="960" alt="image" src="https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/08270aae-4433-4bd0-ad0f-44c2dd867131">
<br>
^ tried following along with the video to get a hang of the dart playground (syntax is similar to Java)

* When I followed along with the video, it showed that I didn't need to initialize the variables yet, but then I saw the error comments telling me to initialize, which finally got my code to work (old video so it probably used to be that one didn't have to initialize for the variable to work
* learned about inheritance and extending classes

**Overall it seems that Flutter is similar to Java and it seems relatively suitable for the app I want to make. However, I want to make an IOS app Xcode is needed for me to make an IOS app on Flutter.**

---

11/5/23:
* followed along this [video](https://youtu.be/C5lpPjoivaw?si=fC4CxmCT-LlnvXe7) and made this:
<img width="960" alt="image" src="https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/cd33cf65-92dd-4de5-9a86-39567dd87324">
<br>

* first step to forming an app UI
  * it was hard to make the button even though I followed how netninja did it (might try it again next time I tinker)
* next steps: try to see what Swift has to offer to make my final decision about what tool I am using.

---

Tool: **Swift**

11/12/23:
[Swift Youtube Playlist](https://www.youtube.com/playlist?list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW)
* watched parts 1 and 2 on variables and constants
  * syntax is similar to how javascript declares and initializes variables

* found out about Swift playground and possibly use it to make the app without the need for Xcode
  
![image](https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/bcad02ef-f3e2-4491-a989-6a8edf644dd3)

---

11/19/23:
* watched [part 3 - types](https://youtu.be/48v8FH46mQs?si=-dn7eozv6znIF_Dg)
   * learned about types
     * Swift assumes variable type but it can be declared like `var varName: dataType = "anything here"`
   * do `import UIKit` to import user interface elements

* watched [part 4 - functions & parameters](https://youtu.be/fffG55Ei1Qc?si=k-NBPZAnnPZkBKlC)
```swift
func funcName(paramName1: value, randomNum: Int) -> expectedReturnVal {
return paramName1 + randomNum
}
```
 * learned how to make/call a function, parameters, how to make a function return something, and how a return type is set  in a function

---

11/26/23:
* watched a [video](https://youtu.be/uSanD_pFwis?si=F1I5DG-PvTtuh2GZ) to get a sense of SwiftUI
    * followed along with the video on my own Xcode and did what the YouTuber did and got a feel of how it was like coding with SwiftUI
    * Didn't fully understand what I was typing in but I started to understand some little bits of what was what
    * stopped at 4:43 in the video

---

12/3/23:
* continued with the [video](https://youtu.be/uSanD_pFwis?si=F1I5DG-PvTtuh2GZ)
  *  learned about SF Symbols - https://developer.apple.com/sf-symbols/
    * tried to get SF Symbols to work but it didn't so I'll try again next time
    * did not try to code along with the video because it looked too complicated at the moment so I just watched how the person did it
    * stopped video at 13:42
 
12/10/23: 
* decided to ditch the previous video because it wasn't helpful and I got too confused with everything since there was no explanation as to the things she coded
* watched [part 5 - classes and structs](https://youtu.be/ys3dPSKssgk?si=P-dvOx54FKktY_2P) of the playlist from before
  
* from the video I made my version of a class and its variables and indicator:
![image](https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/17af863d-a759-4db2-bb0b-eaf53636e9c9)<br>

* what I learned from the video on the differences between classes and structs
![image](https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/bc772dc0-0788-4965-9f83-32b67fb983b8)<br>

1/1/24:
* watched part 6 [video](https://www.youtube.com/watch?v=8Z0mImrIITA&list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW&index=6)<br>
![image](https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/82ef86a0-c808-4918-86a4-954a4ae6134c)<br>

* this video was easy since it was fairly similar to how Java is, except the `for in` which was new
  * the `for in` does the same as the `for each`
* watched part 7 [video](https://www.youtube.com/watch?v=9K89xEuSiYA&list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW&index=7)
  * paused the video at 7:39 because I got error messages while I was coding along
    * kept saying something about "Expressions/Statements are not allowed at the top level"
    * went online to search for answers about the error message (stack overflow) but I couldn't understand it (will research more
    * while clicking around to get the error message to go away, I found a [documentation](
https://docs.swift.org/swift-book/documentation/the-swift-programming-language/) for Swift
      * will browse the documentation more next time
 
1/7/24:
* finished part 7 video
  * optionality is a good way to represent errors
    * gives flexibility with assigning values of a particular variable
   
* followed along [part 8 video](https://www.youtube.com/watch?v=rBotA3jwWkY&list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW&index=8)
```java
// conditionals
if condition {
  // stuff
} else if condition {
  // stuff
} else {
  // stuff
}
```
* operators are the same as Java
*  will watch part 9 and part 10 (see what I learn from that and maybe code a mini project)

1/15/24:
* watched [part 9](https://www.youtube.com/watch?v=DTd7HHSAw-4&list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW&index=9)
```java
// guard statements
// - they are much more "cleaner" (simpler) than if/else statements
guard conditional1, conditional2 else { wtvHappensIfConditionalsAreFalse }
  // code that will run if conditions are met
```
* using guards to unwrap optionals and also a simpler way than if/else statement are the most common
<img width="331" alt="image" src="https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/24a95701-f991-4783-89de-a54bc5b87e78">
^^ optional


1/21/24:
* watched [part 10](https://www.youtube.com/watch?v=_qxm-MvRw_Y&list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW&index=10)
```java
// enums and switch statements
//An enum is another way to represent cases (used to represent multiple states)

enum States {
  case InProgress, Aborted, Complete, WillStart
}

let current = States.InProgress

enum States: String{}
^ enum States inherits strings
```
* enum is a special data type that allows variables to be predefined
* stopped video at 8:31


1/29/24:
* continued with part 10
  * switch allows you to inspect a value and match it with a case
```java
func checkStats() {
  switch current {
    case .InProgress:
      // CODE
      break
    case .Aborted:
      // CODE
      break
    case .Complete:
      // CODE
      break
    case .WillStart:
      // CODE
      break
  }
}
```
* since `current` is set to `states.InProgress` (from code snippet in last tinker log), whatever code that is for `.InProgress will run



3/3/24:
* watched [part 11](https://www.youtube.com/watch?v=ELRH8vkOlNs&list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW&index=12) of the swift playlist
  * learned about protocols
    * basically like a place to declare your variables and functions before initializing it
    * used for when say those variables and functions can be used in other classes besides just one
```java
// protocols
protocol AnyFun {
  var anything: String { get set } // the get set is so the classes can get and set the value of the var

  func anyWords()
  func haveApple() -> Bool
}

// class
class haveApple() ->  {
  var anything: String
  init(var anything: String) {
    self.color = color
  }

}
```

3/10/24:
* watched [part 12 - strong vs weak memory](https://www.youtube.com/watch?v=I2mu9gMUbF0&list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW&index=12)
  * if something is `strong` in memory, that means that it won't deleted away by whatever it is tied to (even if we don't use/need it)
    * variables are by default set to strong 
  * if something is `weak` in memory, that means that it will be deleted away if the "parent" or whatever it is tied to is deleted
    * ex: `weak var balloon = "str"`

* learned about closures through the [documentation](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/closures)
  * Closures: self-contained blocks of code that can be passed around and used in other parts of code; similar to the workings of a function, except it is more shortened 
```java
// closure expression syntax
{ (<#parameters#>) -> <#return type#> in
   <#statements#>
}
```    



3/17/24:
* watched [video](https://youtu.be/xiS5gJOIQxI?si=tLNR1s2ygoM74aeu) on the difference of when to use `@escaping` and nonescaping closures
  * use `@escaping` when closure needs to outlive the life of its function, meaning that the closure is allowed to escape
```java
// documentation's example of @escaping
var completionHandlers: [() -> Void] = []
func someFunctionWithEscapingClosure(completionHandler: @escaping () -> Void) {
    completionHandlers.append(completionHandler)
}
```


3/24/24: 
* watched this [video](https://youtu.be/4PI04Yj3Ngs?si=kaUTIh473YU2iGF1) on how to change fonts
  * upload font into swift project
  * add it to a plist file
    * <img width="682" alt="image" src="https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/6df8b9f4-01d7-4f84-8d3f-87c43f6db223">
  * go to where you want the font to be used
    * `.font(.custom(name: fontFamName, size: #))` (like `.font(.custon(name: ZenLoop-Regular, size: 50))`)

how to figure out the name of the font (it might not be the file name of the font):
```java
init() {
  for familyName in UIFont.familyNames {
      print(familyName)

      for fontName in UIFont.fontNames(forFamilyName: familyName) {
          print("-- \(fontName)")
      }
  }
}
```


4/1/24:
* watched this [video](https://www.youtube.com/watch?v=nqTcAzPS3oc) to learn how to add a title on a page
  * `.navigationTitle()` allows you to add a title to nav view 
```java
NavigationView {
  .navigationTitle("Any Title!")
}
```

* watched this [video](https://www.youtube.com/watch?v=D0siMqCwMJY) to learn how to navigate between views
  * can navigate between views (pages) with the use of `NavigationLink()`
```java
NavigationView {
    VStack {
        NavigationLink(destination: OtherFile()){
            Text("Click to Navigate")
        }  
    }
}
```

* watched this [video](https://www.youtube.com/watch?v=tXFwyFdkSas)
  * `navigationBarTitleDisplayMode(.inline)` makes the nav bar turns into this when scrolling down:
    * <img width="101" alt="image" src="https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/ac07c8fd-42e3-4e88-b69e-6e431501f438">
    
```java
// ScrollView allows you to scroll on whatever is put inside
ScrollView {
    Text("Hello, How are you?")
    Text("Hello, How are you?")
    Text("Hello, How are you?")
}
```


4/7/24:
* watched [part 14 - strings](https://www.youtube.com/watch?v=TqN9Asm0Zvo&list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW&index=14) about strings
  * string interpolation: the concept of putting a variables value inside of a string
    * put the variable in parentheses and then prefix it with a backslash, like `"\(first) \(last)"`
    * doesn't have to be a string, it can also be a number
    * `var.count` gives you the number of characters in a string
   

4/14/24:
* watched [part 15 - Arrays & Dictionaries](https://www.youtube.com/watch?v=-uwSmesQKHE&list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW&index=15)
    * arrays and dictionaries are both a type of collection, both data structures
    * dictionaries have keys and values
        * https://www.tutorialspoint.com/swift/swift_dictionaries.htm
```java
// array of integers
var nums: [Int] = [1, 2, 3,]

// array of strings
var names: [String] = [Chanry, Bob, Billy]

// array with more than one datatype
var anything: [Any] = [Chanry, 1.23, 5]

// iterating through array (integers)
for num in nums {
    print(num)
}

// dictionary of strings as keys and integers as values
var characters: [String: Int] = ["chanry": 1, "bob": 2, "billy": 3]

// iterating through dictionary
for (key, value) in characters {
    print(key)
    print(value)
}

// print will be like:
// chanry
// 1
// bob
// 2
// billy
// 3

``` 
<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->

