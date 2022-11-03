# KrystalZhang-Wordle 2.0 App
My replica of the popular word game Wordle, developed programmatically using UIKit, Swift, and CGRect to build the UI, logics and various extensions. The App allows users to play the Wordle game by guessing the correct 5-lettered word gievn within 6 tries. 
## ***[Copyright and Commercial Use Disclaimer](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/README.md#please-carefully-read-licensemd-about-the-open-source-restrictions-and-the-personal-use-policy-of-this-project-under-gpl-30-license-any-commericial-uses-on-this-project-by-other-than-the-owner-krystalzhang612-or-the-authorized-users-and-organizations-including-unauthorized-modifications-forks-pull-requests-and-other-commercial-related-uses-will-be-subjected-to-copyright-violation-with-sebsequent-legal-concerns)***
⏬

### ***Please carefully read [LICENSE.md](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/LICENSE) about the Open Source restrictions and the personal use policy of this project under [GPL-3.0 license](https://www.gnu.org/licenses/gpl-3.0.en.html), any commericial uses on this project by other than the owner [@KrystalZhang612](https://github.com/KrystalZhang612) or the authorized users and organizations, including unauthorized modifications, forks, pull requests, and other commercial-related uses will be subjected to copyright violation with sebsequent legal concerns.***


## Wordle 2.0 App Overview:
<p align = "center">
        <img src = "https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/wordle2.0-overview1.png" width = "401.8181" height ="839.090"/>&nbsp; 
        <img src = "https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/wordle2.0-overview2.png"width = "401.8181" height ="839.090"/>
        <img src ="https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/wordle2.0-overview3.png" width = "401.8181" height ="839.090"/>&nbsp; 
        <img src ="https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/wordle2.0-overview4.png" width = "401.8181" height ="839.090"/>
        <img src ="https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/wordle2.0-overview5.png" width = "401.8181" height ="839.090"/>&nbsp;
        <img src ="https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/wordle2.0-overview6.png" width = "401.8181" height ="839.090"/>&nbsp;    
</p> 


# Build
[Method to Run & Test the Project Locally](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/README.md#method-to-run--test-the-project-locally)<br/>
[Prerequisites & Setups](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/README.md#prerequisites--setups)<br/>
[Synchronous Developing Notes](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/README.md#synchronous-developing-notes)<br/> 
[Testing Result](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/README.md#testing-result)

# Contribution
[Author]()
# Functionalities/Demo
-  Similar rules to the original Wordle App. A user has six tries to guess a five-letter word. To begin, enter a word. The App will reveal whether the word entered has any correct letters. A green letter is in the correct spot, an orange letter is in the word but in an incorrect spot, and a gray letter is not in the word. The user will win by guessing the word correctly within six tries.

# Compatibility
|   OS             | Supported          |
| -------          | ------------------ |
| iOS 15.2+        | :white_check_mark: |
| < iOS 15.2       | :x:                |
| macOS Mojave     | ✅                 |
| macOS Monterey   | ✅                 |

# Method to Run & Test the Project Locally

### Download the entire project to local directory
### Xcode must be `13.4` and higher versions with all Xcode dependencies updated.
### Compatible with `MacOS Monterey 12.0` or higher versions
### Run the project, choose Simulator `iPhone 14` or `iPhone 14 Pro` for best compatiability.

# 🛠️ Developing Languages, Tools, and Techniques Needed
[Xcode 14.0.1](https://developer.apple.com/documentation/xcode-release-notes/xcode-14_0_1-release-notes)<br/>
[Xcode Simulator iOS 16.0 iPhone 14 Pro](https://docs.expo.dev/workflow/ios-simulator/)<br/>
`(Compatible with iOS 15.2+)`<br/>
[SwiftUI](https://developer.apple.com/xcode/swiftui/)<br/>
[Swift 5](https://www.swift.org/blog/swift-5-released/)<br/>
<div>
        <img src ="https://github.com/devicons/devicon/blob/master/icons/xcode/xcode-plain.svg" title ="Xcode" alt ="Xcode" width ="60" height ="60"/>&nbsp; 
        <img src ="https://github.com/devicons/devicon/blob/master/icons/swift/swift-original.svg" title ="SwiftUI" alt = "SwiftUI" width ="60" height ="60"/>&nbsp; 
        <img src ="https://github.com/KrystalZhang612/KrystalZhang-RepliFlix/blob/main/swift%20ui%20symbol%20logo.png" title ="Swift 5" alt ="Swift 5" width ="60" height ="60"/>&nbsp;      
        <img src ="https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/new%20york%20times%20logo.png" title ="New York Times" alt ="New York Times" width ="60" height ="60"/>&nbsp;     
        <img src ="https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/cgrect%20logo.png" title ="CGRect" alt ="CGRect" width = "171" height ="60"/> 
</div>

# Prerequisites & Setups
Create two Cocoa Class files [KeyboardViewController.swift](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/Wordle%202.0%20App/Core/KeyboardViewController.swift) and [BoardViewController.swift](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/Wordle%202.0%20App/Core/BoardViewController.swift) in [Core](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/tree/main/Wordle%202.0%20App/Core).<br/>
Give keyboard and board different background colors:
```Swift
view.backgroundColor = .red/.blue
```
# Synchronous Developing Notes:
## ***Main Architecture:***
Add main view controllers to build architecture in [ViewController.swift](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/Wordle%202.0%20App/Core/ViewController.swift):
```Swift 
private func addChildren(){
        addChild(keyboardVC)
        keyboardVC.didMove(toParent: self)
        keyboardVC.view.translatesAutoresizingMaskIntoConstraints = false 
        view.addSubview(keyboardVC.view)
        addChild(boardVC)
        boardVC.didMove(toParent: self)
        boardVC.view.translatesAutoresizingMaskIntoConstraints = false
        view.addSubview(boardVC.view)
}        
```
## ***Constraints:***
To make the keyboard and board view controller background colors visible add constraints:
```Swift 
 func addConstraints(){
  NSLayoutConstraint.activate([
  boardVC.view.leadingAnchor.constraint(equalTo: view.leadingAnchor),
  boardVC.view.trailingAnchor.constraint(equalTo:
view.trailingAnchor),
  boardVC.view.topAnchor.constraint(equalTo: view.topAnchor),
  boardVC.view.bottomAnchor.constraint(equalTo:
keyboardVC.view.topAnchor),
  boardVC.view.heightAnchor.constraint(equalTo: view.heightAnchor,
multiplier: 0.6),
   keyboardVC.view.leadingAnchor.constraint(equalTo:
view.leadingAnchor),
   keyboardVC.view.trailingAnchor.constraint(equalTo:
view.trailingAnchor),
keyboardVC.view.bottomAnchor.constraint(equalTo: view.bottomAnchor)}
```
After adding constraints, the VCs background color displayed:<br/>
[vc background colors displayed.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/vc%20background%20colors%20displayed.png)<br/>
## ***Keyboard:***
In [KeyboardViewController.swift](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/Wordle%202.0%20App/Core/KeyboardViewController.swift), create keyboard collection views:
```Swift 
class KeyboardViewController: UIViewController {
    let letters = ["qwertyuiop", "asdfghjkl", "zxcvbnm"]
    private var keys: [[Character]] = []
    let collectionView: UICollectionView = {
        let layout = UICollectionViewFlowLayout()
        layout.minimumInteritemSpacing = 2
        let collectionView = UICollectionView(frame: .zero,
collectionViewLayout: layout)
        collectionView.translatesAutoresizingMaskIntoConstraints =
false
        collectionView.backgroundColor = .yellow
        return collectionView
    }()
```
Run the simulator to test if Keyboard UI Collection VIew working:<br/>
[keyboard ui collection view works.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/keyboard%20ui%20collection%20view%20works.png)<br/>
## ***Delegate Data Source:***
Assign delegate and datasource to self in viewdidload function:
```Swift 
 collectionView.delegate = self
  collectionView.dataSource = self
```
## ***Keys:***
Create keyboard view controller extensions components.<br/>
Initialize in [KeyCell.swift](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/Wordle%202.0%20App/Core/KeyCell.swift):
```Swift 
    override init(frame: CGRect) {
        super.init(frame: frame)
        backgroundColor = .systemGray5
    }
    required init?(coder: NSCoder){
        fatalError()
    }
```
Now keyboard-shaped squares displayed underneath:<br/>
[keyboard squares displayed.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/keyboard%20squares%20displayed.png)<br/>
## ***Centering the Keyboard Cells:***
Adjust keyboard cells alignment to make them centered:
```Swift 
 func collectionView(_ collectionView: UICollectionView, layout
collectionViewLayout: UICollectionViewLayout, insetForSectionAt
section: Int) -> UIEdgeInsets {
        var left: CGFloat = 1
        var right: CGFloat = 1
        let margin: CGFloat = 20
        let size: CGFloat = (collectionView.frame.size.width -
margin)/10
        let count: CGFloat =
CGFloat(collectionView.numberOfItems(inSection: section))
        let inset: CGFloat = (collectionView.frame.size.width - (size
* count) - (2 * count))/2
        left = inset
        right = inset
        return UIEdgeInsets(
            top: 2,
            left: left,
            bottom: 2,
            right: right
)
```
Now keyboard cells are all centered:<br/>
[keyboard cell centered.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/keyboard%20cell%20centered.png)<br/> 
## ***Board Controller:***
Configure in [KeyboardViewController.swift](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/Wordle%202.0%20App/Core/KeyboardViewController.swift):
```Swift
let letter = keys[indexPath.section][indexPath.row]
        cell.configure(with: letter)
        return cell
```
Now all keys letters are visible:<br/> 
[keys letters displayed.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/keys%20letters%20displayed.png)<br/>
In [BoardViewController.swift](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/Wordle%202.0%20App/Core/BoardViewController.swift):<br/> 
Similar to Keyboard view controller, set all board characters with A to test out:
```Swift 
func collectionView(_ collectionView: UICollectionView, cellForItemAt indexPath: IndexPath) -> UICollectionViewCell {guard let cell = collectionView.dequeueReusableCell(withReuseIdentifier: KeyCell.identifier, for: indexPath) as? KeyCell else {
            fatalError()
        }
        cell.configure(with: Character("A"))
return cell
```
[wordle board A character test works.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/wordle%20board%20A%20character%20test%20works.png)<br/> 
To create an interaction on the keyboard cells:
```Swift 
 protocol KeyboardViewControllerDelegate: AnyObject {
    func keyboardViewController(
        _vc: KeyboardViewController,
        didTapKey letter: Character
...
weak var delegate: KeyboardViewControllerDelegate?
```
And to use delegate:
```Swift 
func collectionView(_ collectionView: UICollectionView,
didSelectItemAt indexPath: IndexPath) {
       //
        collectionView.deselectItem(at: indexPath, animated: true)
        let letter = keys[indexPath.section][indexPath.row]
        delegate?.keyboardViewController(_vc: self, didTapKey: letter)
} }
```
To get actual access to the delegate, add an extension in ViewController.swift:
```Swift 
extension ViewController: KeyboardViewControllerDelegate {
    func keyboardViewController(_vc: KeyboardViewController, didTapKey
letter: Character) {
        print(letter)
    }
}
```
So now when we type the letter on the simulator keyboard, the letters appear on the console.
## ***Data Source:***
Add a protocol to get data source in BoardViewController.swift:
```Swift 
protocol BoardViewControllerDataSource: AnyObject {
var currentGuesses: [[Character?]] {get}}
```
Then to get the board showing, add boardVC extension in ViewController.swift:
```Swift 
 extension ViewController: BoardViewControllerDataSource  {
    var currentGuesses: [[Character?]] {
        return guesses
    }
}
```
Now update these guesses and tell the board controllers to reload itself:
```Swift 
public func reloadData(){
        collectionView.reloadData()
    }
}
```
To make the key tap responsive and tapped letters show up on board, we need to configure data source in BoardViewController.swift:
```Swift 
 let guesses = datasource?.currentGuesses ?? []
        if let letter =
            guesses[indexPath.section][indexPath.row] {
            cell.configure(with: letter)
        }
```
Now when tap keyboard, the tapped letters responded and become visible on board:<br/> 
[tapped letters displayed on board in order.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/tapped%20letters%20displayed%20on%20board%20in%20order.png)<br/>
## ***Logic:***
Set up the rule: if the tapped letter exists in the word and at the correct spot, green color, if the tapped letter exists in the word and at the wrong spot, orange color, else if the tapped letter is not in the word, gray color. In ViewController.swift:
```Swift 
extension ViewController: BoardViewControllerDataSource  {
    var currentGuesses: [[Character?]] {
        return guesses
    }
    func boxColor(at indexPath: IndexPath) -> UIColor? {
        let rowIndex = indexPath.section
        let count = guesses[rowIndex].compactMap({ $0 }).count
        guard count == 5 else {
return nil }
        let indexedAnswer = Array(answer)
        guard let letter = guesses[indexPath.section][indexPath.row],
indexedAnswer.contains(letter) else {
return nil }
        if indexedAnswer[indexPath.row] == letter {
            return .systemGreen
}
        return .systemOrange
```
Test out with the answer word: AFTER:<br/>
[wordle works with the answer AFTER.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/wordle%20works%20with%20the%20answer%20AFTER.png)<br/>
Add app name:<br/> 
Other -> Main -> ViewController->View-> Editor-> Embed in-> Navigator-> Right hand bar<br/>
[wordle 2.0 title displayed.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/wordle%202.0%20title%20displayed.png)<br/> 
Now import a bunch of A-B five-lettered words:
```Swift 
let answers = ["abuse","adult", "agent", "anger", "apple", "award", "basis", "beach","birth", "block", "blood", "board", "brain","bread", "break", "brown"]
```
Test word BRAIN works:<br/>
[test BRAIN works.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/test%20BRAIN%20works.png)<br/>

# Testing Result 
[vc background colors displayed.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/vc%20background%20colors%20displayed.png)<br/>
[keyboard ui collection view works.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/keyboard%20ui%20collection%20view%20works.png)<br/>
[keyboard squares displayed.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/keyboard%20squares%20displayed.png)<br/>
[keyboard cell centered.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/keyboard%20cell%20centered.png)<br/> 
[keys letters displayed.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/keys%20letters%20displayed.png)<br/>
[wordle board A character test works.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/wordle%20board%20A%20character%20test%20works.png)<br/> 
[tapped letters displayed on board in order.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/tapped%20letters%20displayed%20on%20board%20in%20order.png)<br/>
[wordle works with the answer AFTER.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/wordle%20works%20with%20the%20answer%20AFTER.png)<br/>
[wordle 2.0 title displayed.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/wordle%202.0%20title%20displayed.png)<br/> 
[test BRAIN works.PNG](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/test%20BRAIN%20works.png)<br/>

# Author
Krystal Zhang 
https://github.com/KrystalZhang612<hr>
*This file was generated by [Wordle 2.0-App-readme](https://github.com/KrystalZhang612/KrystalZhang-Wordle-2.0-App/blob/main/README.md), on October 27, 2022*
